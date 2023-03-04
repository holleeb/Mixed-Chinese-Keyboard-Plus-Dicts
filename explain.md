```

    public String getCandidateMap(char key1stChar, char key2ndChar){
        String candidateMap;
        if (this.mIsChineseKey) {
            if (21413 >= key1stChar) {
                candidateMap = loadRawString(0);
            } else if (23460 >= key1stChar) {
                candidateMap = loadRawString(1);
            } else if (25238 >= key1stChar) {
                candidateMap = loadRawString(2);
            } else if (26999 >= key1stChar) {
                candidateMap = loadRawString(3);
            } else if (29281 >= key1stChar) {
                candidateMap = loadRawString(4);
            } else if (31757 >= key1stChar) {
                candidateMap = loadRawString(5);
            } else if (33769 >= key1stChar) {
                candidateMap = loadRawString(6);
            } else if (36076 >= key1stChar) {
                candidateMap = loadRawString(7);
            } else if (38287 >= key1stChar) {
                candidateMap = loadRawString(8);
            } else {
                candidateMap = loadRawString(9);
            }
        } else if (this.mRCandidateMapID.length == 53) {
            if ('a' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(0);
                } else {
                    candidateMap = loadRawString(26);
                }
            } else if ('b' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(1);
                } else {
                    candidateMap = loadRawString(27);
                }
            } else if ('c' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(2);
                } else {
                    candidateMap = loadRawString(28);
                }
            } else if ('d' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(3);
                } else {
                    candidateMap = loadRawString(29);
                }
            } else if ('e' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(4);
                } else {
                    candidateMap = loadRawString(30);
                }
            } else if ('f' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(5);
                } else {
                    candidateMap = loadRawString(31);
                }
            } else if ('g' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(6);
                } else {
                    candidateMap = loadRawString(32);
                }
            } else if ('h' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(7);
                } else {
                    candidateMap = loadRawString(33);
                }
            } else if ('i' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(8);
                } else {
                    candidateMap = loadRawString(34);
                }
            } else if ('j' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(9);
                } else {
                    candidateMap = loadRawString(35);
                }
            } else if ('k' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(10);
                } else {
                    candidateMap = loadRawString(36);
                }
            } else if ('l' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(11);
                } else {
                    candidateMap = loadRawString(37);
                }
            } else if ('m' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(12);
                } else {
                    candidateMap = loadRawString(38);
                }
            } else if ('n' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(13);
                } else {
                    candidateMap = loadRawString(39);
                }
            } else if ('o' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(14);
                } else {
                    candidateMap = loadRawString(40);
                }
            } else if ('p' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(15);
                } else {
                    candidateMap = loadRawString(41);
                }
            } else if ('q' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(16);
                } else {
                    candidateMap = loadRawString(42);
                }
            } else if ('r' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(17);
                } else {
                    candidateMap = loadRawString(43);
                }
            } else if ('s' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(18);
                } else {
                    candidateMap = loadRawString(44);
                }
            } else if ('t' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(19);
                } else {
                    candidateMap = loadRawString(45);
                }
            } else if ('u' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(20);
                } else {
                    candidateMap = loadRawString(46);
                }
            } else if ('v' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(21);
                } else {
                    candidateMap = loadRawString(47);
                }
            } else if ('w' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(22);
                } else {
                    candidateMap = loadRawString(48);
                }
            } else if ('x' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(23);
                } else {
                    candidateMap = loadRawString(49);
                }
            } else if ('y' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(24);
                } else {
                    candidateMap = loadRawString(50);
                }
            } else if ('z' == key1stChar) {
                if (this.key2ndCharBoundary >= key2ndChar) {
                    candidateMap = loadRawString(25);
                } else {
                    candidateMap = loadRawString(51);
                }
            } else {
                candidateMap = loadRawString(52);
            }
        } else if ('a' >= key1stChar) {
            candidateMap = loadRawString(0);
        } else if ('b' == key1stChar) {
            candidateMap = loadRawString(0);
        } else if ('c' == key1stChar) {
            candidateMap = loadRawString(0);
        } else if ('d' == key1stChar) {
            candidateMap = loadRawString(1);
        } else if ('e' == key1stChar) {
            candidateMap = loadRawString(1);
        } else if ('f' == key1stChar) {
            candidateMap = loadRawString(1);
        } else if ('g' == key1stChar) {
            candidateMap = loadRawString(2);
        } else if ('h' == key1stChar) {
            candidateMap = loadRawString(2);
        } else if ('i' == key1stChar) {
            candidateMap = loadRawString(2);
        } else if ('j' == key1stChar) {
            candidateMap = loadRawString(3);
        } else if ('k' == key1stChar) {
            candidateMap = loadRawString(3);
        } else if ('l' == key1stChar) {
            candidateMap = loadRawString(3);
        } else if ('m' == key1stChar) {
            candidateMap = loadRawString(4);
        } else if ('n' == key1stChar) {
            candidateMap = loadRawString(4);
        } else if ('o' == key1stChar) {
            candidateMap = loadRawString(4);
        } else if ('p' == key1stChar) {
            candidateMap = loadRawString(5);
        } else if ('q' == key1stChar) {
            candidateMap = loadRawString(5);
        } else if ('r' == key1stChar) {
            candidateMap = loadRawString(5);
        } else if ('s' == key1stChar) {
            candidateMap = loadRawString(6);
        } else if ('t' == key1stChar) {
            candidateMap = loadRawString(6);
        } else if ('u' == key1stChar) {
            candidateMap = loadRawString(6);
        } else if ('v' == key1stChar) {
            candidateMap = loadRawString(7);
        } else if ('w' == key1stChar) {
            candidateMap = loadRawString(7);
        } else if ('x' == key1stChar) {
            candidateMap = loadRawString(7);
        } else if ('y' == key1stChar) {
            candidateMap = loadRawString(8);
        } else {
            candidateMap = loadRawString(8);
        }
        return candidateMap;
    }

    ```
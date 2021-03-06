# PRG -- Počítadlo znaků

[![Join the chat at gitter.im/spseol/Python](https://badges.gitter.im/spseol/PRG-No.svg)](https://gitter.im/spseol/Python?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

Vytvořte program, který na výstup vypíše a zobrazí v grafu počty jednotlivých 
znaků, které mu přicházení na standardní vstup.

Například:

```
$ curl https://cs.wikipedia.org/wiki/IPv6 2>/den/null | html2text -utf8 \
  | ./pocitadlo.py 

 -----------------------------------------------------------------------------
| A:                 2575 | B:                  391 | C:                 1094 |
 -----------------------------------------------------------------------------
| D:                 1188 | E:                 2945 | F:                  299 |
 -----------------------------------------------------------------------------
| G:                  184 | H:                  538 | I:                 2776 |
 -----------------------------------------------------------------------------
| J:                  477 | K:                  844 | L:                  977 |
 -----------------------------------------------------------------------------
| M:                  779 | N:                 2193 | O:                 2540 |
 -----------------------------------------------------------------------------
| P:                 1484 | Q:                    3 | R:                 1732 |
 -----------------------------------------------------------------------------
| S:                 1587 | T:                 1931 | U:                 1131 |
 -----------------------------------------------------------------------------
| V:                 1462 | W:                  106 | X:                   87 |
 -----------------------------------------------------------------------------
| Y:                  739 | Z:                  825 |
 -----------------------------------------------------------------------------
meritko: * = 58.90 znaku
                2575 | A |*******************************************
                 391 | B |******
                1094 | C |******************
                1188 | D |********************
                2945 | E |*************************************************
                 299 | F |*****
                 184 | G |***
                 538 | H |*********
                2776 | I |***********************************************
                 477 | J |********
                 844 | K |**************
                 977 | L |****************
                 779 | M |*************
                2193 | N |*************************************
                2540 | O |*******************************************
                1484 | P |*************************
                   3 | Q |
                1732 | R |*****************************
                1587 | S |**************************
                1931 | T |********************************
                1131 | U |*******************
                1462 | V |************************
                 106 | W |*
                  87 | X |*
                 739 | Y |************
                 825 | Z |**************
meritko: # = 117.80 znaku
             #                                                                
             #           #                                                    
             #           #                                                    
 #           #           #                 #                                  
 #           #           #                 #                                  
 #           #           #                 #                                  
 #           #           #              #  #                                  
 #           #           #              #  #                                  
 #           #           #              #  #              #                   
 #           #           #              #  #              #                   
 #           #           #              #  #        #     #                   
 #           #           #              #  #        #  #  #                   
 #           #           #              #  #  #     #  #  #     #             
 #           #           #              #  #  #     #  #  #     #             
 #        #  #           #              #  #  #     #  #  #     #             
 #     #  #  #           #              #  #  #     #  #  #  #  #             
 #     #  #  #           #        #     #  #  #     #  #  #  #  #             
 #     #  #  #           #     #  #     #  #  #     #  #  #  #  #           # 
 #     #  #  #           #     #  #  #  #  #  #     #  #  #  #  #        #  # 
 #     #  #  #           #     #  #  #  #  #  #     #  #  #  #  #        #  # 
 #     #  #  #        #  #  #  #  #  #  #  #  #     #  #  #  #  #        #  # 
 #  #  #  #  #        #  #  #  #  #  #  #  #  #     #  #  #  #  #        #  # 
 #  #  #  #  #  #     #  #  #  #  #  #  #  #  #     #  #  #  #  #        #  # 
 #  #  #  #  #  #  #  #  #  #  #  #  #  #  #  #     #  #  #  #  #        #  # 
______________________________________________________________________________ 
 A  B  C  D  E  F  G  H  I  J  K  L  M  N  O  P  Q  R  S  T  U  V  W  X  Y  Z 

```
# PRG-pocitadlo_znaku

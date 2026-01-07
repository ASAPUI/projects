# sequence-of-adn-using-python
la_sequence_d_ADN=input("ENTRE YOU SEQUENCE OF ADN: ").upper().split() #exemple:ATGC
A="T"
C="G"
T="A"
G="C"
for base in la_sequence_d_ADN[0]:
    if base=="A":
        print(A,end="")
    elif base=="C":
         print(C,end="")
    elif base=="T":
         print(T,end="")
    elif base=="G":
         print(G,end="")

# README

##### Nome: <h/1> Afonso Lechugo Isaac
##### Email: afonso.isaac@fatec.sp.gov.br
##### GitHub ID: afonsolechugo
##### R.A.: 3011542423032


## CODIGO PYTHON

print(f" P | Q | R | S | (𝒑→𝒒) | (𝒓→𝒔) | (𝒑∨𝒓) | (𝒒∨𝒔) | ((𝒑→𝒒)∧(𝒓→𝒔)∧(𝒑∨𝒓)) | ((𝒑→𝒒)∧(𝒓→𝒔)∧(𝒑∨𝒓))→(𝒒∨𝒔)")
n = 0
for a in range (0,2,1):
    for b in range (0,2,1):
        for c in range (0,2,1):
            for d in range (0,2,1):
                if a==0:
                    P = "V"
                else: 
                    P = "F"
                if b==0:
                    Q = "V"
                else:
                    Q = "F"
                if c==0:
                    R = "V"
                else:
                    R = "F"
                if d==0:
                    S = "V"
                else:
                    S = "F"
                if (P=="V" and Q=="V") or (P=="F"):
                    PQ="V"
                else:
                    PQ="F"
                if (R=="V" and S=="V") or (R=="F"):
                    RS="V"
                else:
                    RS="F"
                if P=="V" or R=="V":
                    PvR = "V"
                else:
                    PvR = "F"
                if Q=="V" or S=="V":
                    QvS = "V"
                else:
                    QvS = "F"
                if PQ =="V" and RS =="V" and PvR =="V":
                    leftside = "V"
                else:
                    leftside = "F"
                if leftside =="V" and QvS =="V" or leftside =="F":
                    result = "V"
                else:
                    result = "F"
                if a==0:
                    print(f" {P} | {Q} | {R} | {S} |   {PQ}   |   {RS}   |   {PvR}   |   {QvS}   |           {leftside}          |            {result}")
                else:  



#TrabalhoFinalizado
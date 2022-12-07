# cakeslicing.python
CAKE SLICING

for i in range(int(input("No. of testcases:"))):
    N=int(input("No. of pieces: "))
    s="no"
    t="no"
    u="no"
    if N>=0:
        if 360%N==0:
            s="Yes"
        if N<=360:
            t="yes"
        if N<=26:
            u="yes"
    print(s,t,u)

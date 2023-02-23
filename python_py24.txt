import random

szamlalo = 0 
for i in range(20):
    szam = random.randint(1, 12) 
    if szam % 3 == 0:  
        print(szam) 
        szamlalo += 1 

print(f"Az 1 és 12 közötti 3-mal osztható számok darabszáma: {szamlalo}")

# Guess-my-number
Zabawa z wykorzystaniem modułu random

import random
mojaLiczba = random.randint(0,20)
odpowiedz=-1
 
print("Zgadnij o jakiej liczbie myślę(od 0 do 20)")
 
while odpowiedz != mojaLiczba :
 
    odpowiedz = int(input())
    
    if odpowiedz == mojaLiczba:
        print("Brawo! Odgadłeś, to właśnie:",mojaLiczba)
    elif odpowiedz>mojaLiczba:
        print("Niestety, moja liczba jest mniejsza od", odpowiedz, "Spróbuj jeszcze raz!")
    else:
        print("Niestety, moja liczba jest większa od", odpowiedz, "Spróbuj jeszcze raz!")


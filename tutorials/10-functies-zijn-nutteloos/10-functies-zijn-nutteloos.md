# 10. Functies zijn vanzichzelf nutteloos

## Hoezo nutteloos?

Functies zijn stukje codes die iets doen voor jou, maar ze kunnen ook iets ``terug geven`` net als een resultaat voor een plus som. 

## Terug geven
laten we zeggen we willen iets maken net als dit
```py
resultaat = optellen(10, 20)
print(resultaat) # 30
```
we willen dat ``optellen`` dat uitrekent, hoe doen we dat?

## De return keyword

In programmeren, gebruiken we de ``return`` keyword om van een functie een waarde weg te geven.

voorbeeld:
```py
def optellen(x, y):
    return x + y
resultaat = optellen(10, 20) # 30
resultaat = optellen(50, 60) # 110
```

een andere leuke voorbeeld
```py
def is_volwassen(leeftijd):
    if leeftijd > 18:
        return True
    else:
        return False
ben_ik_volwassen = is_volwassen(14)
if ben_ik_volwassen == True:
    print("ik ben volwassen!")
else:
    print("ik ben nog een baby..")
```
dit kijkt of de eerste parameter ``leeftijd`` hoger is dan 18, als dat klopt dan geven we de waarde ``True`` af, anders ``False``

voila, functies zijn wel handig.. Je vindt ze overal
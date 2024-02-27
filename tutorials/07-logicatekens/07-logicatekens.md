# 7. Logica tekens 

## logic!

zijn appels hetzelfde als peren? Nee tuurlijk niet!

logica noemen we dit ook, is deze getal groter dan dit etc...

We gebruiken logica vaker met **variabelen** 
en logica tekens geven als resultaat altijd een **Booleans**(True of False)
## x is hetzelfde als y
dit kan met de ``==`` teken, dit kijkt als links hetzelfde is als rechts
```py
x = 10
y = 10
print(x == y) # True
persoon1 = "Taseen"
persoon2 = "Lars"
print(persoon1 == persoon2) # False
is_lamp_uit = False
ben_ik_gay = False
print(is_lamp_uit == ben_ik_niet_gay) # True

```


## x is niet hetzelfde als y
Dit kan met de ``!=`` teken, dit kijkt als links niet hetzelfde is als rechts
```py
x = 10
y = 10
print(x != y) # False
persoon1 = "Taseen"
persoon2 = "Lars"
print(persoon1 != persoon2) # True
lamp_uit = True
deur_open = False
print(lamp_uit != deur_open) # True
```

## x is groter dan y

Dit kan met de ``>`` teken, dit kik als links groter is dan rechts

***linkts en rechts** moeten allebei een integer of een float zijn. Anders heb je een error!*

```py
x = 10
y = 20
print(x > y) # False
print(y > x) # True
a = 3.14
b = 2.4
print(a > b) # True
a = 3
b = 3
print(a > b) # False
```
gebruik de ``>=`` voor **groter dan of hetzelfde**
```py
x = 10
y = 10
print(x >= y) # True
```

## x is kleiner dan y
Dit kan met de ``<`` teken, dit kik als links kleiner is dan rechts
```py
x = 10
y = 20
print(x < y) # True
x = 10
y = 10
print(x < y) # False
x = 100
y = 10
print(x < y) # False
```
Gebruik de ``<=`` teken voor **kleiner dan of hetzelfde**
```py
x = 10
y = 10
print(x <= y) # True
```


Voila, logica == True!

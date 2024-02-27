# 9. Functies

## dit klinkt eng

functies zijn niet eng! Functies zijn stukje codes die je meerdere keren kan gebruiken. Dit kan iets van 20 lijntjes verkorten naar 1 lijn.

Je gebruikt de ``def`` keyword om een functie te maken, een functie heeft dezelfde regels als een variabel
```py
def say_hello():
    print("Dag jongens")
```
vergeet voor nu de (), de ``:`` is om te vertelen wat de begin is van onze functie. Alles wat in de functie zit moet beginnen met een ``tab``.

Als we dit runnen.. dan gebeurt er niks.
hoezo? er zit toch een print erin?

## een functie roepen 
Om een functie te gebruiken, moet je het roepen. Roepen is net als vragen om iets te runnen.

Een bekende functie die je nu al kent is ``print``

om ``say_hello`` te roepen
```py
def say_hello():
    print("dag jongens")

say_hello()
```
dit gaat
```
dag jongens
```
laten zien. 

Een coole ding van functies is dat je ze vaker kan roepen.
```py
def say_hi():
    print("hi")
say_hi()
say_hi()
say_hi()
```
terminal:
```
hi
hi
hi
```

## functies met argumenten
het verschil tussen onze ``say_hi`` functie en ``print`` is dat ``print`` een variabel neemt in die haakjes. Dit noemen we ``parameters``.

```py
def print_variable(variable):
    print(variable)

print_variable("Hello")
print_variable(10)
```
terminal resultaat:
```
Hello
10
```

dit kan handig zijn en uniek voor functies. Je bent trouwens **verplicht** om iets te geven in de haakjes voor nu.

Om meerdere parameters toe te voegen, moet je gewoon een ``,`` toevoegen tussen elke parameter naam.
```py
def optellen(x, y):
    print(x + y)
optellen(10, 20)
```

wees vrij om ``functies.py`` te gebruiken als een speeltuin! 

voila, functies af!
# 8. Wat als dit

## Wat als wat?

Wat als dit klopt, dan doe dit stukje code. Dit wordt ook wel een **iif statement** genoemd. Dit gebeurt als iets ``True`` is dan wordt de stukje code gedraaid

een voorbeeld van hoe het werkt:
```py
a = 10
b = 10
if a == b:
    print("a is hetzelfde als b")
```
**let op de 4 spaties (oftewel de tab), alles wat een tab heeft na de conditie wordt dan geexecuteerd.**

## Doe dan iets anders als het niet klopt

Dit wordt ook wel een ``else statement`` genoemd, dit is een andere stukje code die wordt gerunt als de ``if statement`` niet ``True`` is
```py
a = 10
b = 20
if a == b:
    print("a is b")
else:
    print("a is niet b")
```
**let op dat de else geen identatie nodig heeft**

## Anders als dit

Dit wordt ook wel een ``elseif statement`` genoemd, dit stukje wordt gerunt als vorige conditie niet True was.
Gebruik de **elif** daarvoor
```py
a = 10
b = 20
if a == b:
    print("a is b")
elif a != b:
    print("a is niet b")
```

voila, conditie mijn ba-
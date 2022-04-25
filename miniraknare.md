# Miniräknaren

Din uppgift är att koda ett program för att visa det du har lärt dig hittills. Ditt program ska använda numeriska uttryck, selektion och iteration. Det ska alltså upprepa, välja och räkna… En miniräknare.

Utgå från detta repo. Klona ned det och öppna det i visual studio och koda. Det är viktigt att du commitar medans du arbetar (det är en del av din dokumentation, skriv begripliga meddelanden som beskriver vad du gjort).
Det ska finnas en commit när du börjar. En när du har kodat meny loopen, en när du kodat en uträkning och så vidare.

## Krav

Programmet ska ha en meny, som ska visas tills användaren väljer att avsluta programmet.
Programmet ska kunna räkna med flera räknesätt och användaren ska kunna mata in talen som det räknas med.

```python
Välkommen till miniräknaren.
[1] Räkna med +
[2] Räkna med -
[3] Räkna med *
[4] Valfritt arbete, om du vill
[5] Avsluta
```
Här behöver du en loop som fortsätter köra programmet så länge valet inte är 5. Resten av menyn styrs med en if elif else sats.

När ett val har gjorts så får du utforma koden kring det och hur programmet ska se ut som du vill. Det kan exempelvis vara.
```python
Skriv ett tal:
Skriv ett andra tal:
Summan av tal1 + tal2 är summa.
```
Skriv några kommentarer i din kod och förklara den så att jag kan se hur du tänkt.

## Hjälp

Jens.
Kursboken, du hittar information i kapitel 2-4.
Kolla dina tidigare program.

## Tips

När du jobbar med programmet, skriv huvudmenyn först och sedan loopen. 
Koda sedan ett räknesätt, för du kan sedan kopiera denna kod till de andra sätten och justera den efter räknesättet.

## Extra

Felhantering, ditt program ska inte kunna krascha. Se kapitel 10.

Vill du öka komplexiteten för att visa att du kan mer så loopa inmatningen, låt användaren lägga till fler tal som kan räknas med så länge de inte skriver ett = tecken, då skriver du ut summan.
När beräkningen är färdig återvänder programmet till huvudmenyn.

Skriv menyvalen(räknesätten) som en funktion, för större komplexitet så kan du även acceptera räknesättet som en parameter till funktionen, så att du kan använda samma metod till alla beräkningar.
Om du har tid över och vill lägga till något extra så kan du göra detta i menyval 4.

Grafiskt gränssnitt, https://realpython.com/python-gui-tkinter/

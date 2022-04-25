# Uppgiftsbeskrivning
Du ska omsätta dina programmeringskunskaper och skapa ett verktyg du kan använda i din framtida yrkesroll.

Programmet ska vara en hjälp till automatisering för skapandet av användare, med tillhörande uppgifter, i ett system.

Programmet ska kunna läsa in en lista med användare, från någon form av fil, hantera dessa och skapa användarnamn, lösenord.
Resultatet ska sedan sparas i en ny fil.

## Krav

* Läsa in data från en CSV fil.
  * Manual, https://docs.python.org/3/library/csv.html
  * Skapa data med https://www.mockaroo.com/ 
* Läsa från cmdline med argparse 
  * https://docs.python.org/3/howto/argparse.html 
  * https://docs.python.org/3/library/argparse.html 
  * Ange vilken fil som ska läsas
  * Ange vilken fil som ska skrivas
  * Ange regler för användarnamn och lösenord

### Skapa usernames

För att skapa användarnamn behöver du arbeta med index och skivor i strängar.
Du ska kunna plocka ut ett par bokstäver ur förnamn och efternamn samt konvertera dem till små bokstäver. Se kap 5.

### Generera lösenord

Här behöver du skapa en metod för att generera ett lösenord.
Att använda random är en god start och du behöver använda dig av både bokstäver, siffror och specialtecken (@#?+-*)

### Extra

* Utöka progammets gränssnitt
  * Låt programmet köras genom en webbsida med Flask
  * Testa att göra ett grafiskt användargränssnitt med TK, https://realpython.com/python-gui-tkinter/
* Kontrollera användarens operativsystem med OS modulen och anpassa efter detta, https://docs.python.org/3/library/os.html
* Skapa faktiskta användare med New-ADUser eller useradd, köra subprocess
  * https://docs.python.org/3.2/library/subprocess.html
  * https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.localaccounts/new-localuser?view=powershell-5.1
  * https://docs.microsoft.com/en-us/powershell/module/activedirectory/new-aduser?view=windowsserver2022-ps
  * http://manpages.ubuntu.com/manpages/bionic/en/man8/useradd.8.html

## Utförande

### Planering
Programmet ska i första stadiet planeras. Du ska skapa pseudokod och/eller strukturdiagram/flödesschema för att visa hur det ska fungera.
Detta är viktigt, dels för dig som ska utöka funktionaliteten på programmet för att visa vad du har tänkt, men även för dig som känner att det är väldigt svårt att koda detta program, för då kan det räcka med att du visar din förståelse med dessa verktyg.

Mer information finns i kap 7 i kursboken.

Diagram skapas med draw.io Pseudokod skrivs i pseudokod

### Koda
När planeringen är utförd så kan du börja koda på hela programmet eller någon del.
Du ska åtminstone kunna visa att du kan koda viss funtionalitet för programmet för godkänt på uppgiften.

Den kod som lämnas in ska hantera eventuella körtidsfel och inte krascha.

Din kod ska använda sig av någon form av

* kontrollstrukturer, if else, while, kap 3-4
* metoder, funktioner(inbyggd eller egen), kap 8 eller csv reader
* variabler
* datastrukturer(lista), kap 6
* gränssnitt
* felhantering, kap 10

#### Textfil

Den hanterade datan kan sedan skrivas ut till en csv fil med csv.writer eller så skriver du direkt till textfil, se kapitel 11 i kursboken.

## Dokumentation
Du ska i arbetet dokumentera vad du gör varje arbetspass.
Detta görs dels genom git commit-meddelanden, men även genom att du skriver en kort anteckning om hur ditt arbete har gått under lektionen, vad du har arbetat med, hur det har gått och att du dokumenterar de problem du har löst (och eventuella fel).

### Logg skrivs i loggbok

När arbetet är utfört så dokumenteras detta kort i loggboken. Där ska du även beskriva vad du eventuellt inte har hunnit med att göra samt att ge förbättringsförslag på ditt program och arbetssätt.

## Bedömning
Uppgiften kommer att bedömas utifrån planeringen, kodens kvalite och hur självständigt ditt arbete med att lösa uppgiften har varit.

För högre betyg behöver du visa att du behärskar programmeringsspråket och kan arbeta självständigt med uppgiften. Du bör även kunna utöka programmets funktion enligt listan.

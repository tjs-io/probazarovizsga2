## 1 Feladat: Hogwards express jegyautomata

A Marvel új web alapú rajongó oldalt készít az X-man képregény adaptációkból.


Itt találod a webes applikáció prototípusát:
[https://witty-hill-0acfceb03.azurestaticapps.net/mutant_teams.html](https://witty-hill-0acfceb03.azurestaticapps.net/mutant_teams.html)

Készíts egy Python python applikációt (akár csak egy darab python fileban) ami selenium-ot használ.

Teszteld le, hogy a különböző szűrőfeltételek alapján megfelelő karaktereket mutatja az oldal.

Tehát mondjuk `iceman` pontosan az `original` és a `factor` csapatban van benne és a `hellfire` illetve a `force` csapatokban nincs benne.

(Figyelem: ne engedd, hogy az oldal dinamikus működése elvonja a figyelmed a célról! A karaktereket csoporthoz tartozását nem feltétlenül a felület változásával tudod ellenőrizni.)

Al alkalmazás helyesen mutatja a felületen a csoporthoz tartozást. Nincs külön tesztadat leírás ehhez a feladathoz, tehát a látottak alapáj kell a tesztadatot összeállítanod.


Az ellenőrzésekhez __NEM kell__ teszt keretrendszert használnod (mint pl a pytest). Egyszerűen használj elágazásokat
__NEM kell__ OOP-t használnod. Viszont tartalmazzon vizsgálatot a megodásod. Lehetőleg használj az `assert` összehasonlításokat.

### A megoldás beadása

* a megoldásokat a `testproject` mappába tedd, `mutants.py`
* a lokálisan kidolgozott megoldásokat előbb commitold `git commit`
* majd ne felejtsd el `git push` segítségével a Github szerverre is felküldeni
* ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása (`ctlr`+`alt`+`l`)
* akkor is add be megodásod, ha nem vagy benne biztos, mert részpontokat ér mindennemű a tárgyhoz kötődő kód beadása
* a megodás fájlba írjál kommentet amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen
  komment nélkül leadott fájlod.
* nem beadott vagy üres fálj formájában beadott feladat megoldás `0` pontot ér :(
{"mode":"full","isActive":false}
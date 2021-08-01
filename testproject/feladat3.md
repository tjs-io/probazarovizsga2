# 3 Feladat: Guess the number automatizálása

Készíts egy Python python applikációt (egy darab python file) ami selenium-ot használ. 

A program töltse be a Guess the number app-ot az [https://witty-hill-0acfceb03.azurestaticapps.net/guess_the_number.html](https://witty-hill-0acfceb03.azurestaticapps.net/guess_the_number.html) oldalról.

Feladatod, hogy automatizáld selenium webdriverrel az app funkcionalitását tesztelését.

* Egy tesztet kell írnod ami addig találgat a megadott intervallumon belül amíg ki nem találja a helyes számot.
Nem jár plusz pont azért ha úgy automatizálsz, hogy minnél optimálisabban és gyosabban találja ki a helyes számot a program

* Amikor megvan a helyes szám, ellenőrizd le, hogy a szükséges lépések száma mit az aplikáció kijelez egyezik-e a saját belső számlálóddal.

* Teszteld le, hogy az applikáció helyesen kezeli az intervallumon kívüli találgatásokat. Az applikéció -19 vagy 255 értéknél nem szabad, hogy összeomoljon. Azt kell kiírnia, hogy alá vagy fölé találtál-e.

Az ellenőrzésekhez __NEM__ kell teszt keretrendszert használnod (mint pl a pytest).
Egyszerűen használj elágazásokat vagy `assert` összehasonlításokat.

### A megoldás beadása
* a megoldásokat a `testproject` mappába tedd, `guess_the_number.py`
* a lokálisan kidolgozott megoldásokat előbb commitold `git commit`
* majd ne felejtsd el `git push` segítségével a Github szerverre is felküldeni
* ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása (`ctlr`+`alt`+`l`)
* akkor is add be megodásod, ha nem vagy benne biztos, mert részpontokat ér mindennemű a tárgyhoz kötődő kód beadása
* a megodás fájlba írjál kommentet amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen komment nélkül leadott fájlod.
* nem beadott vagy üres fálj formájában beadott feladat megoldás `0` pontot ér :(
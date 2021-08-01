# 2 Feladat: Film register applikáció funkcióinak automatizálása

Készíts egy Python python applikációt (egy darab python file) ami selenium-ot használ. 

A program töltse be a sales Film register app-ot az [https://witty-hill-0acfceb03.azurestaticapps.net/film_register.html](https://witty-hill-0acfceb03.azurestaticapps.net/film_register.html) oldalról.

Feladatod, hogy automatizáld az alkalmazás két funkciójának a tesztelését
* Teszteld le, hogy betöltés után megjelennek filmek az alkalmazásban, méghozzá 24 db.
* Teszteld le, hogy fel lehet-e venni az alábbi adatokkal egy új filmet:
    * Film title: Black widow
    * Release year: 2021
    * Chronological year of events: 2020
    * Trailer url: https://www.youtube.com/watch?v=Fp9pNPdNwjI
    * Image url: https://m.media-amazon.com/images/I/914MHuDfMSL._AC_UY327_FMwebp_QL65_.jpg
    * Film summary: https://www.imdb.com/title/tt3480822/


Az ellenőrzésekhez __NEM__ kell teszt keretrendszert használnod (mint pl a pytest).
Egyszerűen használj elágazásokat vagy `assert` összehasonlításokat.


### A megoldás beadása
* a megoldásokat a `testproject` mappába tedd, `film_register.py`
* a lokálisan kidolgozott megoldásokat előbb commitold `git commit`
* majd ne felejtsd el `git push` segítségével a Github szerverre is felküldeni
* ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása (`ctlr`+`alt`+`l`)
* akkor is add be megodásod, ha nem vagy benne biztos, mert részpontokat ér mindennemű a tárgyhoz kötődő kód beadása
* a megodás fájlba írjál kommentet amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen komment nélkül leadott fájlod.
* nem beadott vagy üres fálj formájában beadott feladat megoldás `0` pontot ér :(
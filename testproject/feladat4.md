# 4 Feladat: charterbooker automatizálása

Készíts egy Python python applikációt (egy darab python file) ami selenium-ot használ. 

A program töltse be a charterbooker app-ot az [https://witty-hill-0acfceb03.azurestaticapps.net/charterbooker.html](https://witty-hill-0acfceb03.azurestaticapps.net/charterbooker.html) oldalról.

Feladatod, hogy automatizáld selenium webdriverrel a charterbooker app tesztelését.

Az ellenőrzésekhez __NEM__ kell teszt keretrendszert használnod (mint pl a pytest).
Egyszerűen használj elágazásokat vagy `assert` összehasonlításokat.

* Teszteld le a többoldalas formanyomtatvány működését. 
* Ellenőrizd a helyes kitöltésre adott választ: "Your message was sent successfully. Thanks! We'll be in touch as soon as we can, which is usually like lightning (Unless we're sailing or eating tacos!)."
* Készíts tesztesetet az e-mail cím validációjára.


### A megoldás beadása
* a megoldásokat a `testproject` mappába tedd, `charterbooker.py`
* a lokálisan kidolgozott megoldásokat előbb commitold `git commit`
* majd ne felejtsd el `git push` segítségével a Github szerverre is felküldeni
* ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása (`ctlr`+`alt`+`l`)
* akkor is add be megodásod, ha nem vagy benne biztos, mert részpontokat ér mindennemű a tárgyhoz kötődő kód beadása
* a megodás fájlba írjál kommentet amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen komment nélkül leadott fájlod.
* nem beadott vagy üres fálj formájában beadott feladat megoldás `0` pontot ér :(
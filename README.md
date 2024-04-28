# Házi feladat

Ebbe a könyvtárba kerül az opcionális **házi feladat** megoldása. Továbbá ide kell majd a specifikációt is elkészíteni. 

## Beadás és értékelés
> [!IMPORTANT]
> A specifikációt és a házi feladatot a laborokhoz hasonlóan pull request formájában kell beadni a határidő előtt a Moodle alatt található **Git tudnivalók** leírásban található utasítások alapján.
> - Hozz létre egy **új branchet** `megoldas` néven, és ezen dolgozz.
> - Töltsd ki a `neptun.txt` fájlt a saját Neptun kódoddal.
> - Minden egyes részegység után kommitolj, és használj értelmes kommit üzeneteket.
> - A feladat végeztével **pushold** a megoldásodat és hozz létre egy **pull requestet**.
> - Ellenőrizd a pull request tartalmát és rendeld hozzá a laborvezetődet **reviewernek**.

> [!CAUTION]
> A nem ilyen formában megadott megoldások nem lesznek értékelve!

## Specifikáció

### A feladat rövid bemutatása

    A házi feladatom egy süteményes receptekből álló weboldalt mutat be.
A kezdőoldal bemutatja az aktuális recepteket és a felhasználóknak lehetőséget nyújt regisztrálni vagy bejelentkezni. Továbbá a kezdőoldal felső részén rangsorolva láthatóak a legnépszerűbb receptek.
Oldalt megjelenő kategóriák közül lehet választani, hogy milyen fajta süteményeket tartalmaz az oldal, vagy külön keresni is lehet.
A regisztrált/bejelentkezett felhasználók újabb recepteket tudnak feltölteni, ezen felül értékelhetik egymás receptjeit és komment hozzáfűzésére is van opciójuk.

### Az adatbázis sémája

-Felhasználó: ID, név, email, felhasználónév, jelszó, recept
-Recept: ID, név, kategótia, leírás, komment, értékelés
-Értékelés: ID, felhasználó, érték, recept
-Komment: ID, időpont, szöveg, felhasználó, recept
![](schema![schema](https://github.com/HZAnett/HF/assets/160552334/320fe8d9-a2fe-4eba-afc3-f327c242ebc3)
.png)

### Elérhető oldalak és funkciók listája

- Kezdőlap:
    - Funkciók:
        -Regiszttrálás/bejelentkezés(külön oldal)
        -Keresés
        -Rangsorolás
        -Recept hozzáadás/törlése
-Belépés:
    -Funkciók:
        -Új profil létrehozása/törlése
        -Jelszó változtatás      
- Recept:
    - Funkciók:
        -Értékelés
        -Megjegyzés írása

## Elkészült házi feladat

A házi feladat működését bemutató videó (max. 5 perc) linkje: [Videó](https://...) 

# Könyvtár kezelési rendszer PHP MySQL projekt
## A projekt célja
\
A Könyvtárkezelő Rendszer fő célja, hogy megoldást nyújtson a papírmunkával kapcsolatos problémákra, amelyek különböző okokból adódnak. Lehetővé teszi, hogy minden tevékenységet egy helyen kezeljenek. A rendszer segítségével az adminisztrátor különböző műveleteket végezhet egyszerre, ugyanazon a helyen. A Könyvtárkezelő Rendszer képes biztonságosan tárolni a könyvekkel kapcsolatos adatokat. Weboldalunkon a legjobb szolgáltatást nyújtjuk, és a felhasználók igényeire összpontosítunk. Új funkciókat fejlesztünk, hogy a felhasználók könnyen megértsék és megbízzanak a rendszerünkben.

## A projekt háttere
* Ez a Könyvesbolt-kezelő Rendszer Szoftver lehetővé teszi az adminisztrátor számára, hogy tárolja a könyv- és az ügyfél adatokat.
* Könnyebb hozzáférés az információkhoz, mint például az ügyfél információkhoz és 
* Lehetőséget biztosít az adatok tárolására a papírmunka csökkentése érdekében.
* A Könyvesbolt-kezelő Rendszerben a felhasználók könyvet vásárolhatnak, és az adminisztrátor megmutatja a nevüket és más háttér-információkat a felhasználóról.
* Egy új ötlet a Könyvesbolt-kezelő Rendszer működéséről. 
* A rendszer számítógépesítése.

## A projekt hatóköre
* A Könyvtárkezelő Rendszer célja a túlóra-fizetés csökkentése és a pontosan kezelhető rekordok számának növelése; A jelen dokumentumban szereplő követelmények funkcionálisak és nem funkcionálisak egyaránt.
* A helyes és pontos keresés a keresési művelet alkalmazásával eredményez.
* Az ügyfelek néhány kattintással lefoglalhatnak egy könyvet.
* Adjon rugalmasságot az adminisztrátornak a adatbázis hatékony használatához, és használja a szót, ne a betűt és a számológépet.
* Minden szinten egyértelmű és érthető.

## A projekt alkalmazhatósága
* Ügyfeleknek , akik könyveket akarnak venni bárhol, bármikor.
* Az adminisztrátor jogosult könyvek beszúrására és a könyvek listájának megtekintésére. 
* Az adatbázist az adatok tárolására és lekérésére használják, így mind a felhasználók, mind az adminisztrátorok lekérhetik vagy olvashatják az adatokat.

## Követelmény specifikációk:
A Könyvtárkezelő Rendszer Követelményei szerint két (2) modulból áll:

1)Adminisztrátor
2)Ügyfél

##### Admin funkciók:
-Ez a modul a következő feladatokat tartalmazza:
* Kategória bevitele.
* Kategória lista.
* Új könyv hozzáadása.
* Könyv megtekintése.
* Üzenetek megtekintése, amelyeket az ügyfél küldött.

## Hardver követelmény
* System type 32-bit Operating System.
* Windows 7/8/8.1/10
* Linux  Ubuntu / Light ubuntu
* Mac OS
* 350MB RAM

## Szoftver követelmény
* Wamp Szerver
* MySQL
* Böngésző
* PHPMyAdmin

**Projekt analízis és tervezés**

A Könyvesbolt-kezelő Rendszer elengedhetetlen az online rendelés felállításához, hogy az ügyfelek böngészhessenek a könyvkategóriák között. Ez egy kis léptékű projekt a Könyvesbolt-kezelő Rendszerhez. Az alapötlet az, hogy az ügyfelek bárhonnan, bármikor vásárolhatnak könyvet készpénzzel.

**Felhasználó**

* A felhasználók tudnak regisztrálni, bejelentkezni és kijelentkezni a rendszerből.
* Megtekinteni különböző könyv-kategóriákat.
* Kapcsolatba lépni az adminisztrátorral.
* Könyveket hozzáadni a kosárhoz.
* Könyveket rendelni.

**Funkcionalítás**

* Egy vagy több felhasználó éátogatja a weboldalat egyidőben.

**Használhatóság**

* Bármilyen böngészőn futtathatja a weboldalat.

**Teljesítmény**

* A weboldalt a felhasználó operációs rendszerének megfelelően jeleníti meg.

**Adminisztrátor**

* Az adminisztrátor tudja kezelni a rendszert.
* Könyvekkel lát el.

**Funkcionalítás**

* Az adminisztrátor beilleszthet egy könyvet vagy kezelheti a nyilvántartásokat.

### Adatbázis és Szerkezet design

A rendszerben használt számos táblázatok a következők:

1. Adminisztrátor
2. Könyv
3. Kategória
4. Elérhetőség
5. Regisztráció
6. Rendelés

**Következtetés**

* Első ránézésre elmondhatjuk, hogy a Könyvesbolt-kezelő Rendszer tökéletes rendszer, de számos korlátozása van, amelyek a következők:
* Ez a rendszer a kategóriák és könyvek listázására, valamint a könyvesbolt ügyfelei és könyvei kezelésére is szolgál.
* A Könyvesbolt-kezelő Rendszer a könyvekről szóló információk megadására szolgál az ügyfelek számára.
* Problémákkal szembesültünk, mint például az adatbázis létrehozása, a rendszerünk folyamata, az elülső és hátsó végi eszközök tervezése, a kódolás stb.
* Csak egyetlen felhasználó használhatja a rendszert egyszerre.
* Ebben a rendszerben nem tudunk szolgáltatási modult hozzáadni.
* Új nyelveket tanultunk, mint például a jQuery, PHP, Bootstrap, HTML, CSS stb.

## A rendszer korlátozása

*Segítség*

Jelenleg a súgó funkció nem érhető el. Ezt a funkciót használva a felhasználók segítséget kaphatnak a rendszerrel kapcsolatban.

*Fizetés*

Jelenleg az online fizetés funkciója nem érhető el. A felhasználók nem tudnak online fizetni.

*Többnyelvűség*

A többnyelvűség nem támogatott a rendszerünkben. Ezért a felhasználók nem tudnak különböző nyelveken dolgozni.

*Biztonsági mentés és helyreállítás:*

A felhasználók nem tudnak biztonsági mentést készíteni vagy helyreállítani az adatokat ebben a rendszerben.

És még sok más.

## A rendszer jövőbeli hatótere

Segítség modul

Ezt a modult használva a felhasználók segítséget kaphatnak a rendszerhez való hozzáférésről. A rendszer összes funkcióját leírják ebben a modulban. A felhasználó könnyen elérheti az egész modult ezzel a funkcióval.

Online fizetési modul

A felhasználók online fizethetnek ezzel a funkcióval. A jövőben online fizetést fogunk hozzáadni, hogy megkönnyítsük a felhasználók számára a fizetést.

Többnyelvű

Ebben a rendszerben hozzá fogjuk adni a többnyelvűséget, így a felhasználók különböző nyelveken dolgozhatnak és könnyen megérthetik.

## **Bemenet/ kimenet design**

1. Főoldal – A Könyvesbolt Kezelő Rendszer Főoldala bejelentkezés nélküli felhasználó számára.
2. Kiválasztott Kategória – A detektív kategória van kiválasztva. Megjeleníti a detektív kategória könyveit.
3. Könyv Részletek (Bejelentkezés előtt) – Könyv részletek a látogatók számára. A látogatók nem tudnak könyveket hozzáadni a kosárhoz.
4. Látogató Bejelentkezési Oldal – Bejelentkezési oldal a nézők számára.
5. Regisztrációs Oldal – Regisztrációs oldal a nézők számára.
6. Kapcsolatfelvételi Oldal
7. Kosár Oldal
8. Rendelési Oldal – A rendeléshez csak a készpénzes fizetés lehetséges.
9. Főoldal (Bejelentkezve) – Automatikusan megváltozik a navigációs sáv. A felhasználó kijelentkezhet.
10. Könyv Részletek (Bejelentkezve) – A felhasználók hozzáadhatnak könyveket a kosárhoz. Eltávolítva a bejelentkezési linket.
11. Kosárba helyezés (Bejelentkezve) – A felhasználók hozzáadhatnak könyveket a kosárhoz. A könyvek és az ár részletei. Kattintson a "Újraszámítás" gombra a mennyiség, az ár és az összeg kiszámításához. A felhasználók rendelhetnek könyveket.
12. Könyvek Keresése – Könyvkeresési funkció.
13. Adminisztrátor Bejelentkezési Oldal (Új Sablon)
14. Adminisztrátor Főoldal – Új Sablon.
15. Kategória Hozzáadása (Adminisztrátor)
16. Kategória Megtekintése – A könyvek listája.
17. Könyvek Hozzáadása.
18. Könyvek Megtekintése – A könyvek listája az adminisztrátor számára.
19. Kapcsolatfelvételi Lista Megtekintése – A Kapcsolatfelvételi Oldalon keresztül kapcsolatba lépett személyek listája.
20. Felhasználók Listája
21. Jelszó Elfelejtve
# Családfa
Az alkalmazás célja hogy a felhasználók grafikus feluleten tudják nyomonkövetni családfájukat.
## Funkcionális követelmények
* Felhasználói fiók létrehozása(regisztráció)
* Belépés
### Belülről elérhető funkciók

#### Profil

* A felhasználó itt a fiókjához tartozó  néhány adatot kezelheti: felhasználói név  változtatása, Jelszó változtatása,  e-mailcím változtatása, profil törlése
* Adataim megadása
  * Vezetéknév
  * Keresztnév
  * Születési dátum (év,hónap,nap)
  * Születési hely
  * Nem
  * Fénykép
  * Szülők és testvérek hozzáadása
#### Családfám
Grafikusan megjelenne a felhasználó családfája, ahol a következő funkciókat érhetné el:

* Új családtag felvétele
  * Feugró ablakban megadhatók az új családtag adatai és beállíthatók a szülők és a testvérek (ezek az ábrán nyilakkal lennének reprezentálva)
* Rokonsági kapcsolatok mutatása (alapértelmezetten az 1-es rokonsági kapcsolatok lennének láthatóak)
  * Ennek a kapcsolónak az aktiválásakor az éppen betöltött családfában megjelennének azok a rokoni kapcsolatok (nyilak) amik alacsonyabb rendűek mint a megadott Minél közelebbi rokon a felhasználó és a családfában szereplő személy annál alacsonyabb rendű a kapcsolat
* Családtag törlése, szerkesztése
  * Ha egy családtagot reprezentáló objektumot kijelölünk, 
    * akkor szerkeszthetjük egy az objektum jobb felső sarkában megjelenő ikonra kattintva. Ekkor az "Új családtag felvétele"-nél felugró ablakban megjelenik az éppen kiválasztott személy adatait.
    * vagy törölhetjük. EkkorÉrtelem szerűen az adatbázisból törölnünk kell az adott objektumot és az összes hozzá tartozó "Rokonsági kapcsolat"-ot
#### Családfák keresése
Kereshetnénk a portálon található családfák között (létrehozó alapján)
#### Családfa szerkesztése
Lehetőség lenne egy családfát többen szerkeszteni, ehhez a családfát létrehozó felhasználónak hozzá kellene rendelni a tovább szerkesztőket a fához
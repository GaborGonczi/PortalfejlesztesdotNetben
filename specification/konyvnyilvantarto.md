# Könyv nyilvántartó rendszer

Az alkalmazás célja, hogy a felhasználók webes felületen tudják követni az otthonukban megtalálható könyveket ezzel időt spórolva nekik, ha kíváncsiak arra, hogy egy adott könyv megvan-e nekik vagy el kell menniük kikölcsönözni a könyvtárból.

## Funkcionális követelmények
* Felhasználói fiók létrehozása(regisztráció)
* Belépés
### Belülről elérhető funkciók

#### Profil

     A felhasználó itt a fiókjához tartozó  néhány adatot kezelheti: felhasználói név  változtatása, Jelszó változtatása,  e-mailcím változtatása, profil törlése

#### Saját könyveim
* Könyvek listázása
    * Lista rendezés a fejlécre kattintva növekvő ill csökkenő módon
* Keresési funkció
    * Részletes keresés
        * Szerző, cím, kiadás éve, kiadó, tárgyszó, témakör
    * Egyszerű keresés
        * Szerző, cím
* Könyv hozzáadása
  *  Szerző
  *  Cím
  *  Kiadás éve
  *  Kiadó
  *  Tárgyszó
  *  Témakör
  *  Leírás
  *  Kép
  *  [Hely](#könyveim-elrendezése) 
* Könyv törlése

#### Könyveim elrendezése
Grafikus felületen látható lenne, hogy milyen elrendezésben vannak tárolva a könyvek
* Polc hozzáadása
  * Méret
  * Azonosító
  * Pozíció
  * stb


#### Könyv keresése ismerőseink könyvei között (ez opcionális)
Lehetőség lenne az általunk barátoknak jelölt emberek könyvei között keresni, ha a sajátjainkban nem találunk meg. Ha megtaláltuk a keresett könyvet üzenetben felvehetjük, a tulajdonossal a kapcsolatot a könyv "kikölcsönzésével" kapcsolatos részletek megbeszéléséhez
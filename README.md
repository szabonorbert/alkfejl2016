# Mafia todo

Ha a szervezett bűnözésnek készítenénk todo rendszert, természetesen nem így csinálnánk. Ez inkább szimuláció.

##Funkcionális követelmények
*Vendégként:*

+ szeretném látni az aktuális feladatokat felsorolva (rejtett szöveggel) és azok nehézségét
+ szeretnék regisztrálni, hogy családtagként én is végezhessek feladatot


*Felhasználóként:*

+ szeretnék belépni az oldalra
+ szeretném elolvasni a feladat címét, pontos leírását és nehézségét
+ szeretném elvégezni a feladatot
+ szeretném a profiladataimat szerkeszteni
+ szeretnék kijelentkezni


*Családfőként:*
+ szeretnék új feladatot kiírni
+ szeretném látni az összes feladatról, hogy ki és mikor végezte el


##Nem funkcionális követelmények

+ Felhasználóbarát
+ Biztonságos
+ Gyors hozzáférés


##Use-case
![Use-case](https://github.com/szabonorbert/alkfejl2016/blob/master/usecase.png)

##Adatmodellek
![Data](https://github.com/szabonorbert/alkfejl2016/blob/master/data.png)

##Szerepkörök
+ *Vendég:* megnézheti az aktuális feladatok listáját és a feladatokhoz tartozó nehézséget (de nem láthatja a feladat címét és leírását, ez "titkos"). Ezenkívül regésztrálhat a családba, hogy ő is hozzájárulhasson a "cég" tevékenységéhez.
+ *Családtag:* láthatja az aktuális teljes feladatlistát, azaz címeket, leírásokat és nehézségeket. Feladatot jelölhet elvégzettnek.
+ *Családfő (Don):* Ha egy családtag családfő is, akkor a családtag számára elérhető funckiókon kívül adhat hozzá feladatot és láthatja az elvégzett feladatok listáját is, kiegészítve az elvégzés dátumával és a végrehajtó azonosítójával.

##Oldaltérkép
**Publikus:**
+ Feladatlista (csak nehézség)
+ Bejelentkezés
+ Regisztráció

**Családtag:**
+ Feladatlista (teljes)
  + Feladat elvégzése
+ Profiladatok
  + Profil szerkesztése
+ Kijelentkezés

**Családfő:**
+ Feladatlista (teljes)
  + Feladat elvégzése
  + Feladat hozzáadása
+ Elvégzett feladatok listája
+ Profiladatok
  + Profil szerkesztése
+ Kijelentkezés

##Folyamatok
Hamarosan.

##Végpontok
Hamarosan.

##Vázlatok
Hamarosan.

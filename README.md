## Alkalmazások fejlesztése (1. beadandó feladat)
### Császári Attila (TTDFU6)

#### Megtekintés a Heroku webszerveren
https://http://alkfejlbeadveglegescsattila.herokuapp.com/

#### Feladat leírása
A cél egy családi teendők menedzselését biztosító egyszeű internetes alkalmazás elkészítése.

#### Funkciók
* Regisztráció
* Bejelentkezés
* Új teendő flevétele
* Meglévő teendő törlése
* Meglévő teendő szerkesztése

A teendők adatbázisához csak regisztrációt követően lehet hozzáférni. Azaz ezután tudunk újat hozzáadni, törölni és szerkeszteni. A program az adatokat fájlban tárolja.

#### Szemantikus URIk
* /errors/edit - Szerkesztés
* /errors/list - Hibalista megjelenítése
* /errors/new - Új hiba felvétele
* /login/index - Bejelentkezési oldal
* /login/signup - Regisztrációs oldal

#### Adatbázismodellek
![Spongya](http://kepfeltoltes.hu/151108/jogosultsagok_www.kepfeltoltes.hu_.png)

#### A futtatáshoz szükséges az alábbiak megléte:
- Egy javascript futtatására alkalmas böngésző (Edge, Firefox, Chrome, Safari, Opera)

#### Fejlesztőknek
- Github repository klónozása után egy ``` npm init ``` parancsot kell kiadnunk.
- ``` npm install ``` segítségével telepíthetők a szükséges csomagok a fejlesztéshez a ``` package.json ``` alapján.
- NodeJS szükséges a futtatáshoz



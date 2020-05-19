Posistemė skirta SAULĖ IS duomenų viešinimo procesų tvarkymui, prenumeratų procesų valdymui ir apklausų sudarymui, 
atlikimui ir automatiniam rezultatų apskaičiavimui. Posistemė užtikrina automatinį duomenų viešinimą išoriniame portale, 
socialiniuose tinkluose, informacijos perdavimą kitoms IS ir kitiems informacijos viešinimo priemonėms 
įvairiais nustatytais duomenų pateikimo formatais (įskaitant, bet neapsiribojant, API (XML). 
Šios posistemės aprašyme pateikiami šie procesai:
*	SAULĖ IS duomenų viešinimas;
*	SAULĖ IS prenumeratų valdymas;
*	Apklausų sudarymas ir valdymas.


* [3.3.4.1	SAULĖ IS informacijos viešinimas](#user-content-3341-saulė-is-informacijos-viešinimas)
* [3.3.4.2	SAULĖ IS prenumeratų valdymas](#user-content-3342-saulė-is-prenumeratų-valdymas)
* [3.3.4.3	Apklausų sudarymas ir valdymas](#user-content-3343-apklausų-sudarymas-ir-valdymas)

-----------------------------------
## 3.3.4.1 SAULĖ IS informacijos viešinimas

Proceso trumpas aprašymas: 

Procesas skirtas SAULĖ IS saugomų duomenų viešinimo veiklų automatizavimui. Procesas užtikrina galimybę Sistemos administratoriui:
•	Nustatyti automatines duomenų ar jų grupių viešinimo/neviešinimo taisykles;
•	Nustatyti automatiškai viešinamų duomenų pateikimo formatą, vietą, dažnumą ir kt. taisykles;
•	Nustatyti automatiškai viešinamų duomenų panaikinimo (neviešinimo) terminą;
•	Nustatyti SAULĖ IS naudotojų analizės parametrus (Google analitika ar lygiavertės programinės įrangos pagalba), rodiklius ar kitą naudotojų žingsnių analitinę analizę.

Kokiais atvejais procesas inicijuojamas – esant poreikiui viešinti SAULĖ IS duomenis. 

3.19 lentelė. Proceso dalyviai

Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Sistemos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Nustato automatines SAULĖ IS duomenų ar jų   grupių viešinimo/neviešinimo taisykles;   ¨         Nustato automatiškai viešinamų duomenų   pateikimo formatą, vietą, dažnumą ir kt. taisykles;   ¨         Nustato automatiškai viešinamų duomenų   panaikinimo (neviešinimo) terminą.
SAULĖ IS | Sistema, kurioje atliekami   veiksmai
Kitų organizacijų IS | Sistemos, kurios per   integracinę sąsają (API, XML formatu) gauna SAULĖ IS viešinamus duomenis

Procese aprašomas šių rezultatų pasiekimas:
•	Informacijos viešinimas. 

Procesas „SAULĖ IS informacijos viešinimas“ yra susijęs su visais SAULĖ IS procesais.


Proceso įeitis (angl. input) | Proceso rezultatas   (angl. output) | Lydintys ar įtakojantys   dokumentai
-- | -- | --
SAULĖ IS kaupiami duomenys | Išviešinta reikiama informacija ir duomenys | -

![image](https://user-images.githubusercontent.com/61745726/81939895-99567280-95ff-11ea-9cd9-a6df28ab5b2d.png) 3.8 pav. Proceso „SAULĖ IS informacijos viešinimas“ diagrama

3.21 lentelė. Proceso SAULĖ IS informacijos viešinimas“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis viešinti informaciją | Sistemos administratorius | Iškilo poreikis viešinti informaciją. |   |  
T1 | Pasirinkti duomenis / duomenų paketą | Sistemos administratorius | Sistemos administratorius pasirenka pavienius   duomenis arba duomenų paketus, kuriuos nori viešinti. | Turi būti galima pasirinkti pavienius duomenis.   Turi būti galima pasirinkti duomenų paketus. |  
T2 | Nustatyti viešinimo parametrus | Sistemos administratorius | Sistemos   administratorius pasirenka viešinimo formatą. | Turi būti galimybė pasirinkti viešinimo formatą. |  
T3 | Pasirinkti viešinimo kanalą (-us) | Sistemos administratorius | Sistemos administratorius pasirenka viešinimo kanalą   (Facbeook, twitter, el. paštas, kitos informacinės sistemos (web   service priemonėmis) ir kt.) ir duomenų pateikimo formatą. | Turi būti galimybė pasirinkti viešinimo kanalą. |  
T4 | Nustatyti viešinimo periodiškumą | Sistemos administratorius | Sistemos administratorius   nustato viešinimo periodiškumą (data nuo iki). | Turi būti galimybė nustatyti viešinimo periodiškumą. |  
T5 | Nustatyti viešinimo algoritmą | Sistemos administratorius | Sistemos administratorius nustato viešinimo algoritmą   (Pvz.: Informacijos paketas apie statybas bus viešinamas, jei įrašyta   medžiaga „medis“ ir visi susiję pirkimai.). | Turi būti galimybė nustatyti viešinimo algoritmą. |  
T6 | Išsaugoti nustatyti parametrus | Sistemos administratorius | Sistemos administratorius inicijuoja parametrų   išsaugojimo veiksmą. | Sistemos administratoriui inicijavus veiksmą saugoti   parametrus turi išsaugoti nustatytus parametrus. |  
E2 | Proceso pabaiga | Sistemos administratorius | - | - |  


## 3.3.4.2 SAULĖ IS prenumeratų valdymas

Proceso trumpas aprašymas: 

Procesas skirtas SAULĖ IS prenumeratorių ir jiems siunčiamos informacijos valdymui. Procesas užtikrina galimybę:
•	Automatiniu būdu registruoti prenumeratorius ir jų pageidautą gauti informaciją;
•	Automatiniu būdu registruoti prenumeratoriams siunčiamos informacijos formatą ir kanalus – el. paštu, žinute į mobilų telefoną ar kt.; 
•	Automatiniu būdu, prenumeratoriui pageidavus, atlikti pateikiamos informacijos vertimą;
•	Automatiniu būdu išregistruoti prenumeratorius;
•	Sistemos administratoriui rankiniu būdu registruoti prenumeratorių ir/ar keisti prenumeratorių nustatymus. 
Kokiais atvejais procesas inicijuojamas – naudotojui pažymėjus poreikį gauti tam tikrą informaciją. 

3.22 lentelė. Proceso dalyviai


Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Naudotojas | Dalyvis atlieka šiuos veiksmus:   ¨         Išreiškia pageidavimą tapti prenumeratoriumi;   ¨         Pasirenka kokią informaciją ar duomenis (jų   grupes) pageidauja gauti;   ¨         Pasirenka, kokiu formatu pageidauja gauti   informaciją;   ¨         Keisti prenumeratos nustatymus.
Sistemos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Jei gaunamas prašymas, registruoti   prenumeratorių ir/ar keisti prenumeratorių nustatymus.
SAULĖ IS | ¨         Automatiniu būdu registruoja prenumeratorius   ir jų pageidautą gauti informaciją;   ¨         Automatiniu būdu registruoja prenumeratoriams   siunčiamos informacijos formatą ir kanalus – el. paštu, žinute į mobilų   telefoną ar kt.;    ¨         Automatiniu būdu, prenumeratoriui pageidavus,   atlieka pateikiamos informacijos vertimą;   ¨         Automatiniu būdu išregistruoja   prenumeratorius.

Procese aprašomas šių rezultatų pasiekimas:
•	Informacijos sklaida. 

Procesas „SAULĖ IS prenumeratorių valdymas“ yra susijęs su procesu „SAULĖ IS viešinimas“.

3.23 lentelė. Proceso „SAULĖ IS prenumeratorių valdymas“ rezultatas ir lydintys dokumentai

Proceso įeitis (angl. input) | Proceso rezultatas   (angl. output) | Lydintys ar įtakojantys   dokumentai
-- | -- | --
Išreikštas naudotojo pageidavimas gauti atitinkamą   informaciją/duomenis | Prenumeratoriui pateikta informacija ir duomenys | -

![image](https://user-images.githubusercontent.com/61745726/81940249-11bd3380-9600-11ea-82c9-291d0844d509.png) 3.9 pav. Proceso „SAULĖ IS prenumeratorių valdymas“ diagrama

3.24 lentelė. Proceso SAULĖ IS prenumeratorių valdymas“ aprašymas


Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis redaguoti prenumeratą | Naudotojas, organizacijos administratorius | Naudotojui, organizacijos administratoriui iškyla   poreikis redaguoti prenumeratą. |   |  
T1 | Inicijuoti veiksmą susijusį su prenumerata | Naudotojas, organizacijos administratorius | Naudotojas, organizacijos administratorius inicijuoja   veiksmą susijusį su prenumerata:   ¨         Užsisakyti prenumeratą;   ¨         Redaguoti prenumeratos parametrus;   ¨         Atsisakyti / pašalinti prenumeratą. | Turi būti galima užsisakyti prenumeratą.   Turi būti galima redaguoti prenumeratos parametrus.   Turi būti galima atsisakyti prenumeratos.   Turi būti galima pašalinti prenumeratą. |  
T2 | Pasirinkti informaciją / duomenis | Naudotojas, organizacijos administratorius | Pasirenkami   duomenys, duomenų grupė, kurią naudotojas nori prenumeruoti. | Turi būti galima pasirinkti duomenis arba duomenų   grupė. |  
T3 | Nustatyti parametrus | Naudotojas, organizacijos administratorius | Nustatomi parametrai į kur siųsti prenumeratą, kokiu   dažnumu naudotojas gaus prenumeratą. | Turi būti galima nustatyti prenumeratos gavimo   dažnumą.   Turi būti galima nustatyti prenumeravimo kanalą. |  
T4 | Redaguoti prenumeratą | Naudotojas, organizacijos administratorius | Naudotojas redaguoja   prenumeratos parametrus (pvz. pakeičia dažnumą, siuntimo adresą, informacijos   temą). | Turi būti galima redaguoti prenumeratą. |  
T5 | Pašalinti prenumeratą | Organizacijos administratorius | Organizacijos administratorius gali ištrinti   organizacijos naudotojo prenumeratą. | Turi būti galima pašalinti prenumeratą. |  
T6 | Atsisakyti prenumeratos | Naudotojas | Naudotojas atsisako prenumeratą:   ¨         Gaunamu kanalu;   ¨         Prisijungus per paskyrą. | Turi būti galima atsisakyti prenumeratos. |  
E2 | Proceso pabaiga | Naudotojas, organizacijos administratorius | - | - |  

## 3.3.4.3 Apklausų sudarymas ir valdymas

Proceso trumpas aprašymas: 

Procesas skirtas SAULĖ IS naudotojų apklausų sudarymui ir valdymui. Procesas užtikrina galimybę:
•	Kurti apklausas;
•	Publikuoti ir atšaukti publikavimą išoriniame portale;
•	Redaguoti ir šalinti apklausas;
•	Peržiūrėti apklausų rezultatus
•	Eksportuoti apklausų rezultatus.
 
Kokiais atvejais procesas inicijuojamas – esant poreikiui, atlikti naudotojų apklausą SAULĖ IS išoriniame portale.  

3.25 lentelė. Proceso dalyviai

Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Pagalbos posistemės specialistas | Dalyvis atlieka šiuos veiksmus:   ¨         Kuria apklausas;   ¨         Publikuoja ir atšaukia publikavimą išoriniame   portale;   ¨         Redaguoja ir šalina apklausas;   ¨         Peržiūri apklausų rezultatus   ¨         Eksportuoja apklausų rezultatus.
SAULĖ IS | Sistema, kurioje atliekami veiksmai


Procese aprašomas šių rezultatų pasiekimas:
•	Atlikta apklausa. 

Procesas „Apklausų sudarymas ir valdymas“ yra susijęs su procesu „SAULĖ IS viešinimas“.

3.26 lentelė. Proceso „Apklausų sudarymas ir valdymas“ rezultatas ir lydintys dokumentai

Proceso įeitis (angl. input) | Proceso rezultatas   (angl. output) | Lydintys ar įtakojantys   dokumentai
-- | -- | --
Apklausos klausimynas | Publikuota apklausa | -

![image](https://user-images.githubusercontent.com/61745726/81940441-44ffc280-9600-11ea-9f42-c1c2946522be.png) 3.10 pav. Proceso „Apklausų sudarymas ir valdymas“ diagrama

3.27 lentelė. Proceso „Apklausų sudarymas ir valdymas“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Redaguoti apklausą (-as) | Pagalbos posistemės administratorius | Pagalbos posistemės administratoriui iškyla poreikis   redaguoti apklausą. | - |  
T1 | Pasirinkti apklausos funkcionalumą | Pagalbos posistemės administratorius | Pagalbos posistemės administratorius pasirenka   apklausos funkcionalumą. |   |  
T2 | Kurti apklausą | Pagalbos posistemės administratorius | Pagalbos   posistemės administratorius pasirenka kurti apklausą, nurodomi klausimai,   nurodoma klausimo validacija. | Turi būti galima kurti apklausą.   Turi būti galima nurodyti klausimyno parametrus   (klausimai, validacijos ir kt.). |  
T3 | Pasirinkti apklausą | Pagalbos posistemės administratorius | Pasirenkama apklausa iš esamų apklausų. | Turi būti galima pasirinkti apklausą. |  
T4 | Redaguoti apklausą | Pagalbos posistemės administratorius | Pasirinkus apklausą galima pasirinkti redaguoti.   Redaguojami klausimai, klausimų išdėstymas, klausimo tipas, klausimo   validacija. | Turi būti galima nurodyti klausimyno parametrus   (klausimai, validacijos ir kt.). |  
T5 | Peržiūrėti apklausą | Pagalbos posistemės administratorius | Pasirinkus apklausą galimą peržiūrėti apklausą:    ¨         Redagavimo režimu;   ¨         Peržiūros režimu. | Turi būti galima peržiūrėti apklausą peržiūros   režimu.   Turi būti galima peržiūrėti apklausą redagavimo   režimu. |  
T6 | Eksportuoti apklausą | Pagalbos posistemės administratorius | Pasirinkus apklausą galima   eksportuoti apklausos rezultatus. | Turi būti galima eksportuoti apklausos rezultatus. |  
T7 | Publikuoti apklausą | Pagalbos posistemės administratorius | Pasirikus apklausą galima ją   publikuoti. | Turi būti galima publikuoti apklausą. |  
T8 | Pašalinti apklausą | Pagalbos posistemės administratorius | Pasirinktą apklausą galima   pašalinti. | Turi būti galima pašalinti apklausą. |  
E2 | Proceso pabaiga | Pagalbos posistemės administratorius | - | - |  



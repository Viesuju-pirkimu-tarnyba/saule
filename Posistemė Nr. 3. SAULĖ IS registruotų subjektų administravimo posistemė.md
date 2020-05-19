Posistemė skirta visoms SAULĖ IS organizacijoms, kurios vykdys pirkimus, dalyvaus pirkimuose ar vykdys pirkimų priežiūros funkcijas. Posistemės tikslas – registruoti organizacijas, naudotojus ir valdyti jų roles bei teises. Ši sistemos dalis prieinama tik prisiregistravusiems naudotojams.

SAULĖ IS registruotų subjektų administravimo posistemė skirta:
* Organizacijų registravimui;
* Naudotojų autentifikavimui;
* Organizacijos naudotojų valdymui;
* Sistemos administratoriaus ir organizacijos administratoriaus funkcijų perdavimo valdymui;
* Pirkimų vykdytojų, Tiekėjų ir Išorinių kontrolierių veiksmų sistemoje autorizavimui (teisių priskyrimui);
* Organizacijos ir naudotojų deaktyvavimui.

[3.3.3.1 Organizacijų registravimo procesas](#user-content-3331organizacijų-registravimo-procesas)
[3.3.3.2 Naudotojo autentifikavimo procesas](#user-content-3332naudotojo-autentifikavimo-procesas)
[3.3.3.3 Organizacijos naudotojų valdymas](#user-content-3333organizacijos-naudotojų-valdymas)
[3.3.3.4 Sistemos ar Organizacijos administratoriaus funkcijų perdavimo valdymo procesas](#user-content-3334sistemos-ar-organizacijos-administratoriaus-funkcijų-perdavimo-valdymo-procesas)
[3.3.3.5 Pirkėjų, Tiekėjų ir Išorinių kontrolierių veiksmų sistemoje autorizavimo procesas (rolių bei teisių administravimas)](#user-content-3335pirkėjų-tiekėjų-ir-išorinių-kontrolierių-veiksmų-sistemoje-autorizavimo-procesas-rolių-bei-teisių-administravimas-)
[3.3.3.6 Organizacijos deaktyvavimas](#user-content-3336organizacijos-deaktyvavimas)

## 3.3.3.1	Organizacijų registravimo procesas

Proceso trumpas aprašymas: 

Procesas skirtas Organizacijų ir organizacijų administratorių registravimui sistemoje, informacijos apie organizaciją tvarkymui.

Kokiais atvejais procesas inicijuojamas: 

a)	Esant poreikiui registruoti SAULĖ IS organizaciją.

3.3 lentelė. Proceso dalyviai

Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Sistemos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Jei užsienio šalies atstovas arba būtina   naudotojui išduoto įgaliojimo atstovauti Organizaciją peržiūra, tvirtina   Organizacijos duomenis.
Organizacijos atstovas | Dalyvis atlieka šiuos veiksmus:   ¨         Autentifikuojasi SAULĖ IS;   ¨         Patvirtina Organizacijos paskyrą.
Autentifikuotas naudotojas | Dalyvis atlieka šiuos veiksmus:    ¨         Jei yra galimybė, autentifikuojasi VIISP   priemonėmis;   ¨         Jei nėra galimybės (užsienio pilietis apie   kurį nėra duomenų VIISP ar Užsieniečių registre) autentifikuotis VIISP   priemonėmis, teikia paraišką be autentifikavimo;   ¨         Atlieka Organizacijos registravimo veiksmus.
VIISP (IVPK) | Naudotojo autentifikavimas
Užsieniečių registras (VRM) | Naudotojo autentifikavimas
Įgaliojimų registras (RC) | Įgaliotų asmenų duomenys
JAR (RC) | Juridinio asmens duomenys
VTEK | Privačių interesų derinimo   deklaracijų duomenys
SAULĖ IS | Sistema, kurioje atliekami   veiksmai

Procese aprašomas šių rezultatų pasiekimas:
•	SAULĖ IS Organizacijos ir Organizacijos administratorius paskyros sukūrimas. 

Procesas „Organizacijų registravimas“ yra susijęs su visais SAULĖ IS procesais.

3.4 lentelė. Proceso „Organizacijų registravimas“ rezultatas ir lydintys dokumentai

Proceso įeitis (angl. input) | Proceso rezultatas   (angl. output) | Lydintys ar įtakojantys   dokumentai
-- | -- | --
Naudotojo prisijungimas ir pateikti duomenys apie   norimą registruoti organizaciją | SAULĖ IS Organizacijai sukurta paskyra | ¨         VIISP asmens duomenys;   ¨         JAR juridinio asmens duomenys;   ¨         Įgaliojimas (jei atstovauja asmuo, kuris   remiantis JAR  neturi teisių atstovauti   Organizacijos);   ¨         Esant poreikiui (užsienio ūkio subjektas),   skanuoti Organizacijos registracijos ir naudotojo asmens dokumentai.

![image](https://user-images.githubusercontent.com/61745726/81938511-b12cf700-95fd-11ea-9af5-8c7a05d68a5a.png)3.2 pav. Proceso „Organizacijos registravimas Lietuvos piliečiui“ diagrama

3.5 lentelė. Proceso „Organizacijos registravimas Lietuvos piliečiui“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis sukurti organizaciją | Organizacijos administratorius | Iškyla poreikis sukurti organizaciją. | - |  
T1 | Autentifikuoti naudotoją | SAULĖ IS | Autentifikacija vyksta per VIISP sistemą. Autentifikacijai įvykus   tikrinama ar fizinis ar juridinis asmuo:   ·          Jei juridinis   asmuo, toliau vykdomas žingsnis „T2 tikrinti įgaliojimą išorinėse sistemose“;   ·          Jei fizinis   asmuo, toliau vykdomas žingsnis „T7 Sukurti organizaciją“. | Turi būti autentifikuojamas naudotojas. |  
T2 | Tikrinti organizacijos atstovavimo teisę išorinėse   sistemose | SAULĖ IS | Tikrinama ar naudotojas turi Organizacijos   atstovavimo teisę (VIISP, Įgaliojimų registre, JAR*).       *JAR – JAR arba kita RC valdoma / tvarkoma   informacinė sistema. | Turi būti tikrinama organizacijos atstovavimo teisė. |  
T3 | Patikrinti atstovavimą | SAULĖ IS | Jei JAR nerandama, kad naudotojas yra Organizaciją   atstovaujantis asmuo, tikrinama, ar nėra registruoto įgaliojimo Įgaliojimų   registre. | Turi būti galimybė gauti duomenis iš JAR. |  
T4 | Patikrinti deklaraciją ir atvaizduoti pranešimą | SAULĖ IS | Patikrinama ar Pirkimo vykdytojo atstovas yra   užpildęs deklaraciją:    ·          jei nėra užpildęs deklaracijos informuojamas   pranešimu, kad nėra užpildęs deklaracijos;   ·          jei deklaracija užpildyta, naudotojas   informuojamas sėkmės pranešimu. |   |  
T5 | Išsiųsti pranešimą atstovaujančiam asmeniui | SAULĖ IS | Išsiunčiamas pranešimas organizacijos atstovui su   nuoroda į kuriamą organizacijos paskyrą. | Turi būti galimybė išsiųsti pranešimą organizacijos   atstovui, pagal gautus atstovavimo duomenis iš JAR. |  
T6 | Peržiūrėti duomenis | Organizacijos atstovas | Organizacijos atstovas   peržiūri, kuriamos organizacijos duomenis. | Turi būti galimybė peržiūrėti kuriamos organizacijos   duomenis. |  
T7 | Patvirtinti duomenis | Organizacijos atstovas | Organizacijos atstovas patvirtina organizacijos   duomenis. | Turi būti galimybė organizacijos atstovui patvirtinti   organizacijos duomenis. |  
T8 | Sukurti organizaciją | SAULĖ IS | Automatiškai sukuriama organizacija SAULĖ IS. | Turi automatiškai susikurti   organizacijos paskyra:   ·          Jei organizacijos atstovas patvirtina;   ·          Jei kuria organizaciją fizinis asmuo. |  
T9 | Automatiškai išsiųsti pranešimą | SAULĖ IS | Automatiškai išsiunčiamas pranešimas naudotojams,   informuojantis:   ·          Sukurtą organizaciją;   ·          Atmestą organizacijos kūrimą. | Turi būti automatiškai išsiunčiamas pranešimas   informuojantis apie sistemoje:    ·          patvirtintą organizacijos kūrimą;   ·          nepatvirtintą organizacijos kūrimą. |  
T10 | Nepatvirtinti duomenų | Organizacijos atstovas | Jei organizacijos atstovas nekuria organizacijos   SAULĖ IS, tokiu atveju nepatvirtina duomenų. | Turi būti galimybė organizacijos atstovui   nepatvirtinti organizacijos duomenų. |  
T11 | Prisegti pasirašytą įgaliojimą | Organizacijos administratorius | Prisegamas pasirašytas įgaliojimas. | Turi būti galimybė prisegti dokumentus. |  
T12 | Patikrinti deklaraciją ir atvaizduoti pranešimą | SAULĖ IS | Patikrinama ar pirkimo vykdytojo atstovas yra   užpildęs deklaraciją:    ·          jei nėra užpildęs deklaracijos informuojamas   pranešimu, kad nėra užpildęs deklaracijos;   ·          jei deklaracija užpildyta, naudotojas   informuojamas sėkmės pranešimu. |   |  
T13 | Patikrinti deklaraciją ir atvaizduoti pranešimą | SAULĖ IS | Patikrinama ar pirkimo vykdytojo atstovas yra   užpildęs deklaraciją:    ·          jei nėra užpildęs deklaracijos informuojamas   pranešimu, kad nėra užpildęs deklaracijos;   ·          jei deklaracija užpildyta, naudotojas   informuojamas sėkmės pranešimu. |   |  
T14 | Automatiškai išsiųsti pranešimą su nuoroda | SAULĖ IS | Jei randa įgaliojimą   įgaliojimų registre, automatiškai išsiunčia laišką sistemos administratoriui. | Turi automatiškai išsiųsti pranešimą, apie kuriamą   organizaciją, jei įgaliojimų registre randamas įgaliojimas. |  
T15 | Tikrinti pateiktus duomenis | Sistemos administratorius | Sistemos administratorius patikrina gautus duomenis. | Turi būti galimybė patikrinti duomenis. |  
T16 | Patvirtinti duomenis | Sistemos administratorius | Jei duomenys pateikti teisingi, sistemos   administratorius patvirtina organizacijos sukūrimą. | Turi būti galima patikrinti duomenis.   Turi būti galimybė patvirtinti organizacijos kūrimą. |  
T17 | Sukurti organizaciją | SAULĖ IS | Automatiškai sukuriama organizacija. | Turi automatiškai sukurti organizaciją, jei sistemos   administratorius patvirtina gautus duomenis. |  
T18 | Automatiškai išsiųsti pranešimą | SAULĖ IS | Jei duomenys patvirtinami – automatiškai išsiunčiamas   pranešimas organizacijos administratoriui su pranešimu apie sėkmingai sukurtą   organizacijos paskyrą.   Jei duomenys nepatvirtinami - automatiškai   išsiunčiamas pranešimas organizacijos administratoriui dėl nepatvirtintų   duomenų. | Turi automatiškai išsiųsti pranešimą. |  
T19 | Nepatvirtinti duomenų | Sistemos administratorius | Jei duomenys pateikti neteisingi, sistemos   administratorius nepatvirtina duomenų ir nurodo priežastį. | Turi būti galima patikrinti duomenis.   Turi būti galimybė nepatvirtinti organizacijos   kūrimą. |  
E2 | Proceso pabaiga | Sistemos administratorius | - | - |  

![image](https://user-images.githubusercontent.com/61745726/81938601-ce61c580-95fd-11ea-84c3-b1e2005f3e10.png) 3.3 pav. Proceso „Organizacijos registravimas užsienio piliečiui“ diagrama


3.6 lentelė. Proceso „Organizacijos registravimas užsienio piliečiui“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis sukurti organizaciją | Organizacijos administratorius | Poreikis sukurti organizaciją   iškylą užsienio piliečiams. | - |  
T1 | Autentifikuoti naudotoją | SAULĖ IS | Autentifikuoti naudotoją per VIISP sistemą.   VIISP sistemoje pasirinkta užsienio autentifikacijos sistema. | Turi būti autentifikuojamas naudotojas. |  
T2 | Pateikti organizacijos duomenis | Organizacijos administratorius | Pasirenkama organizacija (jei yra daugiau nei viena   organizacija), pateikiama, kad norima kurti pasirinktai organizacijai   organizacijos paskyrą. | Turi būti galimybė pasirinkti organizaciją.   Turi būti galimybė išsiųsti sistemos administratoriui   prašymą, pasirinktos organizacijos paskyros sukūrimui. |  
T3 | Pateikti prašymą ir pridėti skanuotus dokumentus | Organizacijos administratorius | Pateikiamas prašymas sistemos administratoriui ir   pateikiami skanuoti dokumentai. | Turi būti galimybė užpildyti formą.   Turi būti galimybė prisegti dokumentus. |  
T4 | Tikrinti pateiktus duomenis | Sistemos administratorius | Patikrinami pateikti duomenys. | Turi būti patikrinti pateiktus duomenis. |  
T5 | Patvirtinti duomenis | Sistemos administratorius | Jei duomenys pateikti teisingi, sistemos administratorius   patvirtina organizacijos sukūrimą. | Turi būti galimybė patvirtinti dokumentus. |  
T6 | Sukurti organizaciją | SAULĖ IS | Automatiškai sukuriama organizacija | Turi automatiškai sukurti organizaciją, jei sistemos   administratorius patvirtina gautus duomenis. |  
T7 | Automatiškai išsiųsti pranešimą | SAULĖ IS | Jei duomenys patvirtinami – automatiškai išsiunčiamas   pranešimas organizacijos administratoriui su pranešimu apie sėkmingai sukurtą   organizacijos paskyrą.   Jei duomenys nepatvirtinami - automatiškai   išsiunčiamas pranešimas organizacijos administratoriui dėl nepatvirtintų   duomenų. | Turi automatiškai išsiųsti pranešimą. |  
T8 | Nepatvirtinti duomenų | Sistemos administratorius | Jei duomenys pateikti neteisingi, sistemos   administratorius nepatvirtina duomenų ir nurodo priežastį. | Turi būti galima patikrinti duomenis.   Turi būti galimybė nepatvirtinti organizacijos   kūrimą. |  
E2 | Proceso pabaiga | Sistemos administratorius | - | - |  

## 3.3.3.2	Naudotojo autentifikavimo procesas

Proceso trumpas aprašymas: 

Procesas skirtas naudotojo registravimui SAULĖ IS.

Kokiais atvejais procesas inicijuojamas: 

a)	Esant poreikiui registruoti naudotoją SAULĖ IS.

3.7 lentelė. Proceso dalyviai

Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Organizacijos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Patvirtina naudotojo paraišką tapti   Organizacijos naudotoju;   ¨         Atlieka naudotojo registravimą ir sukuria   paskyrą;   ¨         Patvirtina arba priskiria naudotojui rolę bei   teises.
Naudotojas | Dalyvis atlieka šiuos veiksmus:    ¨         Jei yra galimybė, autentifikuojasi VIISP   priemonėmis;   ¨         Jei nėra galimybės (užsienio pilietis apie   kurį nėra duomenų VIISP ar Užsieniečių registre), organizacinėmis priemonėmis   teikia paraišką tapti Organizacijos naudotoju
VIISP (IVPK) | Naudotojo autentifikavimas
Užsieniečių registras (VRM) | Naudotojo autentifikavimas
SFMIS (FM) | Jei atstovauja Įgyvendinančią   instituciją - naudotojo duomenys, jo rolė ir teisės
VTEK | Privačių interesų derinimo   deklaracijų duomenys
SAULĖ IS | Sistema, kurioje atliekami   veiksmai

Procese aprašomas šių rezultatų pasiekimas:
•	SAULĖ IS registruoto naudotojo sukūrimas. 

Procesas „Naudotojo autentifikavimas“ yra susijęs su šiais procesais:
•	SAULĖ IS Organizacijos registravimas;
•	Viešųjų pirkimų planavimas;
•	Viešųjų pirkimų procedūrų vykdymas;
•	Viešųjų pirkimų dokumentų tvarkymas;
•	Viešųjų pirkimų sutarčių valdymas;
•	Komunikacija (susirašinėjimas);
•	Preliminariųjų sutarčių posistemės procesais;
•	Įgyvendinančių institucijų posistemės procesais.

3.8 lentelė. Proceso „Naudotojo autentifikavimas“ rezultatas ir lydintys dokumentai

Proceso įeitis (angl. input) | Proceso rezultatas   (angl. output) | Lydintys ar įtakojantys   dokumentai
-- | -- | --
Naudotojo prisijungimas ir Organizacijos pasirinkimas | Sukurtas SAULĖ IS naudotojas | ¨         VIISP asmens duomenys;   ¨         EDAS duomenys apie naudotojo darbovietes;   ¨         JAR juridinio asmens duomenys;   ¨         SFMIS (jei norima tapti Įgyvendinančios   institucijos naudotoju) duomenys;   ¨         Užsieniečių registro duomenys, jei užsienio   pilietis;   ¨         Jei registruojama organizacinėmis priemonėmis   – asmens dokumentas ir kiti Organizacijos vidine tvarka nustatyti dokumentai.

![image](https://user-images.githubusercontent.com/61745726/81938739-0537db80-95fe-11ea-844f-8c669aa10c3b.png) 3.4 pav. Proceso „Naudotojo autentifikavimo procesas“ diagrama

3.9 lentelė. Proceso „Naudotojo autentifikavimo procesas“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis atstovauti organizaciją | Naudotojas | Iškylą poreikis atstovauti organizaciją |   | -
T1 | Autentifikuoti naudotoją | Naudotojas | Autentifikuojamas   naudotojas per VIISP. Yra galimybė prisijungti vardu ir slaptažodžiu. | Turi būti galimybė prisijungti per VIISP.   Turi būti galimybė prisijungti naudojant prisijungimo   vardą ir slaptažodį. | -
T2 | Pasirinkti atstovaujamą organizaciją | Naudotojas | ·          Naudotojas gali prisijungti prie organizacijos   paskyros tokiu atveju jei organizacijos administratorius yra sukūręs   darbuotojo naudotojo teises ir roles ir SAULĖ IS randa darbuotojo atstovavimo   duomenis.    ·          Jei naudotojui nėra priskirtas organizacijos   atstovavimas, naudotojas gali rašyti prašymą organizacijos administratoriui,   tokiu atveju toliau vykdomas žingsnis „T4 Suvesti prašymo organizacijai   atstovauti duomenis“. | Naudotojas turi galimybę pasirinkti organizaciją,   kurios atstovavimas jau patvirtintas.   Naudotojas turi būti prijungiamas prie organizacijos   paskyros prie kurios atstovavimas patvirtintas.   Naudotojas turi galimybę išsiųsti prašymą   organizacijos administratoriui su pateiktais duomenimis. | -
T3 | Patikrinti deklaraciją ir atvaizduoti   pranešimą | SAULĖ IS | Patikrinama ar pirkimo vykdytojo atstovas yra   užpildęs deklaraciją:    ·          jei nėra užpildęs deklaracijos informuojamas   pranešimu, kad nėra užpildęs deklaracijos;   ·          jei deklaracija užpildyta, naudotojas   informuojamas sėkmės pranešimu. | Turi būti patikrinama naudotojo interesų derinimo   deklaraciją.   Turi būti atvaizduojamas pranešimas. |  
T4 | Suvesti prašymo organizacijai atstovauti duomenis | Naudotojas | Naudotojas suveda privalomus duomenis (vardas,   pavardė, įmonės pavadinimas, įmonės kodas ir kitus reikiamus duomenis).   Suvedus duomenis prašymui, prašymas yra siunčiamas organizacijos   administratoriui patvirtinimui. Jei prašymas buvo užpildytas įgyvendinančios   institucijos darbuotojo, toliau vykdomas žingsnis „T5 Automatiškai priskirti   rolę ir teises“. | Turi būti galima suvesti atstovavimo prašyme   duomenis.   Turi būti galima pateikti prašymą. | -
T5 | Automatiškai priskirti rolę ir teises | SAULĖ IS | Atliekamas patikrinamas ar   prašymą pateikia įgyvendinanti institucija jei prašymas pateikiamas   įgyvendinančios institucijos darbuotojo / atstovo automatiškai naudotojui   priskiriamos rolė ir teisės. | Turi būti galimybė automatiškai priskirti naudotojo   rolę ir teises. |  
T6 | Išsiųsti pranešimą | SAULĖ IS | Jei prašymą pateikia įgyvendinančios institucijos   darbuotojas / atstovas, išsiunčiamas pranešimas organizacijos   administratoriui patvirtinti paskyros sukūrimą.   Jei prašymą pateikia ne įgyvendinanti institucija   išsiunčiamas prašymas organizacijos administratoriui peržiūrėti prašymą ir   priskirti naudotojui rolę ir teises. | Turi būti automatiškai išsiunčiamas pranešimą. |  
T7 | Patvirtinti paskyrą | Organizacijos administratorius | Organizacijos administratorius peržiūrėjęs duomenis   gali patvirtinti prašymą / paskyrą ir jei reikia redaguoti naudotojo role ir   teises. | Turi būti galimybė patvirtinti naudotojo atstovavimą   organizacijoje.   Turi būti galimybė pridėti naudotojo rolę   Turi būti galimybė pridėti naudotojo teises   Turi būti galimybė pakeisti naudotojo rolę   Turi būti galimybė pakeisti naudotojo teises   Turi būti galimybė pašalinti naudotojo rolę ir (arba)   teises. |  
T8 | Priskirti naudotojui rolę ir teises | SAULĖ IS | Automatiškai priskiriamos teisės ir rolė.   Organizacijos administratoriui pridėjus naudotojo   rolę ir teises, patvirtinus informaciją automatiškai SAULĖ IS sukuria   naudotojui paskyrą su priskirta role ir teisėmis. | Turi būti galimybė automatiškai priskirti naudotojo   rolę ir teises. |  
T9 | Nepatvirtinti paskyros | Organizacijos administratorius | Organizacijos administratorius peržiūrėjęs duomenis   turi galimybę prašymo / paskyros nepatvirtinti. | Turi būti galimybė nepatvirtinti naudotojo   atstovavimo organizacijoje. |  
T10 | Išsiųsti pranešimą | SAULĖ IS | Išsiunčiamas pranešimas naudotojui nurodantis ar   naudotojo atstovavimas organizacijos patvirtintas ar nepatvirtintas. | Turi automatiškai išsiunčiamas pranešimas. |  
E2 | Proceso pabaiga | - | Naudotojas gali būti   ·          Prijungiamas prie paskyros   ·          Neprijungiamas prie paskyros | - |  



## 3.3.3.3	Organizacijos naudotojų valdymas

Proceso trumpas aprašymas: 

Procesas skirtas Organizacijos naudotojų valdymui SAULĖ IS. Procesas užtikrina galimybę:
•	kurti/naikinti naujus naudotojų profilius, rekvizitus;
•	administruoti naudotojų roles ir teises pagal nustatytą naudotojų rolių ir teisių matricą;
•	deaktyvuoti naudotojus;
•	atlikti naudotojų paiešką.

Kokiais atvejais procesas inicijuojamas: 

a)	Esant poreikiui tvarkyti naudotojo profilį;
b)	Esant poreikiui priskirti ar redaguoti naudotojo roles ir teises;
c)	Esant poreikiui atlikti naudotojų paiešką.

3.10 lentelė. Proceso dalyviai

Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Organizacijos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Atlieka naudotojų paiešką;   ¨         Priskiria arba redaguoja naudojo roles ir   teises;   ¨         Tvarko naudotojo profilį, rekvizitus.
Naudotojas | Dalyvis atlieka šiuos veiksmus:    ¨         Atlieka naudotojų paiešką;   ¨         Tvarko naudotojo profilį, rekvizitus.
SAULĖ IS | Sistema, kurioje atliekami   veiksmai

Procese aprašomas šių rezultatų pasiekimas:
•	SAULĖ IS registruoto naudotojo profilio ir rolių ir/ar teisių valdymas. 

Procesas „Organizacijos naudotojų valdymas“ yra susijęs su šiais procesais:
•	SAULĖ IS Organizacijos registravimas;
•	Įgyvendinančių institucijų posistemės procesais.

3.11 lentelė. Proceso „Organizacijos naudotojų valdymas“ rezultatas ir lydintys dokumentai

Proceso įeitis (angl. input) | Proceso rezultatas   (angl. output) | Lydintys ar įtakojantys   dokumentai
-- | -- | --
Naudotojo ar Organizacijos administratoriaus   prisijungimas | Sukurtas/redaguotas SAULĖ IS naudotojo profilis ir/ar   rolės/teisės | -

![image](https://user-images.githubusercontent.com/61745726/81938881-39ab9780-95fe-11ea-8fb7-9cd63d34b7e9.png) 3.5 pav. Proceso „Organizacijos naudotojų valdymas“ diagrama

3.12 lentelė. Proceso „Organizacijos naudotojų valdymas“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis redaguoti naudotoją | Organizacijos administratorius | - | - | -
T1 | Atlikti naudotojų paiešką | Organizacijos administratorius | Atliekama naudotojo paieška    ·          Organizacijos   naudotojų sąraše;   ·          SAULĖ IS. | Turi būti galimybė atlikti paiešką organizacijos   naudotojų sąraše.   Turi būti galimybė atlikti naudotojų paiešką   sistemoje. | -
T2 | Pasirinkti naudotoją | Organizacijos administratorius | Suradus naudotoją   pasirenkamas naudotojas. | Turi būti galimybė pasirinkti naudotoją. | -
T3 | Naudotojo registravimo procesas | Organizacijos administratorius | Naudotojas yra priskiriamas prie organizacijos.   Naudotoją priskiria rankiniu būdu organizacijos administratorius.    Kitu atveju organizacijos prisiskyrimas vykdomas iš   naudotojo pusės.    Šis sub-procesas yra   aprašomas procese „Naudotojo registravimo procesas“. | Turi būti galimybė organizacijos administratoriui   pridėti naudotoją prie organizacijos. | -
T4 | Redaguoti naudotojo paskyrą | Organizacijos administratorius | Suradus darbuotojas   organizacijos sąraše ir pasirinkus funkciją tvarkyti naudotojo paskyrą   organizacijos administratorius turi galimybę pakeisti rolę, teises,   sustabdyti / deaktyvuoti naudotoją, redaguoti informaciją.   Suradus naudotoją SAULĖ IS sąraše ir pasirinkus   funkciją tvarkyti naudotojo paskyrą organizacijos administratorius turi   galimybę pridėti naudotoją prie organizacijos. | Turi būti galimybė organizacijos naudotojui pakeisti   rolę.   Turi būti galimybė organizacijos naudotojui pakeisti   teises.   Turi būti galimybė organizacijos naudotoją   deaktyvuoti.   Turi būti galimybė organizacijos naudotoją   sustabdyti.   Turi būti galimybė pridėti sistemos naudotoją prie   organizacijos | -
T5 | Organizacijos ir sistemos   naudotojo deaktyvavimas | Organizacijos administratorius | Naudotojas yra sustabdomas   arba deaktyvuojamas organizacijos administratoriaus. | Turi būti galimybė organizacijos naudotoją   sustabdyti.   Turi būti galimybė organizacijos naudotoją   deaktyvuoti | -
T6 | Išsaugoti pakeitimą (-us) | SAULĖ IS | Išsaugomi organizacijos administratoriaus įvykdyti   pakeitimai, išsaugoma veiksmų istorija. | Turi būti išsaugomi sistemoje atlikti pakeitimai. | -
E2 | Proceso pabaiga | Organizacijos administratorius | - | - | -

## 3.3.3.4	Sistemos ar Organizacijos administratoriaus funkcijų perdavimo valdymo procesas

Proceso trumpas aprašymas: 

Procesas skirtas Sistemos administratoriaus ir/ar Organizacijos administratoriaus funkcijų perdavimui. Procesas užtikrina galimybę, esant poreikiui (atostogos, liga, išėjimas iš darbo) perduoti Sistemos administratoriaus ir/ar Organizacijos administratoriaus įgaliojimus (rolę ir teises) kitam naudotojui. 

Kokiais atvejais procesas inicijuojamas: 

a)	Esant poreikiui perduoti Sistemos ar Organizacijos administratoriaus rolę ir teises. 

3.13 lentelė. Proceso dalyviai

Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Sistemos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Atlieka naudotojų paiešką;   ¨         Priskiria naudotojui (terminuotai ar   neterminuotai) Sistemos administratoriaus rolę ir teises (Sistema   automatiškai panaikina ankstesnio Sistemos administratoriaus funkcijas).
Organizacijos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Atlieka naudotojų paiešką;   ¨         Priskiria naudotojui (terminuotai ar   neterminuotai) Organizacijos administratoriaus rolę ir teises (Sistema   automatiškai panaikina ankstesnio Sistemos administratoriaus funkcijas).
Naudotojas | Dalyvis atlieka šiuos veiksmus:    ¨         Patvirtina įgaliojimų priskyrimą;   ¨         Jei įgaliojimas priskirtas terminuotai, esant   poreikiui, pratęsia įgaliojimo priskyrimo terminą.
SAULĖ IS | Sistema, kurioje atliekami   veiksmai

Procese aprašomas šių rezultatų pasiekimas:
•	SAULĖ IS Sistemos ar Organizacijos administratoriaus rolės ir teisių perdavimas naudotojui. 

Procesas „Sistemos ar Organizacijos administratoriaus funkcijų perdavimo valdymas“ yra susijęs su šiais procesais:
•	SAULĖ IS Organizacijos registravimas;
•	Organizacijos naudotojų valdymas;
•	Naudotojo autentifikavimo procesas;
•	Įgyvendinančių institucijų posistemės procesais.

3.14 lentelė. Proceso „Sistemos ar Organizacijos administratoriaus funkcijų perdavimo valdymas“ rezultatas ir lydintys dokumentai

Proceso įeitis (angl. input) | Proceso rezultatas   (angl. output) | Lydintys ar įtakojantys   dokumentai
-- | -- | --
Sistemos ar Organizacijos administratoriaus   prisijungimas | Naudotojui priskirtos Sistemos ar Organizacijos   administratoriaus rolė ir teisės. | -

![image](https://user-images.githubusercontent.com/61745726/81939020-74adcb00-95fe-11ea-90f8-9930197bfe68.png) 3.6 pav. Proceso „Sistemos ar Organizacijos administratoriaus funkcijų perdavimo valdymas“ diagrama

3.15 lentelė. Proceso „Sistemos ar Organizacijos administratoriaus funkcijų perdavimo valdymas“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis perduoti administravimą | Sistemos administratorius, organizacijos   administratorius | Sistemos administratoriui ir   (arba) organizacijos administratoriui iškyla poreikis perduoti administravimo   rolę ir teises. | - |  
T1 | Pasirinkti funkciją perduoti administravimą | Sistemos administratorius, organizacijos   administratorius | Sistemos   administratorius, organizacijos administratorius pasirenka funkciją perduoti   administravimą. | Turi būti funkcija perduoti administravimą. |  
T2 | Nurodyti perdavimo priežastį | Sistemos administratorius, organizacijos   administratorius | Nurodoma priežastis, įrašoma arba pasirenkama iš   sąrašo. | Turi būti galimybė nurodyti priežastį:   ·          Įrašyti priežastį;   ·          Pasirinkti priežastį iš sąrašo. |  
T3 | Pridėti dokumentus | Sistemos administratorius, organizacijos   administratorius | Pridedami dokumentai pagal nurodytą priežastį. | Turi būti galimybė pridėti dokumentus. |  
T4 | Atlikti naudotojų paiešką | Sistemos administratorius, organizacijos   administratorius | Atliekama naudotojų paieška sistemos sąraše. | Turi būti galima atlikti naudotojų paiešką:   ·          Organizacijos naudotojų sąraše;   ·          Sistemos naudotojų sąraše. |  
T5 | Pasirinkti naudotoją | Sistemos administratorius, organizacijos   administratorius | Pasirenkamas naudotojas, kuriam norima perduoti   administravimą. | Turi būti galimybė pasirinkti naudotoją. |  
T6 | Nurodyti terminą | Sistemos administratorius, organizacijos   administratorius | Jei yra būtina nurodomas   terminas. Nurodyto termino pradžioje priskiriama rolė ir teisės, pasibaigus   terminui automatiškai pašalinama rolė ir teisė.   Jei sistemos administratorius   neturi galimybės po termino laiko atlikti savo darbo, galima priskirtam   naudotojui prasitęsti terminą. | Turi būti galimybė nurodyti terminą (data ir laikas). |  
T7 | Pasirašyti | Sistemos administratorius, organizacijos administratorius | Pasirašoma sisteminiu parašu. | Turi būti galimybė pasirašyti sisteminiu parašu. |  
T8 | Automatiškai išsiųsti pranešimą | SAULĖ IS | Automatiškai išsiunčiamas pranešimas, apie numatomus   pakeitimus administratoriui;   Automatiškai išsiunčiamas pranešimas naudotojui su   nurodytu terminu, role ir teisėmis, nukreipiamas į SAULĖ IS patvirtinti /   nepatvirtinti perduodamos rolės ir teisių nurodytam laikotarpiui. | Turi būti automatiškai išsiunčiamas pranešimas apie   numatomus pakeitimus.   Turi būti automatiškai išsiunčiamas informatyvus   laiškas priskirtam naudotojui. |  
T9 | Patvirtinti administravimą | Naudotojas | Naudotojas patvirtina   priskiriamas teises ir rolę. | Turi būti galimybė patvirtinti priskirtą administravimą. |  
T10 | Automatiškai išsiųsti pranešimą | SAULĖ IS | Automatiškai išsiunčiamas   pranešimas sistemos administratoriui / organizacijos administratoriui su   informacija apie patvirtintas priskirtas teises ir rolę. | Turi automatiškai išsiųsti pranešimą, naudotojui   patvirtinus priskirtas teises ir rolę. |  
T11 | Pagal terminą pakeisti rolę ir teises | SAULĖ IS | Suėjus terminui naudotojui   suteikiama rolė ir teisės. | Automatiškai SAULĖ IS turi pakeisti naudotojo teises   ir rolę suėjus termino laikotarpiui. |  
T12 | Nepatvirtinti administravimo | Naudotojas | Naudotojas nepatvirtina priskiriamų teisių ir rolių | Turi būti galimybė nepatvirtinti priskiriamų teisių   ir rolės. |  
T13 | Automatiškai išsiųsti pranešimą | SAULĖ IS | Automatiškai išsiunčiamas   pranešimas sistemos administratoriui, organizacijos administratoriui, kad   naudotojas nepatvirtina teisių ir rolės. | Turi automatiškai išsiųsti   pranešimą naudotojui nepatvirtinus priskiriamų teisių ir rolės. |  
E2 | Proceso pabaiga | Naudotojas | - | - |  


## 3.3.3.5	Pirkėjų, Tiekėjų ir Išorinių kontrolierių veiksmų sistemoje autorizavimo procesas (rolių bei teisių administravimas) </summary>

Atskiras procesas nereikalingas, naudotojų teisių ir rolių valdymą užtikrina Procesas „Organizacijos naudotojų valdymas“, kuris aprašomas [3.3.3.3](#user-content-3333organizacijos-naudotojų-valdymas) 



## 3.3.3.6	Organizacijos deaktyvavimas

Proceso trumpas aprašymas: 

Procesas skirtas Organizatoriaus ir naudotojo deaktyvavimui SAULĖ IS. Procesas užtikrina galimybę:
•	Sudaryti galimybę organizacijai deaktyvuoti savo statusą sistemoje;
•	Sudaryti galimybę blokuoti organizacijos atliekamus veiksmus sistemoje;
•	Sudaryti galimybę organizacijai perkelti pirkimus ir su jais susijusią informaciją kitai organizacijai.

Kokiais atvejais procesas inicijuojamas: 

a)	Išsiregistravus Organizacijai iš Juridinių asmenų registro arba pakeitus statusą į „Likviduojama“;
b)	Reorganizavus organizaciją, pakeitus pavadinimą, statusą;
c)	Organizacijai priėmus sprendimą nebedalyvauti viešųjų pirkimų procesuose.

3.16 lentelė. Proceso dalyviai

Dalyviai | Dalyvio vaidmuo, veiksmai ir funkcijos
-- | --
Organizacijos administratorius | Dalyvis atlieka šiuos veiksmus:    ¨         Deaktyvuoja organizaciją;   ¨         Blokuoja organizacijos atliekamus veiksmus;   ¨         Perkelia pirkimus ir su jais susijusią   informaciją kitai organizacijai.
JAR | Juridinio asmens duomenys
SAULĖ IS | Sistema, kurioje atliekami   veiksmai

Procese aprašomas šių rezultatų pasiekimas:
*	SAULĖ IS organizacijos deaktyvavimas. 

Procesas „Organizacijos deaktyvavimas“ yra susijęs su šiais procesais:
*	SAULĖ IS Organizacijos registravimas.

3.17 lentelė. Proceso „Organizacijos deaktyvavimas“ rezultatas ir lydintys dokumentai

Proceso įeitis (angl. input) | Proceso rezultatas    (angl. output) | Lydintys ar įtakojantys    dokumentai
-- | -- | --
Organizacijos administratoriaus prisijungimas | Deaktyvuota organizacija | -

![image](https://user-images.githubusercontent.com/61745726/81939454-09182d80-95ff-11ea-88c2-342f9dd3becb.png)
 3.7 pav. Proceso „Organizacijos deaktyvavimas“ diagrama

3.18 lentelė. Proceso „Organizacijos deaktyvavimas“ aprašymas

Žingsnio Nr. | Žingsnio pavadinimas | Proceso dalyvis | Aprašymas | Taikomi reikalavimai | Teisinis    reglamen-tavimas
-- | -- | -- | -- | -- | --
E1 | Poreikis deaktyvuoti organizaciją, paskyrą | Organizacijos administratorius | Poreikis deaktyvuoti organizaciją arba paskyrą. | - |  
T1 | Tikrinti organizacijos būsenas | SAULĖ IS | Kas tam tikrą laikotarpį tikrinama gaunama informacija apie   organizacijos būsenas. Galimos būsenos:   ·          Likviduojama;   ·          Likviduota;   ·          Struktūrizuojama;   ·          Struktūrizuota;   ·          Reorganizuojama;   ·          Reorganizuota;   ·          Kt. | Turi gauti informaciją iš JAR organizacijos būsenas. |  
E2 | Nėra likviduotų organizacijų | SAULĖ IS | Jei   nerasta būsena „Likviduota“, toliau proceso pabaiga „E2 Nėra likviduotų“ | - |  
T2 | Inicijuoti deaktyvavimą | Organizacijos administratorius | Organizacijos   administratorius inicijuoja paskyros deaktyvavimą. | Turi būti galimybė inicijuoti paskyros deaktyvavimą. |  
T3 | Pakeisti organizacijos būseną | SAULĖ IS | Jei randama nors viena organizacija su būsena   „Likviduota“ automatiškai pakeičiama SAULĖ IS organizacijos būsena ir deaktyvuojama   paskyrą. | Turi automatiškai pakeisti būsenas. |  
E3 | Pakeista organizacijos būsena | SAULĖ IS | Automatiškai pakeista   organizacija į likviduota. | - |  
T4 | Užpildyti deaktyvavimo anketą ir pasirašyti | Organizacijos administratorius | Jei organizacija yra reorganizuojama ar   struktūrizuojama, organizacijos administratorius pasirenka funkciją perkelti   duomenis ir deaktyvuoti paskyrą. | Turi būti galimybė pateikti prašymą.   Turi būti galimybė perketi duomenis.   Turi būti galimybė deaktyvuoti paskyrą. |  
T5 | Pateikti deaktyvavimo prašymą | Organizacijos administratorius | Pateikiamas deaktyvavimo prašymas sistemos naudotojui   su prašyme nurodyta kita organizaciją, kuriai norima perduoti duomenis. | Turi būti galimybė pateikti prašymą. |  
T6 | Nepatvirtinti deaktyvavimo | Sistemos administratorius, pagalbos posistemės   administratorius | Sistemos naudotojas nepatvirtina deaktyvacijos. | Turi būti galimybė nepatvirtinti deaktyvacijos. |  
T7 | Automatiškai išsiųsti pranešimą | SAULĖ IS | Automatiškai išsiunčiamas pranešimas apie   nepatvirtintą prašymą. | Turi automatiškai išsiųsti pranešimą apie nepatvirtintą   prašymą. |  
T8 | Patvirtinti deaktyvavimą | Sistemos administratorius, pagalbos posistemės   administratorius | Administratorius peržiūrėjęs   deaktyvavimo prašymus, deaktyvuoja prašyme nurodytą organizaciją. Jei   nurodyta priežastis reorganizavimo ar restruktūrizavimo sistemos   administratorius arba pagalbos posistemės administratorius gali nurodyti,   prie kokios organizacijos perkelti deaktyvuojamos organizacijos duomenis. | Turi būti galimybė patvirtinti deaktyvaciją. |  
T9 | Perduodami duomenys organizacijai | SAULĖ IS | Automatiškai po sistemos administratoriaus patvirtinimo   perduodami duomenys į nurodytą organizaciją. | Turi automatiškai išsiųsti pranešimą apie patvirtintą   prašymą. |  
T10 | Išsaugoti duomenis ir istoriją | SAULĖ IS | Išsaugomi duomenys ir duomenų istorija. | Turi būti išsaugotas prašymas.   Turi būti išsaugoma istorija.   Turi būti perkelti dokumentai. |  
E4 | Deaktyvuojama organizacija, paskyra | SAULĖ IS | Deaktyvuojama organizacija,   paskyra.   Išsiunčiamas pranešimas apie   nepatvirtintą prašymą. | - |  



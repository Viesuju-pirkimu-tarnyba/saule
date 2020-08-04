# 8	NEFUNKCINIAI REIKALAVIMAI
## 8.1	REIKALAVIMAI REIKALAVIMŲ ĮGYVENDINIMUI
2400. Diegėjas privalo realizuoti visus specifikacijos reikalavimus.
2401. Šiame dokumente vartojami terminai „turi būti / turėti / veikti / užtikrinti / leisti / atitikti“, „turi turėti galimybę“, „turi būti galima“ yra lygiaverčiai ir reiškia, kad Diegėjas privalo sukurti ir įdiegti (ar pateikti ir įdiegti) atitinkamą funkcionalumą ir suteikti atitinkamas paslaugas. Funkcionalumas, kuris yra nurodytas būsimuoju laiku („bus“, „leis“, „apims“) nurodo siekiamą įgyvendinti būseną ir reiškia, kad Diegėjas privalo sukurti ir įdiegti (ar pateikti ir įdiegti) atitinkamą funkcionalumą.
2402. Diegėjas ar VPT gali siūlyti alternatyvų atskiro specifikacijos reikalavimo įgyvendinimo būdą arba reikalavimo įgyvendinimo iškeitimą į lygiavertį funkcionalumą, kuris niekaip neigiamai neturėtų įtakos projekto tikslui, uždaviniams ir galutiniams rezultatams bei neprieštarautų pirkimus reglamentuojančių teisės aktų reikalavimams. Kiekvienas siūlomas alternatyvus ar reikalavimą keičiantis funkcionalumas turi būti suderinamas su VPT bei tvirtinimas reikalavimo pakeitimo, tikslinimo protokolu. Reikalavimo keitimo į lygiavertį funkcionalumą atveju, Diegėjas turės pateikti raštišką pagrindimą, apimantį pakeitimo poveikio ir kritiškumo aprašymą, pagrindžiant, kad pakeitimas neįtakoja viso SAULĖ IS funkcionalumo.
2403. Diegėjas gali siūlyti alternatyvius architektūros realizavimo būdus, kurie užtikrintų lygiavertę ar geresnę SAULĖ IS greitaveiką, aukštą prieinamumą, plečiamumą, interoperabilumą, palaikymą, saugumą ir patogumą. Kiekvienas siūlymas turi būti įvertintas ir patvirtintas VPT. 
## 8.2	REIKALAVIMAI SAULĖ IS ARCHITEKTŪRAI
### 8.2.1	Reikalavimai aukštam prieinamumui

2404. Architektūrinis sprendimas turi užtikrinti SAULĖ IS aukštą prieinamumą (angl. High availability), kuris gali būti realizuojamas virtualizacijos programinės įrangos funkcionalumu, konteinerių orkestravimo programinės įrangos funkcionalumu,  operacinių sistemų funkcionalumu, techninės įrangos galimybėmis ar kitos programinės įrangos pagalba. Aukštas prieinamumas turi būti realizuojamas paslaugų lygyje, integracijų lygyje ir duomenų lygyje.
2404.1. Visų diegiamų komponentų ir jų valdymo komponentų diegimas turi užtikrinti jų aukštą prieinamumą. Aukšto prieinamumo sprendimai turi būti paremti naudojamos PĮ gamintojo rekomendacijomis (pateikiant nuorodas į gamintojo skelbiamas diegimo (aukšto patikimumo) rekomendacijas).
2404.2. Aukšto prieinamumo sprendimai turi veikti automatiškai (incidentų atveju). Žmogaus įsitraukimas gali būti reikalingas tik SAULĖ IS veikimą atstatant į būseną, kuri buvo prieš incidentą.
2404.3. Aukšto prieinamumo sprendimas turi būti aprašytas projektavimo dokumente ir patvirtintas VPT.
2404.4. Didelių duomenų platformos duomenų mazgai (angl. data nodes) turi būti bent jau triplikuojami. Didelių duomenų valdymo mazgai (angl. name nodes) turi būti diegiami pagal PĮ gamintojo rekomendacijas jų aukštam prieinamumui užtikrinti.
2404.5. Aukšto prieinamumo užtikrinimui ir srautų balansavimui turi būti naudojami apkrovų balansatoriai (angl. load balancers), kurie gali būti diegiami kaip programinė įranga arba naudojama specializuota duomenų centro teikiama techninė įranga (angl. appliances).
2404.6. Aukšto prieinamumo sprendimas turi užtikrinti RPO (angl. Recovery point objective) – 15 min., RTO (angl. Recovery time objective) – 1 val. (kai tokį ar geresnį paslaugų teikimo lygį užtikrina duomenų centro infrastruktūra).
2404.7. Diegėjo suprojektuotas SAULĖ IS sprendimas turi užtikrinti, kad SAULĖ IS prieinamumas būtų ne mažesnis nei 96% laiko visą parą, kiek to neribos SAULĖ IS infrastruktūra (kai tokį ar geresnį paslaugų teikimo lygį užtikrina duomenų centro infrastruktūra). 
2404.8. SAULĖ IS turi būti suprojektuota su galimybe būti atstatyta ar veikti atsarginiame duomenų centre (Disaster Recovery) į iš anksto pasiruošusią įrangą (warm recovery). Tam turi būti pateiktos reikiamos licencijos, jei to reikia.

### 8.2.2	Reikalavimai plečiamumui
2405. Architektūra turi palaikyti SAULĖ IS pajėgumų plėtros galimybes prijungiant papildomą techninę įrangą arba virtualią infrastruktūrą;
2406. Architektūra turi būti projektuojama daugiapakopės architektūros pagrindu, sudarant jos plėtros atskirų sluoksnių lygmenyse galimybes;
2407. Turi būti sudarytos sistemos plėtros galimybės neatliekant papildomų sistemos perprojektavimo ar realizavimo darbų papildyti sistemą naujais skaičiavimo ar saugyklų resursais. Pajėgumų didinimas turi būti atliekamas nestabdant sistemos darbo.
### 8.2.3	Reikalavimai rezervinių kopijų darymui, atstatymui ir sistemos stebėjimui
2408. Diegėjas turi įvertinti VDPT teikiamas paslaugas ir apibrėžti bei realizuoti rezervinių kopijų darymo procesus, priemones ir taisykles. SAULĖ IS turi leisti atstatyti duomenis iš rezervinių duomenų kopijų. Diegėjas turi apibrėžti ir realizuoti kopijų atstatymo procesus, priemones ir taisykles. Diegėjas turi realizuoti atsarginių kopijų darymo ir atstatymo procesus su VPT pateikta atsarginių kopijų darymo ir atstatymo PĮ (laikinai, iki bus naudojamasi VDPT paslaugomis, kurios turės užtikrinti atsarginių kopijų darymo ir atstatymo PĮ, Perkančioji organizacija pateiks atsarginių kopijų darymo ir atstatymo PĮ pereinamuoju laikotarpiu).
2409. Turi būti realizuoti sistemos ir jos komponentų veikimo stebėjimo ir išankstinio perspėjimo (angl. monitoring) sprendimai. Sistemos administratoriaus teises turintiems vartotojams turi būti užtikrinta galimybė web priemonėmis stebėti sistemos bei atskirų jos komponentų veikimo rodiklius (aktyvūs vartotojai, atminties panaudojimas, procesorių apkrova ir kiti svarbūs rodikliai) bei gauti pranešimus sutrikus komponentų veikimui ar rodikliams pasiekus kritines reikšmes.

### 8.2.4	Reikalavimai mikroservisų architektūrai
2410. SAULĖ IS turi būti kuriama ir diegiama vadovaujantis mikroservisų architektūros principais:
2410.1. SAULĖ IS turi būti dekomponuojama į logiškus, racionalius, savarankiškai veikiančius programinius vienetus (mikroservisus), kurie su kitais SAULĖS IS mikroservisais komunikuotų RESTful ar lygiaverčių technologijų principais;
2410.2. Mikroservisai turi realizuoti nuosavas duomenų struktūras (tiesiogiai naudojamas tik paties mikroservisų) (išimtys taikomos analizės PĮ, dirbtinio intelekto PĮ ir pan.).
2410.3. Turi būti naudojama PĮ, kuri užtikrintų automatinį mikroservisų paleidimą veikti (angl. auto scaling), kai yra pasiekiamos nustatytos ribinės mikroserviso apkrovos. Bendras SAULĖS IS sprendimas turi leisti (neriboti) mikroservisų automatinio paleidimo funkcionalumo.
2410.4. Turi būti naudojamas mikroservisų paieškos servisas (angl. service registry, service discovery).
2410.5. Komunikavimui tarp mikroservisų turi būti naudojama žinučių eilių valdymo ar lygiavertė programinė įranga.
2410.6. Mikroservisų įdiegimas, veikimas ir išjungimas turi būti nepriklausomas nuo kitų mikroservisų veikimo ar neveikimo.
2410.7. Turi būti naudojami ir kiti būtini mikroservisų architektūros realizavimo principai, remiantis SAULĖS IS architektūros realizavimui naudojamos PĮ gamintojų rekomendacijomis.
2410.8. Naujų SAULĖS IS versijų diegimas neturi reikalauti SAULĖS IS stabdymo (pakartotinio paleidimo).
2410.9. Turi būti realizuotas SAULĖS IS komponentų automatizuotas testavimas ir diegimas (angl. Continuous Integration and Delivery (CI/CD)). Turi būti realizuotas automatinis testų vykdymas ir testavimo duomenų generavimas. Diegėjas turi realizuoti automatinius testus ir automatinį testavimo duomenų generavimą pagal projektavimo etape suderintas apimtis, kurios užtikrintų kiek įmanoma platesnį automatizuotą SAULĖ IS funkcionalumo testavimą.
2410.10. Turi būti pateiktos priemonės ir realizuoti sprendimai užtikrinantys kuriamų, testuojamų ir diegiamų SAULĖ IS versijų suderinamumą.
2410.11. Turi būti pateiktos priemonės ir realizuoti sprendimai užtikrinantys mikroservisų pokyčių valdymą.
2410.12. Turi būti naudojami kiti, mikroservisų architektūros užtikrinimui būtini gerosiomis praktikomis paremti sprendimai. Diegėjo siūlomi sprendimai turi būti patvirtinti Perkančiosios organizacijos analizės ir projektavimo etape.
2411. Turi būti vengiama realizuoti monolitines aplikacijas – programinę įrangą, kuri skirtingus dalykinius uždavinius ir savarankiškus panaudos atvejus realizuoja vienoje (ar vos keliuose) aplikacijoje (vienas (ar keli) sukompiliuoti programinės įrangos išeities kodų failai įdiegti viename aplikacijų serveryje).

### 8.2.5	Reikalavimai daugiapakopei architektūrai
2412. SAULĖ IS architektūra turi būti daugiapakopė (angl. Multi-tier, N-tier), ją turi sudaryti mažiausiai 4 hierarchiniai lygmenys (vaizdavimo, veiklos logikos, duomenų bazės, integracijų). Daugiapakopė architektūra turi būti kombinuojama su mikroservisų architektūra siekiant racionaliausios SAULĖ IS architektūros realizacijos.
2412.1. Vaizdavimo lygmuo (angl. Presentation Layer)  turi užtikrinti kompiuterinių priemonių visumą prieigai prie SAULĖ IS pateikiamo skaitmeninio turinio galimais skaitmeniniais kanalais ir tuo pačiu prie SAULĖ IS naudotojo sąsajų, reikalingų SAULĖ IS funkcijų atlikimui. Vaizdavimo lygmuo turi sąveikauti su veiklos logikos lygmeniu sisteminių pranešimų pagalba.
2412.2. Veiklos logikos lygmuo (angl. Application Layer) programinėmis priemonėmis turi pilnai ar iš dalies automatizuoti veiklos procesų žingsnius ar jų dalį bei kontroliuoti programinių funkcijų vykdymo eigą. Veiklos logikos lygmenyje sisteminiai pranešimai turi būti priimami, apdorojami ir perduodami vaizdavimo lygmeniui. Taip pat šis lygmuo turi aptarnauti: (a) duomenų lygmenį, teikiant atitinkamas duomenų užklausas, apdorojant gautus duomenis, perduodant juos saugojimui ar keičiant juos; (b) vaizdavimo lygmenį, perduodant į jį iš duomenų lygmens gautus ir/ ar veiklos logikos lygmenyje apdorotus duomenis bei priimant ir perduodant kitas sistemines instrukcijas.
2412.3. Duomenų bazės lygmuo (angl. Database Layer) turi būti realizuotas operacinių sistemų failų sistemos, duomenų bazių, duomenų talpyklų ar saugyklų pavidalu. Duomenų bazės lygmenyje skirtingi duomenų rinkiniai turi būti integruojami į vieną unifikuotą duomenų mainų platformą veiklos logikos lygmenyje esančių komponentų pagalba.
2412.4. Integracijų lygmuo (angl. Integration Layer) turi užtikrint reikalingų duomenų mainus tiek tarp vidinių SAULĖ IS komponentų tiek ir su išorinėmis informacinėmis sistemomis. Duomenų mainai užtikrinami realizuotomis WS ar RESTful integracinėmis sąsajomis ir/ arba tiesiogine prieiga prie DB.

### 8.2.6	Reikalavimai duomenų modeliui
2413. SAULĖ IS duomenų modelis turi būti kuriamas naudojant OCDS (angl. The Open Contracting Data Standard) standarto duomenų modelį (https://www.open-contracting.org/data-standard/):
2413.1. Visi techninėje specifikacijoje įvardinti SAULĖ IS duomenys turi būti realizuoti duomenų modelyje, atitinkantį OCDS duomenų modelį;
2413.2. Diegėjas turi realizuoti visas duomenų esybes (kartu su atributais ir sąsajomis) pagal OCDS duomenų modelį, kurios yra būtinos siekiant sukurti specifikacijoje įvardintas funkcijas;
2414. Tiekėjas turi realizuoti SAULĖ IS funkcijas (be tų, kurios aprašytos specifikacijoje), kurios yra būtinos tvarkyti duomenis (duomenų esybes ir jų atributus), kurie sistemoje bus realizuoti remiantis OCDS ar kitais standartais.
2415. Duomenys tvarkomi turi būti pagal OCDS standartą ir taikomas turi būti tiems SAULĖ IS procesams, kurie reikalingi bendram planuojamam kurti Europos pirkimų registrui (angl. contract registry). Daugiau informacijos apie planuojamą sukurti Europos pirkimų registrą pateikta šioje nuorodoje https://www.open-contracting.org/2020/01/23/open-contracting-the-eu-in-2020-what-to-expect/.
2416. SAULĖ IS turi būti kaupiami visi eForms standarte, aprašomame 2019 m. rugsėjo 23 d. Komisijos įgyvendinimo reglamente (ES) 2019/1780, aprašyti duomenų objektai, nebent VPT išsakys poreikį tam tikrų duomenų kaupimo SAUPĖ IS atsisakyti. Detalios analizės ir projektavimo etapo metu turės būti pateikiamas eForms standarte aprašytų duomenų objektų susiejimas su SAULĖ IS kaupiamais duomenų objektais. 
2417. Projektuojant SAULĖ IS realizaciją, turės būti nuolatos pildomas ir su VPT derinamas struktūrizuotų ir viešam pakartotiniam naudojimui teiktinų duomenų sąrašas. 
2418. SAULĖ IS tvarkomi duomenys turi būti įvedami vieną kartą ir automatiškai susiejami ar perpanaudojami ten, kur tai gali būti taikoma. 
2419. Žemiau esančioje schemoje yra pateikiama principinė su pirkimu susijusių duomenų objektų struktūra ir tarpusavio sąsajos. Schema neturėtų būti vertinama kaip detalus SAULĖ IS duomenų modelis. Taip pat dėl schemos patogesnio skaitymo joje nėra išskirti objektai kurie gali būti keli to paties tipo viename pirkime. 

![image](https://user-images.githubusercontent.com/61745726/89342494-8954a900-d6ab-11ea-9d1d-97304c427fad.png)

### 8.2.7	Kiti reikalavimai architektūrai
2420. Turi būti naudojami atviri dokumentų ir duomenų formatai, t. y. oficialiai įregistruoti rinkmenų tarptautiniai standartai (pvz. HTML, PDF/A, PDF, ADOC, TIFF, JPEG, PNG, ODF formatai, OOXML formatai, XML ir kt.).
2421. SAULĖ IS realizavimui turi būti remiamasi bendrai priimtais technologiniais ir veikimo standartais (pvz., SOA, JEE, OSGi, JMX, JPA, SSL, MTOM ir pan.).
2422. Esant kelioms galimoms standarto ar reikalavimo interpretacijoms, reikia laikytis geriausios praktikos principo.
2423. SAULĖ IS turi būti atviros architektūros, t. y. turėti specializuotas, gamintojo pateikiamas programinės įrangos vystymo priemones (angl. Software Development Kit), programinės įrangos naudojimo sąsajas (angl. Application programming interface (API)), leidžiančias be diegėjo pagalbos vystyti SAULĖ IS (papildyti jos funkcionalumą, pritaikyti ją naujai iškilusiems VPT poreikiams) bei integruoti ją su kitomis informacinėmis sistemomis.
2424. SAULĖ IS turi būti galimybė dirbti nutolusioje darbo vietoje, naudojantis saugia nuotoline prieiga (pavyzdžiui, VPN (angl. Virtual Private Network) ar analogiškomis priemonėmis).
2425. Visi SAULĖ IS funkciniai komponentai privalo palaikyti Unicode (UTF – 8) standartą.
2426. SAULĖ IS architektūriniai komponentai turi būti plačiai naudojami praktikoje ir būti stabilūs. Neturi būti naudojamos programinių komponentų versijos, kurios yra testavimo stadijoje.
2427. SAULĖ IS turi būti suprojektuota ir realizuota taip, kad būtų lanksti modifikuojant – realizavus funkcionalumo pakeitimus vienoje ar keliose funkcinėse srityse, pakeitimai neturi būti visos sistemos perkūrimo priežastimi.
2428. Turi būti užtikrinta, kad atliekami SAULĖ IS naudotojų veiksmai neblokuotų kitų SAULĖ IS naudotojų veiksmų ir nedarytų įtakos SAULĖ IS greitaveikai, išskyrus atvejus, kai dėl duomenų integralumo, SAULĖ IS naudotojams blokuojama prieiga prie tuo metu kitų SAULĖ IS naudotojų tvarkomų duomenų. Jeigu yra sąlygų, kurioms esant vyksta SAULĖ IS naudotojo blokavimas, šios sąlygos turi būti aprašytos ir suderintos. Apie blokavimo priežastis SAULĖ IS naudotojai turi būti informuoti informatyviais pranešimais, pateikiamais blokavimo metu.

### 8.2.8	Reikalavimai standartų taikymui
2429. SAULĖS IS realizavimui neapsiribojant turi būti taikomi šie standartai:
2429.1. ODBC (angl. Open Database Connectivity)  arba JDBC (angl. Java Database Connectivity) pagrindu veikiančios arba lygiavertės taikomosios programinės įrangos programavimo sąsaja (API) prisijungimui prie duomenų bazių.
2429.2. SOAP saityno paslaugų priemonėmis vykdomų duomenų mainų protokolas (angl. Simple Object Access Protocol, www.w3.org/TR/soap/) v1.1.
2429.3. Saityno paslaugų funkcionalumo aprašymo kalba WSDL (angl. Web Services Description Language, http://www.w3.org/TR/wsdl) arba lygiavertė.
2429.4. Elektroninio pašto žinučių siuntimo protokolas SMTP (angl. Simple Mail Transfer Protocol, http://tools.ietf.org/html/rfc821).
2429.5. Saityno paslaugų interoperabilumo WS-I arba lygiaverčiai standartai ir specifikacijos (angl. Web Services Interoperability, http://www.ws-i.org/).
2429.6. Turi būti naudojamas SSL arba lygiavertis kriptografinis protokolas internetu perduodamos informacijos saugai užtikrinti (angl. Secure Sockets Layer) šiuose komunikacijos scenarijuose: sistema – naudotojas ir sistema – sistema.
2429.7. Turi būti naudojamas saityno paslaugų saugos WS-Security (angl. Web Services Security, www.oasis-open.org/committees/wss/) arba lygiaverčiai standartai ir specifikacijos. 
2429.8. SAULĖ IS duomenų mainų saugos ir patikimumo užtikrinimui, SAULĖ IS realizuojamos saityno paslaugos turi naudoti WS-* standartų grupės arba lygiaverčius protokolus, tokius kaip: WS-Security, WS-Secure Conversation, WS-SecurityPolicy, WS-MetadataExchange, WS-Trust, WS-AtomicTransaction, WS-ReliableMessaging.
2429.9. HTTP (Hypertext Transfer Protocol) (https://tools.ietf.org/html/rfc2616).
2429.10. JSON (JavaScript Object Notation) duomenų perdavimui ir saugojimui (https://tools.ietf.org/html/rfc7159).
2429.11. URI (Uniform Resource Identifier) (https://tools.ietf.org/html/rfc3986).
2429.12. XML (Extensible Markup Language) (https://www.w3.org/TR/xml/).
2429.13. CSS (Cascading Style Sheets) (https://www.w3.org/Style/CSS/specs.en.html).
2429.14. ISO/IEC 20546:2019  Information technology - Big data - Overview and vocabulary.
2429.15. LDAP (Lightweight Directory Access Protocol) (https://tools.ietf.org/html/rfc4511).
2429.16. AMQP (Advanced Message Queuing Protocol) (http://docs.oasis-open.org/amqp/core/v1.0/amqp-core-messaging-v1.0.html).

## 8.3	REIKALAVIMAI SAULĖ IS SAUGUMUI IR SAUGOS ARCHITEKTŪRA
2430.  Žemiau pateikiama principinė Saulė IS saugos (hibridinės saugos) architektūros schema

![image](https://user-images.githubusercontent.com/61745726/89342588-ab4e2b80-d6ab-11ea-8898-dabaa90c1098.png)

2431. SAULĖ IS saugos architektūra turi būti išskaidyta į tris saugos sluoksnius:
2431.1. Į pirmąjį saugos sluoksnį turi patekti VPT ir kitų priežiūros ir įgyvendinančių institucijų patalpose esanti infrastruktūra ir joje veikiantys komponentai;
2431.2. Antrasis saugos sluoksnis turi apimti ryšių tinklus ir komunikaciją jais. Saugi komunikacija ryšių tinklais turi būti užtikrinama naudojant VPN, HTTPS ir kitas lygiavertes saugaus ryšio užtikrinimo priemones ir technologijas. Išorinių portalo „SAULĖ“ naudotojų (Visuomenės, Pirkimo vykdytojų, Tiekėjų) prieigai prie portalo „SAULĖ“ turi būti naudojamas HTTPS protokolas, o VPT ir kitų priežiūros ir įgyvendinančių institucijų specialistų prieigai prie SAULĖ IS vidinio portalo ir susijusių komponentų papildomai turi būti naudojami VPN protokolai;
2431.3. Trečiasis saugos sluoksnis turi apimti VDPT infrastuktūroje dislokuotus SAULĖ IS komponentus.

### 8.3.1	Reikalavimai saugą reglamentuojančių teisės aktų taikymui
2432. Pagrindiniai saugą (tiek programinės įrangos, tiek duomenų) reglamentuojantys teisės aktai, kuriais turi būti vadovaujamasi modernizuojant SAULĖ IS yra šie:
2432.1. 2016 m. balandžio 27 d. Europos Parlamento ir Tarybos reglamentas (ES) 2016/679 dėl fizinių asmenų apsaugos tvarkant asmens duomenis ir dėl laisvo tokių duomenų judėjimo ir kuriuo panaikinama Direktyva 95/46/EB (Bendrasis duomenų apsaugos reglamentas (BDAR));
2432.2. Lietuvos Respublikos asmens duomenų teisinės apsaugos įstatymas;
2432.3. Lietuvos Respublikos kibernetinio saugumo įstatymas;
2432.4. Techninių kibernetinio saugumo reikalavimų, taikomų subjektams, valdantiems ir (arba) tvarkantiems valstybės informacinius išteklius, ypatingos svarbos informacinės infrastruktūros valdytojams, sąrašas, patvirtintas Lietuvos Respublikos Vyriausybės 2018 m. gruodžio 5 d. nutarimu Nr. 1209 „Dėl Lietuvos Respublikos Vyriausybės 2018 m. rugpjūčio 13 d. nutarimo Nr. 818 „Dėl Nacionalinės kibernetinio saugumo strategijos patvirtinimo“ pakeitimo“;
2432.5. Techniniai valstybės registrų (kadastrų), žinybinių registrų, valstybės informacinių sistemų ir kitų informacinių sistemų elektroninės informacijos saugos reikalavimai, patvirtinti Lietuvos Respublikos vidaus reikalų ministro 2013 m. spalio 4 d. įsakymu Nr. 1V-832 „Dėl Techninių valstybės registrų (kadastrų), žinybinių registrų, valstybės informacinių sistemų ir kitų informacinių sistemų elektroninės informacijos saugos reikalavimų patvirtinimo“;
2432.6. Bendrųjų elektroninės informacijos saugos reikalavimų aprašas, patvirtintas Lietuvos Respublikos Vyriausybės 2013 m. liepos 24 d. nutarimu Nr. 716 „Dėl Bendrųjų elektroninės informacijos saugos reikalavimų aprašo, Saugos dokumentų turinio gairių aprašo ir Elektroninės informacijos, sudarančios valstybės informacinius išteklius, svarbos įvertinimo ir valstybės informacinių sistemų, registrų ir kitų informacinių sistemų klasifikavimo gairių aprašo patvirtinimo“;
2432.7. Duomenų teikimo formatų ir standartų rekomendacijos, patvirtintos Informacinės visuomenės plėtros komiteto prie Susisiekimo ministerijos direktoriaus 2013 m. kovo 25 d. įsakymu Nr. T-36 „Dėl Duomenų teikimo formatų ir standartų rekomendacijų patvirtinimo“.

### 8.3.2	Reikalavimai duomenų saugai
2433. Duomenų sauga turi būti užtikrinama:
2433.1. užtikrinant duomenų vientisumą ir neprieštaringumą;
2433.2. registruojant SAULĖ IS naudotojų atliekamus veiksmus su duomenimis, įskaitant duomenų paiešką ir peržiūrėjimą;
2433.3. sukuriant priemones, sudarančias galimybes SAULĖ IS administratoriui patikrinti SAULĖ IS naudotojų veiksmus (SAULĖ IS naudotojų stebėsenos sistema);
2433.4. numatant apsaugos nuo atsitiktinio duomenų ištrynimo (pvz., perspėjimai apie numatomą duomenų ištrynimą) priemones;
2433.5. darbui su moduliais SAULĖ IS naudotojus suskirstant į grupes pagal duomenų tvarkymo pobūdį, kai kuriems iš jų suteikiant specialiąsias teises (roles) atlikti tam tikrus tvarkymo veiksmus. SAULĖ IS naudotojų grupių ir rolių aprašymai turi būti parengti analizės ir projektavimo etape;
2433.6. saugoma informacija negali būti ištrinta jokiais kitais būdais ar aplinkybėmis išskyrus analizės ir projektavimo etapuose numatytais atvejais;
2433.7. Diegėjas turi suderinti failų formatus, kuriuos leidžiama prisegti SAULĖ IS, ir suderinti juos su VPT (pvz., neturi būti leidžiama prisegti potencialiai nesaugių, galinčių automatiškai pasileisti (angl. self-executive) failų).

### 8.3.3	Reikalavimai naudotojų valdymo saugumui
2434. SAULĖ IS turi automatiškai nutraukti SAULĖ IS naudotojų darbo seansą praėjus parametrais apibrėžtam neaktyvumo laikotarpiui ir informuoti apie atjungimo priežastį pranešimu. SAULĖ IS administratoriui turi būti galimybė keisti neaktyvumo laikotarpio parametro reikšmę.
2435. SAULĖ IS turi būti numatytas SAULĖ IS naudotojų privalomas slaptažodžio keitimas kas nustatytą laikotarpį.
2436. SAULĖ IS naudotojų vardai, kiti asmens duomenys, kuriems taikomos duomenų apsaugos įstatymo nuostatos, slaptažodžiai turi būti saugomi su tinkamu prieigos kontrolės užtikrinimu ir informacijos šifravimu.
2437. SAULĖ IS turi būti galimybė suskirstyti SAULĖ IS naudotojus į atskiras roles su skirtingomis priėjimo teisėmis prie atskirų sistemos funkcijų ir pan. SAULĖ IS naudotojas turi galėti peržiūrėti ir keisti tik tokią informaciją ir naudotis tik tokiomis funkcijomis, kurios yra nustatytos priėjimo teisėmis. 
2438. SAULĖ IS naudotojui pagal jo pateiktą užklausą turi būti rodomi tik tie įrašai, kuriuos jis turi teisę peržiūrėti.
2439. Vienas SAULĖ IS naudotojas gali turėti tik vieną naudotojo seansą, SAULĖ IS turi užtikrinti, kad veikiant vienam SAULĖ IS naudotojo darbo seansui, nebūtų galima prisijungti naudojantis jo identifikaciniais duomenimis.
2440. Jei autentifikavimo būdas pasirinktas „SAULĖ IS priemonėmis“, SAULĖ IS naudotojai turi turėti galimybę inicijuoti savo slaptažodžio keitimo procedūrą.
2441. SAULĖ IS turi būti galimybė nustatyti prisijungimo slaptažodžio minimalų reikalaujamą ilgį. Turi būti galimybė keisti slaptažodžio minimalaus reikalaujamo ilgio reikšmę. 
2442. SAULĖ IS turi būti galimybė nustatyti ir keisti prisijungimo slaptažodžio sudėtingumą skirtingoms naudotojų grupėms (pvz., naudotojų slaptažodį turi sudaryti 8 simboliai, iš kurių bent 2 skaičiai ir bent viena didžioji raidė, administratorių slaptažodžiui turi būti galima nustatyti griežtesnius reikalavimus). 
2443. SAULĖ IS neturi sudaryti sąlygų spėlioti slaptažodžius. 
2444. SAULĖ IS neturi vaizduoti įvedamo slaptažodžio.
2445. SAULĖ IS turi būti galimybė nustatyti naudotojo neteisingų prisijungimų skaičių, po kurio naudotojo prisijungimo vardas būtų blokuojamas. Prisijungimų skaičius turi būti apibrėžtas parametru, kurį gali koreguoti sistemos administratorius. Taikoma tik autentifikavimo būdui „SAULĖ IS priemonėmis“.
2446. SAULĖ IS audito ir saugos modulyje veikiantis privilegijuotų naudotojų valdymo sprendimas turi užtikrinti galimybę sistemos administratoriams suteikti prieigą prie SAULĖ IS programinės įrangos neatskleidžiant jiems slaptažodžių arba suteikiant vienkartinius prisijungimo slaptažodžius.

### 8.3.4	Reikalavimai auditavimui
2447. Turi būti vykdomas visų SAULĖS IS komponentų funkcionalumo naudojimo (naudotojų atliekamų veiksmų) auditavimas. 
2447.1. Rekomenduojami informacijos saugojimo momentai:
2447.1.1. vartotojo autentifikavimasis (prisijungimas) ir darbo sesijos pabaiga sistemoje;
2447.1.2. atliekama paieška ir paieškos kriterijai (frazės);
2447.1.3. įvairių parametrų keitimas;
2447.1.4. duomenų esybių laukų pakeitimas (atnaujinimas, įterpimas, pašalinimas).
2447.2. Atliekant auditavimo įrašo išsaugojimą duomenų bazėje, turi būti kaupiama:
2447.2.1. kas atliko veiksmą (vartotojas);
2447.2.2. kada atliko veiksmą (data, laikas);
2447.2.3. kokius duomenis atnaujino;
2447.2.4. kokius duomenis įterpė;
2447.2.5. naudotojo IP adresas;
2447.2.6. kokius duomenis pašalino;
2447.2.7. kokias paieškos frazes naudojo;
2447.2.8. kita informacija, nustatyta analizės ir projektavimo etapų metu.
2447.3. Turi būti audituojami integracinėmis sąsajomis siunčiamų / gaunamų duomenų momentai, išsaugant informaciją:
2447.3.1. iš kokios sistemos, registro ar duomenų bazės gaunami duomenys;
2447.3.2. į kokią sistemą, registrą ar duomenų bazę siunčiami duomenys;
2447.3.3. duomenų gavimo/siuntimo data ir laikas;
2447.3.4. siųsti / gauti duomenys (jeigu tam yra poreikis);
2447.3.5. kita informacija, nustatyta detalios analizės ir projektavimo etapu metu
2447.4. Administravimo priemonėmis turi būti galimybė atlikti audito įrašų analizę (paiešką, filtravimą pagal įvairius parametrus). Reikalingi analitiniai veiksmai su auditavimo įrašais turi būti identifikuoti ir suderinti su Perkančiąja organizacija analizės ir projektavimo etapų vykdymo metu.
2447.5. Audito įrašų peržiūra detalios analizės ir projektavimo etape apsibrėžta apimtimi turi būti galima Sistemos administratoriui, Organizacijos administratoriui, Institucijos administratoriui ar kitam naudotojui, turinčiam audito įrašų tvarkymo teisę.
2447.6. Siekiant išvengti perteklinės auditavimo informacijos kaupimo tikslūs audito įrašų darymo momentai turi būti identifikuoti analizės ir projektavimo etapų vykdymo metu.
2448. Visis SAULĖ IS realizuojami moduliai turi būti susieti audito ir saugos moduliu, įgyvendinančiu veiksmų registravimo ir kontrolės mechanizmą (angl. audit trail).
2449. SAULĖ IS audito ir saugos modulyje turi būti įgyvendintas saugos informacijos ir įvykių valdymo sprendimas, skirtas žurnalinių įrašų rinkimui, kaupimui, auditavimui ir perdavimui į VPT centralizuotą audito įrašų administravimo programinę įrangą. Saugos informacijos ir įvykių valdymo sprendimas turi:
2450. Sugebėti registruoti žurnalinius įrašus (angl. log records) iš visos SAULĖ IS programinės įrangos.
2451. Apsaugoti žurnalinius įrašus nuo nesankcionuoto ar netyčinio pakeitimo.
2452. SAULĖ IS turi būti saugomi visi administravimo parametrų pakeitimai.
2453. Audito informacija turi būti saugoma be galimybės pakeisti.
2454. Audito duomenys saugomi nurodytą laikotarpį.
2455. SAULĖ IS konfigūracijos keitimo veiksmai turi būti registruojami audito įrašais, fiksuojant datą, laiką, keitimą vykdančio SAULĖ IS naudotojo vardą ir keitimo apibūdinimą.
2456. Turi būti galima eksportuoti pasirinktus audito įrašus į CSV ar lygiaverčio formato rinkmeną.
2457. Turi būti galimybė archyvuoti audito ir saugos modulio saugomus duomenis. Audito archyvo duomenų keisti turi būti negalima.
2458. SAULĖ IS naudotojų administravimo modulyje turi būti priemonės kontroliuoti prieigos teises prie audito ir saugos modulio saugomo veiksmų žurnalo.
2459. Audito žurnalas turi būti sudaromas vadovaujantis „1849-2016 - IEEE Standard for eXtensible Event Stream (XES) for Achieving Interoperability in Event Logs and Event Streams“ standartu.

### 8.3.5	Rizikų, grėsmių ir pažeidžiamumų valdymas
2460. Rizikų, grėsmių ir pažeidžiamumų valdymas:
2460.1. SAULĖ IS Diegėjas privalo vadovautis pripažintomis saugaus programinės įrangos kūrimo metodikomis;
2460.2. SAULĖ IS Diegėjas privalo užtikrinti, kad visi programinės įrangos kūrime dalyvaujantys darbuotojai susipažinę su saugaus programinės įrangos kūrimo metodikomis;
2460.3. SAULĖ IS Diegėjas privalo identifikuoti pagrindines sistemos saugumo rizikas, bei saugumo pažeidžiamumus (CWE/SANS TOP 25 Most Dangerous Software Errors ir OWASP 10 Most Critical Web Application Security Risks) ir imtis priemonių rizikų sumažinimui, bei saugumo pažeidžiamumų šalinimui. Diegėjas privalo pateikti deklaraciją dėl CWE/SANS TOP 25 ir OWASP TOP 10 rizikų/pažeidžiamumų identifikavimo ir sėkmingo pašalinimo.
2460.4. SAULĖ IS Diegėjas privalo pateikti visų, sistemoje naudojamų trečių šalių komponentų sąrašą;
2460.5. SAULĖ IS Diegėjas privalo imtis tinkamų veiksmų (angl. reasonable effort) užtikrinant, kad trečių šalių komponentai atitinka VPT saugumo reikalavimus;
2461. Priėmimo testavimo etapo metu (ar kitų sutartu metu) Diegėjas turi sudaryti visas reikiamas sąlygas VPT atstovų specialistams, kurie atliks atsparumo įsilaužimams testavimą. Esant poreikiui Diegėjas turės atlikti konfigūravimo ar programavimo darbus, kurie bus būtini siekiant ištestuoti SAULĖ IS saugumą įvairiais jos naudojimo scenarijais. Diegėjas neturės pateikti jokios programinės ar techninės įrangos, skirtos našumo ir greitaveikos testavimo vykdymui. 
2462. Diegėjas turi atlikti reikiamus SAULĖ IS programavimo ir / ar konfigūravimo darbus, atsižvelgiant į VPT atstovų atliktų atsparumo įsilaužimams testavimų rezultatus, kad prieš pradedant eksploatuoti SAULĖ IS būti pašalinti visi nustatyti svarbūs saugumo pažeidžiamumai.

### 8.3.6	Kiti saugos reikalavimai
2463. Saugumo pataisų ir atnaujinimų valdymas:
2463.1. SAULĖ IS Diegėjas privalo teikti saugumo pataisas ir atnaujinimus viso sistemos gyvavimo ciklo metu;
2463.2. Prieš teikiant VPT saugumo pataisas/atnaujinimus jie privalo būti ištestuoti Diegėjo testinėje aplinkoje;
2463.3. SAULĖ IS Diegėjas privalo užtikrinti sistemos platformos (OS, DBMS, middleware) saugumo pataisų/atnaujinimų palaikymą viso sistemos gyvavimo ciklo metu. Diegėjas privalo ištestuoti ir patvirtinti platformos pataisų/atnaujinimų suderinamumą su SAULĖ IS (arba pasiūlyti alternatyvą – angl. workaround) ne vėliau kaip per 30 dienų po platformos pataisų/atnaujinimo paviešinimo.
2463.4. Nuotolinė ar lokali neautorizuota prieiga:
2463.5. Sistemoje draudžiama bet kokia neautorizuota ar nedokumentuota nuotolinė ar lokali prieiga/paskyros ar bet koks slaptas (nedokumentuotas) funkcionalumas galintis pažeisti sistemos saugumą.
2463.6. Saugi konfigūracija:
2463.7. SAULĖ IS Diegėjas privalo pateikti detalias sistemos ir platformos (OS, DBMS, middleware) saugumo konfigūravimo instrukcijas;
2463.8. SAULĖ IS Diegėjas privalo pateikti sistemos funkcionavimui būtinų platformos komponentų, sisteminių paslaugų, prievadų sąrašą. Visi nebūtini SAULĖ IS funkcionalumui komponentai turi būti deaktyvuoti prieš pradedant sistemos eksploataciją.
2463.9. Tinklo architektūra:
2463.10. Duomenų srautai tarp skirtingų lygių turi būti dokumentuoti, nurodant reikalingus komunikacijai prievadus ir protokolus, bei ribojami ugniasienių;
2463.11. Portalas „Saulė“ turi būti atskiroje nuo vidaus naudotojų platformoje ir atskirame tinklo segmente.

## 8.4	REIKALAVIMAI SAULĖ IS GREITAVEIKAI IR NAŠUMUI
2464. Portalo „Saulė“ realizacija turi užtikrinti, kad kai su portalu „Saulė“ vienu metu dirba 3000 naudotojų ir jų veiksmų – dokumentinių įrašų įterpimo, keitimo ir šalinimo, kitų veiksmų atlikimo (kurių vykdymo laikas nepriklauso nuo sąsajų su išorinėmis sistemomis), vidutinė atsako trukmė  (trukmė nuo serverio HTTP užklausos gavimo iki HTTP atsakymo išsiuntimo) neturi viršyti 3 sekundžių, esant bendram HTTP užklausų kiekiui per minutę 350. Galimi išimtiniai atvejai, kurie turi būti suderinti su VPT (pvz., ataskaitų generavimas, duomenų importavimas ar eksportavimas, didelės apimties rinkmenų įkėlimas, veiksmai apimantys užklausas ir atsakymų gavimus iš trečių šalių sistemų ir kt.).
2465. Vidinio portalo realizacija turi užtikrinti, kad kai su vidiniu portalu vienu metu dirba 300 naudotojų ir jų veiksmų – dokumentinių įrašų įterpimo, keitimo ir šalinimo, kitų veiksmų atlikimo (kurių vykdymo laikas nepriklauso nuo sąsajų su išorinėmis sistemomis), vidutinė atsako trukmė (trukmė nuo serverio HTTP užklausos gavimo iki HTTP atsakymo išsiuntimo) neturi viršyti 3 sekundžių esant bendram HTTP užklausų kiekiui per minutę 200. Galimi išimtiniai atvejai, kurie turi būti suderinti su Perkančiąja organizacija (pvz., ataskaitų generavimas, duomenų importavimas ar eksportavimas, didelės apimties rinkmenų įkėlimas, veiksmai apimantys užklausas ir atsakymų gavimus iš trečių šalių sistemų ir kt.).
2466. Turi būti realizuotas užklausų, kurios viršija nustatytus našumo reikalavimus, auditavimas. Audito įraše turi būti pakankamai duomenų, kad būtų galima nustatyti kuri SAULĖ IS funkcija netenkina našumo reikalavimų.
2467. Integracinių sąsajų realizacija turi užtikrinti, kad projektavimo metu apibrėžti integraciniai scenarijai įvyks per racionalų laiko tarpą ir niekaip neigiamai neįtakos SAULĖ IS aplikacijų naudojimo patogumo ir našumo.
2468. Priėmimo testavimo etapo metu (ar kitų sutartu metu) Diegėjas turi sudaryti visas reikiamas sąlygas VPT atstovų specialistams, kurie atliks našumo ir greitaveikos testavimą. Esant poreikiui Diegėjas turės atlikti konfigūravimo ar programavimo darbus, kurie bus būtini siekiant išbandyti SAULĖ IS našumą įvairiais jos naudojimo scenarijais. Diegėjas neturės pateikti jokios programinės ar techninės įrangos, skirtos našumo ir greitaveikos testavimo vykdymui. 
2469. Diegėjas turi atlikti reikiamus SAULĖ IS programavimo ir / ar konfigūravimo darbus, atsižvelgiant į VPT atstovų atliktų našumo ir greitaveikos testavimų rezultatus, jeigu testų rezultatai netenkins aukščiau punktuose įvardintų našumo ir greitaveikos reikalavimų.

## 8.5	REIKALAVIMAI SAULĖ IS PROGRAMINĖS ĮRANGOS LICENCIJOMS
2470. Diegėjas, įvertinęs specifikacijos reikalavimus, turi pateikti reikiamą programinę įrangą ir licencijas (ar bet kokius kitus leidimus (sertifikatus, prenumeratas ir pan.) naudoti programinę įrangą) reikalingas siūlomo sprendimo realizacijai. Jeigu šioje techninėje specifikacijoje tokia programinė įranga ar licencijos nėra išreikštinai reikalaujamos, tačiau yra būtinos SAULĖ IS kūrimo veikloms įgyvendinti (pavyzdžiui, aplikacijų serveriai, ataskaitų programinė įranga, programavimo karkasai (angl. framework) ar pan.), Diegėjas turi pateikti tokią programinę įrangą ir licencijas.
2471. Diegėjo pateikiama standartinė licencinė programinė įranga (angl. Commercial Off-The-Shelf Software) (aplikacijų serveriai, monitoringo programinė įranga, ataskaitų sudarymo programinė įranga, programavimo karkasai, turinio valdymo sistemos ir pan.), kuri reikalinga SAULĖ IS veikimui, turi būti pateikiama kartu su visomis reikiamomis licencijomis (jeigu yra licencijuojama), kad VPT ne mažiau kaip 3 metus nereikėtų įsigyti papildomų licencijų (ar kitaip patirti išlaidų) programinės įrangos veikimui.
2472. Licencijuojama programinė įranga turi turėti ne mažiau 3 metų gamintojo palaikymą: atnaujinimų parsisiuntimą ir diegimą, naujų komponentų pateikimą.
2473. Jeigu siūloma programinė įranga yra licencijuojama priklausomai nuo sistemą naudojančių naudotojų (žmonių ar sistemų) kiekio, tarnybinių stočių parametrų ar pan., tai Diegėjas turi pateikti licencijas, kurios užtikrintų racionalų ir efektyvų SAULĖ IS veikimą ir naudojimą 3 metų perspektyvoje.
2474. Visi reikalingos programinės įrangos kaštai turi būti įskaičiuoti į pasiūlymą.
2475. Visos reikalingos licencijos turi būti įgyjamos VPT vardu. VPT turi būti perduotos visos SAULĖ IS veikimui reikalingos licencijos. Licencijų galiojimo trukmė pagal specifikacijos reikalavimus turi būti skaičiuojama nuo bandomosios eksploatacijos pradžios. Jeigu licencijos yra būtinos kūrimo etape (iki bandomosios eksploatacijos), Diegėjas turi pateikti atitinkamas licencijas jų galiojimo termino neįtraukiant į aukščiau reikalaujamą licencijų galiojimo terminą, atitinkamai prisiimant visus su tuo susijusius kaštus.

## 8.6	REIKALAVIMAI SAULĖ IS INTEGRACINĖMS SĄSAJOMS
2476. Duomenų mainai turi būti vykdomi naudojant žiniatinklio paslaugas ar lygiavertes technologijas, SOAP, HTTP (RESTfull) ar lygiavertį protokolą. Esant objektyvioms priežastims (pvz: neegzistuoja išorinės sistemos žiniatinklio sąsaja), galimos išimtys. Diegėjas turi suderinti duomenų mainams naudojamas technologijas ir protokolą. Diegėjas turi atsižvelgti į patvirtintą Informacinės visuomenės plėtros komiteto prie Susisiekimo ministerijos direktoriaus 2013 m. kovo 25 d. įsakymą Nr. T-36 „Dėl duomenų teikimo formatų ir standartų rekomendacijų patvirtinimo“.
2477. Jei integracija realizuota WS pagrindu, duomenų patikrinimas turi vykti naudojant XML schemas (XSD).
2478. Jei integracija realizuota žiniatinklio paslaugų pagrindu, duomenų teikimui turi būti:
2478.1. naudojamas XML (angl. Extensible Markup Language) formatas;
2478.2. atlikta žiniatinklio paslaugos patikra pagal WS-I (angl. Web Services Interoperability) standartą;
2478.3. naudojamas vieningas duomenų teikimo protokolas SOAP 1.1 (angl. Simple Object Access Protocol).
2479. Diegėjas turi užtikrinti, kad nebus sutrikdytas jau veikiančių integracinių sąsajų veikimas.

## 8.7	REIKALAVIMAI SAULĖ IS NAUDOTOJO SĄSAJAI IR ERGONOMIKAI
2480. Diegėjas turi sukurti SAULĖ IS dizainą, taikant geriausias UX (angl. User experience) ir UI (angl. User interface) praktikas, siekiant naudotojo sąsają padaryti kiek labiau įmanoma intuityvią ir suprantamą, vengiant visų perteklinių veiksmų. SAULĖ IS naudotojo sąsaja turi būti modernizuojama ir tobulinama atsižvelgiant į viešųjų administracinių elektroninių paslaugų patogumo naudotis metodinį dokumentą „Tinkamumo problemų sprendimo gairės“.
2481. VPT vertinimui turi būti pateiktas SAULĖ IS portalo dizaino eskizas su informacijos atvaizdavimo pavyzdžiais įvairaus tipo įrenginių ekranams.
2482. Suderinus su VPT vieną dizaino eskizo variantą, pagal jį Diegėjas turi sukurti prototipą (pvz. naudojant https://www.axure.com/) ir prieš kurdamas dizainą iš VPT bei kitų suinteresuotų šalių (ne mažiau 20 asmenų) surinkti atsiliepimus (rengiant apklausas, interviu ir pan.). Kuriant naudotojo sąsaja turi būti atsižvelgiama į naudotojų nuomonę. Susitikimai, apklausos turi būti dokumentuojami ir pateikti VPT.
2483. Bandomosios eksploatacijos metu Diegėjas turės atlikti visus VPT nurodytus naudotojo sąsajos pakeitimus, nenukrypstant nuo suderinto dizaino, jeigu to bus reikalaujama.
2484. SAULĖ IS komponentų naudotojo sąsaja turi būti prieinama naudojant interneto naršyklę (išimtys gali būti taikomos standartinei licencinei programinei įrangai, jeigu tokia teikiama (pvz. ataskaitų ir statistikos programinei įrangai, duomenų bazių administravimo programinei įrangai ir pan.)).
2485. SAULĖ IS (portalas „Saulė“, vidinis portalas) turi būti konstruojama „responsive web design“ principais. Detalios analizės metu turi būti nustatyta, kurios SAULĖ IS funkcijos turi būti pasiekiamos naudojant mobilius įrenginius (žemesnės raiškos ekranus), o kurios – naudojant kompiuterį (aukštesnės raiškos ekranus).
2486. Per interneto naršyklę pasiekiami SAULĖ IS komponentai turi vienodai funkcionuoti bei būti atvaizduojami šiose interneto naršyklėse (naršyklių versijos turi būti suderintos Projektavimo etape):
2486.1. Microsoft Edge / Microsoft Internet Explorer;
2486.2. Mozilla Firefox;
2486.3. Safari;
2486.4. Google Chrome.
2487. Portalas „Saulė“ turi būti realizuotas lietuvių ir anglų kalbomis (įskaitant klasifikatorius ir susijusius komponentus). Vidinis portalas turi būti realizuotas lietuvių kalba. Kalba turi būti naudojama laikantis bendrinių lietuvių kalbos taisyklių. Sistemos administratoriams skirtos programinės priemonės ir pranešimai turi būti lietuvių arba anglų kalba.
2488. Turi būti galimybė TVS ar kitomis priemonėmis įdiegti kitas portalo kalbas.
2489. Naudotojų sąsajos klaidų pranešimai turi būti suformuluoti taip, kad naudotojui būtų aišku, kas atsitiko ir kokius veiksmus jam toliau reikia atlikti, kad galėtų tęsti darbą.
2490. SAULĖ IS naudotojo sąsaja turi būti intuityvi, suprantama ir nesudėtinga naudoti naudotojams, turintiems reikalaujamą kompiuterinio raštingumo lygį (ECDL ar aukštesnį), bei atitikti šiuolaikinius ergonomikos reikalavimus. 
2491. Siekiant užtikrinti šiuolaikinius naudotojų sąsajos ergonomikos reikalavimus, rekomenduojama vadovautis LST EN ISO 9241–110:2006 „Žmogaus ir sistemos sąveikos ergonomika. 110 dalis. Dialogo principai (ISO 9241–110:2006)“ standartu arba lygiaverčiu. 
2492. Naudotojo sąsaja turi būti pritaikyta reikalavimams, kurie keliami neįgaliesiems pritaikytų valstybės ir savivaldybių institucijų ir įstaigų interneto svetainių kūrimo, testavimo ir įvertinimo metodinėse rekomendacijose, patvirtintose Informacinės visuomenės plėtros komiteto prie Lietuvos respublikos susisiekimo ministerijos direktoriaus 2013 m. gegužės 23 d. įsakymo Nr. T-72 Dėl Informacinės visuomenės plėtros komiteto prie Lietuvos Respublikos Vyriausybės direktoriaus 2004 m. kovo 31 d. įsakymo Nr. T-40 „Dėl Neįgaliesiems pritaikytų valstybės ir savivaldybių institucijų ir įstaigų interneto svetainių kūrimo, testavimo ir įvertinimo metodinių rekomendacijų patvirtinimo“ pakeitimo“.  Remiantis įsakymo 7 punktu „Rekomenduojama siekti interneto svetainę pritaikyti ne žemesniu kaip AA lygiu“, Diegėjas turi užtikrinti „AA“ lygmens pasiekiamumą pagal „Web Content Accessibility Guidelines 2.1“ skaitmeninio turinio prieinamumo gaires (https://www.w3.org/TR/WCAG21/) su galimybe plėsti SAULĖ IS funkcionalumą, ateityje siekiant užtikrinti „AAA“ lygmenį.
2493. SAULĖ IS turinys, įgyvendinant gaires interneto turinio prieinamumui užtikrinti (WCAG), turi būti pateikiamas tokia forma, kad klausos ir regos negalią turintys asmenys galėtų laisvai naudotis SAULĖ IS funkcionalumais.
2494. SAULĖ IS komponentų, pasiekiamų per interneto naršyklę, naudotojo sąsaja turi atitikti W3C XHTML arba lygiavertę specifikaciją ir turi būti naudojama ne žemesnė kaip 1.0 W3C XHTML arba lygiavertė versija. Realizavimui turi būti naudojama ne žemesnė kaip 2.1 lygio CSS2 arba lygiavertė technologija (Cascading Style Sheets Language 2 Revision 1, www.w3.org/Style/CSS/).
2495. Naudotojų sąsajos valdymas turi remtis pelės ir klaviatūros įrenginiais.
2496. Turi būti realizuotas naudojimo patogumą užtikrinantis funkcionalumas:
2496.1. operatyvios (angl. Online) duomenų paieškos priemonės;
2496.2. TAB klavišo seka einant per duomenų įvedimo laukus;
2496.3. užuominų ir paaiškinimų pateikimas pelės žymeklį užvedus ant grafinio objekto;
2496.4. automatinis įvestų duomenų išsaugojimas keičiant aktyvius langus, laukus ar nutrūkus naudotojo sesijai.
2496.5. duomenų įvedimo formose duomenų laukai turi būti užpildomi automatiškai, jeigu SAULĖ IS yra saugomi atitinkami duomenys;
2496.6. naudotojo sąsajos elementai, kurie remiantis SAULĖ IS įgyvendinta logika negali būti panaudojami, privalo būti pažymimi neaktyviais ir / ar paslepiami.
2497. Duomenų sąrašai turi būti:
2497.1. puslapiuojami, su galimybe nurodyti kiek sąrašo puslapyje rodyti eilučių. Naudojant naršyklės mygtuką „Grįžti“, turi būti grįžtama į prieš tai buvusį puslapį. Iš konkretaus duomenų sąrašo puslapio įėjus į pasirinktą sąrašo objektą ir grįžus atgal, turi būti atvaizduojamas tas pats duomenų sąrašo puslapis iš kurio buvo nueita į pasirinktą sąrašo objektą;
2497.2. filtruojami pagal sąrašui aktualius kriterijus. Diegėjas, detalios analizės metus, turės identifikuoti kiekvieno sąrašo filtravimo kriterijus ir juos realizuoti;
2497.3. rikiuojami pagal sąrašo rikiuotinus elementus;
2497.4. eksportuojami į rinkmenas (*.pdf, *.docx, .*xlxs ar lygiavertes). Detalios analizės metu turi būti nustatyta, kuriems sąrašams yra reikalinga pastaroji funkcija;
2497.5. atveriami spausdinimo režimu. Detalios analizės metu turi būti nustatyta, kuriems sąrašams ir formoms yra reikalinga pastaroji būsena;
2497.6. duomenys, susidedantys iš lietuviškų rašmenų, turi būti rūšiuojami pagal lietuvišką abėcėlę;
2498. SAULĖ IS kuriamiems įrašams (dokumentams, objektams ir kt.) turi būti realizuojamos veiklos taisykles tenkinančios tų įrašų redagavimo, trynimo, anuliavimo funkcijos.
2499. SAULĖ IS turi būti indikuojami ilgiau trunkantys procesai (funkcijos), kad naudotojui būtų aišku, jog SAULĖ IS veikia ir nėra būtinybės iškviesti tų pačių funkcijų keletą kartų. Jei procesas yra toks, kurį norint tęsti reikia palaukti kol SAULĖ IS apdoros reikiamus duomenis, tokiu atveju naudotojui turi būti apribota galimybė inicijuoti kitus veiksmus, nebent pranešime, kuris indikuoja, kad procesas gali užtrukti, naudotojas inicijuoja ilgiau trunkančio proceso atšaukimą.
2500. Reikalavimai naudotojų informavimui:
2500.1. SAULĖ IS naudotojui pateikiami pranešimai turi būti suformuluoti taip, kad naudotojui būtų aiški pranešimo pateikimo priežastis. Informacija apie pranešimo pateikimą sąlygojančią priežastį privalo būti pateikiama nurodant konkrečius SAULĖ IS duomenų objektus (pavyzdžiui, laukų pavadinimus);
2500.2. naudotojui pateikiamame klaidos pranešime privalo būti nurodoma, kokius veiksmus naudotojas privalo atlikti tam, kad galėtų pašalinti pranešimo pateikimo priežastis ir tęsti darbą su SAULĖ IS;
2500.3. naudotojui turi būti pateikiami sėkmės pranešimai, nurodantys, kad naudotojo atlikti veiksmai yra sėkmingi (pavyzdžiui, informuojama, kad įrašas išsaugotas / ištrintas / pakoreguotas, duomenys sėkmingai įkelti ir pan.);
2500.4. klaidų pranešimai, sėkmės pranešimai ir informaciniai pranešimai turi būti išskirti skirtingomis spalvomis ar skirtingais simboliais, kad vizualiai būtų galima atskirti;
2500.5. jeigu naudotojui atlikus veiksmus rezultatai turės didelės įtakos, prieš atliekant veiksmą SAULĖ IS turi pateikti pranešimą ir paprašyti naudotojo patvirtinti, kad veiksmą tikrai norima vykdyti.
2501. Naudotojui turi būti pateikiamos pagalbos priemonės padedančios greičiau išmokti naudotis SAULĖ IS (pavyzdžiui, pagalbos mygtukai, naudotojo vadovas, video medžiaga). 
2502. Naudotojo sąsajoje esantys duomenų įvedimo laukai turi turėti duomenų validavimo taisykles ir tikrinti įvedamų duomenų logikos korektiškumą. Laukai ir laukų validavimo taisyklės turi būti suderinti su VPT detalios analizės ir projektavimo etapų metu. Preliminariai turės būti:
2502.1. tikrinami privalomi įvesti duomenys;
2502.2. tikrinimas duomenų formatas (datos, skaičiaus, teksto ar kitas nustatytas taisykles);
2502.3. tikrinami įkeliamų rinkmenų plėtiniai ir dydžiai;
2502.4. atliekamas loginis tikrinimas tarp formos elementų – vieno formos elemento parinkimas (įvedimas) turi galėti įjungti/ išjungti kitus formos elementus ir atlikti kitus veiksmus, kurie turės būti suderinti su VPT.

## 8.8	REIKALAVIMAI SAULĖ IS DUOMENŲ MIGRAVIMUI
2503. CVPIS duomenys neturi būti migruojami į SAULĖ IS.
2504. Diegėjas turi atlikti pradinį iš išorinių informacinių sistemų ir registrų gaunamų duomenų migravimą (angl. initial data loading), jeigu integracinės sąsajos specifika reikalaus tokių duomenų įkėlimo.
2505. Duomenų migravimas turi būti dokumentuotas, t. y. parengtas duomenų migravimo procedūros aprašas. Diegėjas, prieš atlikdamas duomenų migravimą, turi pateikti ir suderinti duomenų migravimo procedūros aprašą. Atlikus duomenų migravimą Diegėjas turi pateikti duomenų migravimo ataskaitą.

## 8.9	REIKALAVIMAI SAULĖ IS ARCHYVAVIMUI
2506. SAULĖ IS turi turėti funkcijas, suteikiančias galimybę atlikti SAULĖ IS tvarkomų duomenų loginį archyvavimą. Realizuojant loginio duomenų archyvavimo priemones, duomenų objektui (įrašui, susijusiems įrašams, failui ar kitam objektui) turi būti priskiriamas archyvo požymis, SAULĖ IS funkciniams moduliams paliekant tokio paties lygio prieigą kaip ir prie nearchyvuotų duomenų. SAULĖ IS funkcinių modulių veiklos logikoje turi būti numatytos taisyklės kaip elgtis su logiškai suarchyvuotais duomenimis (pvz., vykdant skaitmeninio turinio paiešką, pagal nutylėjimą paiešką atlikti tik tuose SAULĖ IS duomenyse, kurie nėra pažymėti kaip perkelti į SAULĖ IS loginį archyvą, tačiau SAULĖ IS naudotojo sąsajoje palikti galimybę įjungti paiešką ir tarp logiškai archyvuotų duomenų – tai yra reikalinga SAULĖ IS paieškos funkcijų ir kitų funkcijų veikimo spartos optimizavimui).
2507. Detalios analizės projektavimo etape turi būti apibrėžtos archyvuotinų duomenų taisyklės (dažnumas, apimtis ir pan.).

## 8.10	REIKALAVIMAI PASLAUGŲ TEIKIMUI
### 8.10.1	Reikalavimai dokumentacijai ir jos derinimui
2508. Visa dokumentacija turi būti parengta laikantis bendrinės lietuvių kalbos taisyklių. Dokumentacija, kurioje nėra aprašomi veiklos procesai ir funkcijos (architektūros sprendimai, diegimo ir administravimo instrukcijos ir pan.), gali būti rengiama anglų kalba.
2509. Visi Diegėjo parengti dokumentai turės būti suderinti su Perkančiąja organizacija ir Techninės priežiūros paslaugų teikėju. Detalūs dokumentų derinimo principai turės būti pateikti ir suderinti Diegėjo parengtame projekto vykdymo reglamente. 
2510. Diegėjas turės parengti dokumentaciją, nurodytą 8.11 skyriaus lentelėje.
2511. Reikalavimai rezultatų pateikimo ir derinimo terminams:
2511.1. Tikslus dokumentų pateikimo terminas turi būti sutartas Paslaugų teikimo reglamente.
2511.2. Perkančioji organizacija įsipareigoja pateikti pastabas derinimui pateiktiems dokumentams tokiais terminais:
2511.2.1. iki 100 puslapių dokumento: 
2511.2.1.1. pirma versija – per 8 darbo dienas ar kitą sutartą terminą, 
2511.2.1.2. po pastabų pataisyta dokumento versija – per 5 darbo dienas ar kitą sutartą terminą,
2511.2.2. virš 100 puslapių dokumento: 
2511.2.2.1. pirma versija – per 10 darbo dienas ar kitą sutartą terminą, 
2511.2.2.2. po pastabų pataisyta dokumento versija – per 8 darbo dienas ar kitą sutartą terminą.
2511.3. Diegėjas dokumentus tikslinta ir teikia ne ilgiau kaip per 10 darbo dienų nuo pastabų gavimo dienos.
2511.4. Diegėjo rezultatai derinami su Perkančiąja organizacija ir Techninės priežiūros paslaugų teikėju ne daugiau kaip 2 (dviem) iteracijomis, jeigu nesutarta kitaip. 
2511.5. Perkančioji organizacija turi teisę per derinimui skirtus terminus atsisakyti teikti pastabas pirmai dokumento versijai, jeigu ji nėra tinkama derinimui ir pastabų teikimui:
2511.5.1. Dokumente pateikta ne visa apimtis vertikaliai, t. y. nepateikti visi būtini tokiam dokumentui pateikti skyriai ir dalys.
2511.5.2. Dokumente pateikta ne visa apimtis horizontaliai, t. y. dokumentas neapima visų SAULĖ IS modulių ar funkcijų, kurie (-ios) turi būti šiame dokumente. 
2512. Diegėjo pataisyti dokumentai turi būti teikiami su matomais pakeitimais („track changes“ funkcija).
2513. Su Perkančiąja organizacija suderinti dokumentai turi (gali) būti keičiami vėlesnių etapų metu, jeigu yra vykdomi kuriamos informacinės sistemos pakeitimai, atsižvelgiant į priėmimo testavimo bei bandomosios eksploatacijos rezultatus, kitas projekto veiklas ir aplinkybes, kurios susijusios su pateiktos dokumentacijos turiniu. Projekto dokumentacija turi būti aktualizuojama (atnaujinama) ir galutinės versijos pateiktos su Perkančiąja organizacija suderintais terminais bet ne vėliau kaip iki galutinio priėmimo perdavimo akto pateikimo dienos.
2514. Dokumentų galutinės versijos turi būti pateiktos elektroniniu (MS Word arba kitu su Perkančiąja organizacija suderintu redagavimui tinkamu formatu įrašant dokumentą (-us) į CD, DVD ar kitą skaitmeninę laikmeną), o atskirtu Perkančiosios organizacijos nurodymu - popierinės.
2515. Preliminarios (projektinės) versijos turi būti pateikiamos elektroniniu formatu elektroninio ryšio priemonėmis. Pastabos bei korekcijos dokumentų projektuose turi būti teikiamos MS Office programinio paketo (ar lygiaverčio) pakeitimų sekimo (angl. track changes) bei komentavimo funkcijomis. Turi būti vykdomas pateikiamų dokumentų versijavimas (versijų kontrolė).

### 8.10.2	Reikalavimai demonstracijoms
2516. Diegėjas kūrimo etape turi atlikti SAULĖ IS demonstracijas gyvai demonstruojant sistemos veikimą. Turi būti atliekamas SAULĖ IS demonstravimas, o ne prototipo.
2517. Demonstruojamo funkcionalumo apimtis ir laikiškumas turi būti nustatyti projekto reglamente. Iki priėmimo testavimo etapo pradžios VPT turi būti pademonstruotas visas SAULĖ IS funkcionalumas, išskyrus tą funkcionalumą, kuris bus suderintas kaip nedemonstruotinas (pavyzdžiui, integracijos).
2518. Demonstracijų tikslas – supažindinti VPT su kuriama programine įranga bei gauti atsiliepimus dėl sukurto (kuriamo) funkcionalumo.
2519. Pastabos (atsiliepimai) gali būti išsakomos pakartotinai priėmimo testavimo etape, jeigu į jas nebus atsižvelgta iki pastarojo etapo.
2520. Demonstracijų metu išsakomi atsiliepimai (pastabos) turi būti registruojami susitikimo protokoluose ar kita sutarta forma (pavyzdžiui, specializuotoje klaidų registravimo ir sekimo sistemoje).
2521. Funkcionalumo demonstraciją turi vykdyti Diegėjas, o VPT atstovai turi teikti atsiliepimus.

### 8.10.3	Reikalavimai testavimui
2522. Turi būti atliktas modernizuotos SAULĖ IS priėmimo testavimas.
2523. Testavimo tikslai:
2523.1. įsitikinti, kad yra įgyvendinti visi funkciniai ir nefunkciniai specifikacijos reikalavimai;
2523.2. įsitikinti, kad reikalavimų įgyvendinimas atliktas tinkama apimtimi;
2523.3. nustatyti ar reikalavimų įgyvendinimas tenkina VPT ir kitas suinteresuotas šalis;
2523.4. identifikuoti ir užregistruoti funkcionalumo klaidas, problemas, trūkumus (angl. bugs).
2524. Turi būti atlikti šie testavimai:
2524.1. vidinis testavimas. Vidinius atskirų komponentų testavimus Diegėjas turi atlikti nedalyvaujant VPT atstovams, tačiau turi pateikti tokio testavimo įrodymus – vidinio testavimo ataskaitą ir nustatytų neatitikimų sąrašą. Vidinis testavimas turi būti atliktas SAULĖ IS kūrimo aplinkoje;
2524.2. priėmimo testavimas (angl. acceptance testing). Šis testavimas turi būti atliekamas dalyvaujant Diegėjui, VPT ir kitoms suinteresuotoms šalims. Šio testavimo metu turi būti tikrinamas testavimo tikslų įgyvendinimas (įgyvendinimo lygio nustatymas). Priėmimo testavimo veiklos turi būti vykdomos remiantis apibrėžtu priėmimo testavimo metodika ir priėmimo testavimo scenarijais (rengia Diegėjas).
2524.3. SAULĖ IS sąrankos (kompiliavimo) ir diegimo testavimas. Testavimas turi būti vykdomas Perkančiosios organizacijos atstovų pagal Diegėjo pateiktas SAULĖ IS diegimo instrukcijas. Testavimų metu Perkančiosios organizacijos atstovai turi sukompiliuoti SAULĖ IS išeities kodą, įdiegti kitus SAULĖ IS komponentus, atlikti tinkamą SAULĖ IS komponentų konfigūravimą ir paleidimą darbui. Diegėjo atstovai turi teikti konsultacijas SAULĖ IS diegimo klausimais. Diegėjas turi registruoti klaidas, jas šalinti, tikslinti diegimo instrukcijas, automatizuoti diegimo procesą ir atlikti kitus pakeitimus pagal Perkančiosios organizacijos pateiktas pastabas.
2525. Atlikti testavimai turi užtikrinti, kad modernizuota SAULĖ IS yra tinkama bandomajai eksploatacijai.
2526. Testavimų metu turi būti vykdomas identifikuotų klaidų, problemų ir trūkumų registravimas. Už registravimą atsakingas Diegėjas. 
2527. Klaidų žurnalas turi būti specializuota problemų registravimo ir sekimo programinė įranga (angl. issue tracking software), paremta tinklinėmis technologijomis, t. y. pasiekiama naudojant interneto naršyklę.
2528. Diegėjas turės parengti visus testavimui reikalingus testavimo duomenis.
2529. Diegėjas turės užtikrinti, kad priėmimo testavimo metu SAULĖ IS būtų pakankamai testavimo duomenų, kurie leistų visiškai ištestuoti modernizuotos SAULĖ IS funkcionalumus.
2530. Priėmimo testavimas bus užbaigiamas, kai bus tenkinami testavimo metodikoje įvardinti testavimo priėmimo kriterijai.
2531. Perkančioji organizacija savo iniciatyva gali atlikti bet kokius kitus SAULĖ IS testavimus ir bandymus (išeities kodų tikrinimą, konfigūracijos tikrinimą, našumo tikrinimą, aukšto prieinamumo tikrinimą, plečiamumo tikrinimą ir kt.) siekdama užtikrinti SAULĖ IS kokybę ir atitikimus reikalavimams. Diegėjas turės atsižvelgti į Perkančiosios organizacijos atstovų atliktų bandymų ir testavimų rezultatus, atlikti visų testavimų rezultatuose nurodytų trūkumų (pažeidimų, rekomendacijų) šalinimą. Diegėjas turės sudaryti reikiamas sąlygas suplanuotiems testavimams ir bandymams atlikti – pateikti išeities kodą, pateikti prisijungimo duomenis prie SAULĖ IS komponentų, sukurti testavimui reikalingus naudotojus, įjungti/ išjungti SAULĖ IS komponentus, sudaryti prieigos galimybes specializuotai testavimo ir bandymų programinei įrangai, atlikti kitas reikiamas veiklas, kurios užtikrintų pilnavertį testavimų ir bandymų proceso įvykdymą.

### 8.10.4	Reikalavimai diegimui
2532. Žemiau pateikiama principinė SAULĖ IS diegimo schema. Schemoje pateiktas PĮ diegimo paskirstymas tarp virtualių mašinų ir konteinerių yra iliustracinio pobūdžio ir turi būti tikslinamas projektavimo etape, apibrėžiant ir pagrindžiant diegimo paskirstymą kiekvienu atveju.

![image](https://user-images.githubusercontent.com/61745726/89342887-17309400-d6ac-11ea-9314-6a090d67650f.png)

2533. Turi būti įdiegtos šios SAULĖ IS aplinkos:
2533.1. Produkcinė – naudojama visą SAULĖS IS eksploatavimo laikotarpį;
2533.2. Testavimo –  naudojama visą SAULĖS IS eksploatavimo laikotarpį. Testavimo aplinkos architektūriniai sprendimai turi būti paremti produkcinės aplinkos sprendimais. Testavimo aplinkos diegiamų komponentų kiekis gali būti mažinamas (ir / ar grupuojamas) siekiant racionalaus resursų panaudojimo, tokiems sprendimams turi būti gautas Perkančiosios organizacijos pritarimas. Testavimo aplinkai nėra keliami aukšto prieinamumo reikalavimai. Testavimo aplinkai nėra keliami rezervinio duomenų kopijavimo reikalavimai. Testavimo aplinkos greitaveika turi užtikrinti, kad vidutinė SAULĖ IS atsako trukmė  (trukmė nuo serverio HTTP užklausos gavimo iki HTTP atsakymo išsiuntimo) neturi viršyti 3 sekundžių, esant bendram HTTP užklausų kiekiui per minutę 60.
2533.3. Mokymų aplinka – naudojama visą SAULĖS IS eksploatavimo laikotarpį. Mokymų aplinka turi būti diegiama apimtimi, kuri bus reikalinga mokymams atlikti. Diegimo apimtis turės būti suderinta projektavimo etape. Mokymų aplinkai nėra keliami aukšto prieinamumo reikalavimai. Mokymų aplinkai nėra keliami rezervinio duomenų kopijavimo reikalavimai. Mokymų aplinkos greitaveika turi užtikrinti, kad vidutinė SAULĖ IS atsako trukmė  (trukmė nuo serverio HTTP užklausos gavimo iki HTTP atsakymo išsiuntimo) neturi viršyti 3 sekundžių, esant bendram HTTP užklausų kiekiui per minutę 150, kai su sistema vienu metu dirba iki 50 naudotojų.
2533.4. „Sand box“ aplinka – naudojama visą SAULĖS IS eksploatavimo laikotarpį. „Sand box“ aplinka skirta VPT specialistams, kurie savarankiškai ar su Diegėjo pagalba vykdys SAULĖ IS komponentų testavimus, bandymus, eksperimentus (keis konfigūracinius parametrus, diegimo parametrus, diegs kitą (papildomą) PĮ) ir pan. „Sand box“ aplinka turės būti diegiama pagal produkcinės aplinkos architektūrinius principus. „Sand box“ aplinkos diegiamų komponentų kiekis gali būti mažinamas (ir / ar grupuojamas) siekiant racionalaus resursų panaudojimo, tokiems sprendimams turi būti gautas Perkančiosios organizacijos pritarimas. „Sand box“ turi būti realizuojami aukšto prieinamumo sprendimai jų testavimo ir konfigūravimo tikslais. „Sand box“ aplinkos komponentai, įdiegimo apimtis, konfigūravimo parametrai ir panaudoti sprendimai turi būti keičiami Perkančiajai organizacijai nurodžius tokį poreikį. Visi pakeitimai turi būti atliekami siekiant parinkti, išbandyti ir realizuoti tinkamiausius sprendimus SAULĖS IS sukūrimui ir eksploatavimui. „Sand box“ aplinkai nėra keliami aukšto prieinamumo reikalavimai. „Sand box“ aplinkai nėra keliami rezervinio duomenų kopijavimo reikalavimai. „Sand box“ greitaveikos reikalavimai turi būti suderinti projektavimo etape.
2534. Turi būti galimybė pagal diegimo instrukciją įdiegti kitas (papildomas) aplinkas, valdyti diegimo apimtį ir pagrindinius parametrus.
2535. Didelių duomenų platformos valdymo PĮ, konteinerių valdymo PĮ, VM platformos valdymo PĮ turi būti diegiama atskiroje techninėje įrangoje nuo techninės įrangos, kurioje įdiegta valdomi komponentai. Išimtys galimos jeigu kitokį diegimą oficialiai rekomenduoja naudojamos PĮ gamintojas.
2536. SAULĖS IS komponentai turi būti diegiami konteineriuose („Docker“ ar lygiaverčiuose) ir tiesiogiai virtualiose mašinose. Kiekvieno komponento diegimo principas turi būti pagrįstas projektavimo etape. Schemoje pateiktas PĮ diegimo paskirstymas tarp virtualių mašinų ir konteinerių yra iliustracinio pobūdžio.
2537. Konteineriai gali būti diegiami tiesiogiai tarnybinėse stotyse arba VM platformoje. Kiekvieno komponento diegimo principas turi būti pagrįstas projektavimo etape. 
2538. Testavimo, Mokymosi, „Sand box“ aplinkose turi būti naudojami aktualūs, bet tik „nuasmeninti“ duomenys.
2539. SAULĖ IS turi būti įdiegta Valstybės debesijos paslaugų teikėjo VDPT infrastruktūroje. VDPT teikiamos paslaugos ir VDPT architektūra aprašyta šiame dokumente: https://ivpk.lrv.lt/uploads/ivpk/documents/files/veikla/VII%20konsolidavimas/Login%C4%97_Debesijos_paslaug%C5%B3_teikimo_IT_infrastrukt%C5%ABros_architekt%C5%ABra.pdf
2540. SAULĖ IS turi veikti hibridinio debesies principu (didžioji dalis komponentų turės būti įdiegti VDPT, kiti su VPT suderinti komponentai bus eksploatuojami VPT infrastruktūroje). Diegėjas turi užtikrinti galimybę SAULĖ IS virtualią infrastruktūrą perkelti į kitą nutolusį duomenų centrą, neatliekant esminių SAULĖ IS programinių komponentų perkūrimo darbų.
2541. Sutartu Projekto vykdymo metu Diegėjas turi pateikti poreikius (specifikaciją) dėl SAULĖ IS veikimui būtinos techninės ir programinės infrastruktūros, gaunamos kaip debesijos paslaugos. Turi būti įvertinti techninės infrastruktūros poreikis, programinės įrangos poreikis ir specifiniai reikalavimai (pvz. licencijuojamų produktų poreikis, reikalavimai prieinamumui, tinklo pralaidumui, saugumui ir pan.).

### 8.10.5	Reikalavimai bandomajai eksploatacijai
2542. Turi būti atlikta SAULĖ IS bandomoji eksploatacija.
2543. Bandomosios eksploatacijos tikslai: 
2543.1. užtikrinti SAULĖ IS kokybę;
2543.2. išbandyti gamybinę SAULĖ IS komponentų konfigūraciją;
2543.3. identifikuoti ir pašalinti bandomosios eksploatacijos metu pastebėtus defektus;
2543.4. stabilizuoti darbinės aplinkos konfigūraciją, atsižvelgiant į bandomosios eksploatacijos metu sukauptą patirtį.
2544. Bandomosios eksploatacijos veiklas Diegėjas turės vykdyti pagal su VPT atstovų pateiktą bandomosios eksploatacijos planą ir Diegėjo sudarytą bandomosios eksploatacijos metodiką bei scenarijus.
2545. Diegėjas, iki bandomosios eksploatacijos pradžios, privalo paruošti SAULĖ IS infrastruktūrą darbui:
2545.1. atlikti SAULĖ IS komponentų konfigūravimą, kad visi bandomosios eksploatacijos dalyviai turėtų galimybę prisijungti prie SAULĖ IS iš savo darbo vietų. Naudotojo darbo vietų parengimą užtikrins VPT. Diegėjas turi pateikti rekomendacijas dėl naudotojų darbo vietų paruošimo;
2545.2. sumigruoti (įkelti ir suvesti) visus būtinus SAULĖ IS duomenis bei pašalinti perteklinius (bandomajai eksploatacijai nereikalingus) duomenis, taip pat privalo užtikrinti, kad visi duomenys SAULĖ IS būtų integralūs.
2546. Diegėjas privalo užtikrinti SAULĖ IS veikimą visos bandomosios eksploatacijos metu, jeigu nebus sutarta kitaip.
2547. Bandomoji eksploatacija yra baigiama, kai tenkinami bandomosios eksploatacijos priėmimo kriterijai, kurie pateikiami bandomosios eksploatacijos metodikoje.

### 8.10.6	Reikalavimai mokymams
2548. Diegėjas turi atlikti SAULĖ IS naudotojų mokymus. Turi būti apmokyti:
2548.1. Ne mažiau 70 VPT darbuotojų darbui su vidiniu portalu (ne didesnėmis nei 10 asmenų grupėmis);
2548.2. Ne mažiau 7 VPT administratoriai darbui su SAULĖ IS administravimo komponentais, didelių duomenų platforma, integracijų posisteme, TVS, kitų komponentų administravimo funkcionalumu;
2548.3. Ne mažiau 2 VPT darbuotojai darbui su dirbtinio intelekto PĮ;
2548.4. Ne mažiau 2 VPT darbuotojai darbui su Rizikos valdymo posisteme;
2548.5. Ne mažiau 10 VPT darbuotojų darbui su analitikos PĮ.
2549. Mokymai vedami lietuvių kalba VPT patalpose ir VPT darbo valandomis.
2550. Diegėjas turi parengti mokymų planą ir mokymų medžiagą.
2551. Turi būti parengta visoms SAULĖ IS naudotojų grupėms skirta vaizdinė (video medžiaga) metodinė medžiaga 4K formatu ir aukštos kokybė garso įrašu, kurioje būtų demonstruojamas ir aiškinamas portalo SAULĖ naudojimas. 
2552. Turi būti parengtos SAULĖ IS administravimo instrukcijos, SAULĖ IS įdiegimo instrukcijos.
2553. Turi būti parengtos portalo „Saulė“ ir vidinio portalo naudotojų instrukcijos. Instrukcijos turi būti patalpintos portale „Saulė“ ir vidiniame portale, naudotojams patogiu formatu skaityti ir naršyti.

### 8.10.7	Reikalavimai garantinei priežiūrai
2554. Diegėjas turi užtikrinti Projekto metu sukurto ir įdiegto SAULĖ IS funkcionalumo garantinę priežiūrą bei visų šios Specifikacijos įgyvendinimo metu suteiktų paslaugų rezultatų (dokumentacijos, įdiegimo konfigūracijos, duomenų migravimo ir kt.) garantinę priežiūrą. Garantinė priežiūra turi būti vykdoma pagal su VPT suderintą garantinės priežiūros reglamentą.
2555. Garantinės priežiūros terminas - 36 mėnesiai nuo galutinio priėmimo–perdavimo akto pasirašymo datos.
2556. Garantinės priežiūros paslaugos apima sukurtos ir įdiegtos programinės įrangos sutrikimų šalinimą bei VPT atsakingų asmenų konsultavimą.
2557. Diegėjas turi vykdyti VPT atsakingų asmenų konsultavimą SAULĖ IS veikimo, naudojimo bei tobulinimo klausimais. Konsultacijos turi būti teikiamos telefonu, el. paštu, naudojant priežiūros tarnybos (angl. Help Desk) programinę įrangą (turi būti suderinta ar naudojama VPT programinė įranga ar programinę įrangą pateikia Diegėjas) ar atvykus į VPT.
2558. Garantinės priežiūros paslaugos teikiamos visą parą, septynias dienas per savaitę („24/7“).
2559. Programinės įrangos veikimo sutrikimu laikoma situacija, kai SAULĖ IS naudotojai dėl Diegėjo sukurtos programinės įrangos funkcionalumo trūkumų negali atlikti numatytų SAULĖ IS funkcijų (neveikia funkcija, neveikia sistema, neveikia integracinė sąsaja ir kt.) ar funkcijos veikia nekorektiškai. 
2560. Programinės įrangos sutrikimų atstatymo trukmė:
2560.1. **1-asis reagavimo lygis** – atsako laikas yra 30 minučių po susisiekimo su Paslaugų teikėju per Pagalbos sistemą Support Desk, telefonu ir el. paštu. Veikimo sutrikimai turi būti pašalinti ne vėliau kaip per 1 valandą nuo Paslaugų teikėjo atsako į Problemą per Pagalbos sistemą Support Desk, telefonu ir el. paštu. Gedimų, kurių nepavyksta pašalinti per 1 valandą (kai dėl to susitaria Paslaugų teikėjas ir Perkančioji organizacija), paslaugų teikėjas turi paruošti statuso ir veiklos planą, kuris bus pateiktas Perkančiajai organizacijai per 2 valandas. Tolesni veiksmai bus vykdomi pagal veiklos planą (turi būti suderinta tarp šalių). Veikimo sutrikimas – sutrikimas, kai visi ar dauguma Paslaugų naudotojų (atskirose organizacijose) negali atlikti savo funkcijų.
2560.2. **2-asis reagavimo lygis**. Reagavimo laikas  yra 1 valanda. Problemos šalinimo procesas trunka ne ilgiau kaip 3 valandas nuo Paslaugų teikėjo atsako į Problemą. Gedimų, kurių nepavyksta pašalinti per 3 valandas (kai dėl to susitaria Paslaugų teikėjas ir Perkančioji organizacija), Paslaugų teikėjas turi paruošti statuso ir veiklos planą, kuris bus pateiktas Perkančiajai organizacijai per 5 valandas. Tolesni veiksmai bus vykdomi pagal veiklos planą (turi būti suderinta tarp šalių).
2560.3. **3-asis reagavimo lygis**. Reagavimo laikas yra 1 valanda. Problemos šalinimo procesas trunka ne ilgiau kaip 8 valandas nuo Paslaugų teikėjo atsako į Problemą. Gedimų, kurių nepavyksta pašalinti per 8 valandas (kai dėl to susitaria Paslaugų teikėjas ir Perkančioji organizacija), Paslaugų teikėjas turi paruošti statuso ir veiklos planą, kuris bus pateiktas Perkančiajai organizacijai per 12 valandų. Tolesni veiksmai bus vykdomi pagal veiklos planą (turi būti suderinta tarp šalių).
2560.4. **4-asis reagavimo lygis**. Reagavimo laikas yra 5 dienos. Problemos šalinimo procesas trunka ne ilgiau kaip 1 mėnesį nuo Paslaugų teikėjo atsako į Problemą.
2561. Pašalinus sutikimus Perkančiajai organizacijai turi būti pateikiamas atnaujintas SAULĖ IS išeities kodas.

### 8.10.8	Reikalavimai galutiniam SAULĖ IS priėmimui
2562. Galutinis SAULĖ IS priėmimas bus vykdomas pasibaigus bandomajai eksploatacijai, t. y. priėmimas galės būti vykdomas tik tada, kai bus pasiekti bandomosios eksploatacijos priėmimo kriterijai.
2563. Visos SAULĖ IS sukūrimo paslaugos (paslaugų rezultatai) bus priimamos pasirašant galutinį priėmimo-perdavimo aktą.
2564. Siekiant užtikrinti sklandų Projekto tęstinumą:
2564.1. Diegėjas, nepažeidžiant autoriaus teisių turėtojo ar trečiųjų šalių intelektinės nuosavybės teisių, sutartimi perduoda VPT autorių turtines teises į pagal užsakymą sukurtą programinę įrangą ir parengtus projektinius dokumentus, įskaitant, bet neapsiribojant, teisę neribotą laiką ir be papildomo atlygio naudoti sukurtą programinę įrangą; teisę daryti sukurtos programinės įrangos kopijas; teisę modifikuoti ir toliau plėtoti sukurtą programinę įrangą; teisę perkelti programinę įrangą į kitą technologinę platformą; teisę naudoti ir keisti jai sukurtos programinės įrangos pradinį kodą (mašininės kalbos pradinius tekstus).
2564.2. Jeigu pagal užsakymą sukurtoje programinėje įrangoje panaudota kita autoriaus teisių turėtojo ar trečiųjų šalių programinė įranga, kuri integruota į pagal užsakymą sukurtą programinę įrangą ar kitaip susieta su atliktu užsakymu ir autoriaus turtinių teisių į sukurtą programinę įrangą ar parengtus projektinius dokumentus, jos perdavimas VPT neturi apriboti šias teises perdavusio Diegėjo teisės be atskiro VPT sutikimo toliau vystyti, tobulinti, platinti ir atlikti kitus reikiamus veiksmus su sukurta programine įranga ar parengtais projektiniais dokumentais.
2564.3. Kartu su kompiuterine programa, kaip ši sąvoka apibrėžta Lietuvos Respublikos autorių teisių ir gretutinių teisių įstatyme, VPT perduodamas ir programos išeitinis kodas. Kompiuterių programos autoriaus asmeninės neturtinės teisės negali būti naudojamos tokiu būdu, kuris suvaržytų autorių turtinių teisių į šią kompiuterinę programą turėtojo teises, tarp jų ir teisę savo nuožiūra adaptuoti, keisti ir neatlygintinai platinti šiuos kūrinius. Šiame punkte numatytos autorių turtinės teisės, vadovaujantis Autorių teisių ir gretutinių teisių įstatymo ir Valstybės informacinių išteklių valdymo įstatymo 12 str. nuostatomis,  perduodamos ir suteikiamos Lietuvos Respublikos ir Europos Sąjungos šalių teritorijoje neribotam laikui.
2564.4. Diegėjas turi perduoti Perkančiajai organizacijai projekto metu sukurtą programinę įrangą ir jos išeitinį kodą paslaugų priėmimo – perdavimo akto pasirašymo datai. 
2564.5. Diegėjas neturi teisės atskleisti jokios su paslaugų teikimu susijusios informacijos trečiosioms šalims be Perkančiosios organizacijos raštiško leidimo arba jei to reikalauja įstatymai.

## 8.11	REIKALAVIMAI SAULĖ IS KŪRIMO PASLAUGŲ ETAPAMS IR TERMINAMS
2565. Žemiau esančioje lentelėje pateikti Paslaugų etapai, etapų metu atliekami darbai (veiklos), diegimo dalyvių atsakomybių aprašymas ir reikalavimai dokumentacijai.
2566. Projektas turi būti įgyvendinamas iteraciniu-inkrementiniu informacinės sistemos kūrimo būdu, taikant gerąsias „Agile“ programinės įrangos kūrimo praktikas.
2567. Projektas turi būti įgyvendintas sukuriant šešis prieaugius (iteracijas):
2567.1. Pirmasis prieaugis turi apimti inicijavimo, detalios analizės, projektavimo, kūrimo, diegimo testavimo aplinkoje ir priėmimo testavimo etapus (reikalavimai etapams pateikti žemiau lentelėje).
2567.2. Antrasis, trečiasis, ketvirtasis ir penktasis prieaugiai turi apimti detalios analizės, projektavimo, kūrimo, diegimo testavimo aplinkoje ir priėmimo testavimo etapus (reikalavimai etapams pateikti žemiau lentelėje). Atskiru perkančiosios organizacijos nurodymu šie prieaugiai gali apimti bandomąją eksploataciją ir diegimą į gamybinę aplinką, kai Projekto vykdymo metu sutariama, kad dalis funkcionalumo turi būti įdiegta į gamybą.
2567.3. Šeštasis prieaugis turi apimti visus (išskyrus inicijavimo) etapus (reikalavimai etapams pateikti žemiau lentelėje).
2568. Prieaugių realizavimo metu Diegėjas turi atlikti visus prieš tai buvusių prieaugių metu sukurtų funkcionalumų pakeitimus (modernizavimą), jeigu toks poreikis paaiškėja detalios analizės ir projektavimo etape.
2569. Diegėjas paslaugų teikimo reglamente turi nurodyti kokias konkrečias SAULĖ IS modernizavimo veiklas (kokias funkcijas kurs/ modernizuos, kokias sąsajas realizuotas ir t.t.) atliks kiekviename prieaugyje.
2570. Pasirašius paslaugų teikimo sutartį bendru sutarimu (esant pagrindimui ir Perkančiosios organizacijos pritarimui) gali būti tikslinamas projekto veiklų grafikas (prieaugių kiekis, etapų terminai ir pan.).
2571. Diegėjas turės atlikti etapų rezultatų ir siūlomų sprendimų pristatymus (demonstracijas, prezentacijas ir pan.), jeigu to pareikalaus Perkančioji organizacija.
2572. Visos paslaugos turi būti suteiktos Paslaugų teikimo sutartyje numatytais terminais ir sąlygomis.

8.1 lentelė. Paslaugų etapai, etapų rezultatai ir terminai

Nr. | Paslaugų teikimo etapas | Reikalavimai etapo darbams | Rezultatas | Terminas
-- | -- | -- | -- | --
1. | Inicijavimas | Diegėjas:   ·         Parengia Paslaugų teikimo reglamentą ir suderina su Perkančiąja   organizacija.   Perkančioji   organizacija:   ·         Suteikia reikalingą informaciją;   ·         Teikia pastabas ir rekomendacijas. | Paslaugų teikimo reglamentas. Paslaugų teikimo reglamente nurodomi   Projekto tikslai, prioritetai, etapų apimtys ir rezultatai, suinteresuotos   šalys, darbų atlikimo grafikas, naudojami standartai ir kokybiniai   reikalavimai, rizikos ir jų suvaldymo būdai, komunikavimo principai,   atsakomybės, Projekto problemų nustatymo ir valdymo procedūros, tarpinių ir   galutinių rezultatų priėmimo kriterijai, pokyčių valdymo procedūra, problemų   sprendimo procedūra, rizikų valdymo procedūra ir visa kita Projekto vykdymui   ir pokyčių valdymui aktuali informacija. | Etapo   rezultatai turi būti pateikti per 15 darbo dienų nuo Paslaugų teikimo   sutarties įsigaliojimo datos.
2. | Detali   analizė | Diegėjas:   ·         Atlieka esamos ir siekiamos padėties įvertinimą, parengia detalios   analizės dokumentaciją ir ją suderina su Perkančiąja organizacija.   Perkančioji   organizacija:   ·         Suteikia reikalingą informaciją;   ·         Teikia pastabas ir rekomendacijas;   ·         Tvirtina etapo Diegėjo rezultatus. | Detalios analizės dokumentai. Detalios analizės dokumentuose   išanalizuojami ir detalizuojami funkciniai ir nefunkciniai Techninės   specifikacijos reikalavimai bei kiti Perkančiosios organizacijos išsakyti   poreikiai, parengiami naudojimo atvejai (angl. use case), kurie pateikiami naudojimo atvejų diagramomis pagal   UML (angl. Unified Modeling Language)   notaciją ir detalizuojami aprašant kiekvieno naudojimo atvejo vykdymo   žingsnius (pagrindinę eigą, alternatyvią eigą, išimtinę eigą) ir kitus   apribojimus. Sudėtingesni naudojimo atvejai ar jų grupės turi būti detalizuojami   pateikiant veiklos bei SAULĖ IS veikimo procesus, naudojant procesų   modeliavimo diagramas (angl. UML   activity diagram, BPMN (Business Process Model and Notation) ar   lygiavertes diagramas). Pateikiami pastarųjų diagramų struktūrizuoti aprašai.   Aprašomi SAULĖ IS naudotojai ir jų teisės. Turi būti atliktas visų šios Specifikacijos   funkcinių ir nefunkcinių reikalavimų susiejimas su detalios analizės   dokumento turiniu (skyriais, naudojimo atvejais, diagramomis ir pan.).   Siejimas turi būti atliekamas tokia forma, kad būtų aišku kokiu būdu yra   projektuojamas ir realizuojamas kiekvienas šios Specifikacijos reikalavimas. | -
3. | Projektavimas | Diegėjas:   ·         Parengia SAULĖ IS projektavimo dokumentaciją;   ·         Parengia integracines sąsajas aprašančius dokumentus.   Perkančioji   organizacija:   ·         Suteikia reikalingą informaciją;   ·         Teikia pastabas ir rekomendacijas;   ·         Tvirtina etapo Diegėjo rezultatus. | Projektavimo dokumentai. Turi būti pateiktas SAULĖ IS architektūros   aprašymas fizinių komponentų ir programinių komponentų požiūriu, naudojamos   technologijos (jų pavadinimai, versijos), informacinis vaizdas (duomenų bazės   struktūros (su paaiškinimais), duomenų bazių sąsajų schemos ir kt.),   funkcinis vaizdas (SAULĖ IS funkciniai vienetai, jų funkcijos, tarpusavio   sąsajos, naudotojo sąsajos prototipai, ir kt.), integracinis vaizdas (sąsajos   tarp vidinių ir išorinių sistemų, kuriamos sistemos atžvilgiu), operacinis   vaizdas (sisteminiai procesai, algoritmai, periodiniai sisteminiai darbai ir   pan.), dislokavimo vaizdas (programinių komponentų pasiskirstymas techninėje   įrangoje) ir kt.   Integracines sąsajas aprašantys   dokumentai.   Juose turi būti detalizuojama kiekvienos integracinės ir duomenų mainų   sąsajos paskirtis, realizavimo sprendimas, siunčiamus / gaunamos užklausos,   teikiami / gaunami duomenys, prisijungimo ir kiti parametrai, integracinės   sąsajos naudojimo pavyzdžiai ir scenarijai (angl. sequence diagram) ir kita   aktuali informacija, aprašanti integracinės sąsajos veikimą, jos naudojimą. | -
4. | Kūrimas | Diegėjas:   ·         Vykdo reikalingus programavimo ir konfigūravimo darbus (savo kūrimo   aplinkoje), įgyvendina funkcinius ir nefunkcinius reikalavimus;   ·         Atlieka komponentų (angl. unit)   testavimą, vidinį testavimą, sąsajų su kitomis sistemomis ir registrais   (integravimo) testavimą ir parengia vidinio testavimo ataskaitą.   ·         Vykdo SAULĖ IS demonstracijas.   ·         Parengia SAULĖ IS diegimo instrukcijas.       Perkančioji   organizacija:   ·         Suteikia reikalingą informaciją;   ·         Peržiūri ir įvertina vidinio testavimo rezultatus;   ·         Teikia pastabas ir rekomendacijas SAULĖ IS demonstracijų metu.   ·         Teikia reikiamą informaciją dėl SAULĖ IS diegimo testavimo aplinkoje. | Vidinio testavimo ataskaita, kurioje aprašyti atlikto vidinio testavimo   rezultatai (apimtis, vykdymo metodika, naudoti testavimo scenarijai,   testavimo scenarijų vykdymo rezultatai, testavimo aplinka, išvados).   Parengta programinė   įranga diegimui.   Parengtos   SAULĖ IS diegimo instrukcijos.   Atliktos SAULĖ IS demonstracijos. | Vidinio   testavimo ataskaita turi būti pateikta bent 2 savaitės iki kūrimo etapo   pabaigos.   SAULĖ   IS demonstracijos turi būti vykdomos nuolatos, pagal atskirai suderintą   grafiką.
5. | Diegimas   testavimo aplinkoje | Diegėjas:   ·         Parengia ir pateikia programinę įrangą tinkamą įdiegimui Perkančiosios   organizacijos testavimo aplinkoje;   ·         Atlieka sukurtos programinės įrangos įdiegimą testavimo aplinkoje.   ·         Pateikia priėmimo testavimo scenarijus ir testavimo metodiką.   Perkančioji   organizacija:   ·         Suteikia reikalingą informaciją;   ·         Kontroliuoja testavimo aplinką;   ·         Teikia pastabas priėmimo testavimo metodikai ir scenarijams. | Sukurta programinė įranga įdiegta   Perkančiosios organizacijos testavimo aplinkoje.   Priėmimo testavimo scenarijai ir   metodika. | Šis   diegimo etapas turi būti baigtas iki priėmimo testavimo etapo pradžios.
6. | Priėmimo   testavimas | Diegėjas:   ·         Parengia naudotojų vadovus (dokumentus): naudotojų instrukciją ir SAULĖ   IS administravimo instrukciją, diegimo instrukciją;   ·         Vykdo priėmimo testavimą;   ·         Atlieka testavimo metu išaiškėjusius reikalingus klaidų / neatitikčių   taisymus;   ·         Parengia priėmimo testavimo ataskaitą.   Perkančioji   organizacija:   ·         Vykdo priėmimo testavimą;   ·         Priima programinę įrangą diegimui į gamybinę aplinką.   ·         Atlieka naudotojo sąsajos patogumo naudotis vertinimą. | Sėkmingai atliktas priėmimo testavimas   (tenkinami sėkmingo priėmimo testavimo kriterijai).       Parengti naudotojų vadovai (naudotojų instrukcijos,   administravimo instrukcijos).       Parengta priėmimo testavimo ataskaita.       Diegimui į gamybinę aplinką parengta SAULĖ   IS. | Priėmimo   testavimas turi būti atliktas iki bandomosios eksploatacijos pradžios.
7. | Diegimas   gamybinėje aplinkoje | Diegėjas   atlieka šiuos darbus:   ·         Parengia ir pateikia programinę įrangą tinkamą įdiegimui Perkančiosios   organizacijos eksploatavimo aplinkoje.   ·         Įdiegia programinę įrangą eksploatavimo aplinkoje.       Perkančioji   organizacija:   ·         Teikia pastabas ir rekomendacijas;   ·         Teikia informaciją dėl eksploatavimo aplinkos; kontroliuoja eksploatavimo   aplinką. | Parengta eksploatavimo aplinka Perkančiosios organizacijos   infrastruktūroje.       Sukurta programinė įranga įdiegta Perkančiosios   organizacijos eksploatavimo aplinkoje. | Šis   diegimas gali vykti tik po sėkmingai įvykusio priėmimo testavimo.   Šis   diegimo etapas turi būti baigtas ne ilgiau kaip per dvi savaites nuo priėmimo   testavimo etapo pabaigos ir baigtas iki bandomosios eksploatacijos pradžios.
8. | Mokymai | Diegėjas   atlieka šiuos darbus:   ·         Parengia mokymų planą;   ·         Parengia mokymų medžiagą ir kitas reikalingas priemones;   ·         Įdiegia SAULĖ IS į mokymų aplinką;   ·         Vykdo apmokymus.   Perkančioji   organizacija:   ·         Pateikia pastabas mokymų planui;   ·         Dalyvauja mokymuose. | SAULĖ IS įdiegta mokymų aplinkoje.   Parengtas mokymų planas. Dokumente turi būti aprašytas mokymų   kursų organizavimas, pateikti detalūs mokymų planai/grafikai, mokymų grupės,   mokymų vietos, nurodytos mokymų priemonės.    Parengta mokymų medžiaga.   Įvykdyti mokymai sutartam naudotojų   kiekiui. | Mokymai   turi būti įvykdyti iki bandomosios eksploatacijos pradžios.
9. | Duomenų   migravimo etapas | Diegėjas   atlieka šiuos darbus:   ·         Parengia duomenų migravimo aprašą;   ·         Atlieka duomenų migravimą.       Perkančioji   organizacija:   ·         Suteikia duomenis ar prieigą prie duomenų, kurios reikia migruoti. | Pateiktas ir suderintas duomenų   migravimo aprašas.   Atliktas duomenų migravimas. | Duomenų   migravimas gali vykti tik po sėkmingo įdiegimo produkcinėje (eksploatavimo   aplinkoje etapo).
10. | Bandomoji   eksploatacija | Diegėjas:   ·         Teikia konsultacijas bandomosios eksploatacijos klausimais;   ·         Reaguoja ir pašalina eksploatacijos metu nustatytus defektus;   ·         Užtikrina ekspertų konsultavimą Perkančiosios organizacijos darbuotojams   ir IT specialistams;   ·         Atlieka reikiamus pakeitimus atsižvelgiant į atsparumo įsilaužimams ir   greitaveikos testavimo rezultatus.   ·         Parengia garantinės priežiūros procedūros dokumentus   Perkančioji   organizacija:   ·         Dirba su įdiegta SAULĖ IS;   ·         Registruoja bandomosios eksploatacijos metu nustatytas klaidas;   ·         Vykdo bandomosios eksploatacijos metu nustatytų problemų šalinimo   kontrolę;   ·         Atlieka atsparumo įsilaužimams ir greitaveikos testavimą. | Pašalintos bandomosios eksploatacijos   metu nustatytos klaidos. Sėkmingai baigta bandomoji eksploatacija.   Suteiktos konsultacijos.       Parengtas garantinės priežiūros   procedūros dokumentas. Dokumente turi būti aprašytas garantinės priežiūros teikimo būdas,   detalizuotos garantinės priežiūros teikimo sąlygos, Diegėjo atsakomybė,   Perkančiosios organizacijos atsakomybė, kontaktinė informacija, papildomos   tvarkos (eskalavimo, klaidų registravimo, konsultavimo) ir kt.).   Atlikti reikiami pakeitimai atsižvelgiant į atsparumo   įsilaužimams ir greitaveikos testavimo rezultatus. | Bandomosios   eksploatacijos trukmė derinama su Perkančiąja organizacija.   Garantinės   priežiūros procedūros dokumentas turi būti pateiktas likus ne mažiau kaip 1   mėnesiui iki bandomosios eksploatacijos pabaigos.
11. | Garantinė   priežiūra | Diegėjas   suteikia ne trumpesnį nei 36 mėnesių garantinį aptarnavimą. | Teikiami garantinės priežiūros   įsipareigojimai. | 36   mėnesiai nuo galutinio perdavimo-priėmimo akto pasirašymo dienos.
Viso Projekto metu
12. | Ataskaitų   rengimas | Diegėjas:   ·         Rengia SAULĖ IS modernizavimo eigos ataskaitą ne rečiau, kaip kas   ketvirtį;   ·         Rengia galutinę SAULĖ IS kūrimo ir diegimo ataskaitą (po bandomosios   eksploatacijos).       Perkančioji   organizacija:   ·         Pateikia pastabas ir rekomendacijas ataskaitoms. | Parengtos ataskaitos. Ataskaitose išdėstoma   (neapsiribojant):   ·         pasiekti rezultatai, vykdomos veiklos ir jų progresas SAULĖ IS kūrimo   grafiko atžvilgiu;   ·         rizikos, kritiniai faktoriai ir numatomi veiksmai, prognozės ir kitos   Projekto įgyvendinimui svarbios aplinkybės;   ·         SAULĖ IS kūrimo grafiko pakeitimai. |  


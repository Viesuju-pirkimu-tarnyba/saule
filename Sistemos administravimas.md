## 7.8.6	Reikalavimai Sistemos administravimui
### 7.8.6.1	Reikalavimai vidinio portalo institucijų tvarkymui
2328. VPT sistemos administratorius turi galėti sukurti vidinio portalo institucijos (Priežiūros institucijų, Įgyvendinančių institucijų) paskyrą.
2328.1. Turi būti galima įvesti institucijos duomenis (pavadinimą, kodą, institucijos tipą (priežiūros, įgyvendinanti) kontaktinius duomenis ir kitus detalios analizės ir projektavimo etape suderintus duomenis).
2328.2. Turi būti galima įvesti institucijos administratorių (asmens duomenis, kontaktinius duomenis, prisijungimo būdą ir kt.).
2328.3. Turi būti galima redaguoti institucijos duomenis, keisti ir pridėti institucijos administratorius.
2329. Turi būti galima deaktyvuoti instituciją. Deaktyvuotos institucijos naudotojai neturi galėti prisijungti prie institucijos srities.
2329.1. Turi būti galima nurodyti institucijos deaktyvavimo datą. Nurodytą datą institucija turi būti deaktyvuojama automatiškai.
2330. VPT sistemos administratorius turi galėti įvesti naudotoją (-us) deaktyvuotoje (likviduotoje) organizacijoje, suteikiant atitinkamas teises. Naudotojui turi būti suteikiama galimybė prisijungti prie organizacijos paskyros ir atlikti teisėmis suteiktas funkcijas (pateikti ataskaitas ar pan.).

### 7.8.6.2	Reikalavimai institucijų naudotojų tvarkymui 

2331. Institucijos administratorius (Priežiūros institucijų, Įgyvendinančių institucijų) turi galėti tvarkyti savo institucijos naudotojus.
2332. Institucijos administratorius turi galėti peržiūrėti institucijos naudotojų sąrašą. Sąrašą turi būti galima filtruoti ir atlikti paieškas pagal sąrašą prasmingai atitinkančius atributus.
2333. Turi būti galima deaktyvuoti naudotoją:
2334. Turi būti galima deaktyvuoti pasirinktą institucijos naudotoją. Turi būti galima nurodyti dieną (datą) nuo kurios naudotojas turi būti deaktyvuojamas.
2334.1. Turi būti galimybė automatiškai deaktyvuoti naudotoją, kai paskyra nenaudojama nustatytą laiko tarpą. Šį laiko tarpą nustato VPT sistemos administratorius. Apie artėjantį naudotojo paskyros deaktyvavimą turi būti informuojamas naudotojas.Deaktyvuotas naudotojas neturi galėti prisijungti prie institucijos srities.
2335. Turi būti galima redaguoti naudotojo duomenis:
2335.1. Turi būti galima redaguoti naudotojų duomenis (asmens duomenis, kontaktinius duomenis, roles,  prieigos prie pirkimų teises, prieigos prie projektų teises ir kt.).
2335.2. Naudotojo duomenų redagavimo forma ir jos tvarkymo funkcionalumas turi būti apibrėžtas detalios analizės ir projektavimo etape.
2335.3. Turi būti galima naudotojui priskirti/ atsieti naudotojo roles ir teises. Naudotojų rolės ir teisės turi būti apibrėžtos detalios analizės ir projektavimo etape.
2336. Turi būti galima registruoti naudotoją:
2336.1. Turi būti galima įvesti naudotojo duomenis (asmens duomenis, kontaktinius duomenis, roles, leidimus prieiti prie pirkimų, projektų ir kt.);
2336.2. Turi būti galima nurodyti naudotojo prisijungimo būdą:
2336.2.1. VIISP – privaloma įvesti tinkamą naudotojo asmens kodą, kad per VIISP identifikuotas naudotojas būtų susietas su organizacijos naudotojo paskyra;
2336.2.2. Naudotojo vardu ir slaptažodžiu. Detalios analizės ir projektavimo etape turi būti apibrėžtas saugus prisijungimo duomenų pateikimas naudotojui. Detalios analizės ir projektavimo etape turi būti nuspręsta ar šiam identifikavimosi būdui turi būti galimybė taikyti dviejų faktorių identifikavimo procesą (kaip portalo „Saulė“ naudotojams). 
2336.3. Turi būti galima nurodyti laikotarpį kada naudotojas yra aktyvus (gali prieiti prie institucijos srities). Suėjus terminui naudotojas turi būti automatiškai deaktyvuojamas.
2336.4. Naudotojas turi būti informuojamas apie suteiktas teises prieiti prie institucijos srities.
### 7.8.6.3	Reikalavimai VPT naudotojų tvarkymui
2337. VPT sistemos administratorius turi galėti tvarkyti vidinio portalo naudotojus (VPT naudotojus ir Institucijų naudotojus). Naudotojų administravimo funkcionalumas turi būti realizuotas tokia pat prasminga apimtimi kaip institucijų naudotojų tvarkymo funkcionalumas (žr. 7.8.6.2 skyrių) papildant funkcionalumą sąsaja su VPT „Active directory“ naudotojų katalogo integracija. Vidinio portalo VPT naudotojai turi būti susiejami ar periodiškai automatiškai importuojami (sinchronizuojami) iš „Active directory“ naudotojų katalogo. Naudotojai, kurie pašalinami iš „Active directory“ naudotojų katalogo ar jiems sustabdomos teisės prisijungti prie VPT išteklių, turi atitinkamai negalėti prieiti ir prie SAULĖ IS vidinio portalo.
7.8.6.4	Reikalavimai naudotojų pavadavimui
2338. VPT sistemos administratorius ir Institucijos administratorius turi galėti tvarkyti savo institucijos naudotojų pavadavimą:
2338.1. Turi būti galimybė naudotojui priskirti jį pavaduojantį kitą naudotoją. Pavadavimo priskyrimą turi galėti atlikti VPT sistemos administratorius, Institucijos administratorius ar kitas naudotojas, turintis atitinkamas institucijos pavadavimų tvarkymo teises.
2338.2. Naudotojui, kuriam priskiriama pavaduoti kitą naudotoją, turi būti suteikiamos priskirtojo naudotojo rolės ir teisės, t. y. jis turi įgyti visas pavaduojamojo naudotojo funkcijas bei prieigą prie duomenų. Pavaduojantysis, atlikęs identifikaciją vidiniame portale, turi galėti pasirinkti paskyrą: savo arba pavaduojamojo naudotojo. Norint pakeisti paskyrą neturi reikėti pakartotinai identifikuotis (prisijungti) vidiniame portale.
2338.3. Pavaduojančio naudotojo atliekami veiksmai už pavaduojamąjį naudotoją turi būti audituojami, kaip bet kurie kiti naudojo atliekami veiksmai. Audito įrašuose, kuriuose išsaugomi veiksmą atlikusio naudotojo duomenys, turi būti fiksuojama, kad veiksmą atliko pavaduojantysis naudotojas.
2338.4. Turi būti galimybė atšaukti pavadavimų priskyrimus. Pavadavimo priskyrimo atšaukimą gali įvykdyti pavaduojamas naudotojas, administratorius ar kitas naudotojas turintis atitinkamas pavadavimų tvarkymo teises.
2338.5. Pavadavimas turi būti automatiškai atšaukiamas suėjus nurodytam pavadavimo terminui.
Jeigu detalios analizės ir projektavimo etape bus identifikuotas poreikis tvirtinti pavadavimus (pavyzdžiui, institucijos vadovui), turės būti detalizuotas ir realizuotas tokio proceso funkcionalumas.
### 7.8.6.5	Reikalavimai rolių valdymui
2339. VPT sistemos administratorius ir institucijos administratorius turi galėti:
2339.1. Sudaryti institucijos naudotojų roles (teisių grupes) – rolėms priskirti teises, suteikti rolėms pavadinimus. Naudotojų teisės turi būti statiškos be galimybės jas keisti administravimo priemonėmis.
2339.2. Peržiūrėti ir tvarkyti (redaguoti, šalinti) rolių ir teisių sąrašą.
2339.3. Sudarytas roles ir pavienes teises priskirti institucijos naudotojams (naudotojų valdymo modulyje).
2340. Diegėjas turi pateikti visų rolių ir teisių aprašymus. Teisių ir rolių aprašymai  turi būti pateikiami ir rolių administravimo modulyje.
2341. Pradines vidinio portalo naudotojų roles ir teises turi sudaryti Diegėjas.
2342. VPT sistemos administratorius turi galėti sudaryti ir tvarkyti portalo „Saulė“ roles ir jas publikuoti į portalą „Saulė“. Publikuotas roles turi galėti naudoti portalo „Saulė“ organizacijų administratoriai.
### 7.8.6.6	Reikalavimai problemų registravimo klausimyno tvarkymui
2343. Turi būti galima sudaryti ir tvarkyti klausimyną, kuris būtų pateikiamas naudotojui iniciavus problemos registravimą (žr. 7.6.13.1 skyrių).
2344. Pagalbos posistemės administratoriui turi būti galima sudaryti klausimyną (klausimais ir atsakymais pagrįstą vedlio funkcionalumą), kuris turi padėti naudotojui inicijavus problemos registravimo  funkciją identifikuoti su kokio tipo problema jis susidūrė, pateikti su naudotojo pasirinkta problema susietą DUK srities (kur tvarkoma „ZenDesk“ programiniame įrankyje) informaciją arba bendrą informaciją, o neradus reikiamo atsakymo nuvesti iki problemos registravimo formos.
2345. Klausimyno sudarymo funkcionalumas turi remtis 7.8.6.7 skyriuje aprašytu funkcionalumu.
### 7.8.6.7	Reikalavimai el. vedlio sukūrimui ir įdiegimui
2346. Turi būti realizuotas el. vedlio sukūrimo ir publikavimo (įdiegimo) komponentas, kuris sudarytų galimybę sukurti (be programavimo darbų) ir į norimas SAULĖ IS aplikacijų (kurios paremtos tinklinėmis (angl. web) technologijomis) vietas įdiegti klausimais ir atsakymais pagrįstą komponentą. Komponentas gali būti realizuojamas kaip savarankiškas SAULĖ IS komponentas arba kaip TVS funkcionalumas.
2347. Reikalavimai el. vedlio dialogo (klausimyno) funkcionalumui:
2347.1. Įdiegtas el. vedlio dialogo funkcionalumas turi padėti naudotojui suprasti kokius veiksmus jam reikia atlikti, kaip naudotis tam tikromis SAULĖ IS funkcijomis, kokius dokumentus ar duomenis reikia pateikti ir pan.
2347.2. El. vedlio dialogas turi pateikti naudotojui klausimus ir klausimą atitinkančius atsakymo pasirinkimus. Pasirinkto atsakymo rezultatas:
2347.2.1. Kitas klausimas su atsakymų variantais;
2347.2.2. Pateikta informacija (aiškinamasis tekstas, nuorodos (URL) ar pan.);
2347.2.3. Nukreipimas (angl. redirect) į SAULĖ IS funkciją (modulį ar pan.).
2347.3. El. vedlio dialogas turi galėti išsaugoti naudotojo pasirinkimus (atsakymus) ir leisti tuos duomenis panaudoti kitose formose (pavyzdžiui, užpildant prašymo formą, duomenų paieškos forma ir pan.).
2347.4. Einant el. vedlio žingsniais nuolat turi būti atvaizduojamas klausimų-atsakymų progresas. Jeigu yra galimybė – turi būti rodoma, kiek dar klausimų reikės atsakyti.
2347.5. Diegėjas, naudodamas el. vedlio sukūrimo ir įdiegimo funkcionalumą, turės realizuoti detalios analizės ir projektavimo etape identifikuotus klausimynus ir juos įdiegti į suderintas SAULĖ IS vietas.
2348. Reikalavimai el. vedlio įdiegimui:
2348.1. Turi būti galima el. vedlio dialogą, kuris eksportuojamas iš el. vedlio kūrimo įrankio, įdiegti norimose IS naudotojo sąsajos vietose: formose, kontekstinėje pagalboje ir pan.
2348.2. Įdiegtas el. vedlio dialogas (programinis kodas (HTML, Java Script ir kt.)) turi užtikrinti, kad el. vedlys be papildomo programavimo reikiamoje vietoje pateiks klausimų-atsakymų seką, kuri sudaryta el. vedlio dialogo kūrimo įrankyje.
2348.3. Turi būti galima prieš diegiant el. vedlio dialogą keisti el. vedlio dialogo išeities tekstą (programinį kodą) realizuojant sudėtingesnius el. vedlio scenarijus:
2348.3.1. El. vedlio dialoge esantiems duomenų įvedimo elementams realizuoti įvestų duomenų (pasirinkimų) išsaugojimą duomenų bazėje ar laikinojoje atmintyje, kad įvesti duomenys būtų panaudojami užpildant el. paslaugų formas ar pan.
2348.3.2. El. vedlio dialoge pateikti IS duomenis iš duomenų bazės.
2348.4. Turi būti galima el. vedlio dialogui pritaikyti IS stilius (angl. Cascading Style Sheets).
2348.5. El. vedlio dialogo įdiegimui turi būti naudojama turinio valdymo sistema ar kitas komponentas, kuris turi leisti įdiegti/ išdiegti el. vedlio dialogus į norimas SAULĖ IS vietas.
2349. Reikalavimai el. vedlio dialogo sukūrimui:
2349.1. El. vedlio dialogo sukūrimui turi būti naudojamas el. vedlio kūrimo įrankis (programinė įranga).
2349.2. Prieiga prie el. vedlio kūrimo įrankio turi būti leidžiama tik autorizuotiems naudotojams.
2349.3. Turi būti galima peržiūrėti sukurtų el. vedlio dialogų sąrašą.
2349.3.1. Turi būti galima filtruoti sąrašą pagal sąrašą atitinkančius kriterijus.
2349.3.2. Turi būti galima iš sąrašo atverti el. vedlio dialogą peržiūros (testavimo) režimu.
2349.3.3. Turi būti galima iš sąrašo el. vedlio dialogą atverti redagavimo (kūrimo) režimu.
2349.3.4. Turi būti galima iš sąrašo ištrinti el. vedlio dialogą.
2349.3.5. Turi būti galima iš sąrašo kopijuoti el. vedlio dialogus.
2349.4. Kuriant el. vedlio dialogą:
2349.4.1. Turi būti galima sukurti el. vedlio dialogą ir jį išsaugoti. Turi būti galima suteikti kiekvienam el. vedliui pavadinimą. Išsaugant el. vedlį turi būti automatiškai išsaugomi metaduomenys: vedlio sukūrimo data, kas sukūrė ir kitus laukus suderintus detalios analizės ir projektavimo metu
2349.4.2. Turi būti galima sukurti el. vedlį sudarytą iš kelių išsaugotų el. vedlių.
2349.4.3. Turi būti galima kuriant el. vedlį sudaryti klausimus ir jų atsakymų variantus.
2349.4.4. Atsakymų variantams priskirti atsakymo pasirinkimo veiksmą:
2349.4.4.1. Pateikti kitą klausimą;
2349.4.4.2. Nukreipti į URL (teisės aktą ir pan.); 
2349.4.4.3. Nukreipti į SAULĖ IS funkcionalumą, modulį ar pan.;
2349.4.4.4. Pateikti informaciją (tekstą ar pan.);
2349.4.4.5. Turi būti galima nurodyti, kad į kitą konkretų klausimą pereinama nepriklausomai nuo pasirinkto atsakymo varianto, t. y. atsakymų variantai gali būti skirti tik informacijos surinkimui, o paspaudus mygtuką „kitas klausimas“ pareiti į kitą el. vedlio dialogo klausimą.
2349.4.5. Turi būti galima nurodyti atsakymo pateikimo formą:
2349.4.5.1. laisvai įvedamo teksto laukas;
2349.4.5.2. sąrašo (klasifikatoriaus) tipo laukas. Turi būti galima sudaryti ar importuoti klasifikatoriaus reikšmes;
2349.4.5.3. akutės tipo (angl. radio box);
2349.4.5.4. žymimojo langelio (angl. check box);
2349.4.5.5. datos parinkimo.
2349.5. Turi būti galima sudarytą el. vedlio dialogą eksportuoti į diegimui į SAULĖ IS tinkamą formatą (HTML, javascript, XML ar pan.). Eksportuotą el. vedlio dialogą turi būti galima įdiegti į web technologijomis paremtą aplikaciją. Detalios analizės ir projektavimo etape turi būti suderintas tikslus eksportuojamo el. vedlio dialogo formatas.
### 7.8.6.8	Reikalavimai klasifikatorių tvarkymui
2350. Turi būti sukurtos funkcijos leidžiančios tvarkyti SAULĖ IS (išorinio ir vidinio portalo) klasifikatorius: 
2350.1. redaguoti esamų klasifikatorius reikšmes;
2350.2. įvesti naujas esamų klasifikatorių reikšmes;
2350.3. šalinti (padaryti nenaudojamais) esamas klasifikatoriaus reikšmes;
2350.4. Diegėjas turi įvesti (importuoti, sukurti ar pan.) visus klasifikatorius, kurie bus identifikuoti detalios analizės ir projektavimo etape;
2350.5. Turi būti galima klasifikatoriaus reikšmes įvesti skirtingomis kalbomis.
### 7.8.6.9	Reikalavimai sisteminių parametrų administravimui
2351. Turi būti galima keisti sisteminius parametrus (nustatytus terminus, skaitines reikšmes, adresus (URL), domenus ir kt.). Detali administruojamų parametrų imtis turi būti nustatyta detalios analizės ir projektavimo etape.

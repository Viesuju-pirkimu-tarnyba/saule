## 7.6.3	Reikalavimai Pirkimų skelbimų posistemei
7### .6.3.1	Bendrieji reikalavimai Pirkimų skelbimų posistemei

951. Pirkimų skelbimų posistemėje turi būti realizuotas tokių skelbimų paskelbimo funkcionalumas:
951.1. Išankstinis informacinis skelbimas (arba, kai vykdomas komunalinio sektoriaus pirkimas – Reguliarus orientacinis skelbimas). Šio tipo skelbimas gali būti skelbiamas tokiais tikslais:
951.1.1. Iš anksto informuoti (žr. Reikalavimai proceso „BP2. Paskelbti išankstinį skelbimą (informacija)“ realizavimui);
951.1.2. Sutrumpinti pasiūlymų priėmimo laikotarpį (žr. Reikalavimai proceso „BP3. Paskelbti išankstinį skelbimą (terminai)“ realizavimui);
951.1.3. Pakviesti dalyvauti konkurse (žr. Reikalavimai proceso „BP4. Paskelbti išankstinį skelbimą (kvietimas)“ realizavimui).
951.2. Skelbimas apie pirkimą, Skelbimas apie projekto konkursą arba Koncesijos skelbimas (priklausomai nuo pasirinkto pirkimo būdo), (žr. Reikalavimai proceso „BP8. Paskelbti skelbimą apie pirkimą (projekto konkursą)“ realizavimui);
951.3. Skelbimas dėl klaidų ištaisymo, siekiant paskelbti mažus pakeitimus, esančius jau publikuotuose skelbimuose. Jeigu yra vykdomas supaprastintas ar tarptautinės vertės skelbiamas pirkimas ir, atlikus pirkimo dokumentų pakeitimus, keičiama informacija, esanti jau paskelbtame skelbime, turi būti pildomos šios formos: supaprastintiems pirkimams Skelbimas dėl pakeitimų ar papildomos informacijos (Sk-4 tipinė forma), tarptautinės vertės pirkimams Klaidų ištaisymas (T-14 standartinė forma).
951.4. Skelbimas apie pirkimo rezultatus, Skelbimas apie projekto konkurso rezultatus arba Skelbimas apie koncesijos suteikimą (priklausomai nuo pasirinkto pirkimo būdo), (žr. „Reikalavimai proceso „BP14. Paskelbti apie pirkimo (projekto konkurso) rezultatus“ realizavimui);
951.5. Savanoriško ex ante skaidrumo skelbimą (žr. Reikalavimai proceso „BP16. Paskelbti ex ante skelbimą“ realizavimui).
952. Pirkimų skelbimų struktūros turi atitikti eForms standarte, aprašomame 2019 m. rugsėjo 23 d. Komisijos įgyvendinimo reglamente (ES) 2019/1780, aprašytas struktūras ir duomenų objektus, nebent VPT išsakys poreikį tam tikrų duomenų kaupimo SAULĖ IS atsisakyti. 
952.1. Pildant skelbimą, SAULĖ IS jau esantys ir skelbimui aktualūs duomenys apie pirkimą turi būti užpildomi automatiškai.
952.2. Skelbimai turi būti versijuojami – siekiant pakoreguoti skelbimą pagal gautas VPT pastabas, turi būti kuriama ir teikiama nauja skelbimo versija.
952.3. Kuriant naują skelbimo versiją, ankstesnės versijos duomenys turi būti automatiškai perkeliami į naują versiją.
953. Paskelbti skelbimai turi būti matomi tiek bendrame SAULĖ IS skelbimų sąraše, tiek konkretaus PV profilyje.
954. Visais atvejais, kai yra taikomi terminai, VPT sistemos administratorius turi turėti galimybę terminus konfigūruoti.

### 7.6.3.2	Reikalavimai proceso „BP2. Paskelbti išankstinį skelbimą (informacija)“ realizavimui

955. Žemiau pateikiama bendra proceso „BP2. Paskelbti išankstinį skelbimą (informacija)“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89335669-00d10b00-d6a1-11ea-891d-b0423905ded1.png)

7.26 lentelė. Proceso „BP2. Paskelbti išankstinį skelbimą (informacija)“ realizavimo reikalavimai

Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Procesas turi būti   vykdomas, kai PV inicijuoja išankstino informacinio skelbimo (arba   reguliaraus orientacinio skelbimo) paskelbimą su tikslu iš anksto informuoti   teikėjus (toliau – išankstinis skelbimas (informacija)).
T1 | Parengti   išankstinį skelbimą | Pirkimą   atliekantys asmenys | 2. PV turi turėti galimybę   parengti išankstinį informacinį skelbimą užpildant skelbimo formą   reikalingais duomenimis.
T2 | Pateikti   skelbimą VPT | Pirkimą   atliekantys asmenys | 3. PV užpildytas ir   patvirtintas skelbimas turi būti perduodamas VPT tikrinimui.   4. Teikiant skelbimą turi būti   galimybė prisegti papildomą informaciją. PV turi turėti galimybę nurodyti, ar   papildoma informacija turi būti skelbiama viešai, ar yra skirta tik VPT.   5. Pateikus skelbimą VPT, jis   turi būti užrakinamas (nebegali būti koreguojamas).
BP5 | Paskelbti   skelbimą | VPT | 6. VPT turi turėti galimybę patikrinti   ir paskelbti išankstinį skelbimą SAULĖ IS ir, jei reikia, TED. Bendro proceso   detalizavimą žr. Reikalavimai proceso „BP5.   Paskelbti skelbimą“ realizavimui.
E2 | Srauto   pabaiga | - | -

### 7.6.3.3	Reikalavimai proceso „BP3. Paskelbti išankstinį skelbimą (terminai)“ realizavimui

962. Žemiau pateikiama bendra proceso „BP3. Paskelbti išankstinį skelbimą (terminai)“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89335748-19412580-d6a1-11ea-8943-09049962f00d.png)

7.27 lentelė. Proceso „BP3. Paskelbti išankstinį skelbimą (terminai)“ realizavimo reikalavimai

Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Procesas turi būti   vykdomas, kai PV inicijuoja išankstino informacinio skelbimo (arba   reguliaraus orientacinio skelbimo) paskelbimą su tikslu sutrumpinti pasiūlymų priėmimo laikotarpį (toliau – išankstinis   skelbimas (terminai)).
T1 | Parengti   išankstinį skelbimą | Pirkimą   atliekantys asmenys | 2. PV turi turėti galimybę   parengti išankstinį informacinį skelbimą užpildant skelbimo formą   reikalingais duomenimis.
T2 | Pateikti   skelbimą VPT | Pirkimą   atliekantys asmenys | 3. PV užpildytas ir   patvirtintas skelbimas turi būti perduodamas VPT tikrinimui.   4. Teikiant skelbimą turi būti   galimybė prisegti papildomą informaciją (pvz. teismo sprendimą), skirtą VPT.   Papildoma informacija neturi būti skelbiama viešai.
BP5 | Paskelbti   skelbimą | VPT | 5. VPT turi turėti galimybę patikrinti   ir paskelbti išankstinį skelbimą SAULĖ IS ir, jei reikia, TED. Bendro proceso   detalizavimą žr. Reikalavimai proceso „BP5.   Paskelbti skelbimą“ realizavimui.   6. SAULĖ IS paskelbtas   skelbimas turi galioti 12 mėn. nuo paskelbimo dienos. Praėjus šiam   terminui turi būti nebeleidžiama jo pagrindu sutrumpinti pasiūlymo priėmimo   terminų.
E2 | Srauto   pabaiga | - | -

### 7.6.3.4	Reikalavimai proceso „BP4. Paskelbti išankstinį skelbimą (kvietimas)“ realizavimui

969. Žemiau pateikiama bendra proceso „BP4. Paskelbti išankstinį skelbimą (kvietimas)“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89335808-2e1db900-d6a1-11ea-8125-c581dd2809c0.png)

7.28 lentelė. Proceso „BP4. Paskelbti išankstinį skelbimą (kvietimas)“ realizavimo reikalavimai

Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Procesas turi būti   vykdomas, kai PV inicijuoja išankstino informacinio skelbimo (arba   reguliaraus orientacinio skelbimo) paskelbimą su tikslu pakviesti dalyvauti konkurse (toliau – išankstinis   skelbimas (kvietimas)).   2. Kai paskelbiamas   išankstinis skelbimas (kvietimas), išankstinio skelbimo galiojimo metu   skelbimas apie pirkimą neturi būti skelbiamas.
T1 | Parengti   išankstinį skelbimą | Pirkimą   atliekantys asmenys | 3. PV turi turėti galimybę   parengti išankstinį informacinį skelbimą užpildant skelbimo formą   reikalingais duomenimis.
T2 | Pateikti   skelbimą VPT | Pirkimą   atliekantys asmenys | 4. PV užpildytas ir   patvirtintas skelbimas turi būti perduodamas VPT tikrinimui.   5. Teikiant skelbimą turi būti   galimybė prisegti papildomą informaciją (pvz. teismo sprendimą), skirtą VPT. Papildoma   informacija neturi būti skelbiama viešai.
BP5 | Paskelbti   skelbimą | VPT | 6. VPT turi turėti galimybę patikrinti   ir paskelbti išankstinį skelbimą SAULĖ IS ir, jei reikia, TED. Bendro proceso   detalizavimą žr. Reikalavimai proceso „BP5.   Paskelbti skelbimą“ realizavimui.   7. SAULĖ IS paskelbtas   skelbimas turi galioti 12 mėn. nuo paskelbimo dienos. Praėjus šiam   terminui turi būti nebeleidžiama jo pagrindu kviesti tiekėjų dalyvauti   konkurse – tokiu atveju turi būti inicijuojamas naujas pirkimo projektas arba   skelbiamas skelbimas apie pirkimą.   8. SAUĖ   IS turi priminti PV apie besibaigiantį skelbimo galiojimą likus mėnesiui iki   jo pabaigos.
T3 | Gauti   tiekėjų susidomėjimą | SAULĖ   IS | 9. Turi būti galimybė   tiekėjams išreikšti susidomėjimą pirkimu. Susidomėjimas išreiškiamas   paspaudžiant „Priimti kvietimą“ skelbimo peržiūros lange.   10. Susidomėjimą išreikšti turi   turėti galimybę tik prisijungę naudotojai.   11. SAULĖ IS turi būti   suformuojamas neviešas (matomas tik PV ir kontroliuojančioms institucijoms)   susidomėjimą išreiškusių tiekėjų sąrašas.
E2 | Srauto   pabaiga | - | -

### 7.6.3.5	Reikalavimai proceso „BP5. Paskelbti skelbimą“ realizavimui
981. Žemiau pateikiama bendra proceso „BP5. Paskelbti skelbimą“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.

![image](https://user-images.githubusercontent.com/61745726/89335869-44c41000-d6a1-11ea-8597-c105bc6d9f04.png)

7.29 lentelė. Proceso „BP5. Paskelbti skelbimą“ realizavimo reikalavimai

Proceso Nr. | Proceso pavadinimas | Proceso dalyvis | Reikalavimai realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Procesas turi būti   vykdomas, kai VPT iš PV gauna skelbimą paskelbimui SAULĖ IS (ir, jei reikia,   TED).   2. Gauti skelbimai turi būti   matomi visiems už tikrinimą atsakingiems specialistams. Iš gautų skelbimų   sąrašo specialistai turi turėti galimybę pasiimti skelbimus tikrinimui (konkretus   VPT specialistas paskiriamas kaip atsakingas). Turi būti galimybė esant   poreikiui pakeisti atsakingą asmenį.
T1 | Patikrinti   skelbimą | VPT | 3. Gavęs skelbimą, VPT   specialistas turi turėti galimybę per nustatytą tikrinimo terminą patikrinti   jo tinkamumą.   4. VPT specialistui turi būti   rodomas gautų skelbimų sąrašas.   5. Gautų skelbimų sąraše turi   būti paryškinami skelbimai, kurie turi būti patikrinti per mažiau, nei 1 d.d.   6. VPT specialistas turi   priimti skelbimo tikrinimo užduotį bei turi matyti, kurie skelbimai jau yra tikrinami   kito specialisto.   7. VPT specialistui patikrinus   skelbimą, jis turi pažymėti, ar skelbimas yra tinkamas, koreguotinas arba   sustabdomas.   8. Jei VPT specialistas per   nustatytą tikrinimo terminą skelbimo nepatikrina (t. y. nenurodo, kad   skelbimas yra tinkamas, koreguotinas arba sustabdomas), skelbimas turi būti   automatiškai perduodamas paskelbimui.   9. Sistemos administratoriui   turi būti sudaryta galimybė konfigūruoti tikrinimo terminą. Numatytoji   reikšmė:   9.1. Kai vykdoma koncesija – 5 d. d.;   9.2. Kai pirkimas tarptautinis – 3 d. d.;   9.3. Kai pirkimas supaprastintas – 3 d. d.;   9.4. Kai pirkimas mažos vertės – 0 d. d.   10. Turi būti užtikrintas   atsekamumas, kurie skelbimai buvo patikrinti, o kurie paskelbti automatiškai.   11. VPT turi turėti galimybę   peržiūrėti ankstesnes skelbimo versijas pokyčių palyginimui.
T2 | Pateikti   pastabas | VPT | 12. Jei VPT specialistas   nurodė, kad skelbimą reikia koreguoti, VPT specialistas turi įrašyti   pastabas.   13. VPT specialisto pastabos   turi būti pateikiamos PV.
E2 | Srauto   pabaiga | - | -
T3 | Sustabdyti   skelbimą | VPT | 14. Jei VPT specialistas   pažymėjo, kad skelbimas turi būti sustabdomas, skelbimas neturi būti   skelbiamas automatiškai praėjus numatytam terminui. Procesas toliau gali būti   tęsiamas tik VPT specialistui pasirinkus pateikti pastabas arba paskelbti   skelbimą.   15. Sustabdytas skelbimas VPT   tikrinamų skelbimų sąraše turi būti pažymimas kitaip, nei kiti skelbimai.
T4 | Priimti   sprendimą | VPT | 16. VPT specialistui turi būti   sudaryta galimybė pateikti sprendimą dėl sustabdyto skelbimo – pažymėti, ar   skelbimas yra tinkamas ar koreguotinas.
T5 | Išsiųsti   skelbimą į TED | SAULĖ   IS | 17. Kai pirkimas yra   tarptautinis, per TED eSentool API skelbimas iš SAULĖ IS turi būti   išsiunčiamas į TED.   18. Iš TED turi būti gaunamas   patvirtinimas, kad skelbimas gautas.
T6 | Tikrinti   skelbimo būseną TED | SAULĖ   IS | 19. Nustatytu laiku SAULĖ IS   turi tikrinti išsiųsto skelbimo duomenis tol, kol skelbimo būsena TED bus PASKELBTA   arba NEPASKELBTA.   20. Tikrinimo laikas turi būti   konfigūruojamas VPT sistemos administratoriaus. Numatytoji reikšmė –   kiekvieną dieną 12:15.
T7 | Informuoti   apie skelbimo atmetimą | SAULĖ   IS | 21. Jei skelbimas TED buvo   atmestas (būsena NEPASKELBTA), SAULĖ IS turi informuoti sistemos   administratorių bei PV, kurios skelbimas nebuvo paskelbtas, apie TED atmestą   skelbimą.
E3 | Srauto   pabaiga | - | -
T8 | Paskelbti   skelbimą SAULĖ IS | SAULĖ   IS | 22. Supaprastinto pirkimo   skelbimas SAULĖ IS turi būti skelbiamas iš karto po VPT patikrinimo.   23. Supaprastinto pirkimo   skelbimas SAULĖ IS turi būti skelbiamas po to, kai iš TED gaunamas patvirtinimas,   kad skelbimas paskelbtas TED.   24. Kai tarptautinis skelbimas   yra paskelbiamas TED, skelbimas gauna TED numerį, paskelbimo datą ir nuorodas   į skelbimus TED (pagal esamą API aprašymo versiją, skelbimas kiekviena iš   kalbų, kuriomis yra paskelbtas, gauna atskirą nuorodą). Šie duomenys turi   būti pateikiami ir SAULĖ IS skelbime.   25. TED   numeris ir paskelbimo data turi būti atvaizduojami skelbimų sąrašuose bei   pagal juos turi būti leidžiama atlikti paiešką SAULĖ IS.
E4 | Paskelbtas   skelbimas | SAULĖ   IS | -

### 7.6.3.6	Reikalavimai proceso „BP8. Paskelbti skelbimą apie pirkimą (projekto konkursą)“ realizavimui
1007. Žemiau pateikiama bendra proceso „BP8. Paskelbti skelbimą apie pirkimą (projekto konkursą)“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89335949-5f968480-d6a1-11ea-8c06-e842ecc956f4.png)

7.30 lentelė. Proceso „BP8. Paskelbti skelbimą apie pirkimą (projekto konkursą)“ realizavimo reikalavimai

Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Procesas turi būti   vykdomas, kai PV inicijuoja skelbimo apie pirkimą, skelbimo apie projekto   konkursą arba koncesijos skelbimą.
T1 | Parengti   skelbimą apie pirkimą (projekto konkursą) | Pirkimą   atliekantys asmenys | 2. PV turi turėti galimybę   parengti skelbimą apie pirkimą, skelbimą apie projekto konkursą arba   koncesijos skelbimą užpildant skelbimo formą reikalingais duomenimis.   3. Jei PV pirkimui taiko   pagreitintą procedūrą, skelbime apie pirkimą privalo nurodyti tokį   pasirinkimą pagrindžiančias priežastis.
T2 | Pateikti   skelbimą VPT | Pirkimą   atliekantys asmenys | 4. PV užpildytas ir   patvirtintas skelbimas turi būti perduodamas VPT tikrinimui.   5. Teikiant skelbimą turi būti   galimybė prisegti papildomą informaciją (pvz. teismo sprendimą), skirtą VPT.   Papildoma informacija neturi būti skelbiama viešai.
BP5 | Paskelbti   skelbimą | VPT | 6. VPT turi turėti galimybę patikrinti   ir paskelbti skelbimą SAULĖ IS ir, jei reikia, TED. Bendro proceso   detalizavimą žr. Reikalavimai proceso „BP5.   Paskelbti skelbimą“ realizavimui.
E2 | Srauto   pabaiga | - | -

### 7.6.3.7	Reikalavimai proceso „BP14. Paskelbti apie pirkimo (projekto konkurso) rezultatus“ realizavimui
1014. Žemiau pateikiama bendra proceso „BP14. Paskelbti apie pirkimo (projekto konkurso) rezultatus“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89336012-73da8180-d6a1-11ea-8ed3-974f4bbc384d.png)

7.31 lentelė. Proceso „BP14. Paskelbti apie pirkimo (projekto konkurso) rezultatus“ realizavimo reikalavimai

Proceso    Nr. | Proceso    pavadinimas | Proceso    dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Procesas turi būti   vykdomas, kai PV inicijuoja skelbimo apie pirkimo rezultatus, skelbimo apie projekto   konkurso rezultatus arba skelbimo apie koncesijos suteikimą skelbimą.
E2 | Baigėsi   ketvirtis | - | 2. Šioje vietoje procesas turi   būti pradedamas pasibaigus kiekvienam ketvirčiui, jei PV atliko socialinių ar   kitų specialiųjų paslaugų pirkimus, pirkimus pagal dinaminę pirkimų sistemą   arba preliminarią sutartį ir nutarė šiuos pirkimus sugrupuoti ir paskelbti   vieną skelbimą.
T1 | Parengti   skelbimą apie pirkimo rezultatus | Pirkimą   atliekantys asmenys | 3. PV turi turėti galimybę   parengti skelbimą apie pirkimo rezultatus, skelbimą apie projekto konkurso   rezultatus arba skelbimą apie koncesijos suteikimą, užpildant skelbimo formą   reikalingais duomenimis.   4. Skelbimai rengiami tik   tarptautinio pirkimo atveju, taip pat kai skelbiamos koncesijos (nepriklausomai   nuo vertės).   5. Jei skelbiamas sugrupuotas   skelbimas, skelbiama apie visus į sugrupuotą skelbimą įtrauktus ketvirčio   pirkimus.
T2 | Pateikti   skelbimą VPT | Pirkimą   atliekantys asmenys | 6. PV užpildytas ir   patvirtintas skelbimas turi būti perduodamas VPT tikrinimui.   7. Teikiant skelbimą turi būti   galimybė prisegti papildomą informaciją (pvz. teismo sprendimą), skirtą VPT.   Papildoma informacija neturi būti skelbiama viešai.   8. Jei PV nepateikia skelbimo   VPT per nustatytą terminą, SAULĖ IS turi siųsti PV priminimus apie pradelstą   terminą.   9. Turi būti sudaryta galimybė   sistemos administratoriui konfigūruoti skelbimo apie rezultatus pateikimo   terminus. Numatytosios termino reikšmės:   9.1. Klasikinio sektoriaus – 30 k. d. po sutarties   sudarymo (konkurso rezultatų patvirtinimo);   9.2. Komunalinio sektoriaus – 30 k. d. po sutarties   sudarymo (konkurso rezultatų patvirtinimo);   9.3. Gynybos sektoriaus – 48 k. d. po sutarties   sudarymo (konkurso rezultatų patvirtinimo);   9.4. Koncesijų – 48 k. d. po sutarties sudarymo   (konkurso rezultatų patvirtinimo);   9.5. Kai skelbimai grupuojami – 30 k. d. pasibaigus   ketvirčiui.
BP5 | Paskelbti   skelbimą | VPT | 10. VPT turi turėti galimybę patikrinti   ir paskelbti skelbimą SAULĖ IS ir, jei reikia, TED. Bendro proceso   detalizavimą žr. Reikalavimai proceso „BP5. Paskelbti skelbimą“   realizavimui.
T3 | Įtraukti   į ketvirčio skelbimą | Pirkimą   atliekantys asmenys | 11. Jei PV nutaria, kad grupuos   socialinių ar kitų specialiųjų paslaugų pirkimų skelbimus, informacija apie   atliktą pirkimą turi būti įtraukiama į sugrupuotą ketvirčio skelbimą.
T4 | Suformuoti   ataskaitą | SAULĖ   IS | 12. Pasibaigus pirkimui pagal   turimus duomenis turi būti automatiškai sugeneruojama ataskaita.   13. Ataskaitos turi būti   rengiamos pagal formą Atn-1, išskyrus tuos atvejus, kai pirkimas vykdomas   asinchroniniu būdu (pirkimo dalys nagrinėjamos skirtingu metu). Asinchroninio   pirkimo atveju pirmai daliai (dalių grupei) pasibaigus turi būti skelbiama   ataskaita Atn-1, visoms kitoms dalims pasibaigus kiekvieną kartą turi būti   parengiamos jau paskelbtą Atn-1 ataskaitą papildančios Atn-2 ataskaitos.
T5 | Patikslinti   ataskaitą | Pirkimą   atliekantys asmenys | 14. PV turi turėti galimybę   patikslinti automatiškai sugeneruotą ataskaitą.
T6 | Paskelbti   ataskaitą | SAULĖ   IS | 15. PV turi turėti galimybę patikrintą   automatiškai sugeneruotą ataskaitą paskelbti.   16. Ataskaita turi būti   paskelbta ne vėliau, nei per 15 k. d. (koncesijos atveju – per   5 k. d.) po automatinio ataskaitos sugeneravimo. Jei per šį laiką   PV nepatikslina ataskaitos, ji turi būti paskelbiama automatiškai.    17. Ataskaitos paskelbimo terminai   turi būti konfigūruojami VPT sistemos administratoriaus.   18. Paskelbta ataskaita turi   būti prieinama viešai.
E3 | Srauto   pabaiga | - | -

### 7.6.3.8	Reikalavimai proceso „BP16. Paskelbti ex ante skelbimą“ realizavimui
1033. Žemiau pateikiama bendra proceso „BP16. Paskelbti ex ante skelbimą“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89336095-894fab80-d6a1-11ea-9e4b-77fb509387a9.png)

7.32 lentelė. Proceso „BP16. Paskelbti ex ante skelbimą“ realizavimo reikalavimai

Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Procesas turi būti   vykdomas, kai PV inicijuoja savanoriško ex ante skaidrumo skelbimo   paskelbimą.
T1 | Parengti   skelbimą apie pirkimą (projekto konkursą) | Pirkimą   atliekantys asmenys | 2. PV turi turėti galimybę   parengti savanoriško ex ante skaidrumo skelbimą užpildant skelbimo   formą reikalingais duomenimis.
T2 | Pateikti   skelbimą VPT | Pirkimą   atliekantys asmenys | 3. PV užpildytas ir   patvirtintas skelbimas turi būti perduodamas VPT tikrinimui.   4. Teikiant skelbimą turi būti   galimybė prisegti papildomą informaciją (pvz. teismo sprendimą), skirtą VPT.   Papildoma informacija neturi būti skelbiama viešai.
BP5 | Paskelbti   skelbimą | VPT | 5. VPT turi turėti galimybę patikrinti   ir paskelbti skelbimą SAULĖ IS ir, jei reikia, TED. Bendro proceso   detalizavimą žr. Reikalavimai proceso „BP5.   Paskelbti skelbimą“ realizavimui.
E2 | Srauto   pabaiga | - | -


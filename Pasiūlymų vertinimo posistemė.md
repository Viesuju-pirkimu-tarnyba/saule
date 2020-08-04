## 7.6.5	Reikalavimai Pasiūlymų vertinimo posistemei
### 7.6.5.1	Reikalavimai proceso „BP9. Atrinkti tiekėjus“ realizavimui

1133. Žemiau pateikiama bendra proceso „BP9. Atrinkti tiekėjus“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89336668-6bcf1180-d6a2-11ea-92a0-12ac21ac81c7.png)

7.35 lentelė. Proceso „BP9. Atrinkti tiekėjus“ realizavimo reikalavimai

Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | -
T1 | Gauti   paraiškas | SAULĖ   IS | 1. Turi būti sudaryta galimybė   tiekėjams patvirtinti susidomėjimą dalyvauti pirkime pateikiant paraišką.   2. SAULĖ IS turi išsaugoti   tiekėjų pateikiamas paraiškas.
T2 | Patikrinti   tiekėjo atitikimą reikalavimams | Pirkimą   atliekantys asmenys | 3. Pasibaigus paraiškų teikimo   terminui, PV turi turėti galimybę patikrinti tiekėjų, kurie pateikė paraiškas   dalyvauti konkurse, atitikimą reikalavimams.   4. Tikrindamas reikalavimus   tiekėjams PV prie kiekvieno reikalavimo turi turėti galimybę pažymėti, ar   tiekėjas juos atitinka. Patikrinęs tiekėjo atitikimą reikalavimams, PV turi   turėti galimybę pažymėti, ar konkrečiam tiekėjus bus leidžiama dalyvauti   konkurse.    5. PV turi užtikrinti, kad   konkurse būtų leidžiama dalyvauti tik tiekėjams, atitinkantiems nustatytus   reikalavimus. PV pasirinkus leisti konkurse dalyvauti reikalavimų   neatitinkančiam tiekėjui, SAULĖ IS turi įspėti PV apie galimai neleistiną   veiksmą. Jei PV pasirenka tęsti veiksmą, šis sprendimas turi būti fiksuojamas   rizikos valdymo posistemėje.   6. Turi būti sudaryta galimybė   atmesti paraišką, jei ją pateikęs tiekėjas neatitinka nustatytų reikalavimų.   7. Jei PV neleidžia dalyvauti   konkurse tiekėjui, kuris atitinka visus tiekėjams keliamus reikalavimus (pvz.   vadovaudamasis kompetentingų tarnybų išvadomis), PV privalo nurodyti tiekėjo   atmetimo motyvus.
T3 | Atlikti   kvalifikacinę atranką | Pirkimą   atliekantys asmenys | 8. Jei pirkimo dokumentuose   buvo numatyta taikyti kvalifikacinę atranką, PV turi turėti galimybę iš   reikalavimus atitinkančių kandidatų pagal pirkimo dokumentuose numatytus   kriterijus atrinkti tiekėjus, kuriuos kvies teikti pasiūlymus.   9. VPT sistemos   administratoriui turi būti galimybė nustatyti, kuriems pirkimo būdams gali   būti taikoma kvalifikacinė atranka. Numatyta, kad kvalifikacinė atranka turi   būti taikoma vykdant pirkimą riboto konkurso, skelbiamų derybų, konkurencinio   dialogo, inovacijų partnerystės būdu ir vykdant koncesijos suteikimo procesą.   10. Atrinktų kandidatų skaičius   turi būti ne mažesnis, nei pirkimo dokumentuose PV numatytas mažiausias   kviečiamų kandidatų skaičius, ir, jei buvo numatytas didžiausias kandidatų   skaičius (neprivaloma riboti), ne didesnis už numatytą didžiausią kviečiamų   kandidatų skaičių.   11. VPT sistemos   administratoriui turi būti sudaryta galimybė nustatyti minimalų kviečiamų   kandidatų skaičių pagal pirkimo sektorių ir pirkimo būdą. Numatyta, kad   riboto konkurso atveju minimalus kviečiamų kandidatų skaičius yra 5,   skelbiamų derybų, konkurencinio dialogo ir inovacijų partnerystės atveju – 3,   koncesijos atveju – 3.   12. Mažiausią kviečiamų tiekėjų   skaičių numato PV pirkimo dokumentuose, tačiau jis negali būti mažesnis, nei   sistemos administratoriaus nustatytas minimalus skaičius.   13. Mažesnį skaičių tiekėjų,   nei buvo numatyta, PV turi būti leidžiama kviesti tuo atveju, jei paraiškas   pateikė mažiau reikalavimus atitinkančių tiekėjų. Tuomet turi būti kviečiami   visi reikalavimus atitinkantys tiekėjai.   14. SAULĖ IS turi pasiūlyti   atrinkti geriausius įvertinimus gavusius tiekėjus. PV turi būti leidžiama   pakeisti atrinktus tiekėjus, tačiau tokiu atveju privalo nurodyti tokio   pasirinkimo motyvus.
T4 | Pakviesti   teikti pasiūlymą | Pirkimą   atliekantys asmenys | 15. PV turi būti sudaryta   galimybė vienu metu pakviesti pateikti pasiūlymus visus tiekėjams keliamus   reikalavimus atitinkančius tiekėjus, arba, jei buvo taikoma kvalifikacinė   atranka, visus atrinktus tiekėjus.   16. Tiekėjams kvietimas turi   būti pateikiamas naudojant SAULĖ IS komunikavimo priemones.   17. Jei nebuvo paskelbti visi   pirkimo dokumentai, turi būti galimybė juos pridėti prie kvietimo.   18. PV pakvietus tiekėją teikti   pasiūlymus tiekėjams turi aktyvuotis galimybė pateikti pasiūlymus.
E2 | Srauto   pabaiga | - | -

### 7.6.5.2	Reikalavimai proceso „BP11. Įvertinti pasiūlymus“ realizavimui
1152. Žemiau pateikiama bendra proceso „BP11. Įvertinti pasiūlymus“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.
![image](https://user-images.githubusercontent.com/61745726/89336817-a769db80-d6a2-11ea-9ecf-6aab3f305d7c.png)

7.36 lentelė. Proceso „BP11. Įvertinti pasiūlymus“ realizavimo reikalavimai


Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Proceso   pradžia | - | 1. Prieš pradedant procesą   SAULĖ IS turi būti sukurtas komisijos posėdis ir inicijuota komisijos   susipažinimo su pasiūlymais pradžia „Komisijos susipažinimo su pasiūlymais ar   paraiškomis procedūra“. Komisijos posėdžio sukūrimo ir pasirengimo posėdžiui   funkcionalumas aprašytas 7.6.6 Reikalavimai PK posėdžių planavimo ir organizavimo   posistemei.
T1 | Susipažinti   su formaliais pasiūlymo reikalavimais | Pirkimą   atliekantys asmenys | 2. Komisijos nariams (arba   Organizatoriui) turi būti sudaryta galimybė susipažinti su formaliais   pasiūlymo reikalavimais – patikrinti, ar pasiūlymai pateikti tinkama forma,   patikrinti EBVPD ir kitus pirkimo dokumentuose nurodytus reikalavimus   pasiūlymo pateikimui (atidaro pasiūlymus peržiūrai SAULĖ IS).   3. SAULĖ IS turi automatiškai   patikrinti, ar tiekėjai nėra įtraukti į nepatikimų tiekėjų sąrašus.   4. Jei tiekėjas yra įtrauktas   į nepatikimų tiekėjų sąrašus, SAULĖ IS turi apie tai informuoti komisijos   narius (arba Organizatorių).   5. Susipažinti su pasiūlymais   turi būti leidžiama tik pasibaigus pasiūlymų teikimo terminui.   6. Turi būti fiksuojamas   laikas, kada pirkimą atliekantis asmuo pirmą kartą atidarė pasiūlymą   peržiūrai.   7. SAULĖ IS turi įvertinti   pasiūlymo dalis, kurios yra pateikiamos struktūrine forma ir gali būti   vertinamos sistemiškai, ir apie neatitikimus ar galimus neatitikimus turi   indikuoti pasiūlymą vertinančius SAULĖ IS naudotojui.
T2 | Susipažinti   su pasiūlymu | Pirkimą   atliekantys asmenys | 8. Kai pasiūlymas teikiamas   viename voke, pirkimo Komisijos nariams (arba Organizatoriui) turi būti   sudaryta galimybė susipažinti su pateiktais pasiūlymais (atidaryti pasiūlymo   turinį peržiūrai SAULĖ IS).
T3 | Susipažinti   su pasiūlymo techniniais duomenimis | Pirkimą   atliekantys asmenys | 9. Kai pasiūlymai teikiami   dviejuose vokuose, pirkimo Komisijos nariams (arba Organizatoriui) turi būti   sudaryta galimybė susipažinti su pateiktų pasiūlymų technine dalimi   (atidaryti pasiūlymų techninę dalį peržiūrai SAULĖ IS).
T4 | Įvertinti   pasiūlymo techninę dalį | Pirkimą   atliekantys asmenys | 10. Pirkimo komisijos nariai   posėdžio metu įvertina pasiūlymų techninę dalį. Po posėdžio komisijos   pirmininkas (ar kitas komisijos narys) turi turėti galimybę įkelti posėdžio   protokolą bei įrašo pasiūlymų techninės dalies įvertinimus į sistemą.
E2 | Susipažinimo   su pasiūlymų kaina ar sąnaudomis diena | - | 11. Procesas toliau turi būti   vykdomas, kai ateina nustatyta susipažinimo su pasiūlymų kaina arba   sąnaudomis diena.   12. Susipažinti su kaina /   sąnaudomis turi būti leidžiama tik po to, kai sistemoje įrašomi techninės   dalies įvertinimai.   13. PV turi užtikrinti, kad   susipažinimas su pasiūlymų kaina / sąnaudomis vyks praėjus VPT sistemos   administratoriaus nustatytam laikui po pranešimo apie techninius balus   išsiuntimo dienos. Jei PV bando inicijuoti susipažinimą su pasiūlymų kaina /   sąnaudomis anksčiau, nei sueina nustatytas terminas, SAULĖ IS turi informuoti   PV apie galimai neleistiną veiksmą. Jei po įspėjimo PV nusprendžia nepaisyti   termino, informacija apie galimai neleistinus veiksmus turi būti fiksuojama   rizikos valdymo posistemėje.
T5 | Susipažinti   su pasiūlymo kaina arba sąnaudomis | Pirkimą   atliekantys asmenys | 14. Komisijos nariams (arba   Organizatoriui) turi būti sudaryta galimybė susipažinti su visų neatmestų pasiūlymų   kainomis arba sąnaudomis.   15. Sistema turi pažymėti   pasiūlymą, kurio kaina yra neįprastai maža. Šalia taip pat turi atsirasti   nuoroda į Komunikacijos posistemę iš kurios būtų siunčiamas pranešimas dėl   neįprastai mažos kainos pagrindimo.   16. Neįprastai mažos kainos   nustatymo taisyklė turi būti konfigūruojama administratoriaus. Numatyta   taisyklė: pasiūlymo kaina (sąnaudos) yra 30 ir daugiau proc. mažesnė už kitų   neatmestų pasiūlymų kainų (sąnaudų) aritmetinį vidurkį.
T6 | Įvertinti   pasiūlymą | Pirkimą   atliekantys asmenys | 17. Komisijos nariai posėdžio   metu sutaria dėl kiekvieno pasiūlymo galutinio įvertinimo (jei pasiūlymas   vertinamas pagal kelis parametrus, komisija paskaičiuoja atitinkamus   parametrų santykius). Po posėdžio komisijos pirmininkui (ar kitam komisijos   nariui) turi būti sudaryta galimybė įkelti posėdžio protokolą bei įrašyti   pasiūlymų įvertinimus į sistemą.   18. Sistemoje turi būti   sukurtos skaičiuoklės, skirtos paskaičiuoti įvertinimus (kai vertinami keli   parametrai) pagal dažniausiai naudojamas formules. Skaičiuoklės turi būti   traktuojamos kaip pagalbinė priemonė, pasiūlanti galimą rezultatą – PV gali   įrašyti kitokį rezultatą, nei siūlo skaičiuoklė. Įrašant kitokį rezultatą   turi būti nurodomi tokio pasirinkimo motyvai.
T7 | Suformuoti   pasiūlymų eilę | Pirkimą   atliekantys asmenys | 19. Įvertinus pasiūlymus,   pasiūlymai turi būti surikiuojami į eilę pagal įvertinimą (nuo aukščiausio   iki žemiausio).   20. SAULĖ IS pagal turimus   duomenis (įvestus įvertinimus) turi surikiuoti pasiūlymus automatiškai.   21. Komisijos pirmininkui turi   būti sudaryta galimybė eilę keisti. Pakeitimai turi būti fiksuojami sistemoje   – turi būti matoma iš ko į ką buvo pakeista. Atliekant pakeitimus turi būti   nurodomi tokio pasirinkimo motyvai.
T8 | Nustatyti   laimėtoją | Pirkimą   atliekantys asmenys | 22. PV turi turėti galimybę   SAULĖ IS pažymėti nustatytą laimėtoją (arba pirkimo dalių laimėtojus).   23. Laimėtojas neturi būti   nustatomas, jei pirkimas tęsiamas taikant elektroninį aukcioną arba derybas.
E3 | Subproceso   pabaiga | - | -
EP1. Prašyti patikslinimo   / pagrindimo
E4 | Pateikti   neaiškūs duomenys / pasiūlyta neįprastai maža kaina | Pirkimo   komisijos pirmininkas | 24. PV turi turėti galimybę   inicijuoti procesą, kai nori pasitikslinti neaiškias pasiūlymo dalis, arba   kai tiekėjas pasiūlė neįprastai mažą kainą.   25. Sistema neriboja proceso   inicijavimo – jis gali būti inicijuojamas bet kuriuo metu, kai pirkimo komisija   mato poreikį kontaktui su tiekėju.
KP1 | Prašyti   patikslinimo | Pirkimo   komisijos pirmininkas | 26. PV kreipiasi į tiekėją su   klausimais. Detaliau žr.Komunikacijos posistemėje.
E5 | Subproceso   pabaiga | - | -

### 7.6.5.3	Reikalavimai proceso „PT2: Duomenų ir informacijos teikimas (iš Tiekėjo pusės) pateiktų paraiškų ir pasiūlymų vertinimo metu, paraiškų ir pasiūlymų tikslinimas“ realizavimui

1179. Žemiau pateikiama bendra proceso „PT2: Duomenų ir informacijos teikimas (iš Tiekėjo pusės) pateiktų paraiškų ir pasiūlymų vertinimo metu, paraiškų ir pasiūlymų tikslinimas“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.

![image](https://user-images.githubusercontent.com/61745726/89336896-c49eaa00-d6a2-11ea-915e-7b389384bd44.png)
7.37 lentelė. Proceso „PT2: Duomenų ir informacijos teikimas (iš Tiekėjo pusės) pateiktų paraiškų ir pasiūlymų vertinimo metu, paraiškų ir pasiūlymų tikslinimas“ realizavimo reikalavimai


Proceso Nr. | Proceso    pavadinimas | Proceso dalyvis | Reikalavimai    realizavimui |  
-- | -- | -- | -- | --
E1 | Proceso   pradžia | - | - |  
E2 | Gautas   PV pranešimas dėl EBVPD | Tiekėjas | 1. Tiekėjas   turi gauti PV pranešimą apie atlikto EBVPD vertinimo rezultatus.   2. |  
T1 | Tikslinti   EBVPD | Tiekėjas | 3. Jeigu   PV nustato, kad EBVPD užpildytas netinkamai, PV turi turėti galimybė pateikti   prašymą Tiekėjui patikslinti jo pateiktą EBVPD.   4. EBVPD   atskirai pasirašyti nereikia. |  
T2 | Išsaugoti   patikslinto EBPVD duomenis | SAULĖ   IS | 5. SAULĖ   IS turi būti išsaugomi patikslinto EBVPD duomenys. |  
  | EBVPD   informacija ir duomenys | SAULĖ   IS | 6. SAULĖ   IS turi būti kaupiama EBVPD informacija ir duomenys. |  
E3 | Gautas   PV pranešimas dėl techninių duomenų įvertinimo | Tiekėjas | 7. Tiekėjas   turi gauti PV pranešimą dėl pasiūlymo arba paraiškos techninių duomenų   įvertinimo.   8. Tuo   pačiu pranešimu PV turi galėti informuoti Tiekėją apie vokų su kainomis   atidarymo datą ir laiką. |  
E4 | Gautas   PV pranešimas dėl vokų su kainomis | Tiekėjas | 9. Tiekėjas   turi gauti PV pranešimą dėl vokų su kainomis   atidarymo rezultatus, galutinius visų pasiūlymus ar paraiškas pateikusių   tiekėjų vertinimo balus, nenurodant konkrečių tiekėjų pavadinimų. |  
E5 | Gautas   PV pranešimas dėl laimėtojo nustatymo | Tiekėjas | 10. Tiekėjas   turi gauti PV pranešimą dėl eilės   sudarymo ir laimėtojo nustatymo. |  
E6 | Proceso   pabaiga | - | - |  
E7 | Gautas   PV pranešimas apie pirkimo procedūrų nutraukimą | Tiekėjas | 11. Bet   kuriuo metu iki pirkimo sutarties (preliminariosios sutarties) sudarymo ar   projekto konkurso* (*netaikoma gynybos pirkimų atveju) laimėtojo nustatymo PV   turi teisę savo iniciatyva nutraukti pradėtas pirkimo ar projekto konkurso   procedūras, jeigu atsirado aplinkybių, kurių nebuvo galima numatyti, ir   privalo tai padaryti, jeigu buvo pažeisti teisės aktuose nustatyti principai   ir atitinkamos padėties negalima ištaisyti.   12. Gali   būti nutraukiamas visas pirkimas arba jo dalis. Jei nutraukiama pirkimo dalis,   kitos dalys vykdomos toliau.   13. PV   sprendimas nutraukti pirkimą gali būti ginčijamas. Jei Tiekėjas mano, kad   pirkimo nutraukimas yra neteisėtas, jis turi turėti galimybę šį PV sprendimą   apskųsti teisės aktuose nustatytais terminais bei tvarka. Nukreipiama į SAULĖ   IS Komunikacijos posistemę. |  
E8 | Proceso   pabaiga | - | - |  
E9 | Gautas   kvietimas sudaryti sutartį / preliminarią sutartį | Tiekėjas | 14. Laimėtoju   pripažintas Tiekėjas gauna kvietimą sudaryti sutartį / preliminarią sutartį. |  
  | Sudaryti   sutartį / preliminarią sutartį | Tiekėjas,   Pirkimo vykdytojas | 15. Jeigu   netaikomas atidėjimo terminas, sudaroma sutartis / preliminari sutartis.   Nukreipiama į sutarčių / preliminarių sutarčių posistemę. |  
E10 | Baigėsi   atidėjimo terminas | - | 16. Jeigu   taikomas atidėjimo terminas, tuomet jam pasibaigus sudaroma sutartis /   preliminari sutartis. Nukreipiama į sutarčių / preliminarių sutarčių   posistemę. |  
E11 | Proceso   pabaiga | - | - |  
EP1.   Prašyti paaiškinti vertinimo rezultatus
E12 | Vertinimo   rezultatai kelia abejonių | - | - |  
KP1 | Prašyti   paaiškinti | Tiekėjas | 17. Tiekėjas   susipažinęs su vertinimo rezultatais, turi galėti pateikti prašymą PV   paaiškinti vertinimo rezultatus. Nukreipiama į SAULĖ IS Komunikacijos   posistemę. |  
E13 | Srauto   pabaiga |   | - |  
EP2.   Teikti pretenziją dėl vertinimo rezultatų |  
E14 | PV   nesilaiko teisės aktų reikalavimų | - | 18. Tiekėjas turi turėti galimybę apskųsti PV   sprendimus dėl vertinimo pasiūlymo kiekviename žingsnyje. |  
KP2 | Teikti   pretenziją | Tiekėjas | 19. Jeigu   Tiekėjas mano, kad PV netinkamai įvertino jo pasiūlymą / paraišką ar pažeidė   jo teisėtus interesus, tuomet Tiekėjas, per PV nustatytą / pirkimo sąlygose   nurodytą terminą, turi galėti apskųsti vertinimo rezultatus. Nukreipiama į   SAULĖ IS Komunikacijos posistemę.   20. Jeigu   PV išnagrinėjusi gautą prašymą / pretenziją nustato, kad jis pagrįstas,   tuomet:   20.1. Grąžina pasiūlymą / paraišką į   pradinį vertinimo etapą ir pasiūlymas / paraišką vertinama iš naujo;   20.2. Nutraukia pirkimo procedūras.   20.3. Tiekėjas turi galėti pateikti   pretenzijas ir po nustatyto / pirkimo sąlygose nurodyto termino, tačiau po   termino pateiktų pretenzijų PV neprivalo nagrinėti. |  
E15 | Srauto   pabaiga | - | - |  
EP3.   Pagrįsti kvalifikaciją |  
E16 | Tikrinti   Tiekėjo kvalifikaciją | - | - |  
NS1 | Pagrįsti   kvalifikaciją | PV,   Tiekėjas | 21.   Inicijuojamas   naujas subprocesas NS1 „Pagrįsti kvalifikaciją atitiktį“. |  
E17 | Srauto   baiga | - | - |  
EP3.   Pagrįsti kainą |  
E18 | Nustatyti,   kad kaina neįprastai maža | SAULĖ   IS | 22.   Tiekėjas,   gavęs prašymą pagrįsti neįprastai mažą kainą, turi turėti galimybę inicijuoti   neįprastai mažos kainos pagrindimo subprocesą. |  
NS2 | Pagrįsti   kainą | PV,   Tiekėjas | 23.   Inicijuojamas   naujas subprocesas NS2 „Pagrįsti kainą“. |  
E19 | Srauto   pabaiga | - | - |  
Proceso   metu siunčiami sisteminiai pranešimai |  
E20 | Laikas   pateikti atsakymą | - | - |  
T3 | Priminti   apie termino pateikti kvalifikacinius duomenis pabaigą | SAULĖ   IS | 24.   Jeigu iki   nustatyto termino pabaigos Tiekėjas nepateikė kvalifikaciją pagrindžiančios   informacijos ir duomenų, SAULĖ IS turi siųsti sisteminį pranešimą. Nukreipiama   į SAULĖ IS Komunikacijos posistemę, inicijuojamas procesas KP4: Sisteminių   pranešimų siuntimas registruotiems Sistemos naudotojams. |  
E21 | Srauto   pabaiga | - | - |  
E22 | Laikas   pateikti atsakymą | - | - |  
T4 | Priminti   apie termino pateikti kainos pagrindimą pabaigą | SAULĖ   IS | 25.   Jeigu iki   nustatyto termino pabaigos Tiekėjas nepateikė kainos pagrindimo, SAULĖ IS   turi siųsti sisteminį pranešimą. Nukreipiama į SAULĖ IS Komunikacijos   posistemę, inicijuojamas procesas KP4: Sisteminių pranešimų siuntimas   registruotiems Sistemos naudotojams. |  
E23 | Srauto   pabaiga | - | - |  
E24 | Sudaryta   eilė |   | - |  
T5 | Informuoti   apie taikomą sutarties atidėjimo terminą | SAULĖ   IS | 26.   Sudarius   eilę, Tiekėjai turi būti informuojami apie taikomą sutarties atidėjimo   terminą ir preliminarią sutarties sudarymo datą. Nukreipiama į SAULĖ   IS Komunikacijos posistemę, inicijuojamas procesas KP4: Sisteminių pranešimų   siuntimas registruotiems Sistemos naudotojams. |  
E26 | Srauto   pabaiga | - | - |  

### 7.6.5.3.1	Reikalavimai subproceso „NS1: Pagrįsti kvalifikacijos atitiktį“
1206. Žemiau pateikiama bendra subproceso „NS1: Pagrįsti kvalifikacijos atitiktį“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS.

![image](https://user-images.githubusercontent.com/61745726/89336977-e566ff80-d6a2-11ea-8183-131e8e480c5f.png)

7.38 lentelė. Proceso „NS1: Pagrįsti kvalifikacijos atitiktį“ realizavimo reikalavimai

Subproceso Nr. | Subproceso    pavadinimas | Subproceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Gautas   PV prašymas pagrįsti kvalifikaciją | - | 1.   Tiekėjas   turi gauti PV prašymą dėl Tiekėjo kvalifikacijos atitiktį pirkimo sąlygose   keliamiems reikalavimams pagrindžiančios informacijos ir duomenų pateikimo.
T1 | Grįsti   kvalifikacijos atitiktį | Tiekėjas | 2.   Tiekėjas iki   PV nustatyto termino pabaigos, turi pateikti kvalifikacijos atitiktį pirkimo   sąlygose keliamiems reikalavimams pagrindžiančią informaciją ir duomenis.   3.   Informacija   ir duomenys kvalifikacijai pagrįsti gali būti:   3.1. imami   iš Tiekėjo profilyje saugomos informacijos ir duomenų;   3.2. papildyti   / patikslinti esami Tiekėjo profilyje saugomi duomenys įvedant naują   informaciją ar įkeliant naujus dokumentus;   3.3. prisegami   papildomi dokumentai, jeigu to reikalaujama (pvz., dokumentai, pagrindžiantys   tinkamą sutarčių įvykdymą, siūlomų specialistų diplomų, sertifikatų kopijos   ir pan.).   4.   Tiekėjas   turi galėti tikslinti pateiktą informaciją ir duomenis ne vieną kartą iki   tol, kol bus pasiektas vienas iš įvykių:   4.1. PV   pripažįsta, kad Tiekėjo pasiūlymas atitinka keliamus kvalifikacijos   reikalavimus;   4.2. PV   pasiūlymą atmeta dėl neatitikimo kvalifikacijos reikalavimams.
T2 | Tiekėjo   profilio duomenys | SAULĖ   IS | 5.   Tiekėjas   turi turėti galimybę SAULĖ IS pažymėti, kuriais iš savo profilyje esamų   duomenų grįs atitiktį keliamiems kvalifikacijos reikalavimams.
  | Tiekėjo   profilio duomenys | SAULĖ   IS | 6.   SAULĖ IS   turi būti kaupiama informacija ir duomenys apie Tiekėjo kvalifikaciją.
E2 | Gautas   PV pranešimas dėl kvalifikacijos patvirtinimo | Tiekėjas | 7.   Tiekėjas   turi gauti PV pranešimą, kuriame informuoja, kad Tiekėjo pasiūlymas /   paraiška atitinka keliamus kvalifikacijos reikalavimus.
E3 | Srauto   pabaiga | - | -
E4 | Gautas   PV prašymas patikslinti kvalifikaciją | Tiekėjas | 8.   Tiekėjas   turi gauti PV pranešimą, kuriame:   8.1. informuojama,   kad PV įvertinusi visus Tiekėjo pateiktus kvalifikacijos reikalavimų atitiktį   įrodančius duomenis, nustatė, kad pateikta neišsami ir netiksli informacija ir   duomenys;   8.2. prašoma   patikslinti / paaiškinti / pateikti papildomus dokumentus (jei taikoma).   9.   PV į Tiekėją dėl kvalifikacijos patikslinimo turi   galėti kreiptis ne vieną kartą.
T3 | Prašyti   pratęsti terminą | Tiekėjas | 10.   Jeigu   Tiekėjas, per PV nustatytą terminą, nespėja paruošti kvalifikacijos atitiktį   keliamiems reikalavimams pagrindžiančios informacijos ir duomenų, tuomet jis   turi turėti galimybę kreiptis į PV dėl termino pratęsimo.    11.   Nukreipiama į SAULĖ IS Komunikacijos posistemę.
E5 | Gautas   PV sutikimas dėl termino pratęsimo | Tiekėjas | 12.   Tiekėjas   turi gauti PV pranešimą, kuriame informuojama, kad PV sutinka pratęsti   terminą.
E6 | Gautas   PV nesutikimas dėl termino pratęsimo | Tiekėjas | 13.   Tiekėjas   turi gauti PV pranešimą, kuriame informuojama, kad PV nesutinka nepratęsti   termino.
E8 | Baigėsi   terminas | - | 14.   Jeigu   Tiekėjas iki PV nustatyto termino pabaigos nepateikia kvalifikaciją   pagrindžiančių duomenų ir informacijos, tuomet jo pasiūlymas / paraiška turi   atmetama ir toliau nebevertinama.   15.   Sprendimą dėl pasiūlymo atmetimo priima PV ir   informuoja Tiekėją apie priimtą sprendimą išsiųsdama pranešimą SAULĖ IS el.   susirašinėjimo priemonėmis (per Komunikacijos posistemę).

### 7.6.5.3.2	Reikalavimai subproceso „NS2: Pagrįsti kainą“ realizavimui
1222. Žemiau pateikiama bendra subproceso „NS2: Pagrįsti kainą“ schema ir reikalavimai proceso ir funkcijų realizavimui SAULE IS
![image](https://user-images.githubusercontent.com/61745726/89337040-fd3e8380-d6a2-11ea-95ab-75fa0bbca566.png)

7.39 lentelė. Proceso „NS2: Pagrįsti kainą“ realizavimo reikalavimai

Subproceso Nr. | Subproceso pavadinimas | Subproceso dalyvis | Reikalavimai    realizavimui
-- | -- | -- | --
E1 | Gautas   pranešimas dėl neįprastai mažos kainos | Tiekėjas | 1.   Tiekėjas gauna   pranešimą dėl neįprastai mažos kainos pagrindimo, kuriame prašoma, kad   Tiekėjas pagrįstų pasiūlyme nurodytą prekių, paslaugų, darbų ar jų sudedamųjų   dalių kainą arba sąnaudas.
T1 | Teikti   kainos pagrindimą | Tiekėjas | 2. Tiekėjas   turi turėti galimybę pateikti pasiūlytos kainos pagrindimą, nurodant reikalingas   pasiūlymo detales, įskaitant kainos ar sąnaudų sudedamąsias dalis ir   skaičiavimus.    3.   Tiekėjas turi   turėti galimybę tikslinti pateiktą   informaciją ir duomenis ne vieną kartą iki tol, kol įvyks vienas iš šių   įvykių:   3.1. PV   pripažįsta, kad Tiekėjo kainos pagrindimas tinkamas;    3.2. PV   pasiūlymą atmeta dėl netinkamo kainos pagrindimo;   3.3. PV   pasiūlymą atmeta dėl to, kad Tiekėjas yra gavęs valstybės pagalbą. Pasiūlymas   gali būti atmestas vien šiuo pagrindu, jeigu Tiekėjas negali per pakankamą PV   nustatytą laikotarpį įrodyti, kad valstybės pagalba buvo suteikta teisėtai.   Atmetus pasiūlymą šiuo pagrindu, PV apie tai privalo pranešti Europos   Komisijai. Valstybės pagalba laikoma bet kuri priemonė, atitinkanti Sutarties   dėl Europos Sąjungos veikimo 107 straipsnio 1 dalyje nustatytus kriterijus.
E2 | Gautas   PV pranešimas dėl tinkamo kainos pagrindimo | Tiekėjas | 4.   Tiekėjas   turi gauti PV pranešimą, kuriuo informuojama, kad jo kainos pagrindimas   pripažintas tinkamu.
E3 | Srauto   pabaiga | - | -
E4 | Gautas   PV prašymas patikslinti kainos pagrindimą | Tiekėjas | 5.   Jeigu PV   nustato, kad kainos pagrindime yra klaidų ar kaina yra nepakankamai pagrįsta,   tuomet Tiekėjas turi gauti prašymą patikslinti pateiktą kainos pagrindimą.
T2 | Prašyti   pratęsti terminą | Tiekėjas | 6.   Jeigu   Tiekėjas, per PV nustatytą terminą, nespėja paruošti kvalifikacijos atitiktį   keliamiems reikalavimams pagrindžiančios informacijos ir duomenų, tuomet jis   turi turėti galimybę kreiptis į PV dėl termino pratęsimo.    7.   Nukreipiama į SAULĖ IS Komunikacijos posistemę.
E5 | Gautas   PV sutikimas dėl termino pratęsimo | Tiekėjas | 8.   Tiekėjas   turi gauti PV pranešimą, kuriame informuojama, kad PV sutinka pratęsti   terminą.
E6 | Gautas   PV nesutikimas dėl termino pratęsimo | Tiekėjas | 9.   Tiekėjas   turi gauti PV pranešimą, kuriame informuojama, kad PV nesutinka nepratęsti termino.
E7 | Baigėsi   terminas | - | 10.   Sprendimą dėl pasiūlymo / paraiškos atmetimo priima   PV ir informuoja Tiekėją apie priimtą sprendimą išsiųsdama pranešimą SAULĖ IS   el. susirašinėjimo priemonėmis (per Komunikacijos posistemę).
E8 | Srauto   baiga | - | -


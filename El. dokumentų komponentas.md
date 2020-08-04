1.1.1	Reikalavimai El. dokumentų komponentui
1979. El. dokumento sudarymo ir tikrinimo komponentas turi teikti el. dokumentų formavimo, pasirašymo ir tikrinimo sąsajas SAULĖ IS komponentams (portalui „Saulė“, vidiniam portalui ir kt.), kuriuose realizuojamas el. dokumentų sudarymas, pasirašymas ir tikrinimas.
1980. Turi būti galima sudaryti el. dokumentą (el. dokumento ruošinį).
1980.1.  Sudaryti el. dokumentą turi būti galima perduodant pasirašomą dokumentą (-us) ir metaduomenis per integracines sąsajas iš SAULĖ IS komponentų į el. dokumentų komponentą. Suformuotas el. dokumentas turi būti grąžintas tolimesniam tvarkymui.
1980.2. Turi būti realizuotas funkcionalumas, kuris užtikrintų, kad didelės apimties (pavyzdžiui, daugiau nei 200 MB dydžio) kelių asmenų pasirašomi dokumentai nebūtų kiekvienam pasirašymo veiksmui pakartotinai siunčiami iš SAULĖS IS komponentų į el. dokumentų sudarymo ir tikrinimo komponentą. Detalios analizės ar projektavimo etape turi būti apibrėžtas sprendimas, kuris naudotojo atžvilgiu užtikrintų patogų didelės apimties dokumentų pasirašymo procesą.
1980.3. Turi būti galima sudaryti šiuos el. dokumentus:
1980.3.1. ADOC V1.0 (Lietuvos archyvų departamento prie Lietuvos Respublikos vyriausybės generalinio direktoriaus 2009 m. rugsėjo 9 d. Nr. V-60 įsakymas dėl elektroniniu parašu pasirašyto elektroninio dokumento specifikacijos ADOC-V1.0 patvirtinimo) (toliau – ADOC  specifikacija).
1980.3.2. PDF-LT V1.0 (ar naujesnė šios specifikacijos versija, jeigu projekto įgyvendinimo metu tokia bus. Sprendimas, kokios el. dokumento versijos sudarymo ir tikrinimo funkcijas realizuoti, turi būti priimtas likus ne mažiau 9 mėnesiams iki Projekto įgyvendinimo pabaigos.) (Lietuvos vyriausiojo archyvaro 2014 m. rugpjūčio 29 d. Nr. VE(1.3 E)-42 įsakymas dėl elektroninio dokumento specifikacijos PDF-LT-V1.0 patvirtinimo) (toliau – PDF-LT specifikacija);
1980.3.3. ASiC (ETSI TS 102 918 V1.3.1 (2013-06) „Electronic Signatures and Infrastructures (ESI); Associated Signature Containers (ASiC)“) (toliau – ASiC specifikacija).
1980.4. Komponentas turi leisti parengti elektroninio dokumento nuorašą ir išrašą (su registravimo ir pasirašymo informacija).
1980.5. Komponentas neturi leisti sudaryti ir pasirašyti el. parašu, jeigu negalioja pasirašymui naudojamas skaitmeninis sertifikatas.
1981. Turi būti galima pasirašyti el. dokumentą:
1981.1. Minimaliai turi būti galima pasirašyti el. dokumentą šiais būdais:
1981.1.1. Naudojant stacionarią el. parašo formavimo įrangą (LR asmens tapatybės korteles,  LR valstybės tarnautojo pažymėjimus, USB laikmenas ir pan.);
1981.1.2. Naudojant mobilią el. parašo formavimo įrangą („m. parašą“) (neapsiribojant su šių ryšio operatorių išduodamomis „m. parašo“ priemonėmis: „Telia“, „Bitė“, „Tele2“);
1981.1.3. Naudojant „Smart-ID“ parašo formavimo technologiją;
1981.1.4. Naudojant kriptografinius saugumo modulius (HSM).
1981.2. Turi būti galima vienu pasirašymo veiksmu (vieną kartą įvedant parašo formavimo įrangos PIN kodą) pasirašyti daugiau negu vieną el. dokumentą (paketą el. dokumentų), jeigu per integracines sąsajas iš SAULĖ IS yra perduotas paketas dokumentų, kurių pagrindu reikia suformuoti daugiau nei vieną el. dokumentą.
1981.3. Prieš pasirašant el. dokumentą turi būti galima atlikti el. dokumento peržiūrą ir tikrinimą.
1981.4. El. dokumento pasirašymas visais nurodytais būdais turi būti galimas su Google Chrome, Internet Explorer/ Microsoft Edge, Firefox ir Safari naršyklių naujausiomis versijomis.
1981.5. El. dokumentą turi galėti pasirašyti pats El. dokumentų sudarymo ir tikrinimo komponentas, kai SAULĖ IS kartu su pasirašomais dokumentais perduoda pasirašymui ir požymi, kad turi būti sudarytas sisteminis el. parašas.
1981.6. Pasirašytas el. dokumentas turi būti parsiunčiamas į pasirašymą iniciavusio SAULĖ IS komponentą.
1982. Turi būti galima peržiūrėti ir patikrinti el. dokumentą.
1982.1. El. dokumento peržiūrą ir patikrinimą turi būti galima atlikti veiksmą inicijuojant iš SAULĖ IS komponento, kuriame tvarkomas el. dokumentas. El. dokumento komponentas turi grąžinti el. dokumento patikrinimo rezultatus (pagal el. dokumento specifikaciją).
1982.2. Turi būti galima peržiūrėti el. dokumento rinkmenas, metaduomenis, el. parašus, sertifikatus, laiko žymas ir kt.
1982.3. El. dokumentų sudarymo ir tikrinimo komponentas turi atlikti el. dokumento atitikties vertinimą atitinkamai el. dokumento specifikacijai (žr. 1980.3 punkto papunkčius). Turi būti tikrinamas el. dokumento konteinerio integralumas, el. parašų galiojimas, sertifikatų galiojimas, laiko žymų galiojimas, metaduomenų tinkamumas, rinkmenų tinkamumas, parašų kvalifikuotumas ir kt. Apie nustatytus neatitikimus turi būti informuojamas naudotojas. Kiekvienas neatitikimas (klaida ar pan.) turi būti aiškiai aprašytas bei pateikiamas bent lietuvių kalba.
1982.3.1. Komponentas taip pat turi patikrinti ar asmeniui kvalifikuotą sertifikatą išdavė tam teisę turinti sertifikavimo tarnyba taip pat ar kvalifikuoto sertifikato išdavimo metu sertifikavimo tarnyba tokią teisę turėjo. Patikrinimas turi būti atliekamas patikimų sertifikavimo paslaugų teikėjų sąrašuose (angl. Trust-service Status List).
1982.3.2. Komponentas turi patikrinti ar kvalifikuotas sertifikatas yra galiojantis naudojant sertifikato patikrą realiu laiku (angl. OCSP), o esant sertifikatą išdavusios institucijos sertifikato patikros paslaugos sutrikimams, turi gebėti sertifikato galiojimą patikrint naudojant atšauktų sertifikatų sąrašus (angl. CRL).
1983. El. dokumentų sudarymo ir tikrinimo komponentas turi realizuoti el. dokumentų gyvavimo ciklo užtikrinimo funkcionalumą – el. dokumentų komponentas turi pakelti SAULĖ IS tvarkomų dokumentų el. parašo lygį bei uždėti reikiamas laiko žymas. 
1983.1. SAULĖ IS turi būti realizuotas funkcionalumas, kuris užtikrintų reikiamų el. dokumentų parašo lygio kėlimą. Turi būti galima būti administravimo priemonėmis nurodyti kokiems dokumentams (dokumentų grupėms, dokumentų tipams, kitiems dokumentų imtį identifikuojantiems atributams) koks parašo lygio kėlimo būdas turi būti taikomas / netaikomas.
1984. Turi būti realizuotas el. dokumentų komponento administravimo funkcionalumas:
1984.1. Turi būti galima tvarkyti laiko žymų tarnybų duomenis (adresus ir kt.).
1984.2. Turi būti galima tvarkyti  patikimų sertifikavimo paslaugų teikėjų sąrašų (angl. Trust-service Status List) adresus ir kt.;
1984.3. Turi būti galima tvarkyti atšauktų sertifikatų sąrašus (angl. CRL) adresus ir kt.;
1984.4. Turi būti galima tvarkyti kitus būtinus parametrus pagal kiekvieno el. dokumentų specifikacijos specifiką.
1985. El. komponento naudojimo audito žurnalas turi būti kaupiamas bendrame SAULĖ IS audito žurnale.
1986. El. dokumentų komponento funkcionalumas gali būti realizuojamas kaip trečios šalies kvalifikuota el. dokumentų ir el. parašų sudarymo ir tikrinimo paslauga. Tokiu atveju el. dokumentų komponentui nėra keliami jo administravimo reikalavimai (dėl laiko žymų tarnybų adresų, atšauktų sertifikatų sąrašus adresų, patikimų sertifikavimo paslaugų teikėjų sąrašų adresų ir kt.).
1987. Diegėjas turi užtikrinti (apmokėti išlaidas) visoms mokamoms paslaugoms (parašų formavimui, parašų tikrinimui, laiko žymų sudarymui, archyviniam el. dokumentų sudarymui, OCSP paslaugoms, „m. parašo“ paslaugoms ir kt.), kurios reikalingos sudaryti, tikrinti ir užtikrinti el. parašų ir el. dokumentų galiojimą 500 000 el. dokumentų.

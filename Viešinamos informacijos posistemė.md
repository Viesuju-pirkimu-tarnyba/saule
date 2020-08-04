7.6.12	Reikalavimai Viešinamos informacijos posistemei
1675. Turi būti realizuotas funkcionalumas skirtas SAULĖ IS duomenų viešinimo procesų tvarkymui, portalo „Saulė“ turinio valdymui ir administravimui TVS priemonėmis, prenumeratų ir naujienlaiškių valdymui, prenumeratų procesų valdymui, apklausų sudarymui, jų atlikimui ir automatiniam apklausų rezultatų apskaičiavimui, bei visos kitos su pirkimu susijusios viešinamos informacijos atvaizdavimui ir viešinamos informacijos paieškai (pirkimo skelbimai, ataskaitos, vykdyti pirkimai, metinių pirkimų planai ir kt.). 
1676. Šioje specifikacijoje objektai, kurių duomenys gali būti viešinami arba naudotojui pažymėjus, kad objektas ar jo dalis yra viešinama, šie duomenys turi būti atvaizduojami Viešinimo informacijos posistemyje pagal to objekto sritį. 
1677. Analitiko (BI) posistemyje sukurtos duomenų ataskaitos (duomenų rinkiniai), kurios yra viešinamos, turi būti atvaizduojamos kartu su galimybe išoriniam naudotojui naudoti analitikos (BI) įrankio priemones atvaizdavimui ir vykdyti su paviešintos ataskaitos (duomenų rinkiniu) įvarius analitinius pjūvius ir eksportuojant duomenis į pasirinktą formatą. Sukurtas Analitikos (BI) posistemio pagalba duomenų rinkinys turi atsinaujinti automatiškai pagal kaupiamus SAULĖ IS duomenis. 
1678. Posistemė turi užtikrinti automatinį duomenų viešinimą portale „Saulė“, socialiniuose tinkluose ir kitais įvairiais nustatytais duomenų pateikimo formatais (įskaitant, bet neapsiribojant, API (XML). Viešinimo informacijos posistemyje turi būti sukurta sritis, kurioje būtų viešinamos ir prieinamos SAULĖ IS integracijų ir analitikos (BI) posistemiuose sukurtos atvirų duomenų integracinės sąsajos (API), kartu patiekiant jų aprašymus ir naudotojų instrukcijas (atvirų duomenų rinkmenos). API sąrašas, grupavimas pagal sritis ir jų vizualinis pateikimas turi būti suderintas su Perkančiąja organizacija. Paslaugų teikėjas taip pat turi realizuoti reikalavimus atvirų duomenų rinkmenų paieškai aprašytus 1710 - 1714 punktuose).
1679. Turi būti realizuotos galimybės Sistemos administratoriui:
1679.1. Nustatyti automatines duomenų ar jų grupių viešinimo/neviešinimo taisykles;
1679.2. Nustatyti automatiškai viešinamų duomenų pateikimo formatą, vietą, dažnumą ir kt. taisykles;
1679.3. Nustatyti automatiškai viešinamų duomenų panaikinimo (neviešinimo) terminą;
1679.4. Nustatyti SAULĖ IS naudotojų analizės parametrus (Google analitika ar lygiavertės programinės įrangos pagalba), rodiklius ar kitą naudotojų žingsnių analitinę analizę.
1679.5. Sistemos administratoriui turi būti sukurta tokia viešinimo parametrų ir veiksmų seka:
1679.6. pasirenka pavienius duomenis arba duomenų paketus, kuriuos nori viešinti.
1679.7. pasirenka viešinimo formatą.
1679.8. pasirenka viešinimo kanalą (Facebook, twitter, VPT svetainėje, išoriniame portale, el. paštu ir kt.) ir duomenų pateikimo formatą (naujienlaiškis html formatu, pdf ar kitu formatu).
1679.9. nustato viešinimo periodiškumą (data nuo iki).
1679.10. inicijuoja parametrų išsaugojimo veiksmą.
1680. Turi būti sukurtas Naujienų kūrimo ir administravimo modulis, skirtas Vidiniams naudotojams kurti, peržiūrėti, publikuoti, redaguoti, šalinti bei atlikti kitus su Naujienomis susijusius veiksmus. 
1681. Turi būti sukurtas funkcionalumas, leidžiantis kurti naujienas. Naujienos kūrimo metu turi būti galima nurodyti šią informaciją:
1681.1. Autorių (pagal nutylėjimą turi būti priskiriamas naujieną kuriantis vidinis naudotojas).
1681.2. Naujienos pavadinimą (antraštę).
1681.3. Naujienos turinį (aprašymą).
1681.4. Naujienos publikavimo datą ir laiką.
1681.5. Naujienos galiojimo trukmė. Suėjus naujienos galiojimo trukmės pabaigai, naujiena turi būti archyvuojama. Archyvuotos naujienos turi būti galimos pasiekti Išoriniams naudotojams. Naujienoms automatiškai turi būti priskiriama galiojimo trukmė pagal nutylėjimą. Galiojimo trukmė turi būti konfigūruojama.
1681.6. Naujienos būseną (publikuota / nepublikuota). Pagal nutylėjimą automatiškai priskiriama būsena „Publikuota“.
1681.7. Naujienos prioriteto požymį. Jei pažymėtas, naujiena Išorinio portalo puslapyje bus atvaizduojama naujienų sąrašo viršuje. Tokios naujienos turi būti atvaizduojamos kaip keičiančios viena kitą, t. y. nebūtų statinės.
1681.8. Naujienos žymes (angl. tags).
1681.9. Požymis, ar naujiena turi automatiškai išsiunčiama prenumeratoriams pagal numatytas naujienlaiškių grupes. Pagal nutylėjimą šis požymis turi būti pažymėtas.
1681.10. Kitus su Perkančiąja organizacija analizės ir projektavimo etapų metu suderintus duomenų laukus.
1682. Turi būti galima publikuoti naujienas Išoriniame portale. Publikavimas turi veikti šiais principais:
1682.1. Naujienos turi būti publikuojamos atitinkamame  portalo „Saulė“ puslapyje.
1682.2. Turi būti išpublikuojamos tik naujienos su būsena „Publikuota“.
1682.3. Turi būti galima nurodyti naujienos publikavimo datą (data ir laikas), kuriai atėjus naujienos turi būti automatiškai išpublikuojamos Išoriniame portale.
1682.4. Turi būti galima pakartotinai publikuoti pakoreguotas naujienas. 
1683. Išpublikavus naujieną turi būti automatiškai išsiunčiamas el. laiškas jas prenumeruojantiems asmenims. Laiško turinys ir forma turi būti suderinti su Perkančiąja organizacija analizės ir projektavimo etapų vykdymo metu.
1684. Turi būti sukurtas funkcionalumas, leidžiantis redaguoti naujienas:
1684.1. Turi būti galima redaguoti naujienas, kurios nėra publikuotos Išoriniame portale. Jei naujiena yra publikuota Išoriniame portale, turi būti galima pakeisti naujienos būseną į „Nepublikuota“ ir tuomet redaguoti naujienos atributus.
1684.2. Turi būti negalima redaguoti naujienos autoriaus.
1685. Turi būti galima vartotojui atlikti paiešką ir filtravimą naujienų sąraše pagal su Perkančiąja organizacija analizės ir projektavimo etapų metu suderintus kriterijus.
1686. Turi būti galima peržiūrėti sukurtų naujienų sąrašą. Sukurta naujiena turi būti išsaugoma naujienų sąraše. Naujienų sąraše turi būti pateikiama:
1686.1. Naujienos pavadinimas.
1686.2. Naujienos publikavimo data.
1686.3. Naujienos autorius.
1686.4. Naujienos būsena.
1686.5. Kiti su Perkančiąja organizacija analizės ir projektavimo etapų metu suderinti duomenų laukais.
1687. Naujienų sąraše turi būti pateikiamos visos vidinių naudotojų sukurtos naujienos surikiuotos pagal datą nuo naujausios iki seniausios.
1688. Naujienų sąraše turi būti galima atlikti masinius veiksmus (pažymėti kelias / visas naujienas). Pažymėtas naujienas turi būti galima:
1688.1. Šalinti.
1688.2. Keisti būseną (publikuota / nepublikuota).
1689. Išoriniame portale turi būti galima puslapiuoti pateikiamą naujienų sąrašą.
1690. Išoriniame portale pasirinkus naujieną, turi būti atveriamas naujienos turinys.
1691. Išoriniame portale turi būti galima nusiųsti naujieną įvestu elektroninio pašto adresu. El. laiško turinys turi būti suderintas su Perkančiąja organizacija analizės ir projektavimo etapų vykdymo metu.

1692. Turi būti sukurtas Naujienlaiškių modulis, skirtas Išoriniame portale prenumeruoti ir gauti naujienas ar dominančius skelbimus, įvykusius pasikeitimus el. laiškų pavidalu.
1693. Išorinio portalo naudotojui turi būti galima atlikti šiuos veiksmus:
1693.1. Prenumeruoti naujienas. Turi būti nurodomas elektroninio pašto adresas, į kurį turi būti siunčiamos naujienos. Naujienų siuntimo periodiškumas turi būti suderintas su Perkančiąja organizacija periodiškumu automatiškai bus siunčiama informacija.
1693.2. Pasirenka kokią informaciją ar duomenis (jų grupes) pageidauja gauti -  pvz. skelbimų prenumerata pagal dominančią sritį, viešinamos sutartys arba Portalo naujienos pagal tam tikrą sritį arba visos ir kt. Saulė IS grupės, kurios turi požymi vieša;
1693.3. Pasirenka, kokiu formatu pageidauja gauti informaciją;
1693.4. Keisti prenumeratos nustatymus.
1693.5. Atsisakyti naujienlaiškių siuntimo.
1694. Naujienlaiškių prenumeratos modulyje turi būti kaupiami Išorinių naudotojų elektroninio pašto adresai, juos grupuojant pagal numatytas grupes. Sąraše turi būti matoma būsena, kad naujienlaiškis suformuotas ir išsiųstas. Grupių ir  grupių laukų sąrašas turi būti suderintas su Perkančiąja organizacija analizės ir projektavimo etapų įgyvendinimo metu. 
1694.1. Naujienlaiškių prenumeratos modulis turi automatiškai formuoti laiškus gavėjų grupėms, pagal naudotojo pasirinktus nustatymus kokios informacijos jis pageidauja gauti. Prenumeratoriams yra siunčiama ir formuojama tik viešai prieinama informacija.
1694.2. Išorinių naudotojų elektroninio pašto adresai turi būti automatiškai sinchronizuojami su Naujienlaiškių prenumeratos sistema. Sinchronizavimo periodiškumas turi būti suderintas su Perkančiąja organizacija analizės ir projektavimo etapų įgyvendinimo metu.
1695. Prenumeruojamos informacijos laiško turinys turi būti suderintas su Perkančiąja organizacija analizės ir projektavimo etapų vykdymo metu.

1696. Turi būti sukurtas apklausų modulis, skirtas išoriniams naudotojams dalyvauti apklausoje ir pateikti atsakymus į apklausos klausimus.
1697.  Apklausų modulis turi būti realizuotas turinio valdymo sistemos priemonėmis su galimybe viešinti sukurtą apklausą išoriniame portale, vykdyti apklausą ir gauti apklausų rezultatus.
1698. VPT darbuotojams, turintiems tokią teisę, apklausų modulyje turi būti galima kurti apklausas. Į apklausas turi būti galima įtraukti klausimus su tokių rūšių atsakymais:
1698.1. Atvirais – su galimybe įrašyti laisvos formos atsakymus.
1698.2. Uždarais:
1698.3. Su vienu atsakymo pasirinkimu.
1698.4. Su daugiau nei vienu galimu atsakymo pasirinkimu (nustatant maksimalų pasirinkimų skaičių).
1698.5. Su galimybe pasirinkti atsakymą iš skaičių sekos (angl. scale).
1698.6. Su galimybe pasirinkti atsakymą tinklelyje (angl. grid).
1699. Turi būti galima apklausoje įterpti paveikslėlius populiariausiais formatais (JPG, PNG, BMP ar lygiaverčiais).
1700. Sukurtos apklausos turi būti atvaizduojamos apklausų sąraše.
1701. Apklausas turi būti galima publikuoti / atšaukti publikavimą Išoriniame portale.
1702. Turi būti galima saugoti juodraštyje, redaguoti ir šalinti apklausas. Turi būti galima redaguoti neišpublikuotas apklausas.
1703. Išorinio portalo naudotojų pateikti atsakymai į apklausą turi būti išsaugomi – turi būti kaupiama statistika apie apklausos rezultatus.
1704. Turi būti galimybė peržiūrėti apklausų rezultatus skaitine reikšme, diagramos ar schemos pavidalu.
1705. Turi būti galima eksportuoti apklausų rezultatus XLS arba lygiaverčiu formatu.
1706. Turi būti galima sukurti trumpąsias (vienas klausimas ir vienas atsakymo pasirinkimas) apklausas, skelbiamas Išoriniame portale. Kuriant apklausą turi būti galima nurodyti jos pavadinimą, galimus atsakymo variantus ir kitus duomenis, suderintus su Perkančiąja organizacija analizės ir projektavimo etapų metu.
1707. Trumpąsias apklausas turi būti galima publikuoti Išoriniame portale.
1708. Turi būti galima redaguoti ir šalinti trumpąsias apklausas. Turi būti galima redaguoti neišpublikuotas trumpąsias apklausas.
1709. Galutinis apklausų modulio funkcionalumas turi būti suderintas su Perkančiąja organizacija analizės ir projektavimo etapų metu.
1710. Turi būti sukurtas atvirų duomenų rinkmenų peržiūros ir paieškos modulis, kuriame turi būti atvaizduoti duomenys gauti iš vidinio portalo ir informacija turi būti sugrupuota pagal atitinkamas sritis ir grupes (sričių ir grupių kriterijai ir atvaizdavimo būdas turi būti suderinti su PO).
1711. Duomenų rinkmenų peržiūrą ir paiešką gali atlikti tiek autorizuoti tiek neautorizuoti portalo „Saulė“ vartotojai.
1712. Vartotojas turi galėti peržiūrėti pasirinktą duomenų rinkmeną.
1713. Vartotojui turi būti galimybė atlikti bendrą duomenų rinkmenų paiešką ir sistema turi atvaizduoti rezultatų sąrašą.
1714. Vartotojui turi būti sukurta galimybė atsidarius konkrečią rinkmeną vykdyti jos reikšmių paiešką (pvz., atsidarius temų sąrašą ieškoti konkrečios reikšmės pateiktoje rinkmenoje/sąraše).

1715. Viešinamos informacijos posistemė turi turėti šias bendrąsias funkcijas:
1715.1. Turi būti galima kurti neriboto gylio puslapių struktūrą.
1715.2. Turi būti galima valdyti (įvesti, atnaujinti, šalinti) portalo „Saulė“ turinį nenaudojant HTML ar lygiavertės kalbos žinių (išskyrus su Perkančiąja organizacija suderintus komponentus).
1716. Viešinamos informacijos posistemė turi turėti tekstų stiliaus (CSS) redagavimo, peržiūros priemonę, su teksto valdymo galimybėmis (redaguoti, šalinti, sukurti naujus stilius, keisti šriftą, dydį, spalvą, storį, lygiavimą, transformavimą).
1717. Viešinamos informacijos posistemės teksto redaktoriaus reikalavimai:
1717.1. Redagavimo aplinka turi būti artima Microsoft Word ar kitų lygiaverčių programų aplinkai.
1717.2. Informacija turi būti lengvai (tame tarpe naudojant standartines operacinės sistemos kopijavimo ir įkelties funkcijas) perkeliama iš Microsoft Word, Microsoft Excel, OpenOffice ir kitų lygiaverčių programų. Perkeliant informaciją turi išlikti perkeliamo teksto formatavimas.
1717.3. Turi būti lentelių kūrimo, jų redagavimo ir lentelės bei jos langelių formatavimo funkcijos.
1717.4. Turi būti įprastos teksto formatavimo funkcijos (lygiavimas, šrifto, jo stiliaus, dydžio, spalvos ir kitų parametrų valdymas).
1717.5. Turi būti galimybė įkelti paveiksliuką, audio ir video failus.
1717.6. Turi būti galimybė formatuoti įkeltą paveiksliuką.
1717.7. Redaktoriuje turi būti galimybė tiesiogiai redaguoti patį HTML kodą.
1717.8. Redaktorius turi automatiškai tikrinti pasirinktos kalbos rašybą ir neatitinkančius rašybos taisyklių žodžius pabraukti.
1717.9. Redaktorius turi palaikyti lietuviškų simbolių palaikymą (kabutės, brūkšniai ir kt.) ir tinkamą jų atvaizdavimą.
1717.10. Turi būti galimybė kurti įvairias nuorodas (į kitą puslapį, dokumentą, kitą svetainę, el. pašto adresą).
1718. Viešinamos informacijos posistemė turi palaikyti daugiakalbiškumą.
1719. Viešinamos informacijos posistemė administruojamuose sąrašuose (naujienų ir pan.) turi būti galimybė eksportuoti duomenis. Eksporto funkcionalumas turi būti suderintas su Perkančiąja organizacija analizės ir projektavimo etapų vykdymo metu.
1720. Viešinamos informacijos posistemė administruojamuose sąrašuose (naujienų ir pan.) turi būti galima atlikti įrašų rikiavimą pagal visus atributus.
1721. Viešinamos informacijos posistemė priemonėmis kuriamų įrašų (naujienų ir kt.) kiekis neturi būti ribojamas, t. y. turi būti galima sukurti neribotą skaičių įrašų.
1722. Viešinamos informacijos posistemė turi būti lengvai plečiama, t. y. turi būti galima įdiegti neribotą skaičių įskiepių (angl. plugin).
1723. Viešinamos informacijos posistemės priemonėmis turi būti leidžiama įkelti rinkmenas ir publikuoti jas portale.
1724. Turi būti sukurtas administravimo modulis, skirtas TVS naudotojams valdyti klasifikatorius, klasifikatorių reikšmes, sisteminius parametrus, išvedamų rezultatų skaičius sąrašuose ir kitus parametrus, administruoti naudotojus.
1725. Visi administravimo modulyje pateikti klasifikatoriai turi būti galimi peržiūrėti. Klasifikatorių įrašai, pateikiami sąrašo pavidalu, turi būti galimi ieškoti ir filtruoti pagal su Perkančiąja organizacija suderintus kriterijus.
1726. Viešinamos informacijos posistemė priemonėmis turi būti galima administruoti portalo turinį ir struktūrą. 
1726.1. Turi būti galima valdyti portalo puslapių elementus ir išdėstymą.
1726.2. Turi būti sukurta galimybė maketuoti bet kurį portalo puslapį:
1726.2.1. Kurti naujus puslapius.
1726.2.2. Pakeisti aktualiausių informacijos elementų padėtį ir informaciją juose.
1726.2.3. Įkelti / panaikinti papildomus elementus, koreguoti esamus.
1726.2.4. Naudoti hierarchinį (iki trijų lygių) elementų pateikimą.
1726.2.5. Galimybė įkelti paveikslėlius, video, nuorodas į kitas svetaines ir kt.
1726.2.6. Galimybė administratoriui keičiant ir kuriant bet kurį portalo elemento pavadinimą (pvz. meniu punktas, antraštė, modulis).
1726.2.7. Naikinti ir įtraukti naujus meniu punktus, keisti juos vietomis (išdėstymo tvarką).

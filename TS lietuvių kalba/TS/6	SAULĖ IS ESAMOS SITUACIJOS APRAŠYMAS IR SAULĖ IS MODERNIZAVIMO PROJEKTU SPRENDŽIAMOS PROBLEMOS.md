## 6	SAULĖ IS ESAMOS SITUACIJOS APRAŠYMAS IR SAULĖ IS MODERNIZAVIMO PROJEKTU SPRENDŽIAMOS PROBLEMOS

#### 6.1	VPT INFORMACINIŲ SISTEMŲ APRAŠYMAS 

<p>18. CVPIS paskirtis &ndash; identifikuoti ir autentifikuoti perkančiąsias organizacijas, ar jų įgaliotas kitas organizacijas, atliekančias pirkimus, institucijas, atsakingas už ES lė&scaron;omis finansuojamų projektų atranką, jų įgyvendinimo priežiūrą, parei&scaron;kėjams ir projektų vykdytojams teikiančias informaciją apie projektų rengimo bei įgyvendinimo reikalavimus (toliau &ndash; Įgyvendinančiosios institucijos, IĮ) ir tiekėjų atstovus leidžiant jiems naudotis CVPIS teikiamomis priemonėmis vie&scaron;ųjų pirkimų, pirkimų, kuro pirkimų ir koncesijų suteikimo procedūrų atlikimui, elektroniniu būdu tvarkyti informacinės sistemos duomenis, teikti informaciją duomenų gavėjams procedūrų atlikimo tikslu, identifikuoti galimus interesų konfliktus, identifikuoti ar tiekėjai atitinka Vie&scaron;ųjų pirkimų įstatymo reikalavimus dėl pa&scaron;alinimo pagrindų.<br />18.1. Pagrindinės CVPIS funkcijos:<br />18.2. Administruoti ir sisteminti Pirkimo vykdytojų, pirkimus prižiūrinčių institucijų ir tiekėjų duomenis;<br />18.3. priimti, tvarkyti, kaupti, apdoroti ir vie&scaron;inti vie&scaron;ųjų pirkimų, kuro pirkimų ir koncesijų suteikimo duomenis;<br />18.4. kurti, siųsti ir saugoti vidinius bei i&scaron;orinius sisteminius prane&scaron;imus;<br />18.5. rinkti, kaupti, perduoti ir analizuoti informaciją apie numatomus ir atliekamus Pirkimus, sudarytas Pirkimų sutartis ir pirkimų sutarčių įvykdymo rezultatus;<br />18.6. saugoti ir archyvuoti Pirkimų ir koncesijų suteikimo dokumentus.<br />18.7. &Scaron;iuo metu su pirkimų vykdymu ir kontrole susiję procesai bei pagalbiniai procesai vykdomi:<br />18.8. CVPIS;<br />18.9. Vie&scaron;ųjų pirkimų rizikos valdymo informacinėje sistemoje (toliau &ndash; VPRV IS);<br />18.10. Kitomis organizacinėmis priemonėmis &ndash; DVS, VPT svetainė, el. pa&scaron;tu, naudojant Microsoft Office programinę įrangą (*.doc, *.docx ir kt. formato failai) ir kt.<br />19. Žemiau yra pateikta VPT informacinių sistemų infrastruktūros schema ir ją sudarančių elementų apra&scaron;ymas. 2020 m. II ketvirtyje numatytas susidėvėjusios įrangos atnaujinimas.</p>

![image](https://user-images.githubusercontent.com/61745726/92337130-29895d80-f0b0-11ea-8d22-0319b0eec732.png)

6.1 pav. VPT informacinių sistemų infrastruktūros schema.
20. Žemiau pateikiama loginė VPT informacinių sistemų schema ir jos aprašymas.

![image](https://user-images.githubusercontent.com/61745726/92337137-373ee300-f0b0-11ea-9f12-6549bcedeb1c.png)

6.2 pav. VPT informacinių sistemų loginė schema

6.1 lentelė. VPT informacinių sistemų loginės schemos aprašymas

<table width="100%">
<thead>
<tr>
<td width="21%">
<p>Komponentas</p>
</td>
<td width="53%">
<p>Paskirtis</p>
</td>
<td width="24%">
<p>Naudojama programinė įranga</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="21%">
<p>VPM IS</p>
</td>
<td width="53%">
<p>Vie&scaron;ųjų pirkimų monitoringo informacinė sistema (toliau &ndash; VPM IS), skirta VPT ir kitų valstybės (savivaldybių) institucijų, pirkimų vykdytojų, tiekėjų (rangovų) bei visuomenės poreikių tenkinimui. VPM IS apima &scaron;ias funkcijas:</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; skelbimų publikavimas, paie&scaron;ka ir filtravimas, skelbimų įvedimas, redagavimo peržiūra, publikavimas ir archyvavimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ataskaitų įvedimas, redagavimas ir archyvavimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; sutarčių įvedimas, redagavimas ir archyvavimas.</p>
</td>
<td width="24%">
<p>Microsoft IIS, Microsoft ASP Classic, Microsoft SQL Server 2005 (integracijos sukurtos panaudojant Microsoft BizTalk Server 2006).</p>
</td>
</tr>
<tr>
<td width="21%">
<p>CVPP (senas ir naujas)</p>
</td>
<td width="53%">
<p>Centrinis vie&scaron;ųjų pirkimų portalas (toliau &ndash; CVPP), skirtas vie&scaron;ųjų pirkimų skelbimų ir ataskaitų informacijai vie&scaron;inti. CVPP apima &scaron;ias funkcijas:</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; planuojamų atlikti vie&scaron;ųjų pirkimų suvestinės tvarkymas ir publikavimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; techninių specifikacijų publikavimas ir tvarkymas, skelbimų, ataskaitų ir sutarčių publikavimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; socialinių įmonių gaminamų prekių, teikiamų paslaugų ir atliekamų darbų sąra&scaron;o tvarkymas ir publikavimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; informacijos apie pirkimo sutarties neįvykdžiusius ar netinkamai ją įvykdžiusius tiekėjus, kai pirkimo sutartis buvo nutraukta dėl esminio pirkimo sutarties pažeidimo, kaip jis apibrėžtas Lietuvos Respublikos civiliniame kodekse, arba kai įsiteisėjo teismo sprendimas, kuriuo tenkinami pirkimo vykdytojo reikalavimai pripažinti pirkimo sutarties neįvykdymą ar netinkamą įvykdymą esminiu ir atlyginti dėl to patirtus nuostolius, tvarkymas ir administravimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; laimėjusių dalyvių pasiūlymų, sudarytų sutarčių ir sutarties sąlygų pakeitimų publikavimas, laikantis asmens duomenų teisinės apsaugos įstatymo nuostatų.</p>
</td>
<td width="24%">
<p>Microsoft IIS, Joomla CMS, My SQL, (integracijos sukurtos panaudojant Microsoft BizTalk Server 2006).</p>
</td>
</tr>
<tr>
<td width="21%">
<p>Integracijos platforma</p>
</td>
<td width="53%">
<p>Komponentas, kuris skirtas duomenų mainams tarp VPT naudojamų informacinių sistemų (VPM IS, CVPP, CTM) užtikrinti.</p>
</td>
<td width="24%">
<p>Microsoft BizTalk Server 2006.</p>
</td>
</tr>
<tr>
<td width="21%">
<p>CTM</p>
</td>
<td width="53%">
<p>Vie&scaron;ųjų pirkimų procedūrų vykdymo posistemė (toliau &ndash; CTM), kuri apima &scaron;ias funkcijas:</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; duomenų įvedimas, deaktyvavimas, redagavimas, skelbimas, tikrinimas, &scaron;ablonų nuostatų įvedimas, generavimas, redagavimas ir deaktyvavimas, privalomų laukų nustatymas, neprivalomų laukų nustatymas, konfidencialumo nustatymas, prane&scaron;imų siuntimas, įspėjimų rodymas, pirkimų priskyrimas, failų importas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; tvarkymas, apimantis funkcijas leidžiančias organizuoti, saugoti, perduoti, &scaron;alinti ir kitaip tvarkyti elektroninius dokumentus bei jų meta duomenis;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; pirkimų grupių sukūrimas, tvarkymas, &scaron;alinimas, elektroninių pirkimų sukūrimas, tvarkymas, nutraukimas, elektroninių pirkimų procedūrų &scaron;ablonų nustatymas, apimantis funkcijas leidžiančias nustatyti taisykles, loginius ir kiekinius nustatymus bei apribojimus elektroninių pirkimų elektroninėms procedūroms, elektroninio pirkimo objektų sąra&scaron;o sudarymas, tvarkymas, importavimas ir eksportavimas, kvalifikacinių klausimų tvarkymas, elektroninio pirkimo audito sekos peržiūra, elektroninio pirkimo pasiūlymų tvarkymas ir teikimas, pasiūlymo dokumentų tvarkymas, kainos pateikimo nustatymų tvarkymas, pasiūlymų analizė ir įvertinimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; pasiūlymų dokumentų patvirtinimas skaitmeniniu para&scaron;u, pasiūlymų patvirtinimas ir pateikimas;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; vidinių bei i&scaron;orinių sisteminių prane&scaron;imų ir elektroninių lai&scaron;kų kūrimo, prane&scaron;imų, kūrimo, siuntimo ir saugojimo funkcijas.</p>
</td>
<td width="24%">
<p>-</p>
</td>
</tr>
<tr>
<td width="21%">
<p>VPRV IS</p>
</td>
<td width="53%">
<p>Vie&scaron;ųjų pirkimų rizikos valdymo informacinė sistema (toliau &ndash; VPRV IS), skirta informacinių technologijų priemonėmis vertinti ir valdyti rizikos objektų riziką. VPRV IS apima &scaron;ias funkcijas:</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rinkti duomenis, reikalingus rizikos objektų rizikos valdymui;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; kaupti, apdoroti bei atvaizduoti rizikos objektų rizikos valdymui (skaičiavimui, vertinimui, stebėjimui ir kitiems veiksmams) reikalingą informaciją;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; apdoroti informaciją apie rizikos objektų rizikos pasikeitimus;</p>
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; formuoti rizikos objektų sąra&scaron;us vertinimui ir patikrinimams bei rizikos žemėlapius, reikalingus rizikos objektų rizikai valdyti.</p>
</td>
<td width="24%">
<p>Microsoft SQL Server 2012 Standart Edition</p>
<p>Java 1.7</p>
<p>JBoss AS 7.1.1</p>
<p>Java Server Faces 2.1 , Java Servlet, XHTML, Ajax komponentai (naudojantys JSF technologiją), JavaScript, JQuery</p>
<p>Primefaces 3.5</p>
<p>Eclipse Link 2.5.0</p>
<p>JBoss ESB 4.12</p>
<p>MS SQL Server 2012 Reporting Services</p>
<p>MS SQL Server 2012 Reports Builder 3.0</p>
<p>Apache CXF 2.7.6</p>
</td>
</tr>
<tr>
<td width="21%">
<p>DVS</p>
</td>
<td width="53%">
<p>Dokumentų valdymo sistema (toliau &ndash; DVS), skirta dokumentų informacijos apdorojimui, valdymui, saugojimui ir patogiai prieigai.</p>
</td>
<td width="24%">
<p>&bdquo;Kontora&ldquo;</p>
</td>
</tr>
</tbody>
</table>

#### 6.2	VPT INFORMACINIŲ SISTEMŲ STATISTINĖ INFORMACIJA

<p>21. CVPIS saugomų duomenų apimtys:<br />21.1. &Scaron;iuo metu CVPIS saugomi duomenys užima 495494.40 MB.<br />21.2. Per metus (2019-2020 m.) duomenų kiekiai i&scaron;augo, atitinkamai:<br />21.3. DB duomenys per metus padidėjo nuo 350GB iki 498GB.<br />21.4. Failų talpyklos duomenys padidėjo nuo 18.4TB iki 21,73TB.</p>

![image](https://user-images.githubusercontent.com/61745726/92337158-605f7380-f0b0-11ea-9ee5-8f72dd8bc1fb.png)

6.3 pav. CVPIS saugomų duomenų apimtys 2019-2020 m.

22. Remiantis 2019 m. duomenimis, CVPIS buvo registruota 40675 Pirkimų vykdytojų naudotojų ir 9652 Tiekėjų naudotojų.

![image](https://user-images.githubusercontent.com/61745726/92337162-6e14f900-f0b0-11ea-9ac6-9d55e194b6f3.png)


23. Vidutinis vienos dienos prisijungusių naudotojų (sesijų) kiekis 2019 m. buvo 10451. Žemiau pateikiamas vidutinis vienos dienos prisijungusių naudotojų (sesijų) kiekis skirtingais mėnesiais.
![image](https://user-images.githubusercontent.com/61745726/92337175-766d3400-f0b0-11ea-9f6d-8ec354bdc560.png)

<p>24. CVPIS greitaveikos / na&scaron;umo informacija: <br />24.1. Vidutinis vieno puslapio pateikimo naudotojui laikai (sekundėmis) iki 3 sekundžių.<br />24.2. Pagrindinės žinomos probleminės CVPIS funkcijos, kurių greitaveika nepakankama:<br />24.3. Skelbimų, ataskaitų pildymas, jei yra daugiau nei 50 dalių.<br />24.4. Didelės apimties (~30 MB ir daugiau) dokumentų įkėlimas.<br />24.5. Pasiūlymo pasira&scaron;ymas, jei yra įkeltas didelis kiekis failų (~50 failų ir daugiau).<br />24.6. Pasiūlymo pateikimas, jei pirkime buvo sukurta daug dalių (daugiau nei 15 dalių).</p>

#### 6.3	MODERNIZAVIMO PROJEKTU SPRĘNDŽIAMOS PROBLEMOS

<p>24.7. Esamos situacijos problematika:<br />24.8. Lietuvos Respublikos nacionalinėje kovos su korupcija 2015-2025 m. programoje, patvirtintoje Lietuvos Respublikos Seimo 2015 m. kovo 10 d. nutarimu Nr. XII-1537 &bdquo;Dėl Lietuvos Respublikos nacionalinės kovos su korupcija 2015&ndash;2025 metų programos patvirtinimo&ldquo; (toliau &ndash; Programa) yra įvardytos 8 prioritetinės sritys, kuriose korupcijos paplitimo galimybė yra didžiausia. Viena i&scaron; &scaron;ių sričių yra vie&scaron;ieji pirkimai.<br />24.9. Auk&scaron;tą korupcijos lygį vie&scaron;ųjų pirkimų srityje lemiančios priežastys: <br />24.10. skaidrumo ir vie&scaron;umo stoka, <br />24.11. didelė vie&scaron;ųjų pirkimų įtaka &scaron;alies ekonomikai ir verslo subjektams,<br />24.12. nepakankamai veiksmingas kontrolės mechanizmas, <br />24.13. nepakankama atsakomybė už padarytus pažeidimus, <br />24.14. politikų įtaka ir pan. <br />24.15. Tam tikrais atvejais korupcijai pasireik&scaron;ti vis dar turi įtakos Pirkimų vykdytojų specialistų kompetencijos stoka, neformalūs i&scaron;ankstiniai susitarimai, kvalifikacinių reikalavimų pritaikymas proteguojamoms įmonėms, nereikalingų prekių, paslaugų ar papildomų darbų pirkimas, netinkamas sutarčių vykdymas ir nepakankama jų vykdymo priežiūra, tiekėjų piktnaudžiavimas jiems suteikta teise ginti savo interesus, nepakankama socialinių įmonių konkurencija, neleistini tokių įmonių susitarimai ir piktnaudžiavimas socialinės įmonės statusu, konkurenciją ribojantys (karteliniai) susitarimai. Vie&scaron;uosiuose pirkimuose dalyvaujantys tiekėjai sudaro neleistinus susitarimus ir pagal &scaron;iuo metu galiojantį teisinį reguliavimą sudėtinga tokius tiekėjus pa&scaron;alinti i&scaron; vie&scaron;ojo pirkimo.<br />24.16. Pagrindinės sprendžiamos problemos:<br />24.17. Nepakankamai automatizuota Pirkimų vykdymo sistema, sudaranti prielaidas įvairioms korupcijoms aprai&scaron;koms. Elektroninio valdymo plėtra yra vienas i&scaron; įrankių siekiant skaidrumo, vie&scaron;umo ir piliečių įtraukimo į valdymo ir demokratinius procesus;<br />24.18. Nepakankamai struktūrizuoti Pirkimo sutarčių ir jų įgyvendinimo duomenys;<br />24.19. Nepakankamai vie&scaron;a, skaidri, lengvai randama ir sisteminama informacija, apimanti visus su Pirkimais susijusius procesus bei sutarties įgyvendinimą;<br />24.20. Nėra sukurtos duomenų automatiniam pateikimui reikalingos integracijos su kitomis valstybės informacinėmis sistemomis.<br />24.21. Atsižvelgiant į auk&scaron;čiau i&scaron;vardintas problemas bei remiantis teisės aktais, modernizuojant CVP IS planuojama skaitmenizuoti &scaron;ias atliekamas veiklas:<br />24.22. maksimaliai struktūrizuoti <br />24.23. Integruoti sistemą su kitų institucijų, kurių duomenys reik&scaron;mingi Pirkimų procedūroje bei kontroliuojančių institucijų sistemomis &ndash; tai leistų atsisakyti popierinių dokumentų i&scaron; kompetentingų institucijų gavimo, būtų i&scaron;vengta dokumentų klastojimo.<br />24.24. automatizuoti pirkimų procesą nuo pat pirkimo planavimo iki sutarties sudarymo ir jos įgyvendinimo, kad jame būtų kuo mažiau žmogi&scaron;ko faktoriaus bei būtų i&scaron;vengta neteisingos informacijos teikimo ar dokumentų klastojimo.<br />24.25. kurti priemones didesniam informacijos vie&scaron;inimui. Vie&scaron;umas yra pagrindinė priemonė kovojant su korupcija; <br />24.26. sukurti priemones supaprastintų mažos vertės pirkimų vykdymui siekiant ne&scaron;ali&scaron;ko ir patogaus tiekėjų parinkimo, ypatingai neskelbiamų pirkimų atveju. Mažos vertės pirkimai sudaro nemažą dalį vie&scaron;ųjų pirkimų, jiems atlikti turi būti sukurtos patogios ir užkertančios kelią galimam piktnaudžiavimui priemonės;<br />24.27. sukurti sąsajas su sistemomis ar funkcionalumus, leidžiančius atsekti potencialų interesų konfliktą;<br />24.28. užkardyti korupcines schemas vykdant Pirkimų metu sudarytas sutartis &ndash; viena i&scaron; korupcijos atsiradimo galimybių Pirkimuose yra sutarties sąlygų nustatymas, kai vienas i&scaron; tiekėjų nesirengia jų vykdyti, todėl reikalinga griežtesnė sutarčių priežiūra ir tam skirtos priemonės sistemoje. Numatoma, kad sutartis būtų elektroninė, pildoma sistemoje, joje būtų pildomi ir sutarties pakeitimai, kas leistų tiksliau ir operatyviau identifikuoti sutarčių vykdymo pažeidimus;<br />24.29. automatizuoti pažymų apie sėkmingai įvykdytas sutartis i&scaron;davimo procedūrą;<br />24.30. kuriant automatines priemones tiekėjų, kurie įtraukti į nepatikimų tiekėjų ir/arba melagingą informaciją pateikusių tiekėjų sąra&scaron;us pa&scaron;alinimui i&scaron; pirkimo procedūros;<br />24.31. įgyvendinant kitas priemones, padedančias užkardyti korupcinio pobūdžio veikas.</p>

**25. Pirkimų vykdytojų su pirkimų vykdymo procesais susijusios pagrindinės identifikuotos problemos:**

<ul>
<li>Procedūrų vykdymo ir įforminimo optimizavimo poreikis;</li>
<li>Pasiūlymo vie&scaron;inimo neefektyvumas;</li>
<li>Pasiūlymo vertinimo neefektyvumas;</li>
<li>Nėra galimybės CVPIS naudoti/ pasirinkti pirkimo dokumentų sutarčių &scaron;ablonus;</li>
<li>CVPIS dažniausiai atlieka tik informacijos perdavimo funkciją;</li>
<li>Pirkimų planas egzistuoja kaip atskiras, nekintantis sąra&scaron;as, kurį sunku parengti, o jo duomenys susiejami tik su skelbimu apie Pirkimą, tačiau nesusieti su visa Pirkimo procedūra bei vie&scaron;ojo pirkimo &ndash; pardavimo sutartimi ar koncesijos sutartimi;</li>
<li>Skirtinguose dokumentuose atkartojama informacija, kurią kiekvieną kartą reikia įra&scaron;yti, pvz.: Skirtingų pirkimų pirkimo sąlygų nekintančios dalys;</li>
<li>Per skirtingus pirkimo proceso dokumentus besikartojantys pirkimo duomenys;</li>
<li>Užbaigus pirkimą reikia teikti kelias atskiras ataskaitas &ndash; atskirai teikiama pirkimo sutartis, pildoma ataskaitos forma, tarptautinio pirkimo atveju teikiami skelbimai apie sutarties sudarymą, vie&scaron;ai pateikiami dokumentai tarpusavyje nesisieja (ataskaita apie įvykdytą pirkimą nesusieta su pasira&scaron;yta sutartimi).</li>
</ul>

**26. Tiekėjų atstovų pagrindinės identifikuotos problemos:**

<ul>
<li>Vieningu kodu nėra susiejamas įra&scaron;as pirkimo plane, rinkos konsultacijoje, techninės specifikacijos skelbimo, pirkimo skelbime, todėl nėra konkretaus pirkimo atsekamumo, nėra galimybės sekti pasirinkto pirkimo eigos &ndash; statuso pasikeitimų;</li>
<li>Trūksta informacijos pirkimų planuose (filtrai, pirkimų atnaujinimai, datų atnaujinimai pagal realią situaciją, pirkimų vertės ir pan.);</li>
<li>Rinkos konsultacijų vykdymas &ndash; paskelbiamų duomenų suvienodinimas, klausimų ir atsakymų vie&scaron;inimas, pakeitimų vie&scaron;inimas;</li>
<li>Atnaujinti varžymaisi tame pačiame pirkime rodomi viename puslapyje bendrame sąra&scaron;e, todėl kyla neai&scaron;kumų atskiriant atnaujintų varžymosi procedūras;</li>
<li>Pa&scaron;alinimo pagrindų nebuvimo ir kvalifikacijos duomenų pateikimas (didelės apimtys, negauna automatiniu būdu duomenys i&scaron; kt. IS);</li>
<li>Nepanaudojama pakartotinai informacija i&scaron; ankstesnių pirkimų ir patiktos informacijos;</li>
<li>Nėra sutarčių pasira&scaron;ymo, pakeitimų pasira&scaron;ymo, vykdymo kontrolės mechanizmų, turėtų būti vie&scaron;inama sutarties pabaiga.</li>
</ul>


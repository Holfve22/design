
---
title: "Laddningstid"

views:
    byline:
        region: main
        template: anax/v2/block/default
        sort: 2
        data:
            meta: 
                type: single
                route: block/byline
---
Rapport Laddningstid
=========================

Urval
-----------------------

Jag har valt att anlayser tre stycken hemsidor som jag använder daligen i mit arbete. Dessa är [mfn.se ](https://www.mfn.se/), [avanza.se](https://www.avanza.se/start) & [finansinspektionen.se](https://www.finansinspektionen.se/).

Metod
-----------------------

Till min hjälp använde jag verktyget Google PageSpeed Insights, där man kan testa hemsidors laddningshastighet. Jag använde även Chromes inbyggda verktyg "Devtools" för att se hur många resurser som laddades, hur lång laddningstiden var samt hur stor webbplatsen var. Samtliga sidor testades tre gånger och genomsnittet antecknades.

Resultat
-----------------------

[Länk till rådata](https://docs.google.com/spreadsheets/d/1WayMVYAVCT-37xGhIbgGIeqgump-pNgqe5bzdMKFSKo/edit?usp=sharing)

####1. Avanza

<img src="image/aza.PNG?w=600">

Avanzas sidor fick låga betyg från Google PageSpeed Insights på mobilen(33-62) men lyckades något bättre på desktop(75-91). Laddningshastigheten var i snitt 3,2 sekunder vilket är lite i övre kant om du frågar mig. Av sidorna jag testade så var Avanzas betydligt större än de andra och hade ett snitt på 3,4 MB. 

Google PageSpeed Insights föreslog att de skulle unvika upprepade omdirigeringar på startsida, det var den enskilt största tidsbesparingen. Bland förslagen fanns även att ta bort oanvänd CSS smat att ta bort resurser som blockerar renderingen.

####2. MFN

<img src="image/mfn.PNG?w=600">

MFN hade väldigt bra betyg både på mobil och på desktop på samtliga de testade sidorna(95-100). Laddningshastigheten var som mest på ca 850 ms vilket jag anser är väldigt bra. Sidorna var ganska små, i genomsnitt ca 0,5 MB.

Även här föreslog Google PageSpeed Insights att de skulle unvika upprepade omdirigeringar på startsidan. Övriga förslag låg runt 0,2-0,3 sekunder i besparing och inkluderade att ta bort resurser som blockerar renderingen samt att ta bort oanvänd CSS och/eller minifiera CSS.

####3. FI

<img src="image/fi.PNG?w=600">

Finansinspektionens hemsida fick realtivt höga betyg på desktop men lite sämre på mobilen. Startsidan fick betyget 51 på mobile och 91 på desktop. Förstasidan tar väldigt lång tid att ladda in, ca 12 sekunder, den är dock användbar långt innan dess. Anledningen till den långa tiden är att det ligger en youtube-video på förstasidan som tycks vara långsam. Förstasidan är också ca 6 gånger större än de övriga sidorna med sina 3,2MB.

Google PageSpeed Insights rekommenderar att byta format på bilderna till JPEG 2000, JPEG XR eller WebP för bättre komprimering. De rekommenderar även att koda bilderna mer effektivt samt att skjuta upp inläsning av bilderna som inte visas på skärmen. 

Analys
-----------------------

Det är svårt att dra några generella slutsatser från denna studie, varje sida har sina egna problem bortsett från MFN som tycks fungera mer eller mindre felfritt. Både Avanza och Finansinspektionen har sämre betyg på mobilen än på desktop, även MFN har något sämre betyg på mobilen även om de fortfarande har väldigt höga betyg där också.

Den största förbättringspotentialen har finansinspektionen som uppenbart har problem med sina bilder, de tre första förslagen från Google PageSpeed Insights var gällande bilderna. Då hemsidan har så pass lång laddningstid bör de ha mycket att vinna på att göra något åt detta problem. 


Utifrån resultatet skulle jag rangordna hemsidorna enligt följande:

1. MFN
2. Avanza
3. Finansinspektionen


MFN har fina betyg över hela linjen och känns väldigt snabb och responsiv. Det är visserligen en ganska basic hemsida med få funktioner men man har gjort en bra jobb med snabbheten. Även om Finansinspektionen hade något bättre betyg i snitt än Avanza så tycker jag att Avanza har gjort ett bättre jobb givet att det finns så många fler funktioner på deras hemsida jämfört med FI.

I min mening så är ca 2 sekunder en acceptabel laddningstid för en hemsida även om jag uppskattar när det går betydligt snabbare än så. MFN klarar gärnsen med råge, Avanza ligger strax ovanför detta med ca 3,2 sekunder i snitt. Finansinspektionen har ett snitt om 4,5 sekunder men det tycker jag inte är riktigt rättvist då förstasidan som nämnt har en youtube-video som sänker resultatet. Efter ca 2 sekunder är sidan användbar vilket får anses okej.


Referenser
-----------------------

Analyserade hemsidor:

[avanza.se](https://www.avanza.se/start)

[mfn.se ](https://www.mfn.se/)

[finansinspektionen.se](https://www.finansinspektionen.se/)



Övrigt
-----------------------

Jag har gjort denna rapport ensam.
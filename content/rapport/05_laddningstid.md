---
---
Rapport laddningstid
=========================

Utvärdering av webbplatsers laddningstid och användbarhet för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

De webbplatser jag har valt att undersöka är tre webbplatser som som säljer biljetter till event: www.ticketmaster.se, www.eventbrite.com och www.billetto.se

Urvalet gjorde jag genom att välja ut två webbplatser som jag kände till sedan innan och den tredje googlade jag mig till. Syftet var att ha webbplatser som hade en funktion där de inte bara visade evenemang som är aktuella utan också hade biljettförsäljning.


Metod
-----------------------

För att utföra undersökningen använder jag mig av verktyget PageSpeed Insights för att mäta webbplatsernas laddningstid. Syftet är att mäta både mobile och desktop.

Därefter använder jag Devtools Networks för se hur lång tid det tar att ladda en sida, vad den väger och totala storleken på bilder. Detta utfördes tre gånger för varje webbplats.

Resultat
-----------------------

Resultaten från studien redovisas i ett separat excelark. Du hittar det på [Google Kalkylark](https://docs.google.com/spreadsheets/d/1tUbyH7RE2uSuCfASJ6jytmX8qUqNJ0SGrvouLbswnTY/edit?usp=sharing)

**PageSpeed Insights**

Utifrån det genomsnittliga resultatet från studien visar det att alla webbplatser hade en snabb eller genomsnittlig hastighet när det kom till "desktop" medan alla tre webbplatser uppvisade ett sämre resultat när det kom till "mobil". Där låg alla tre webbplatser på genomsnittlig eller långsam.  

**Devtools Networks**

När jag använde Devtools Networks blev det ett varierat resultat utifrån de tre mätningarna som gjordes på varje webbplats. Eventbrite.com har en slider som gör att den totala laddningstiden blir upp till ca 36 sekunder, men om den inte räknas med blir laddningstiden runt 2,5 sekunder. Billetto.se uppvisade en avvikande mätning första gången där sidan laddas under en sekund och där sidan var 3,21 MB i jämförelse med 14 MB de två andra tillfällena. Jag väljer ändå att ha med denna avvikelse.




Billetto
-----------------------

[FIGURE src=image/billetto.jpg?w=600]


Billetto är en plattform där arrangörer av exempelvis föredrag, teater och konserter kan lägga upp evenemang och sälja biljetter och hanterar betalningen online.

[billetto.se](https://billetto.se)

**Genomsnittlig resultat**

PageSpeedInsight:

Mobil: 30
Desktop: 86

Devtools networks:

Ladda sidan: 2,6 s
Sidan väger: 10 MB
Bilder: 2,6 MB


**Förbättringsförslag**

Skjut upp inläsningen av bilder som inte visas på skärmen.
Ta bort resurser som blockerar renderingen


Eventbrite
-----------------------

[FIGURE src=image/eventbrite.jpg?w=600]

Eventbrite är en global plattform där vem som helst kan skapa och marknadsföra sina evenemang.

[eventbrite.com](https://www.eventbrite.com/)


**Genomsnittlig resultat**

PageSpeedInsight:

Mobil: 52
Desktop: 96

Devtools networks:

Ladda sidan: 2,5 s + slider blir 36 s
Sidan väger: 8,2 MB
Bilder: 1,57 MB

**Förbättringsförslag**

Om filerna cachelagras under längre tid kan upprepade besök på sidan gå snabbare.
Minska tiden det tar att tolka, kompilera och köra JS-kod.



Ticketmaster
-----------------------

[FIGURE src=image/ticketmaster.jpg?w=600]

Ticketmaster, tidigare Ticnet, är Sveriges och Nordens största marknadsplats för evenemang inom sport, kultur, musik & nöje.

[ticketmaster.se](https://www.ticketmaster.se/)

**Genomsnittlig resultat**

PageSpeedInsight:

Mobil: 54
Desktop: 100

Devtools networks:

Ladda sidan: 1,8 s
Sidan väger: 3,74 MB
Bilder: 2,5 MB

**Förbättringsförslag**
Om filerna cachelagras under längre tid kan upprepade besök på sidan gå snabbare.
Använd funktionen font-display i CSS så att texten är synlig för användaren medan webbteckensnitten läses in.

Analys
-----------------------

Vid en första anblick så tycker jag som användare att alla tre webbplatser fungerar bra utifrån laddningshastighet när jag besöker sajterna via min dator och på mobilen.

Eventbrite har i desktop-format en slider som tar ca 30 sekunder att ladda ner totalt men den visas inte när jag går in på mobilen.

Billetto har den tyngsta sidan men det är inte något jag märker av när jag klickar runt bland innehållet. I mobil så har Billetto sämst resultat och de skulle kunna förbättra sajten genom att skjuta upp inläsningen av bilder som inte visas på skärmen.

Av tre tre webbplatserna så utser jag Ticketmaster till vinnaren. Den fick högsta resultatet med PageSpeed Insight när det kommer till desktop och det var det minst tunga sidan. Det är möjligt att de skulle kunna förbättra bilderna en aning. Nummer två väljer jag Eventbrite. Den hade en slider på första sidan som gjorde att laddningstiden blev totalt 30 sek, men det är inget jag lägger större tyngdpunkt kring. Fast jag tycker att webbplatser behöver inte ha sliders. På tredje plats kommer slutligen Billetto. Den hade den tynga sidan med 14 MB och tog längst tid att ladda.

Alla tre webbplatserna fick sämre resultat när det kom till mobil, men inget som jag tyckte påverkade min upplevelse när jag klickade runt med min mobil.

Jag skulle nog säga att gränsen för absolut laddningstid ligger någonstans mellan 5-8 sekunder. Det beror lite på hur man kan använda sajten medan allt laddas ner. Ett exempel är www.ica.se som är en webbplats jag gärna besöker för att hitta recept medan jag står i mataffären. Men jag upplever att den har blivit mycket sämre och jag besöker inte ofta den sajten via mobilen då jag blir frustrerad att det tar för lång tid för att den ska visa de recept jag vill se.

Referenser
-----------------------

Övrigt
-----------------------

Marie Sahlén

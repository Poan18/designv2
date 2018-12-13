---
---
Laddningstid
=======================
Denna uppgift utgår från att man ska välja ett antal olika webbplatser för att sedan testa dem genom att mäta dem. De kommer att mätas genom att undersöka sidans laddningstid och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.


Urval
-----------------------
De tre webbplatser som jag tänkte analysera blev Ninjacasino, Casinostugan och Vikingslots. Valet av webbplatser kom från att jag använde samma sidor till min föregående rapport om färger. Nu när jag redan har en liten uppfattning om webbplatsernas färger så kände jag att det skulle vara intressant att fortsätta analysera dem för att även se hur bra deras laddningstider är.

**Mitt urval av webbplatser är:**

_<a href="https://www.ninjacasino.com/" target="_blank">Ninjacasino</a>  
<a href="https://www.casinostugan.com/casino/#!start" target="_blank">Casinostugan</a>  
<a href="https://sv.vikingslots.com/" target="_blank">Vikingslots</a>_
<!-- _[Ninjacasino](https://www.ninjacasino.com/)  
[Casinostugan](https://www.casinostugan.com/casino/#!start)  
[Vikingslots](https://sv.vikingslots.com/)_ -->

Metod
-----------------------
Under mitt genomförande kommer jag att använda mig ett antal verktyg för att undersöka laddningstiderna. Det första verktyget är googles egna analysering webbsida vid namn <a href="https://developers.google.com/speed/pagespeed/insights/" target="_blank">PageSpeed Insights.</a> Det är en webbsida som analyserar en webbsidas laddningstid på både mobila enheter och datorer. Den ger ett betyg på vardera sida och tar även upp olika ting som kan förbättras för att minska laddningstiden.

Google Chromes inbyggda <a href="https://developers.google.com/web/tools/chrome-devtools/" target="_blank">devtools</a> för nätverk kommer även användas för att få fram specifika detaljer om sidan som till exempel laddningstid och antalet "requests." Detta test genomförs tre gånger per sida för att få ett mer exakt svar då resultaten kan variera mellan varje "refresh" av webbsidan. Resultaten kommer sedan hitta ett medelvärde bland alla tre testerna.

För att lagra all information som samlas in kommer Google Egna <a href="https://docs.google.com/spreadsheets/d/1vgcx34BvXQpDZrD2XzEysmeOWxFma6Ne4F2C7lEnSfU/edit?usp=sharing" target="_blank">kalkylark</a> användas för att lätt samla in information och även automatiskt räkna ut medelvärdet med enkla funktioner.

Sist används även tillägget “Full Page Screen Capture” för att ta bilder av webbsidorna. Det är svårt att få att med hela sida på en vanlig skärmbild. Med detta tillägg kommer hela sidan på bild även om den är längre än min egna skärm.

Resultat
-----------------------

<a href="https://docs.google.com/spreadsheets/d/1vgcx34BvXQpDZrD2XzEysmeOWxFma6Ne4F2C7lEnSfU/edit?usp=sharing" target="_blank">Kalkylark med alla detaljer och resultat.</a>

##### Ninjacasino

<a href="../img/ninjacasino.png" target="_blank">
    ![Ninjacasino snapshot](image/ninjacasino.png&w=1000&height=500&area=0,0,60,0&crop-to-fit "Ninjacasino snapshot")
</a>  

Ninjacasino var min favoritsida från förra rapporten. Sidan såg snygg modern och vem gillar inte ninjor? Ännu en gång blir jag glad när jag undersöker sidan. Enligt SpeedPage får desktop-versionen betyget 100 på alla sidor, och sedan även betyget 90 på alla mobila sidor. Man märker att skaparna av webbplatsen är mycket kunniga inom både färghantering och optimering av laddningstiden. Det finns inte många ställen att förbättra med den största förbättringen sidan kan genomföra är att ta bort resurser som blockerar renderingen, då man kan spara cirka 0.4 sekunder på datorer och 2.1 sekunder på mobila enheter.

##### Casinostugan

<a href="../img/casinostugan.png" target="_blank">
    ![Casinostugan snapshot](image/casinostugan.png&w=1000&height=500&area=0,0,60,0&crop-to-fit "Casinostugan snapshot")
</a>

Casinostugan är mysig att besöka men man märker fort att prestandan kan förbättras. Datorversionen av startsidan fick betyget 75 medans mobila versionen fick betyget 57. Detta var dock den enda mobila sida som fick la sig inom "genomsnittlig hastighet" då andra tester på mobila sidor betygen 34 och 37, vilket är en mycket långsam hastighet. Några förbättringar är att använda bilder i moderna bildformat, skjut upp CSS som inte används och att undvika upprepande omdirigeringar, då detta var den största boven som de mobila sidorna fall för.


##### Vikingslots

<a href="../img/vikingslots.png" target="_blank">
    ![Vikingslots snapshot](image/vikingslots.png&w=1000&height=500&area=0,0,76,0&crop-to-fit "Vikingslots snapshot")
</a>

Vikingar är snabba och mäktiga, men följer sidan dessa spår? Startsidan börjar med ett högt betyg till datorsidan där man ges en 99, dock faller man direkt ner då den mobila varianten får endast 57.Det finns en hel del förbättringar som man kan genomföra men två av dem är att läsa in viktiga resurser i förväg och att även skjuta upp inläsningen av bilder som inte visas på skärmen.


Analys
-----------------------

Alla sidorna har samma syfte, att locka besökare för att spela på deras casinospel. Alla sidorna har även felaktiga saker gemensamt. SpeedPage tog alltid upp att alla sidorna kan förbättra sig genom att ta bort resurser som blockerar renderingen. Dator-versionen av alla sidorna var helt ok och det var inget mer som alla tre hade gemensamt där. Man märker att Ninjacasino är den större fisken i denna uppgift då det finns inget mer som SpeedPage riktigt klagar på. Casinostugan och Vikingslots har dock en hel del saker som de kan förbättra på sin mobila sida. Två förbättringar som båda kan använda sig av är att skjuta upp CSS som inte används och sedan att använda bilder i modernare format. Alla dessa ändringar skulle påverka sidorna på ett positivt sätt genom att förminska laddningstiden och därmed förbättra användningen av webbsidorna.

Enligt mig får webbsidor dessa placeringar:

| Plats     | Webbsida     |
| ----------|:------------:|
| 1         | Ninjacasino  |
| 2         | Casinostugan |
| 3         | Vikingslots  |

Genom alla dessa testar inser jag att det finns en stor skillnad på laddningstiderna mellan olika sidor. Enligt mig är Ninjacasino med sin 1.5-3 sekunder laddningstid en sida som laddar snabbt. Sidan laddar direkt och är allmänt bekväm att använda, det finns inte mycket negativt att säga då det känns som att skaparna vet vad de sysslar med. Vikingslots åt andra sidan kan ta uppåt 10 sekunder och det verkar som att de vet om detta problem då de har en dedikerad "laddningskärm" när man väl anländer till webbsidan, man har inte möjlighet till att se innehållet när denna laddningsskärm blockerar skärmen. När den väl försvinner renderas fortfarande bilder vilket får sidan att kännas mycket slö. Även casinostugan tar rätt lång tid på sig att ladda till fullo men man får möjlighet att använda sidan även när den laddar. En snabb sida enligt mig ligger då runt cirka 2-3 sekunder medans en mer långsam sida ligger över 5 sekunder.

Referenser
-----------------------

<a href="https://www.ninjacasino.com/" target="_blank">Ninjacasino</a>  
<a href="https://www.casinostugan.com/casino/#!start" target="_blank">Casinostugan</a>  
<a href="https://sv.vikingslots.com/" target="_blank">Vikingslots</a>  
<a href="https://developers.google.com/speed/pagespeed/insights/" target="_blank">PageSpeed Insights.</a>

Övrigt
-----------------------

_Skriven och utförd av: Pontus Andersson_


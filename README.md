# systemutveckling-vecka2
Vecka2 - Inlämningsuppgift2

## 1. **Beskriv skillnaden mellan vattenfallsmodellen och agil metodik.**
I förra veckans övningsuppgift liknade jag frågan vid en middagsbjudning. För att inte vara tråkig tänkte jag prova något annat denna veckan. 😛🤘

### Vattenfallsmetoden
Vattenfallsmetoden kan liknas vid en väg som bara har en fil. Bilarna kör efter varandra, tryggt och fint och allt flyter på bra. Dock tar det ganska lång tid innan alla 12´000 bilar har passerat. Om det skulle hända något, någon olycka eller liknande så stannar hela kön upp och *ingen* bil kommer fram förens olyckan är uppstädad och vägen fri igen. 
Om någon bil vill ansluta till vägen så blir alla bilar bakom drabbade och ledtiden blir genast längre. (Litet utrymme för flexibilitet)
Fördelen är att alla bilar kommer fram i tur och ordning och det blir egentligen ingen oreda. Samtliga bilar gås igenom på parkeringen när alla bilar har anlänt. (Testning av färdig produkt) Om en bil inte skulle vara godkänd så skickas den tillbaka. 

### Agil metodik
Agila metoden, med samma analogi skulle vara en väg med 12 filer. Plötsligt flyter trafiken på 12 gånger snabbare. Om det sker en olycka i en fil så stannar DEN filen upp, men de övriga 11 flyter på bra. Om någon bil vill ansluta till motorvägen, så är det inga problem. Den filen som bilen ansluter till kanske går lite långsammare, men övriga 11 filer flyter på bra. (Hög flexibilitet) Alla bilar testas innan dom tillåts parkera på parkeringen. (Varje modul testas innan leverans)

### Slutsats
I analogin är en bil en "ticket" eller en funktion som man arbetar med i sitt team. 
Vägen (filerna) representerar olika utvecklare, team eller utvecklingsprcesser. 
I vattenfallsmetoden har man bara en fil (på vägen) vilket gör att utveklingsprocessen blir linjär. En sak i taget helt enkelt. Slutprodukten testas genomgående. 
I agil metodik har man flera filer och flera arbetsmoment kan slutföras parallellt. Varje modul testas innan den levereras.

### När bör man använda vilken och varför? 
När ett projekt behöver utrymme för flexibilitet så skall man utan tvekan välja agila metoden. Då kan tickets läggas till och lösas utan konstigheter. Man behöver även ha med i beräkningen att detta kan leda till att projektet drar ut på tiden eller att man behöver fler utvecklare än vad som var tänkt, vilket resulterar i en högre kostnad. Agila metoden kan även med fördel användas vid projekt där man kanske inte har en färdig lösning i planeringen utan man väljer en trial-and-error-baserad approach. Utveckla -> Testa -> Repeat. Kunden är med fördel delaktig i utvecklingsprocessen för att ge feedback på UX/UI och hur dom vill att *flödet* skall vara m.m. 
Ju större ett team är, desto mer angeläget är det att använda en agil metod. (Så inte 30 pers beböhver vänta på att en feature ska bli färdig innan dom kan fortsätta)

Om man däremot jobbar för en kund som har begränsad budget för projektet och kunden vet exakt vad denne vill ha, då kan man absolut hålla sig till vattenfallsmetoden. Denna linjära metod är mer förusägningsbar och planerbar gällande tidsaspekten (och därmed även kostanden). Vattenfallsmetoden ger inte så mycket utrymme för flexibilitet och kan därför väljas när kunden inte kan eller vill vara delaktig i utvecklingsarbetet. Detta kräver givetvis en *extremt* tydlig kravspec. Givetvis kan man göra ändringar när projektet når testfasen, varvid buggar rapporteras tillbaka till utvecklarna som då rättar till dessa och skickar tillbaka till testarna. När projektet väl är lanserat så finns det såklart utrymme för uppdateringar, men det är betydligt tyngre att rodda i ett vattenfalls-projekt jämfört med ett agilt projekt. 
Ju mindre ett team är, desto mer angeläget är det att använda en vattenfallsmetod. (Om man är en ensam utvecklare så blir det mer eller mindre vattenfallsmetod hur man än ser på det)

### Reflektion och exempel
Jag skulle föredra att arbeta enligt den agila metoden. Projektet blir inte lika känsligt för oväntade hinder och det finns goda möjligheter till flexibilitet. 

***Exempel på vattenfall***: När spelet Cyberpunk 2077 lanserades, efter flera år av utveckling tog det världen med storm. Grafiken var fantastisk och spelvärlden var enorm. Men spelet var FULLT av buggar. Det är egentligen först nu, efter många år av användarfeedback som spelet faktiskt börjar närma sig ett stadie som kan kallas "färdigt", även om det redan ifrån början lanserades som en färdig produkt.

***Exempel på agilt***: Om vi istället jämför med spelet Star Citizen, som har vait under utveckling sedan 2011, i 14 år (extremt exempel). Där lanserades teknisk alpha 0.0.0.1 för allmänheten med *enbart* möjligheten att gå omkring i sitt hangar och titta på sitt rymskepp. Man kunde gå in i skeppet och sätta sig bakom spakarna. - Men inget mer. Användarfeedback strömmade in och buggar togs om hand. Sen lanserades nästa modul. Då kunde man lämna hangaret med sitt ryndskepp och flyga runt ryndstationen. Användarfeedback strömmade in och buggar togs om hand. Sen lanserades nästa modul. Då kunde man flyga till en planet och landa på ytan. Användarfeedback strömmade in och buggar togs om hand. Iterationerna fortsätter och nya moduler utvecklas än idag. Utvecklarna anpassar hela tiden varje enskilld modul utefter användarfeedback.

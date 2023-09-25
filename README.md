# Min README

## inlämning 1

### Mitt repo
Inför inlämning 1 laddade jag ner koden enligt instruktioner och gjorde ett [Github repo](https://github.com/Hampe024/Traincontroller).

### npm audit
`npm audit` gav några fel men alla fixades med hjälp av `npm audit fix`.

### Api nyckel
När jag försökte starta applikationens backend fick jag felmeddelanden angående resultatet av en fetch i `backend/models/trains.js`. efter lite felsökning med `console.log` kom jag fram till att felet var att det jag fick tillbaka från fetchen endast var ett felmeddelande som klagade på att min API nyckel inte fungerade. Detta för att API nyckeln ska hämtas från .env filen men den filen fanns inte. Jag gjorde därför en .env fil och i den la jag en api nyckel som jag fick från [Trafikverkets hemsida](https://api.trafikinfo.trafikverket.se) och efter det fungerade det.

### Frontend ramverk
Jag har valt att använda mig utav React. Detta för att jag har lite kunskap av det från webapp kursen där vi använde React native. Det är också vad jag har förstått det störta/vanligaste av dessa ramverk och därför större sannolikhet att jag kommer få användning av det senare.

### Github flow
Då jag börjar med denna kursen sent kommer jag att arbeta själv. Jag kommer därför inte använda mig av Github flow i någon större utsträckning. Men jag och min grupp använde det mycket i vteam kursen förra året så jag känner mig redan familiär med det.
En jämförande rapport av tre kommuners laddningstid.
=======================

Jag kommer i denna rapport jämför hur snabbt tre kommuners hemsidor laddas och om det finns några förbättringsmöjligheter med tanke på användarbarhet och laddningstid.

Urval
-----------------------

Jag har valt att analysera tre kommuners hemsidor. De hemsidor jag har valt är från de kommuner där jag tidigare bott. Urvalsmässigt är det också tre kommuner av olika storlek.

De sidor som ska analyseras är:
Örebro, https://www.orebro.se/
Västerås, https://www.vasteras.se/
Göteborg, https://goteborg.se

Metod
-----------------------

Jag kommer analysera kommunernas laddningstid och titta på följande aspekter av sidan:
För 3 olika sidor hos respektive kommun kommer jag mäta laddningstider för Mobile och Desktop med hjälp av Google Pagespeed
Varje sida kommer dessutom devtools flik networks att användas för att notera laddningstid, antalet resurser och sidans totala storlek.

Resultat
-----------------------

<b>Göteborg</b>

![Göteborg](../htdocs/img/goteborg.png)


<b>Pagespeed Insight:</b>
För mobile låg resultatet på 50-61

För desktop var resultatet på 96-100

<b>Devtools Network(snitt av tre besök):</b>
Laddningstid för de olika sidorna varierande mellan 1.2 s till 1.4 s.
Antalet resurser låg på 35-37.
Total storlek varierade mellan 334 kb till 597 kb.

Sidan är väl anpassad för desktop men dåligt anpassad för mobil.
Förslag till förbättrat resultat genom följande:
1. Ta bort resurser som blockerar rendering
2. Skicka bilder i modernare format
3. Undvik upprepade omdirigeringar


<b>Örebro</b>

![Örebro](../htdocs/img/orebro.png)


<b>Pagespeed Insight:</b>
För mobile låg resultatet på 43-44

För desktop var resultatet 99

<b>Devtools Network(snitt av tre besök):</b>
Laddningstid för de olika sidorna varierande mellan 1.2 s till 1.6 s.
Antalet resurser låg på 41.
Total storlek varierade mellan 320 kb till 357 kb.

Sidan är väl anpassad för desktop men dåligt anpassad för mobil.
Förslag till förbättrat resultat genom följande:
1. Ta bort resurser som blockerar rendering
2. Skjut upp CSS som inte används

<b>Västerås</b>


![Västerås](../htdocs/img/vasteras.png)


<b>Pagespeed Insight:</b>
För mobile låg resultatet på 15-16

För desktop var resultatet 94-96

<b>Devtools Network(snitt av tre besök):</b>
Laddningstid för de olika sidorna varierande mellan 1.6 s till 1.8 s.
Antalet resurser låg på 89-90.
Total storlek varierade mellan 734 kb till 1000 kb.

Sidan är väl anpassad för desktop men dåligt anpassad för mobil.
Förslag till förbättrat resultat genom följande:
1. Ta bort resurser som blockerar rendering
2. Skicka bilder i modernare format
3. Skjut upp CSS som inte används


Analys
-----------------------
Om man ska sammanfatta analysen av kommunernas hemsida är det att de är dåliga till extremt dåliga på att anpassa sidorna för mobil användning. En snabb laddningstid bör ligga runt 1 sekund. Kan med detta som utgångspunkt konstatera att ingen av sidorna klarade av detta. Rent generellt var sidorna långsamma.

Den sida som var minst dålig i mitt test var Göteborg kommuns då de hade lägst övre laddningstid på sina sidor. Samtidigt var Örebros sida inte långt efter.

Det som alla sidor skulle behöva förbättra är att ta bort resurser som blockerar rendering, där det i övrigt varierade lite vad som var rimlig förbättringsåtgärd.

Referenser
-----------------------

Örebro, https://www.orebro.se/
Västerås, https://www.vasteras.se/
Göteborg, https://goteborg.se
Pagespeed Insights, https://developers.google.com/speed/pagespeed/insights/
Resultat mätningar, https://docs.google.com/spreadsheets/d/1B7IgYLxnuwfPP618ZcmHxH1dt9I5ZznM4iiOxF3V4wo/edit?usp=sharing

Övrigt
-----------------------
Jag har gjort rapporten på egen hand utan några andra gruppmedlemmar.

Andreas Wahlstedt

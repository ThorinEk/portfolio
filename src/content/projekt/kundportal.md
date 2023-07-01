---
title: Albia kundportal
publishDate: 2020-09-05 00:00:00
img: /assets/kundportal.png
img_alt: Screenshot from QMap warehouse management interactive graphic prototype
description: |
  Jag har under några års tid utvecklat och underhållt Albias kundportal vilken används för att låta kunder kunna se orderhistorik, fakturor, teknisk utrustning som köpts in via Albia samt hantera domännamn.
tags:
  - API
  - PHP
  - Symfony
---

## Mål

Kundportalen hos Albia är ett initiativ som startade nästan omedelbart efter att företaget grundades i mitten av 2020, strax efter att jag och min kollega Erik tog studenten från gymnasiet. Kundportalen är främst utformad för att visa data från olika tjänster som Albia och dess kunder använder. Vi använder oss av flera olika API:er för detta ändamål, inklusive Fortnox API, som jag har stor erfarenhet av att arbeta med, samt NameSRS API för domännamn. Vi planerar att integrera ännu fler tjänster framöver.

## Mentorskap

Under kundportalens utvecklingsprocess har Albia tagit emot två praktikanter som haft huvudansvaret för att utveckla kundportalen. Detta passade utmärkt då det rör sig om ett internt projekt. Genom detta har jag fått möjlighet att samla erfarenhet av att introducera och handleda praktikanter inom systemutveckling, från både högskola och yrkeshögskola.

## Teknologi

När jag började skapa kundportalen 2020, var mina tekniska kunskaper fortfarande ganska begränsade. Därför valde jag att utveckla kundportalen i ren PHP, utan att använda något ramverk för varken frontend eller backend. Detta kan i efterhand betraktas som ett misstag, men då var det ett naturligt val eftersom jag ännu inte fullt ut förstod funktionen och värdet av ramverk som Angular och React. Vid skrivandets stund, tre år senare, har jag dock arbetat mycket med ramverk som Angular och upptäckt hur kraftfulla de kan vara.

Med facit i hand, kan jag konstatera att det skulle ha varit mycket fördelaktigt att använda ett ramverk för kundportalen, eftersom det bidrar till att öka utvecklingstakten, förbättra stabiliteten och säkerheten i applikationen, samt leda till en standardiserad kodstruktur som är enklare för andra utvecklare att sätta sig in i.

I brist på ett initialt ramverk, utvecklades gradvis ett eget ramverk. Enskilda komponenter har dock hämtats in från befintliga PHP-ramverk, som Symfony. Till exempel använder vi Symfonys "view templating engine" i kundportalen, och vi har planer på att integrera fler komponenter i framtiden. 

Trots frånvaron av ett väletablerat ramverk, har kundportalen uppnått en stabil och samtidigt flexibel grundstruktur, mycket tack vare användningen av en trelagersarkitektur och andra "best practices". Slutligen bör det påpekas att valet av PHP kanske inte var optimalt, med tanke på den utveckling som skett inom andra programmeringsspråk. Men, trots detta har PHP uppdaterats med fler objektorienterade funktioner. Och slutligen, det är inte programmeringsspråket som är mest avgörande, det är den som skriver koden! 
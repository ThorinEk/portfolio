---
title: Examensarbete
publishDate: 2023-06-29 00:00:00
img: /assets/Examensarbete.webp
img_alt: Gustav Persson 
description: |
  Jag skrev examensarbete tillsammans med min studiekamrat William Branth. Vi utvecklade en innovativ lösning för att motverka cold start-fördröjningar i mjukvaror byggda med serverless functions.
tags:
  - Serverless
  - Research
  - Cloud Services
---

## Mitigating Serverless Cold Starts Through Predicting Computational Resource Demand

Ovanstående är titeln på mitt examensarbete. Vi valde denna titel med anledning av vårt fokus som låg på att förebygga och minska fördröjningen hos interaktiva system som en följd av "cold starts". Examensarbetet är publicerat i Digitala Vetenskapliga Arkivet (DiVA portal) och tillgängligt [här](https://urn.kb.se/resolve?urn=urn%3Anbn%3Ase%3Ahj%3Adiva-61983).

### Samarbetsföretag

Vi hade förmånen att få skriva examensarbetet med hjälp av Knowit. Vi hade tillgång till expertisen hos en av Knowits mycket kompetenta och erfarna utvecklare som bidrog till att avsevärt höja nivån på vårt arbete.

### Serverless functions

Serverless-functions är ett koncept som tillåter utvecklare att köra kod utan att behöva hantera underliggande infrastruktur. Utvecklaren skapar och laddar upp koden, medan serverless-plattformar (som AWS Lambda, Google Cloud  eller Azure) sköter drift, skalning, back-ups och säkerhet. Den primära fördelen med denna metod är att du bara betalar för den tid din kod faktiskt körs, vilket kan leda till betydande kostnadsbesparingar. 

Däremot finns det en utmaning med serverless, kallad "cold starts", vilket händer när en funktion körs för första gången eller efter en period av inaktivitet, vilket kan orsaka en fördröjning i svarstiden. Rent konkret kan detta innebära att det tar 5 sekunder innan något händer efter att du tryckt på en knapp på en webbplats, istället för kanske bara några millisekunder som det ofta tar utan en kallstart. Kallstarter är ett ämne som kring vilket omfattande vetenskaplig forskning bedrivs.

### Vår lösning

Tidigare forskningsinsatser kring problemet med kallstarter för serverless functions har främst centrerats kring analys av historisk användningsdata. Vi valde dock en annan väg och undersökte potentialen att analysera realtidsdata istället. Vi utvecklade en mjukvaruartefakt, som vi döpte till Adaptive Serverless Invocation Predictor (ASIP), och kunde genom detta identifiera flera viktiga komponenter och förutsättningar som krävs för att kunna förutse behovet av serverless functions, vilket i sin tur hjälper till att förebygga kallstarter.

#### Slutsats

Vi kunde konstatera att vår lösning medförde en betydande minskning av kallstartsdröjsmålet. Dessutom lyckades vi identifiera en rad möjliga förbättringar som kan öka kostnadseffektiviteten hos vår utvecklade mjukvara, ASIP. Detta examensarbete har lett till att jag fördjupat mina kunskaper inom området serverless functions, och jag ser fram emot möjligheten att utveckla fler lösningar baserade på detta framväxande område i framtiden.

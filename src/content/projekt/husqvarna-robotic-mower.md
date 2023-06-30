---
title: Husqvarna Robotgräsklippare
publishDate: 2023-06-01 00:00:00
img: /assets/robot-mower-system.webp
img_alt: AI-genererad bild föreställande ett intelligent mobilt system centrerat kring en robotgräsklippare
description: |
  Jag var med och utvecklade ett intelligent mobilt system som motsvarade Husqvarnas robotgräsklippare samt tillhörande mobilapplikation och backend.
tags:
  - Embedded systems
  - Mobile
  - Backend
---

Mitt slutprojekt under utbildningen, som löpte parallellt med examensarbetet, involverade att jag deltog i ett fascinerande projekt med målet att skapa ett intelligent mobilt system för robotgräsklippare, liknande det som Husqvarna AB tillhandahåller. Projektet utfördes inom ramen för kursen "Intelligenta Mobila System", vilken samordnades i samarbete med Husqvarna AB.

I mitt team av åtta personer fick vi uppgiften att bygga en lösning kring en Arduino Mbot, en liten robot konstruerad specifikt för utbildningssyften. Trots att den inte kan jämföras med en fullfjädrad robotgräsklippare från Husqvarna, fungerade den perfekt för detta tidsbegränsade projekt genom att erbjuda oss en praktisk modell att utveckla lösningen för.

I detta projekt ägnade jag mig främst åt att arbeta med backend, vilket överensstämmer med mitt primära intresse och det område jag har mest erfarenhet av, även om jag uppskattar variationen i att också få jobba med frontend ibland.

Backenden jag utvecklade var avsedd att hantera och lagra navigationsdata från roboten för att i realtid kunna visualisera dess position samt visa tidigare körningar. Dessutom behövde backenden kunna ta emot bilder av hinder som roboten upptäckte och undvek, och sedan vidarebefordra dessa bilder för klassificering av Google Vision AI. Bildklassificering innebar att en AI-algoritm identifierade objekten i bilderna och returnerade denna data, till exempel "läskburk". Detta var oerhört spännande och belyste potentialen att utnyttja denna typ av AI-lösningar.

Utöver mig var två andra studiekamrater ansvariga för backenden, tre arbetade med mobilapplikationen och två från det parallella programmet "Inbyggda system" programmerade roboten. Samarbetet i en så stor grupp var en utmaning men fungerade mycket väl, och vi lyckades framställa en väl fungerande slutprodukt som vi kunde demonstrera på plats hos Husqvarna.
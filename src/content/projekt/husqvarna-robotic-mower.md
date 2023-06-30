---
title: Husqvarna Robotgräsklippare
publishDate: 2023-06-01 00:00:00
img: /assets/robotic-mower.webp
img_alt: AI-genererad bild föreställande ett intelligent mobilt system centrerat kring en robotgräsklippare
description: |
  Jag var med och utvecklade ett intelligent mobilt system som motsvarade Husqvarnas robotgräsklippare samt tillhörande mobilapplikation och backend.
tags:
  - Embedded systems
  - Mobile
  - Backend
---

Som slutprojekt på min utbildning, parallellt med examensarbetet, deltog jag i ett mycket intressant projekt där målet var ett intelligent mobilt system för robotgräsklippare, likt det som erbjuds av Husqvarna AB. Kursen hette Intelligenta Mobila System och bedrevs i samarbete med Husqvarna AB.

Jag ingick i ett team av åtta personer som fick uppgiften att bygga en lösning kring en Arduino Mbot vilket är en liten robot avsedd just för användning i utbildningssammanhang. Medan denna emmellertid inte kan jämföras med en riktig robotgräsklippare från Husqvarna, var den perfekt för detta tidsbegränsade projekt där den möjliggjorde utveckling gentemot den. 

Inom detta projektet arbetade jag huvudsakligen med backenden eftersom jag insett att det är där jag har mitt största intresse och det är det området jag fördjupat mig mest inom, även om jag uppskattar variationen i att även få jobba med frontend ibland. 

Syftet med backenden som jag utvecklade var att hantera och lagra navigeringsdata från robot för att i realtid kunna se var denna befinner sig men också se tidigare körningar. Vidare behövde backenden även kunna ta emot bilder som roboten laddade upp föreställande hinder den upptäckt och undvikit, dessa bilder skulle sedan skickas vidare för klassicifering av Google Vision AI. Bildklassificering innebär i detta fall att en AI-algoritm identiferar motivet på bilden och skickar tillbaka denna data, exempelvis "Läskburk". Detta var förstås mycket intressant och öppnade ögonen för möjligheten att utnyttja den typen av AI-lösningar, utöver revolutionerande AI-lösningar såsom ChatGPT, lanserade kort innan kursens start.

I gruppen fanns även två ytterligare studiekamrater som arbetade med backenden, tre som arbetade med mobilapplikationen och två från det parallella programmet *Inbyggda system* som programmerade själva roboten. Som kunde förväntas var samarbete i en sådan stor grupp utmanande men fungerade trots det mycket väl och vi fick till en välfungerande slutprodukt som kunde demononstreras på plats hos Husqvarna.
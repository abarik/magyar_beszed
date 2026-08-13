---
date: "2021-01-23"
draft: false
title: "Fonetikai adatbázis"
job_nature: ""
category: "Fonetikai paraméterek halmaza beszédszintézishez"
---

**Fonetikai adatokkal megadott beszédadatbázis elemek bemutatása**


A fonetikai adatokból álló adatbázis hangszeleteket tartalmaz, amelyekben a hangszeletre jellemző fonetikai adatok vannak megadva. Hungarovox és Multivox magyar beszédszintetizátorokhoz használták 1982-1990-ben. 

A fonetikai adatok hangszeletenként az adatbázisban a következők:

* F1, F2, F3, F4 formáns frekvencia értéke (Hz)  
* B1, B2, B3, B4 formáns sávszélesség értéke (Hz)  
* Hangmagasság - PI paraméter és Hertz
* Hangerő (dB) - AM
* Gerjesztés (zöngés=V ; zörejes=c) 
* Időtartam= 12ms/hangszelet  - FD

Példa a "jónapot" hangsor  első szótagjához használt hangszelet sorozat összefűzésére 
(1-4 hangszelet sor=j); (5-9=j-ó hangátmenet); (10-17= ó)

 {{< image title="dallam" w="1200" o="webp q100" p="center" c="img-fluid shadow rounded-1" src="images/mb-speech-acoustics/fonetikai_adatok_tts.jpg" alt="alter-text" >}}
 

A teljes adatbázis 370 féle hangszeletet tartalmazott, amelyekkel a magyar beszéd összes hangkapcsolódását meg lehetett valósítani. Memória igénye 1 Kbyte volt. A szintetizált beszéd hangzása robotos volt, de jól érthető. 





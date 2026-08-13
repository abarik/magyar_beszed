---
title: "Mondatdallamok"
subtitle: ""
# meta description
description: "This is meta description"
draft: false
---

Az emberi beszédkeltés egyik legfontosabb eszköze a beszéddallam, amit fizikailag a gégében keletkezett hangszalag rezgés  (alaphang) frekvenciájának változtatásával hoz létre a beszélő. A beszéddallamot alapvetően háromféle formával lehet jellemezni: emelkedő, ereszkedő és lebegő (egyenletes, nem változik). E kategóriákon belül több szintet különböztetnek meg: gyengén emelkedő, emelkedő és szökő, illetve gyengén ereszkedő, ereszkedő, eső. Ezeket dallamépítő elemeknek fogjuk nevezni. A hanglejtés vizsgálatának, ismeretének, modellezésének fontos szerepe van mind a beszédfelismerésben, mind a beszédszintézisben. 
A magyarban a hanglejtésnek mondat szinten van jelentést megkülönböztető szerepe. A mondat dallammenetének egésze a mondat fajtájától és összetettségétől függ. A kijelentő mondat általános dallamformája az ereszkedő, a kérdő mondatoknál a végleges dallamforma a dallamépítő elemek legkülönfélébb kombinációjából áll elő. A mondatszintű dallamok kezdő- és végpontjai szoros összefüggésben vannak egymással a folyamatos beszédben és ezt a nyelv határozza meg. Ez az összefüggés azt jelenti, hogy az egyes mondafajták dallammenetének megvalósulási frekvenciatartománya adott hangfekvésen belül kötött, egymással összefügg. A leggyakoribb magyar mondatdallamok általános modellje alább látható. Részletesebben lásd a Magyar beszéd c. könyv 6.1.  fejezetében.


{{< image title="dallam" w="1200" o="webp q100" p="center" c="img-fluid shadow rounded-1" src="images/mb-speech-acoustics/dallam_modell_hu.png" alt="alter-text" >}}


A modell nem függ a hangfekvéstől. A kiindulási pont minden számításnál az egyszerű kijelentő mondat kezdő Hz értéke, mint referencia pont. Ez a 100%. Más mondattípusok kezdő értékeit a referencia ponthoz képest kell százalékosan meghatározni. 
Például tekintsük a 100%-os referenciapontot 110 Hz-nek (férfi hang). Egy kijelentő mondat kezdő F0 értéke 110 Hz lesz a vége pedig 77 Hz.  Egy kiegészítendő kérdés dallam menetének fizikai Hz értékei a következők lesznek: kezdőérték 130% (133 Hz), és ez a frekvencia az első szótag végéig megmarad. Az F0 a második szótagon belül meredeken 80%-ra (88Hz) csökken, innentől kezdve a kérdés végéig csökkenő forma lesz, aminek a végén az F0 végső értéke 70% (77Hz).
Összetett mondatok esetén az egyes részmondatokra kell alkalmazni a modellt.

A modellből az alábbi következtetések vonhatók le. 

1. A magyar mondatfajták kezdő dallam frekvenciája erősen különbözik egymástól.
2. A magyar mondatfajták befejezése általában ugyanazon a frekvencián van.
3. Bizonyos magyar  mondatfajták belsejében az első szótagnak és az utolsó előtti szótagnak van fontos szerepe.
4. A modell szerint kell a szöveg szintű dallamok vonulatát (több mondatét egymás után) megvalósítani (például gépi szövegfelolvasókban).


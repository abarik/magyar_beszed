---
title: "Beszédadatbázisok"
subtitle: "Különböző beszédreprezentációk adatbázisai fejlesztésekhez"
description: "dddddd"
draft: false
---

A beszédtechnológiai műszaki megoldások fejlesztéseihez elengedhetetlenül szükségesek olyan adatgyűjtemények, amelyek a beszédet valamilyen szempontból reprezentálják. Az ilyen adathalmazokat BESZÉDADATBÁZISOKnak nevezzük. A beszédadatbázisok szerkezete és nagysága szorosan összefügg  a számítógépek és a memória kapacitás fejlődésével. Az 1960-as években a beszédszintézist fonetikai adatok alapján végezték (az első magyar formáns alapú beszédszintetizátor, a HungaroVOX fonetikai elemtára mindössze 370 építőelemből állt és 1 kbyte tárterületet foglalt el). A későbbiekben olyan beszédadatbázisokat készítettek a beszéd szintéziséhez, amelyek már emberi ejtésből származó, felolvasott, de értelmetlen rövid hangsorokat tartalmaztak (logatom adatbázis). Ezek teljes mérete már pár Mbyte nagyságrendű volt. Ilyen hullámforma elemekből építette fel a beszédjelet a ProfiVox-diád és triád beszédszintetizátor. Valódi beszédet tartalmazó beszédadatbázisokat először a gépi beszédfelismeréshez készítettek, hogy az egyéni ejtések változatosságát jellemezni lehessen. Ilyen adatbázis volt a BABEL. Később a statisztikai elvű beszédszintézishez is élő beszédből készítettek beszédadatbázisokat (Profivox-HMM), amelyeket precízen annotáltak és felcímkéztek. 2010-től már sok gigabyte-os beszédadatbázisokkal dolgoznak a kutatók.   

A beszédadatbázisok tervezése és elkészítése bonyolult munka. A felolvasandó szöveg megtervezése, a hangfelvételek elkészítése és a címkézések sok időt és precíz munkát igényelnek. A gépi tanulási algoritmusok fejlődésével lehetővé vált ennek a munkának a lerövidítése, sőt felügyelet nélküli beszédadatbázisokat is készítenek már 2020-ban. 
   
Részletek: [A MAGYAR BESZÉD](download/A-magyar-beszed.pdf) c. könyv 8. fejezetében olvashatók (a 261. oldaltól).

További összefoglalók:
* http://home.sch.bme.hu/~peternac/beszed/gyak/beszedadatbazisok_gyak_2005.pdf
* http://www.nytud.hu/fonetika/FON3l.htm

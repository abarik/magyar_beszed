---
date: "2021-01-20"
draft: false
title: "Beszédadatbázisok"
job_nature: ""
category: "Általánosan"
---


**Beszédadatbázisok folyamatos beszédfelismeréshez és beszédszintézishez**

A tényleges beszédadatbázisok a korszerű gépi beszédfelismerés és beszédszintézis alapját képezik. Megvalósításaikhoz nagy memória kapacitás kell, használatukhoz gyors számítógép.  Mindkét megoldáshoz sok mondatot tartalmazó, nagy beszédadatbázisokat használnak, amelyeket annotálással és címkézéssel látnak el (kézileg vagy gépileg). Magyar nyelven számos beszédadatbázis készült, főleg a BME TMIT beszédkutató laboratóriumaiban. Gépi beszédfelismeréshez különböző szempontokat kell figyelembe venni a beszédadatbázisok tervezésénél.

 {{< image title="dallam" w="1200" o="webp q100" p="center" c="img-fluid shadow rounded-1" src="images/mb-speech-acoustics/beszadatb.png" alt="alter-text" >}}
 
  
Az első valódi beszédadatbázist többek között a gépi beszédfelismerési kutatásokhoz hozták létre. Ez volt a BABEL (1998), amit a BME TMIT kutatói készítettek Vicsi Klára vezetésével, nemzetközi szabvány alapján. Hatvan beszélő olvasott fel szövegeket . Az MTBA magyar telefonbeszéd-adatbázis (2002) vezetékes és mobiltelefonról rögzített beszédgyűjtemény volt. Ötszáz adatközlő 297 vezetékes, 203 mobiltelefonról rögzített felolvasásait tartalmazta.  Az MTA Nyelvtudományi Intézetének Fonetikai Laboratóriumában készítették el több éves munkával a BEA beszélt nyelvi általános adatbázist Gósy Mária vezetésével (2007). Ebben több száz személy beszélt spontán módon és olvasott fel szövegeket. A BEA adatbázist a BME TMIT is használta a gépi beszédfelismerési fejlesztéseknél. A SpeechTex Kft  (2013-tól) számos beszédadatbázist fejlesztett korszerű folyamatos beszédfelismerő és gépi beszédleiratozó műszaki megoldásaihoz.
  
A jó minőségű, emberi hangú beszédszintézishez készült a BME TMIT beszédtechnológiai laboratóriumában a PPBA Párhuzamos Precíziós Beszédadatbázis (2010), amelyben 12 beszélő olvasta fel ugyanazt a 2000 mondatból álló szöveget. Ezt a Profivox-HMM beszédszintetizátor tanításánál használták. Az IDŐJÁRÁS egy személyes beszédadatbázis (2013) 5000 mondatból állt és a ProfiVox-korpusz beszédszintetizátort szolgálta ki internetes szolgáltatásban. A VONAT egyszemélyes beszédadatbázis (2014-től) 12000 mondatot tartalmazott és a MÁV automatikus, hangos utastájékoztatójában működik. Ezeket a beszédszintézishez kialakított beszédadatbázisokat a későbbiekben a BME TMIT Neural ProfiVox beszédszintetizátorok tanításához is felhasználták. Ezekben már mély neurális hálózatok (DNN) működnek.
Ma, a 21. század harmadik évtizedében a beszédadatbázisoknak se szeri, se száma. Ez a memóriák ugrásszerű megnövekedése miatt van így, másrészről a gépi mélytanulás támogatja a kézi munka nélküli beszédadatbázis készítést.

További részletek: [A MAGYAR BESZÉD](download/A-magyar-beszed.pdf) c. könyv 8. fejezetében (261. oldalt) olvashatók




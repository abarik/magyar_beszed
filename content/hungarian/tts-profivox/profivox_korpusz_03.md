---
date: "2020-07-12"
draft: false
title: "ProfiVox korpusz"
description: "Profivox-korpusz, emberi hangszínezet"
icon: ""  # fontawesome icon pack : https://fontawesome.com/icons/
layout: "layout-3"


######################### banner #####################
banner_center:
  title : "ProfiVox korpusz"
  image: ""
  content : "A Profivox-korpusz szövegfelolvasó rendszer rugalmas hullámforma elemkiválasztás-alapú beszédszintézis módszert alkalmaz. Ehhez gyors számítógépre van szükség, mivel nagy a számítási igény. Az eljárásnál figyelembe veszik, hogy a beszéd a pillanat eseménye, a hanghullám folyamatosan változik. Még ugyanazon beszédhang kimondása sem adja pontosan ugyanazt a hullámformát két egymás utáni ejtésben. Ezért tekinthetjük egyéninek beszédünk hangszínezetét, ami erősen személyhez köthető. A korpusz alapú módszer jó hangminőséget biztosít, fel lehet ismerni a hang tulajdonosát. Ez annak köszönhető, hogy szavak-, vagy annál is hosszabb szöveg elemek hullámformáját kapcsolja össze, amikor a szövegből beszédet generál. Igényes helyeken használják, ahol a kifogástalan hangminőség a követelmény (például időjárás jelentés, bank, pályaudvar). Ennek a jó minőségnek az ára, hogy ez a módszer csak kötött témakörben képes ezt a jó teljesítményt szolgáltatni. A szintézis adattára emberi beszédből készített több órás beszédadatbázis. A felolvasó olyan mondatokat, kifejezéseket olvas fel, amelyek nagy valószínűséggel előfordulnak az adott témakörű szövegekben. A felolvasandó szöveget komoly, precíz munkával kell megtervezni. A hangfelvétel készítéskor a 'mester mondat'elvű eljárást kell alkalmazni. A beszédadatbázist részletesen felcímkézik. A beszédszintézist ezek után keresési algoritmusokkal végzik, ami több lépcsőben, súlyozásokkal kiválogatja a korpuszban eltárolt folyamatos beszédből a legmegfelelőbb hullámforma elemeket és azokat fűzi egymáshoz, figyelembe véve a prozódiát is. Utólagos jelfeldolgozát ez a módszer nem alkalmaz! A bonyolult válogató algoritmus futási időben  működik. Az eredmény személyhez köthető és természetes hangzású beszéd. A beszédadatbázist minden témakörhöz egyedileg kell elkészíteni."
  button:
    enable : false
    label : ""
    link : "get-demo/"
  background_class: ""



######################### content_and_waves_ordered #####################
content_and_waves_ordered:
  enable : true
  content : "A Profivox-korpusz beszédszintetizátor hangjai automatikus alkalmazásokban: hirdetésben, banki rendszerben, időpont közlésben, időjárás jelentésben, pályaudvari utas tájékoztatásban."
  title : "ProfiVox korpusz hangok"
  background_class : ""
  waves:
  - sound: "images/ps_profivox/aru_arlista_felolvasas/001.wav"
    subcontent: "Motorolla telefon hirdetés"
    subtitle: "1."
  - sound: "images/ps_profivox/aru_arlista_felolvasas/007.wav"
    subcontent: "Samsung telefon hirdetés"
    subtitle: "2."    
  - sound: "images/ps_profivox/aru_arlista_felolvasas/003.wav"
    subcontent: "Nokia telefon hirdetés"
    subtitle: "3."    
  
  
  
  - sound: "images/ps_profivox/banki_szamlaegyenleg/szamla_1minta.wav"
    subcontent: "Számla egyenleg közlése"
    subtitle: "4."        


  - sound: "images/ps_profivox/datum_es_idopont_felolvasas/1956_december_12.wav"
    subcontent: "Dátum megadása"
    subtitle: "5."    
  - sound: "images/ps_profivox/datum_es_idopont_felolvasas/2004_marcius_30_16_ora_32_ perc.wav"
    subcontent: "Dátum és időpont"
    subtitle: "6."    



  - sound: "images/ps_profivox/idojarasjelentes/0000.wav"
    subcontent: "Időjárás jelentés automatikus felolvasása"
    subtitle: "7."    
  - sound: "images/ps_profivox/idojarasjelentes/0001.wav"
    subcontent: "Időjárás jelentés automatikus felolvasása"
    subtitle: "8."    

  - sound: "images/ps_profivox/vonat_menetrendi_utastajekoztato/MAV_napfurdo_vonat.wav"
    subcontent: "Pályaudvari utastájékoztatás menetrendi szövegekből"
    subtitle: "9."    
  - sound: "images/ps_profivox/vonat_menetrendi_utastajekoztato/MAV_tekergo_vonat.wav"
    subcontent: "Pályaudvari utastájékoztatás menetrendi szövegekből"
    subtitle: "10."    




---
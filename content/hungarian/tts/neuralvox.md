---
draft: false
title: "BME Neural ProfiVox"
description: ""
layout: "how-it-works"


######################### content_and_image_ordered #####################
content_and_image_ordered:
  enable : true
  block:
  - title : "BME Neural ProfiVox"
    background_class : ""
    images:
    - "images/tts/neuralvox_hu.png"
    content : '##### 

A BME Neural ProfiVox, a jövő technológiája: gépi tanulás mély neurális hálózatokkal.
A BME Neural ProfiVox magyar beszédszintetizátor család fejlesztése 2017-től kezdődött. A Google DeepMind csapata 2016-ban mutatta be a WaveNet architektúrát, amely a hang digitális mintavételezésből származó mintáit használta a gépi mélytanulás tanító adathalmazának. A beszéd esetében a tanítás során a beszédhangoknak és a hangátmeneteknek megfeleltetett hullámformák mintáiból tanult a rendszer.  A korábbi DNN megoldásokhoz képest ez a megoldás minőségi ugrást jelent, ugyanis pontosan leutánozza a beszélő hangját (nem robotos a szintetizált hang, hanem személyhez köthető). A BME VIK TMIT SmartLab is adaptálta a WaveNet módszert magyar nyelvre és elkészítette az első ilyen magyar nyelvű beszédszintetizáló megoldást, amelyet BME Neural ProfiVox beszédszintetizátor családnak neveztek el.  


A deep learning modellek folyamatosan fejlődnek azóta is (Tacotron, WaveGlow, FastSpeech, HiFi-GAN, FastPitch stb.). A BME VIK TMIT SmatLab csoportja is elkészítette a magyar nyelvre adaptált Tacotron2 modellt, amely mel spektrogramot hoz létre a bemeneti szövegből, majd ezt alakítja át hullámformává. A Tacotron2 alapú megoldás GPU rendelkezésre állása esetén elfogadható sebességű, de köznapi CPU-s rendszerben nem alkalmas valós idejű beszédszintézisre. 2022-re a SmartLab csapata a BME Neural ProfiVox családon belül többféle modellt is kidolgozott, amelyek nagyon jó minőségű szintetizált beszédet szolgáltatnak. A fejlesztés vezetője Dr. Zainkó Csaba.


A BME Neural ProfiVox magyar megoldásokat 2022-be már az iparban is használják. A modelleket FastPitch és HiFi-GAN megoldások adaptálásával fejlesztették. Ezek már CPU-s környezetben is gyors szintézist tesznek lehetővé. A modellek jellemzője, hogy szöveg vagy hangsorozat bemenetet várnak, amelyet egy köztes mel-spektrogram reprezentációra alakítanak, majd ebből egy másik modell állítja elő a végleges hangsorozat hullámformáját, vagyis a szintetizált beszédet. A legújabb modellek lehetőséget biztosítanak az alapfrekvencia és a sebesség állítására is, így teljes értékű beszédszintetizátorok motorjaként szolgálhatnak. A modellek az adott beszélő hangját élethűen visszaadják, de a modellparaméterek kombinálásával új beszélők hangjai is előállíthatók. Mindezen felül személyhez nem köthető (semleges) hangok is létre hozhatók, ami bizonyos esetekben jogi problémák elkerülésében lehet fontos.'
      

######################### content_and_waves_ordered #####################
content_and_waves_ordered:
  enable : true
  content : ""
  title : "Neural ProfiVox hangok"
  background_class : ""
  waves:
  - sound: "images/tts/no_bme_neuralvox.wav"
    subcontent: "Női hang"
    subtitle: "1."
  - sound: "images/tts/ff_bme_neuralvox.wav"
    subcontent: "Férfi hang"
    subtitle: "2."    
  

---
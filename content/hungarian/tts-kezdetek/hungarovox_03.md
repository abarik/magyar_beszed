---
date: "2019-07-12"
draft: false
title: "Hungarovox"
description: "Az első szövegfelolvasó gép magyar nyelven"
icon: ""  # fontawesome icon pack : https://fontawesome.com/icons/
layout: "layout-3"


######################### product_info #####################
product_info:
  enable : true
  title: "Hungarovox"
  content: ""
  features:
  - image: "images/ps_kezdetek/hu_szabadalmi_okirat.jpg"
    content : "##### Az első szövegfelolvasó gép magyar nyelven

A beszéd gépi előállítása terén a forradalmi változást a számítógép jelentette. Az első számítógéppel vezérelt beszédszintetizátorokat Amerikában és Svédországban fejlesztették ki az 1960-as évek végén. Egy évtizeddel később lépett be a témakör kutatásába Magyarország (1979), Bolla Kálmán fonetikusnak köszönhetően, aki az MTA Nyelvtudományi Intézet Fonetikai Osztályának akkori vezetője volt.
<br><br>

    Az osztály laboratóriumában készítették el az első magyar szövegfelolvasó rendszert – HungaroVox – , amely magyarul olvasott fel tetszőleges begépelt szöveget (1982). A rendszer alkotói: Olaszy Gábor, Nikléczy Péter és Kiss Gábor. Ez a rendszer az MTA Nyelvtudományi Intézetének szolgálati szabadalma (1982, lajstrom száma: 185527). 
    <a href='/download/HungaroVox_patent_HU.pdf'>A szabadalom teljes szövege itt olvasható.</a>
    

<br><br>

Ez volt az első gépi szövegfelolvasó Magyarországon. A HungaroVox rendszer egy cipős doboz méretű, digitálisan vezérelhető analóg formánsszintetizátorból (VOX-12), egy PDP 11/34-es DEC gyártmányú (könyvszekrény nagyságú) számítógépből (a gép központi memóriája 64 kByte volt), valamint egy Fortran nyelven íródott vezérlő programból állt. 



    "

  - image: "images/ps_kezdetek/hu_hungarovox.jpg"
    content : "##### 



A Hungarovox formánsszintézis elven működött, tehát alapvetően fonetikai jellegű paraméterekkel (formánsok, időtartamok, intenzitások stb.) vezérelték a beszédszintetizátor egységet. A beszédet 370 féle fonetikai \"hangszelet\" felhasználásával generálta.  A VOX-12 a vezérlése során 10 ms-onként kapott formáns adatokat a számítógéptől, mindig az adott beszédhangnak/hangátmenetnek megfelelően. A hangja robotos volt, de jól érthető. Tudott énekelni, suttogni, rekedt hangon is beszélni. A szabadalmat a Budapesti Elektroakusztikai Gyár megvásárolta.  A gyár bemutató darabot gyártott belőle.

    "

######################### Intro Video #####################
intro_video:
  enable: true
  title: "VOX-12 hangbemutató"
  content: ""
  video_url: "videos/ps_kezdetek/hu_hungarovox_12_voice_1982.mp4"
  video_thumbnail: "images/ps_kezdetek/hu_video_vox.jpg"
  background_class : "bg-light"



######################### content_and_waves_ordered #####################
content_and_waves_ordered:
  enable : true
  content : "A Hungarovox akár nyelvtörőt is ki tudott mondani, sőt éneket is elő tudott adni a sajátos hangján."
  title : "Hungarovox hangok"
  background_class : ""
  waves:
  - sound: "images/ps_kezdetek/hu_nepdal.wav"
    subcontent: "Hej Dunáról fúj a szél ..."
    subtitle: "1."
  - sound: "images/ps_kezdetek/hu_mondoka.wav"
    subcontent: "Az ipafai papnak ..."
    subtitle: "2."    
  


---
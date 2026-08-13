---
date: "2021-11-21"
draft: false
title: "BME TMIT 1988"
description: ""
icon: ""  # fontawesome icon pack : https://fontawesome.com/icons/
layout: "layout-1"





######################### content_and_image_ordered #####################
content_and_image_ordered:
  enable : true
  block:
  - title : "Verbident beszédfelismerő"
    background_class : ""
    images:
    - "images/asr_kezdetek/hiradastechnika_cikk_fejlece.png"
    content : '##### 
    
1987-ben a BME Távközlési és Telematikai Tanszék kutató gárdája Takács György javaslatára (aki 1986-ban a svéd KTH laborban tett látogatást) a gépi beszédfelismerés kutatásával kezdett foglalkozni. A cél az volt, hogy hétköznapi IBM PC gépen valósuljon meg egy izolált szavas, személyfüggő beszédfelismerő. A kutatást az OMFB támogatta. A rendszer fantázia neve VERBIDENT SD 2 (SD=Speaker Dependent, személy függő). Felépítésének alapvető jellemzője, hogy nem különállóan működő berendezésről van szó, hanem az IBM PC (XT vagy AT) típusú személyi számítógép egy digitális jelfeldolgozó kártyával együttműködve végzi a beszédfelismerést.  Szótárszerkesztő program is tartozik a gépi beszédfelismerőhöz, amellyel a felhasználó tetszése szerinti szótárat szerkeszthet és azt mágneslemezen tárolhatja. A felismerő csak a betanító személy által a szótárba felmondott szavakat képes felismerni. Több személy is használhatta, de minden felhasználónak kellett egy saját hangú szótárt készítenie. 



A kutatás eredményéről a Híradástechnika folyóirat 1988. 3. számában számoltak be a kutatók.
A teljes cikk [itt](../download/1988_03_06_hiradastechnika_teljescikk.pdf) olvasható. 


Ezen kutatási eredményeknek volt köszönhető, hogy 1989-ben Takács Györgyöt 1 évre meghívták a KTH-be Svédországba vendég kutatónak, ahol tovább folytatta beszédfelismerési kutatásait és svéd nyelvre is létrehozott beszédfelismerőt.


'
  


######################### content_and_image_ordered #####################
content_and_image_ordered_2:
  enable : true
  block:
  - title : "Magyar-Svéd beszédfelismerő"
    background_class : ""
    images:
    - "images/asr_kezdetek/tgy_cikk.png"
    content : '##### 
    
A Stockholmi Műszaki Egyetem „Speech, Music and Hearing” tanszékén (KTH) vendégkutató volt Takács György 1989-90-ben. Kidolgozott egy neurális hálózaton alapuló fonéma felismerő rendszert svéd és magyar folyamatos beszédre. A neurális hálózat három részből állt: először alapvető fonetikai jellemzőket határozott meg (zöngés/zöngétlen, nazális/nem nazális stb.), majd egy következő hálózatrész a teljes fonéma készletre adott jelöltet. A hálózat kimenő intenzitása jelezte, hogy mennyire biztos a döntés a fonéma jelöltre és adott második, harmadik jelöltet is. A fonéma határokat egy külön hálózat jelezte. Ez a megoldás a manapság népszerű és sikeres „deep learning” egyfajta előképének tekinthető.


Az erről szóló tanulmány teljes terjedelmében [itt](../download/1990_tgy_kth_cikk.pdf   ) olvasható angol nyelven.


'
  






---
---
date: "2021-07-13"
draft: false
title: "ProfiVox HMM"
description: "Az első statisztikai elvű HMM beszédszintetizátor"
icon: ""  # fontawesome icon pack : https://fontawesome.com/icons/


######################### banner #####################
banner_center:
  title : "ProfiVox HMM"
  image: ""
  content : "A Profivox HMM megoldás statisztikai elvű gépi tanuláson alapul és rejtett Markov-modelleket használ a szintetizálandó beszédjelet reprezentáló paraméterek létrehozására. Ezt a számítástechnika fejlődése tette lehetővé. Nem közvetlenül a hullámformával dolgozik, hanem a hullámformából spektrális és prozódiai jellemzők sokaságát nyeri ki. Komoly fonetikai, nyelvészeti tudásra nincs szükség. Az eljárás a  gépi beszédelőállítás új iránya. Utólagos jelfeldolgozásra nincs szükség, mivel a dallam és a ritmus jellegzetességeit is megtanulja. A szintetizált hullámformát egy beszédkódoló (hangvisszaállító) kimenete szolgáltatja. A tanulás alapját több beszélővel elkészített sok-sok órányi tanító beszédadatbázis szolgáltatja.  Az algoritmus 5 beszédhangnyi elemsorozat középső hangjára határozza meg a paramétereket. Környezet függő címkék és döntési fák segítségével figyelembe veszi a vizsgált beszédhangot, annak időszerkezeti helyét szó- és mondat szinten, valamint felhasználja a szóhatárokat, a szó hosszúságát is a tanulás során. A tanulás eredményeként létrehoz egy optimális paraméter adatbázist, ami sokkal kisebb, mint a tanító beszéd adatbázis volt. A HMM alapú tanítás idő- és tudás igényes folyamat. A tanítást csak egyszer kell elvégezni. A szintézis során a Profivox-HMM a bemeneti mondat betűsorozata alapján válogat a paraméter adatbázisából. Így állítja össze a mondat szintézisét reprezentáló komplex adatsorozatot. Kijelentő és kérdő mondatokat helyesen tud ejteni. A szintézis gyors, különösebben nagy erőforrást nem igényel. A hangkimenet jó minőségű és kötetlen tartalom felolvasására alkalmas. Lehet lassítani és gyorsítani a beszédet. Előnye az eljárásnak, hogy kis munkával más személy hangjából is lehet paraméter adatbázist készíteni, vagyis az alaprendszert adaptálni lehet többféle hangra is. Az adaptáláshoz elég 10-20 percnyi beszéd az új célszemélytől. További részletek a rendszert fejlesztő Tóth Bálit Pál PhD disszertációjában olvashatók [itt](/download/PhD_TB.pdf). "

  button:
    enable : false
    label : ""
    link : "get-demo/"
  background_class: ""



######################### content_and_waves_ordered #####################
content_and_waves_ordered:
  enable : true
  content : "Hallgassa meg ezen ismertető első mondatát különböző személyek hangján!"
  title : "ProfiVox HMM hangok"
  background_class : ""
  waves:
  - sound: "images/ps_profivox/FF_BM_0000.wav"
    subcontent: "Mátyás"
    subtitle: "1."
  - sound: "images/ps_profivox/FF_CSTG_0000.wav"
    subcontent: "Tamás"
    subtitle: "2."    
  - sound: "images/ps_profivox/FF_NG_0000.wav"
    subcontent: "Géza"
    subtitle: "3."    
  - sound: "images/ps_profivox/FF_OG_0000.wav"
    subcontent: "Gábor"
    subtitle: "4."        
  - sound: "images/ps_profivox/N_MK_0000.wav"
    subcontent: "Kati"
    subtitle: "5."    
  - sound: "images/ps_profivox/N_TE_0000.wav"
    subcontent: "Eszter"
    subtitle: "6."    
    
   


---
---
title: "Írás és beszéd"
subtitle: ""
# meta description
description: "This is meta description"
draft: false
---

#### A beszéd és írás kapcsolata, fonetikus átirat

A nyelvi kommunikáció két legfontosabb formája a beszéd és az írás. Míg a beszéd folyamatos levegőrezgés, melynek akusztikai szerkezete állandóan változik, az írás alapvetően a beszéd tartalmi rögzítésére jött létre, ennek megfelelően diszkrét, véges számú egymástól elkülöníthető elemből álló jelkészletet használ (graféma, írásjel).
Az írás és a beszéd egymással szoros kapcsolatban van, ezt a kapcsolatot az adott nyelv fonéma rendszere jelenti. 

A fonéma a nyelv azon eleme, amelyik megkülönböztető szereppel bír a jelentésben. A magyar nyelvnek 65 fonémája van. A fonéma hangzó megfelelője többnyire a beszédhang, az írott szöveg pedig a beszédhangot reprezentáló egy vagy több elemű graféma (betű) sorozat. A kettő közötti kapcsolatot oda-vissza biztosítja a fonetikus átirat, amely hangszimbólumok sorozatával adja meg a szöveg beszédhangjait. 

A beszédtechnológiában sok esetben írott szöveget kell a gép segítségével automatikusan beszéddé alakítani, tehát a diszkrét szimbólumsorozatból kell folyamatosan változó hullámformát készíteni (beszédszintézis). A feldolgozás során a szövegből fonetikus átiratot kell készíteni, majd ebből generálják a beszédet. Ennek fordítottja pedig, amikor az elhangzott beszédből kell a gépnek meghatároznia, hogy mi volt a hangsor nyelvi tartalmát reprezentáló szöveg (gépi beszédfelismerés). Ekkor a beszédből készül el a köztes fonetikus átirat, majd abból az írott szöveg. 

##### Írásból beszéd 

A magyar nyelv többnyire fonemikus írása miatt általában elégséges ha egyes betűcsoportokra vonatkozó egyszerű kiejtési szabályokat tanulunk meg, hogy a fonetikus átiratot elkészítsük. 
A következő példában SAMPA hangjelekkel adjuk meg a fonetikus átirat beszédhangjait egy mondatra: 

A pontos idő 13 óra. =  O p o n t o S i d 2:  t i z e n h A: r o m o: r O

Ebben az átiratban  nincsenek jelölt szóhatárok (hiszen a beszédben sem tartunk szünetet a szavak határán), csak a központozási jeleknél (például: pont, vessző, kettőspont stb.) van szünet. A fonetikus átiratot általában mondat szinten készítik el. A mondat a nyelvi betűszókon kívül tartalmazhat más elemeket is, például számokat, mozaik szavakat, rövidítéseket, Web címeket, márka neveket stb.  Ezek kiejtési formáját a fonetikus átiratnak követni kell.
Az ember segít a gépnek a helyes fonetikus átirat automatikus elkészítéséhez, kivétel szótárakkal. Az ilyen szótárak készítése nehéz, véget nem érő és nagyon sokrétű feladat. Ha a fonetikus átiratot helyesen (a leendő kiejtés szerint hangról hangra) hozták létre, akkor a generált beszéd a megfelelő beszédhangfolyamot fogja tartalmazni.
Az alábbi néhány példasor a Profivox magyar gépi felolvasó kivétel-szótárának Z betűvel kezdődő szavaiból való. A kiejtési formát TMIT hangszimbólumokkal adjuk meg. 

Betűkép | Hangalak (TMIT)
--------|---------
Zeiss |	c;e;j;s
Zeitung	|c;e;j;t;u;n;g
Zellweger|	c;e;l;v;E;g;e;r
Zeneca|	z;e;n;e;k;a
Zeppelin|	c;e;p;e;l;i;n
Zepter|	c;e;p;t;e;r
Zewa|	c;e;v;a
Zidane|	z;i;d,A;n
Zimmer|	c;i;m:;e;r
Zuschlag|	c;u;S,l;A:;g
Zürich|	c;U;r;i;h
Zwilling|	c;v;i;l;i;n;g

Figyelem! A fonetikus átirat nem tartalmaz információt a beszéd időszerkezetéről (hangidőtartamok, szünetek hossza, ritmus stb.). Ezt az információt párhuzamosan kell biztosítani minden beszédhangra a helyes beszédhangzás eléréséhez.
A tervezett szövegfelolvasó megoldást célszerű az adott feladatra, témakörre megtervezni (például: reklám, bank, közlekedés, egészségügy, államigazgatás, informatika, kereskedelem, könyvolvasás stb.).

##### Beszédből írás

Az automatikus beszédfelismerő a beszédből hangról hangra fonetikus átiratot készít, ahogy az a beszédjelben volt. Hogyan alakul át ez helyes nyelvi szöveggé? A fő probléma a kiejtés egyéni változatossága (hangkiesések, hangbeillesztések, szótagkihagyások stb.). Például a miért szó ejtési variációi: mé, mér, mét, mért, mijért.  A másik probléma, hogy szóhatárokat kell meghatározni a fonetikus átiratban, hogy helyes szósor legyen a szöveg kimeneten. Probléma az is, hogy a magyar ragozó nyelv, ragozott szavak esetén nehéz meghatározni a szóhatárt (például: asztal, asztalos, asztalosok, asztalosoké, asztalosokéi, asztalosokéiból). Speciális szótárak, nagy adatbázisok, jó lényegkiemelési módszerek szükségesek ezeknek a problémáknak a leküzdéséhez a gépi beszédleiratozásnál. A kiejtett nevek, márkák stb. helyes gépi átírása is gondot okozhat. Ehhez is kivétel szótárak kellenek.

Fonetikus átiratokat mutatunk be ezen a honlapon a Magyar Kiejtési Szótárban. Továbbá az alábbi címről letölthető Fonetizátor program is erre használható.
http://lsa.tmit.bme.hu/products/phontrans.html

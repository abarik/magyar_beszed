---
date: "2021-01-23"
draft: false
title: "The phonetic database "
job_nature: ""
category: "Speech database elements specified with phonetic data"
---

**Presentation of speech database elements specified with phonetic data**
 
 
 Hungarovox, and Multivox Hungarian speech synthesizers used such data, 1982-1990.

The phonetic database contains a set of short "audio" slices characterised by phonetic data.

The phonetic data per slice in the database are as follows:
* F1, F2, F3, F4 formant frequency value (Hz)
* Value of formant bandwidth B1, B2, B3, B4 (Hz)
* Pitch - PI parameter and Hertz
* Volume (dB) - AM
* Excitation (voiced = V; noisy = c)
* Duration = 12ms / slice - FD

An example of concatenating a series of paramter slices used for the synthesis of the first syllable of the Hungarian expression "Good morning" (Jó napot). 
(1-4 slices = j); (5-9 = j-o sound transition); (9-17 = o )


 {{< image title="dallam" w="1200" o="webp q100" p="center" c="img-fluid shadow rounded-1" src="images/mb-speech-acoustics/fonetikai_adatok_tts.jpg" alt="alter-text" >}}
 

The entire database contained 370 types of parameter slices, with which all the speech sound connections of Hungarian speech could be realized. Memory requirement was 1 Kbyte. The sound of the synthesized speech was robotic, but well understood.





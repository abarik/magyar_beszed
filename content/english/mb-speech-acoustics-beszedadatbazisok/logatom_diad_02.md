---
date: "2021-01-22"
draft: false
title: "Waveform database "
job_nature: ""
category: "Diad elements"


---


**Waveform database of diad elements made for speech synthesis**

Used for Profivox-diad speech synthesizers since 1995

The definition of diad: wave form element containing of two half speech sounds.
 To create the database, we recorded the set of readable atoms (logatoms, i.e. meaningless sound sequences) which represent the Hungarian speech. The waveforms of each diad (wave form of two half speech sounds) were excised and stored from their own logatom.
The Hungarian speech can be covered max. 1600 kinds of diads. The diad database has a matrix layout. The ProfiVox diad system uses 38 speech sounds. The waves of the diads were labeled with: the code numbers of the two concatenated sounds; excitation form as voiced / unvoiced in the waveform part; period boundary for voiced sounds; sound boundary inside the diad.

The example shows 5 diads concatenated, when the word "alma" (apple) is synthesized.


{{< image title="dallam" w="1200" o="webp q100" p="center" c="img-fluid shadow rounded-1" src="images/mb-speech-acoustics/alma.png" alt="alter-text" >}}
 
The size of the diad database is 6 Mbyte per speaker. The Hungarian ProfiVox speech synthesizer can speak in male and female voices.

To create the diad database, designed 3-syllable meaningless sound sequences have been designed, one for each speech diad (sound connection), i.e. a total of 1421 logatom for 38 kinds of speech sounds. As an example, let's look the text items (logatoms) wich carry the the sound connections (diads) of the ba:, pa: da: ta: ga: ka: Ja: speech sound combinations. 

abáka, apáka, adáka, atáka, agáka, akáka, agyáka


{{<audio src="/audio/abaka_8_logatom.wav" caption="" >}}


The reading had to be done in a monotonous voice with normal speech tempo and with the same volume. See the audio example.


{{<audio src="/audio/alma.wav" caption="" >}}


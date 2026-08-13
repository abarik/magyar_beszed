---
date: "2021-01-21"
draft: false
title: "Waveform database "
job_nature: ""
category: "Diad-triad combined"
---



**Diad-triad combined wave form database for speech synthesis**


Used for Profivox-triad speech synthesizers since 2005.

A serious disadvantage of diad-based speech building is that diads are cut and later matched to each other in the middle of the sounds. This causes distortion, mainly in vowels. To eliminate this came the idea of not cutting vowels in the middle of the sound, but leaving them in their natural state in CVC sound combinations, and make cut only in the consonants. Such elements are called triads.  To create a speech waveform database consisting of CVC triad elements, different logatoms (meaningless sequences) must be read than in the case of diads. The waveforms of each triad were excised from their own logatom and stored. Thus, a speech database was created with diads and triad elements.
In the final database there are 1,600 types of dyads and 9000 CVC triads. The waveforms of the CVC triads were also labeled.

To synthesize the Hungarian sentence "Esni fog az eső" (It's going to rain) 1 diad (SN) and 6 triads were concatenated.


{{< image title="dallam" w="1200" o="webp q100" p="center" c="img-fluid shadow rounded-1" src="images/mb-speech-acoustics/esnifogazeso.png" alt="alter-text" >}}
 

The size of the diad-triad combined database is 80 Mbyte for one voice. The voice of the ProfiVox-triad synthesizer was used in the Hungarian Drug Line Information System.


{{<audio src="/audio/esni_fog_az_eso.wav" caption="" >}}



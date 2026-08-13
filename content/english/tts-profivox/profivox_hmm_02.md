---
date: "2021-07-13"
draft: false
title: "ProfiVox HMM"
description: "Based on statistical machine learning"
icon: ""  # fontawesome icon pack : https://fontawesome.com/icons/


######################### banner #####################
banner_center:
  title : "ProfiVox HMM"
  image: ""
  content : "
  
  The Profivox- HMM TTS converter is based on statistical machine learning and uses hidden Markov models to generate parameters representing the speech signal to be synthesized. The development of computer technology made possible to realise this idea. No deep phonetic or linguistic knowledge is required. Speech melody and rhythm is also learned, no post signal-processing is required. The synthesized waveform is provided by the output of a speech encoder. The basis of learning is a large speech database (many hours of speech) created with several speakers. The algorithm determines the parameters for the middle speech sound of a quint-phone sequece step by step. It takes into account the time position (place) of the examined element at word- and sentence level, and also uses the word boundaries and the length of the word information during learning. As a result of learning an optimal parameter database is created, that is much smaller than the original speech database. Teaching process needs to be done only once. HMM-based teaching is a time-consuming and knowledge-intensive process. 
During the synthesis, Profivox-HMM selects data from the parameter database, based on the input text. The systm can pronounce declarative sentences and also questions correctly. The synthesis is fast and does not require much resources. You can slow down and speed up the speech. The advantage of this method is easy adaptation. It is possible to create a parameter database from the voice of another person. Only 10-20 minutes of newly recorded speech is enough for an adaptation. More details can be found [here](download/TB_PhD_thesis_2013.pdf), in the summery of the PhD dissertation of Pál Bálit Tóth, who developed the system.
    "

  button:
    enable : false
    label : ""
    link : "get-demo/"
  background_class: ""



######################### content_and_waves_ordered #####################
content_and_waves_ordered:
  enable : true
  content : "Listen to some synthesized voices in Hungarian"
  title : "ProfiVox HMM voices"
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
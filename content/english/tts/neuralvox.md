---
draft: false
title: "BME Neural ProfiVox"
description: "5 alkalmazás hangmintákkal"
icon: "fas fa-volume-up"  # fontawesome icon pack : https://fontawesome.com/icons/
layout: "layout-1"




######################### content_and_image_ordered #####################
content_and_image_ordered:
  enable : true
  block:
  - title : "BME Neural ProfiVox"
    background_class : ""
    images:
    - "images/tts/neuralvox_en.png"
    content : "##### 


The development of the BME Neural ProfiVox speech synthesizer family started in 2017. In 2016, the Google 
DeepMind team announced the WaveNet architecture, which used the data set of samples of the digitalized wave form to teach the machine. In the case of speech, the system learned from samples of waveforms corresponding to speech sounds and voice transitions. Compared to previous DNN solutions, this solution represents a qualitative leap in that it mimics the speaker's voice exactly (the synthesized voice is not robotic, but can be linked to a person). BME VIK TMIT SmartLab also adapted the WaveNet method to Hungarian and created the first neural based speech synthesis solution in Hungarian, which was named BME Neural ProfiVox family. 


Deep learning models in the world have been evolving ever since (Tacotron, WaveGlow, FastSpeech, HiFi-GAN, FastPitch, etc.). The SmartLab group of BME VIK TMIT also adapted the Tacotron2 model to the Hungarian language. This model creates a mel spectrogram from the input text and then converts it into a waveform. However the Tacotron2-based solution does not run in real-time in CPU environment, only with GPU availability. By 2022, several combinations of solutions of BME Neural ProfiVox speech synthesizers have been developed for Hungarian. The leader of the development is Dr. Csaba Zainkó.


BME Neural ProfiVox solutions are in 2022 used already in the industry. These models have been created using FastPitch and HiFi-GAN solutions, which enable real time synthesis even in a CPU environment. The Neural ProfiVox models are characterized by expecting text or phonemic inputs that are converted to an intermediate mel-spectrogram representation, from which another model produces the final speech waveform. The latest models also offer the ability to adjust the fundamental frequency and speed, so they can serve as engines for full text-to-speech synthesizers. Models can reproduce the voice of a given speaker in real time. Combining model parameters, the voices of other persons can also be produced. In addition, non-personal (neutral) speech can be created, which in some cases can be important in avoiding legal issues.



"
      


######################### content_and_waves_ordered #####################
content_and_waves_ordered:
  enable : true
  content : ""
  title : "Neural ProfiVox voices"
  background_class : ""
  waves:
  - sound: "images/tts/no_bme_neuralvox.wav"
    subcontent: "Female voice"
    subtitle: "1."
  - sound: "images/tts/ff_bme_neuralvox.wav"
    subcontent: "Male voice"
    subtitle: "2."    
  


---
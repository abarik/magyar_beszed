---
title: "Sentence melodies"
subtitle: ""
# meta description
description: "This is meta description"
draft: false
---

One of the most important means of human speech generation is the speech melody. It is physically created by changing the frequency of the sound vibration (voice, pitch) generated in the larynx. There are basically three forms of speech melody: ascending, descending, and floating (smooth, unchanged. Within these categories, several levels are distinguished: weakly rising, rising and escaping, and weakly descending, descending, fast descending. These will are called melody-building elements. Examination, knowledge and modeling of pitch values play an important role in speech recognition and in speech synthesis as well.

In Hungarian, speech melody forms have a distinctive role at sentence level. The whole melody of a sentence depends on the type and complexity of the sentence. The general melody form of the declarative sentence is the descending, in the case of questioning sentences the complex melodic form is derived from the most diverse combination of all melodic building elements. The start and end points of the Hungarian sentence melodies are strongly related to each other in continuous speech. The general model of the Hungarian sentence melody forms is shown below.



{{< image title="dallam" w="1200" o="webp q100" p="center" c="img-fluid shadow rounded-1" src="images/mb-speech-acoustics/dallam_modell_en.png" alt="alter-text" >}}



The model does not depend on the personal voice frequency (F0). The starting Hz value of the statement (100%)is the reference point to calculate the melody form of other sentence types. It means that the starting point of other sentence types must be calculated from the reference point. For example, let us refere the 100% reference point to 100 Hz. The physical Hz values of a Wh question will be the following: start value is 130% (130 Hz)and this frequency remains until the end of the first syllable. The F0 will drop within the second syllable to 80% (80Hz), and from this point it will have a descending form till the end of the question, where the final value of F0 will be 70% (70Hz). 
In the case of complex, long sentences, apply the model to each subsentence.

The following conclusions can be drawn from the model.

1. The starting melody frequency of the Hungarian sentence types depends on the sentence type.
2. The ending melody frequency value of the Hungarian sentence types is usually the same.
3. In Wh and Yes/no questions, the first syllable and the penultimate syllable play an important role when forming the sentence melody.
4. The melody structure of a sentence flow can be implemented according to the model (e.g statement1, question1, statement2, statement3, question2 sentences4) calculating the melody forms for every separate sentence. This may be used in TTS conversion.


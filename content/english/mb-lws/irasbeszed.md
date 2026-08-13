---
title: "Writing and speaking"
subtitle: ""
# meta description
description: "This is meta description"
draft: false
---

#### Speech and text, the phonetic transcript

The two most important forms of human communication are speaking and writing. While speech is a continuous vibration of air, the acoustic structure of which is constantly changing, writing is basically created to record the content of speech, using a set of discrete symbols (graphemes, pictures etc.)
Writing and speaking are closely related to each other, this relationship is represented by the phoneme system of the given language.
The phoneme is the element of language that has a distinctive role in the meaning. The Hungarian language has 65 phonemes. The vocal equivalent of a phoneme is a speech sound. The process called Phonetic Transcription is used to transform the written text to phoneme sequences, that correspond to the speech signal.  A phonetic transcript can be considered as a link between the spoken communication and its written version. 
Speech technology deals with automatic text-to-speech conversion (TTS), where a continuously changing waveform must be created from a series of discrete text elements. During processing, a phonetic transcript of the text must be made, and the speech is generated from it. The reverse is when the machine has to determine from the spoken form the text elements (artificial speech recognition, ASR). In this case the intermediate phonetic transcript is generated from the speech signal.

##### Text-to-speech

Hungarian is a phonemic language, it is usually sufficient to learn simple pronunciation rules to make a phonetic transcript.
In the following example, the phonetic transcript of a sentence  (The exact time is 13 o'clock.) is shown using SAMPA symbols. 

A PONTOS IDŐ 13 ÓRA. = O;p;o;n;t;o;S;i;d;2:;t;i;z;e;n;h;A:;r;o;m;o:;r;O

Attention! There are no marked word boundaries in the phonetic transcript. The phonetic transcript is usually made at sentence level. But a sentence can contain other elements than normal words, such as numbers, acronyms, abbreviations, Web addresses, brand names, and so on. The pronunciation form of these items should be given by sound symbols in exception vocabularies. Creating such dictionaries is a difficult, never-ending task. If the phonetic transcript has been created correctly, the pronunciation will be correct.

The following examples are from the exception vocabulary of the Profivox Hungarian text reader system.

Text | Phonetic transcript
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

##### Speech-to-text

The automatic speech recognizer creates a phonetic transcript from the spoken item. The main problem is the individual variability of pronunciation (sound omissions, sound insertions, syllable omissions, etc.). The other problem is that word boundaries must be defined in the phonetic transcript to have the correct word string in the text output. Another problem is the conjugation which makes difficult to determine the word boundary. Special dictionaries, large databases, good highlighting methods are needed to overcome these problems in speech-to text conversion. Pronounced names, brands, etc. can also be a problem. This also requires exception vocabularies.

On this website we present phonetic transcripts in the Hungarian Pronunciation Dictionary on one hand, but the Phonetizer program below can also be used for this purpose.





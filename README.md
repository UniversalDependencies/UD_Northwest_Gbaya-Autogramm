# Summary

A Universal Dependencies corpus for Northwest Gbaya, a member of the Gbaya branch of the Atlantic-Congo phylum. The language is mainly spoken by about 250,000 speakers in Central African Republic.

# Introduction

The treebank is an automatic conversion of the [mSUD_Northwest_Gbaya-Autogramm](https://github.com/surfacesyntacticud/mSUD_Northwest_Gbaya-Autogramm), which was extracted from Paulette Roulon's corpus in Elan format ([https://corpafroas.huma-num.fr/Archives/corpus.php](https://corporan.huma-num.fr/Archives/corpus.php?codeLangue=GYA)).

Sentences are annotated with the following metadata:

 - `sent_id` (which indicates the source file and the segmentation identifier in the source file)
 - `speaker_id` (which identifies the turn of speech)
 - `sound_url` (which enables playback of the audio recording) (to be added)
 - `sent_timecode` (which enables playback of the sentence)
 - `text` (lexical tokenization)
 - `text_fr` (French interpretation)
  

# Structure

This version of the treebank is a dependency parsing of three files of the original corpus. 

The original data are spoken data, which were originally segmented in interpausal units, and interlinearized, translated and glossed in Elan. For the syntactic treebank, a re-alignment was done using the illocutionary unit as a sentence.

The UD Northwest Gbaya treebank counts 2417 words for 403 sentences.


# Reference

…

# Acknowledgments

This treebank was produced as part of the [Autogramm ANR project](https://autogramm.github.io/en/). With special thanks to Christian Chanard for the conversion from Elan, Sylvain Kahane for the mSUD annotation, Aleksandra Miletic and Bruno Guillaume for the conversion from mSUD to UD. 


## References

* (citation)


# Changelog

* 2024-11-15 v2.15
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Roulon, Paulette
Contributing: elsewhere
Contact: pauletteroulon@gmail.com
===============================================================================
</pre>

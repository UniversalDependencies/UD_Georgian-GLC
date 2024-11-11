# Summary

The Georgian UD Treebank (UD_Georgian-GLC) is the first syntactically annotated corpus of Georgian, based on a collection of annotated sentences selected from the Georgian Language Corpus (GLC) available at http://corpora.iliauni.edu.ge/ and sentences selected from Wiki in accordance with the 132 scientific fields. 

# Introduction

The Georgian UD Treebank (UD_Georgian-GLC) serves as the first syntactically annotated corpus of the Georgian language. It includes 151 utterances randomly selected from the GLC (Doborjginidze et al. 2013), providing detailed annotations encompassing the grammatical structure and dependencies within the sentences.

The treebank's annotations align with the Universal Dependencies (UD) specifications, allowing for greater consistency and compatibility with other UD treebanks. Although the tokenization and segmentation principles of the GLC differ slightly from those of the UD, the UD_Georgian-GLC follows the UD approach, particularly regarding multiword tokens, to minimize differences.

Morpho-syntactic annotations, as discussed in Lobzhanidze (2022), have been automatically adapted to UD requirements. This includes annotations for lemmas (LEMMA), part-of-speech categories (UPOS; XPOS), morphological features (FEATS), transliteration, and tokenization issues (MISC). Furthermore, heads of words (HEADS), dependency relations (DEPREL), and enhanced dependency graphs (DEPS) were automatically converted and then reviewed and manually corrected.

The current version of the UD_Georgian-GLC treebank includes 151 utterances (sentences) or 2123 tokens and 3013 sentences or 44030 tokens from Wikipedia arranged in accordance with the 131 scientific domains. These sentences served as a training set, enriching the treebank and offering a more comprehensive representation of the Georgian language. The primary objective is to provide a more comprehensive and representative dataset for training and analysis purposes.

# Acknowledgments

The UD_Georgian-GLC release is based on the data from the Georgian Language Corpus (GLC) developed with the financial support of the Shota Rustaveli National Science Foundation (Project Nos. DP2016_23, LE/17/1-30/13, AR/320/4-105/11, Y-04-10). 

Special gratitudes goes to Prof. Dr. Stavros Skopeteas from the University of Göttingen for his support and valuable comments on the initial data of the UD_Georgian-GLC treebank, Prof. Dr. Benjamin Roth from the University of Vienna for his feedback concerning the training dataset of the UD_Georgian-GLC treebank and to Prof. Dr. Dan Zeman for his invaluable contributions in making the dataset available on GitHub and offering valuable suggestions.

## References
Doborjginidze, N., Lobzhanidze, I., Gunia, I. (2012). Georgian language corpus. See, http://corpora.iliauni.edu.ge/. Accessed 15 July 2023. 

Doborjginidze, N., Lobzhanidze, I., Mirianashvili, G. (2014). Corpus of Georgian Chronicles. See, http://corpora.iliauni.edu.ge/. Accessed 15 July 2023. 

Lobzhanidze, I. (2022). Finite-State Computational Morphology: An Analyzer and Generator for Georgian. Cham: Springer.

# Changelog

* UD 2.13
  * First release in UD.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.13
License: CC BY-SA 4.0
Includes text: yes
Genre: fiction nonfiction
Lemmas: automatic
UPOS: automatic with corrections
XPOS: automatic 
Features: automatic with corrections
Relations: automatic with corrections
Contributors: Lobzhanidze, Irina
Contributing: here
Contact: irina_lobzhanidze@iliauni.edu.ge
===============================================================================
</pre>

# Summary

The Georgian UD Treebank (UD_Georgian-GLC) is the first syntactically annotated corpus of Georgian, based on a collection of annotated sentences selected from the Georgian Language Corpus (GLC) available at http://oldcorpora.iliauni.edu.ge/. 

# Introduction

The Georgian UD Treebank (UD_Georgian-GLC) is the first syntactically annotated corpus of Georgian. The annotations have been performed on a representative sample of sentences randomly selected from the GLC (Doborjginidze et al. 2013). The annotations provide information about the grammatical structure and dependencies within the sentences, allowing a better understanding of the syntactic structure of the Georgian language. The tokenization and segmentation principles in the GLC (Google Language Codes) differ slightly from those represented in the UD (Universal Dependencies) specifications, particularly regarding multiword tokens and, the UD specifications' approach has been adopted to avoid the above-mentioned difference. Morpho-syntactic annotation already discussed in Lobzhanidze (2022) was automatically converted to meet the requirements of the UD. Thus, the UD_Georgian-GLC incorporates automatic annotation for lemmas (LEMMA), part-of-speech categories (UPOS; XPOS), morphological features (FEATS), transliteration and tokenization issues (MISC). The heads of the current words (HEADS), dependency relations (DEPREL), and enhanced dependency graph (DEPS) have been automatically converted, reviewed, and manually corrected.

The current version of the UD_Georgian-GLC treebank includes 151 utterances (sentences) or 2123 tokens. In future releases, the UD_Georgian-GLC treebank will expand the available data by incorporating additional texts. The primary objective is to provide a more comprehensive and representative dataset for training and analysis purposes.

# Acknowledgments

The UD_Georgian-GLC release is based on the data from the Georgian Language Corpus (GLC) developed with the financial support of the Shota Rustaveli National Science Foundation (Project Nos. DP2016_23, LE/17/1-30/13, AR/320/4-105/11, Y-04-10). 

Special gratitudes goes to Prof. Dr. Stavros Skopeteas from the University of Göttingen for his support and valuable comments on the initial data of the UD_Georgian-GLC treebank and to Prof. Dr. Dan Zeman for his invaluable contributions in making the dataset available on GitHub and offering valuable suggestions.

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

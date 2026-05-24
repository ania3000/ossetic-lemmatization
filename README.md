# Summary 
The present dataset is a collection of Iron Ossetic texts from the [Corpus of Oral Texts](https://www.ossetic-studies.org/en/texts/iron) with manual annotation for lemmas, parts-of-speech and morphological features in UD v2.

Version 1 can be found [here](https://github.com/ania3000/Ossetic-COT).
# Introduction
The Corpus of Oral Texts is manually annotated for parts-of-speech and morphological features in custom schema. The annotation is manually revised and manually converted into the CoNLL-U Format using UD v2 Annotation Guidelines with the addition of language-specific guidelines. It is also augmented with manual annotation for lemmas. Ossetic is an Iranic language from the Indo-European family spoken by up to 614.000 speakers mostly in North Causasus region.

The present dataset contains 5454 sentences total. Training set contains 80% (4364) of the sentences. Validation and test sets contain 10% (545) of the sentences each.

# Statistics

## Subgenre distribution
| Tag | Train | Development | Test |
| :--- | :---: | :---: | :---: |
| Radio | 253 (6.15\%) | 37 (6.79\%) | 29 (5.32\%) |
| Expedition | 4111 (93.85\%) | 508 (93.21\%) | 516 (94.68\%) |

## Top 20 morphological tags
| Tag | Train | Development | Test |
| :--- | :---: | :---: | :---: |
PUNCT | 14924 (24.17\%) | 1866 (23.49\%) | 1825 (23.85\%) |
PART | 6578 (10.66\%) | 871 (10.96\%) | 788 (10.30\%) |
NOUN,Case=Nom\|Number=Sing | 3589 (5.81\%) | 501 (6.31\%) | 480 (6.27\%) |
CCONJ | 2796 (4.53\%) | 351 (4.42\%) | 355 (4.64\%) |
PROPN,Case=Nom\|Number=Sing | 1888 (3.06\%) | 253 (3.18\%) | 277 (3.62\%) |
ADV | 1038 (1.68\%) | 109 (1.37\%) | 127 (1.66\%) |
PART,Polarity=Neg | 1019 (1.65\%) | 115 (1.45\%) | 126 (1.65\%) |
NOUN,Case=Nom\|Number=Plur | 1019 (1.65\%) | 127 (1.60\%) | 140 (1.83\%) |
ADV,PronType=Int | 1014 (1.64\%) | 113 (1.42\%) | 116 (1.52\%) |
ADV,PronType=Dem | 999 (1.62\%) | 123 (1.55\%) | 139 (1.82\%) |
ADJ | 889 (1.44\%) | 121 (1.52\%) | 104 (1.36\%) |
ADV,Deixis=Remt\|PronType=Dem | 852 (1.38\%) | 133 (1.67\%) | 111 (1.45\%) |
VERB,Mood=Ind\|Number=Sing\|Person=3\|<br>Tense=Pres\|VerbForm=Fin | 829 (1.34\%) | 94 (1.18\%) | 85 (1.11\%) |
VERB,Aspect=Perf\|Mood=Ind\|Number=Sing\|<br>Person=3\|Tense=Past\|VerbForm=Fin | 747 (1.21\%) | 95 (1.20\%) | 88 (1.15\%) |
INTJ | 731 (1.18\%) | 116 (1.46\%) | 135 (1.76\%) |
ADV,Deixis=Prox\|PronType=Dem | 700 (1.13\%) | 77 (0.97\%) | 92 (1.20\%) |
VERB,Mood=Ind\|Number=Sing\|Person=3\|<br>Tense=Past\|VerbForm=Fin | 670 (1.09\%) | 96 (1.21\%) | 97 (1.27\%) |
PRON,Case=Gen\|Number=Sing\|Person=3\|<br>PronType=Prs | 643 (1.04\%) | 82 (1.03\%) | 88 (1.15\%) |
NUM,Case=Nom\|NumType=Card\|Number=Sing | 615 (1.00\%) | 65 (0.82\%) | 81 (1.06\%) |
NOUN,Case=Gen\|Number=Sing | 578 (0.94\%) | 90 (1.13\%) | 64 (0.84\%) |

## Top 20 abstract paradigm stats for lemmas
| Tag | Train | Development | Test |
| :--- | :---: | :---: | :---: |
|1\#1 | 43691 (70.77\%) | 5597 (70.45\%) | 5494 (71.81\%) |
| 1\#1+ы | 1153 (1.87\%) | 164 (2.06\%) | 135 (1.76\%) |
| 1+н\#1 | 796 (1.29\%) | 85 (1.07\%) | 96 (1.25\%) |
| 1\#1+мæ | 689 (1.12\%) | 119 (1.50\%) | 92 (1.20\%) |
| 1\#1+тæ | 641 (1.04\%) | 78 (0.98\%) | 84 (1.10\%) |
| 1\#1+ц | 495 (0.80\%) | 56 (0.70\%) | 68 (0.89\%) |
| 1+æв+2+н\#1+2+ди | 469 (0.76\%) | 66 (0.83\%) | 58 (0.76\%) |
| 1\#1+æй | 456 (0.74\%) | 70 (0.88\%) | 73 (0.95\%) |
| 1+æвын\#1 | 348 (0.56\%) | 33 (0.42\%) | 46 (0.60\%) |
| уы+1\#1+æ | 330 (0.53\%) | 51 (0.64\%) | 56 (0.73\%) |
| 1+й\#1+м | 315 (0.51\%) | 42 (0.53\%) | 29 (0.38\%) |
| 1\#1+йы | 314 (0.51\%) | 55 (0.69\%) | 29 (0.38\%) |
| уы+1\#æ+1 | 312 (0.51\%) | 31 (0.39\%) | 32 (0.42\%) |
| у+1+й\#дз+1 | 284 (0.46\%) | 40 (0.50\%) | 27 (0.35\%) |
| 1+ын\#1 | 253 (0.41\%) | 37 (0.47\%) | 31 (0.41\%)|
1+æ\#1+е | 245 (0.40\%) | 35 (0.44\%) | 34 (0.44\%)|
æ+1\#1 | 243 (0.39\%) | 32 (0.40\%) | 28 (0.37\%)|
1+уæвын\#1+и | 239 (0.39\%) | 33 (0.42\%) | 16 (0.21\%)|
1+æнын\#1+одтой | 229 (0.37\%) | 29 (0.37\%) | 27 (0.35\%)|
1+уыдон\#1+сæ | 217 (0.35\%) | 28 (0.35\%) | 22 (0.29\%)|
# References

# Contact
The dataset was prepared by Anna Shatskikh (anapriselec@gmail.com). All questions and comments are welcome.
# Changelog

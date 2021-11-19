# SPReadAH_Project
**SPReadAH** stands for 'Self Paced Reading for Annotation of Humor' and is a 2020 linguistic experiment held in Russian to establish common features of different types of figurative language.


## Experiment Timeline
##### 2018
The first attempt to hold our linguistic experiment.

**Software**: .pptx slides with a new word added to the next slide shown to a group of respondents.

**Language**: English.

The responses on paper answer sheets were put in an **Excel spreadsheet**, and then computationally processed.

**Results reported** at the XXX conference of the International Society for Humor Study (ISHS-2020) in Tallin, Estonia.


##### 2019
**Software**: Google presentation with a new word added to the next slide, each respondent reads the texts at their own speed on their own machine.

**Language**: Russian.

The responses on paper answer sheets were put in an **Excel spreadsheet**, and then computationally processed. 
A comparative analysis of this and previous years results was performed.

**Results reported** at the XXXI ISHS conference in Austin, USA.


##### 2020
**Software**: SPReadAH, a Python-driven software developed with a PsychoPy v.2 package. Each respondent remotely connected to a machine with the software.

Five series of experiments were run. Not all the respondets took part in all the experiments.

**Language**: Russian.

The responses were automatically collected in [.log files](https://github.com/Na-Gan/SPReadAH_Project/tree/master/Raw_Files) , which were later parsed and computationally processed.

**Results reported**: _pending_.

## Purpose
Our experiment was enspired by scientists studying humor (Victor Raskin, Semantic Mechanisms of Humor, 1985), who maintain that in a humorous text, there is a trigger word that has the reader/listener understand that they are presented with a non-bona fide text. 

We decided to check if such a word exists, and if there is a similar phenomenon in non-humorous texts, i.e. texts with metaphors.

## Hypothesis
We assume that in figurative language (as represented by texts) there is a trigger word, that launches a decyphering process in a reader/hearer, when they understand that the text they are reading/listening to imparts additional meaning(s).

## Texts
### Text Ratio
Texts with three types of indirect meaning were used in the experiment: 
* puns,
* irony,
* metaphor.

These accounted for half (12, four texts of each category) of all the texts in a SPReadAH experiment. The other half were texts in direct meaning.

### Text Sources
Texts of several categories were mostly taken from the same sources to ensure stylistic homogeneity ("Seventeen Moments of Spring" by Yulian Semyonov, "The Adventures of Dennis" by Victor Dragunsky, "Pelagia and the White Bulldog" by Boris Akunin). Puns were taken from various social media resources.

## Experiment Setup
The experiment falls in three parts:
* instructions and trial sentences,
* labelling 24 texts,
* assessing the level of funniness of texts labelled 'puns'.

### Navigaton
Within one sentence the right arrow key showed the following word. At the end of a text, the space key let the respondent proceed to the next text.

### Labels
Numbers were used to label texts:
* 1 -- pun,
* 2 -- irony,
* 3 -- metaphor,
* 0 -- text in direct meaning.

If the respontent could not label a text, they could use the key *8*. 

### Funniness Level
As the software was being developed as the respondetns took part in the experiment, funninness assessment may not be found on some of the .log files.


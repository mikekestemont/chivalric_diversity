# The Atlantis of Middle Dutch Chivalric Epics
## An estimation of the text loss using methods from ecodiversity

This (English-language) repository contains the data and code accompanying the following (Dutch-language) paper:

> Mike Kestemont and Folgert Karsdorp, "Het Atlantis van de Middelnederlandse ridderepiek. Een schatting van het tekstverlies met methodes uit de ecodiversiteit". *Spiegel der letteren* (2020).

## Data
`mnl.xlsx`: This spreadsheet contains a tabular overview of the surviving texts and text carriers that are conventionally identified as belonging to the text variety ("genre") of Middle Dutch chivalric epics. Each row represents an individual text carrier. The first column lists the titles of the texts; the right column describes the sources in which they survive. For all issues relating to the inclusion and identification of individual texts, we maximally rely on the repertory by Kienhorst:

> H. Kienhorst, De handschriften van de Middelnederlandse ridderepiek. Een codicologische beschrijving. 2 dln. Deventer, 1988.

However, as described in full in the paper's main text, we have tried to account for any new findings of sources and included these in the data if they proved relevant (situation as of 9 March 2020). Fragmentary text carriers are identified using Kienhorst's sigles (H1-H131). Other witnessess (i.e. non-fragmentary codices and newly found fragments) are described using their full signatures. Post-medieval (printed, prose, etc.) adaptations were not considered. The same goes for excerpts and heavily "Germanized" (e.g. Ripuarian) adaptations of Middle Dutch works.

## Code
`analysis.ipynb`: This stand-alone Python notebook implements and discusses all the code that was used to generate the numbers and figures given in the main paper. The notebook assumes that you are running Python version 3.6 (or higher). All dependencies can be installed via pip, for instance, from the file `requirements.txt` in the repository.
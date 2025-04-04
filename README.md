# Haggadah
~INCOMPLETE CURRENT PROJECT~
First shot at a Haggadah formatted for future adaptability

This project uses liturgical formatting and supporting stylistic and structural files to typeset the Jewish pesach seder text
templates created by John Morris : Git User 2e0Byo , for St. Joseph's Gateshead Church : eg. (https://github.com/St-Josephs-Gateshead/Masses/blob/main/All-Saints/missalette.tex)

A beautiful example of interfaith utilitarian relationships


The structure is as follows:

Haggadah.tex
             ¦__couching.tex
                ¦____blessings.tex
                     ¦
                     ¦___________%.sty
                     ¦___________%.sty

in that we wrap the blessings texts themselves in context before implementing it within the structured output document.
This should enable swift switching between languages, extension and depletion of section length, and addition of novel material and readings as desired.
Blessings can be amended or added to if gender-flexible language is required, new languages or pronunciations are preferred.

Any issues feel free to raise an error or contact me

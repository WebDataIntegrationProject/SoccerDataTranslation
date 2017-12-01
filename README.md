# SoccerDataTranslation
This repository contains all files used for the data translation phase.

## Links to input and output Data
Overall, 7 datasets were mapped:
* **Transfermarkt** (https://www.transfermarkt.de/)
* **DBPedia** (http://wiki.dbpedia.org/)
* **JokeCamp: All World Cup Players** (https://github.com/jokecamp/FootballData/blob/master/World%20Cups/all-world-cup-players.json)
* **JokeCamp: Euro 2016** (https://github.com/jokecamp/FootballData/tree/master/Euro%202016)
* **JokeCamp: Other** (https://github.com/jokecamp/FootballData/tree/master/other)
* **Kaggle SoccerDB** (https://www.kaggle.com/hugomathien/soccer/data)
* **OpenFootball** (https://github.com/openfootball/world-cup)

The input and output files can be accessed via OneDrive:
* **Source Datasets**: https://1drv.ms/f/s!AnXUcj9hNuULgfhrFmNNl6QzgAOR_g
* **Mapped Target Schemas**: https://1drv.ms/f/s!AnXUcj9hNuULgfkrG76oF2AP5OVWPw

## MapForce Processes
Contains all MapForce process files, including some (deprecated) older versions in a separate directory. Also contains additional external files that were used during the mapping.

**NOTE**: The files in the "(Deprecated) Mappings without IDs" folder hold the actual mapping files. The most recent files outside this folder only add IDs to the XMLs created by these older MapForce files.

## Target Schema
Contains an XSD file defining the target schema as well as an XML file describing a sample output file based on the XSD.

## Source Datasets Consolidation
An Excel file which were used during the investigation of attribute overlaps and the target schema definition.

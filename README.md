# xapi-sg-data-generator
Random Data Generator following the Experience API for Serious Games Profile (xAPI-SG)

## Introduction

xAPI-SG data generator is a set of Jupyter Notebooks to generate random xAPI-SG statements (traces) in a selected folder.

## Configuration

The main Jupyter Notebook is **xAPISGDataGenerator.ipynb**. 
By executing this Notebook, you need to select verb(s), type(s)_objects, numbers of traces, random IDs and random players
to generate. 
You can also select the folder to save the generated JSON file containing a list of xAPI-SG statements. 

By executing the generation of one type (like : accessible data, alternative data, completable data or gameobject data ; 
or all type) data. 
All xAPI-SG statements will be generated in a new JSON file in the selected folder with the widget file selector.

### xAPI-SG

The **Experience API Profile for Serious Games (xAPI-SG)** is a validated xAPI Profile to collect information from 
serious games. Each xAPI-SG statement (trace) represents an activity in the context of a serious game.

For more information about the xAPI-SG Profile, check [our wiki page](https://github.com/e-ucm/rage-analytics/wiki/xAPI-SG-Profile) 
and the [official vocabulary website](http://xapi.e-ucm.es/vocab/seriousgames).
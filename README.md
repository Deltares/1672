# Project 1672

## Model Cocreation Framework (MCF)

Inventory of required steps for users to participate in mapathons.

### How to Mapathon

#### Preparation (internal):

  Teams
  - Participants should be divided into teams (how many should be in one team? around 5?)
  - Create a simple sign up sheet, where participants can choose their own teams

  Tasks
  - Decide on what tasks the participants should execute

#### Preparation (external):

  Send participants an email with some preparatory tasks:

  - Sign-up sheet for teams
  - Download QGIS (preferably 3.22)
  - read the QGIS Tips and Tricks document (see [tips&trics](QGIS_TipsAndTrics.md)))
  - GIS tutorial (https://training.datapolitan.com/qgis-training/Introduction_to_GIS_Fundamentals/#1)

#### Execution:

  - Explain the goal of the mapathon
  - Introduce participants to the set-up (i.e. SpatialChat)
  - Give a short GIS tutorial
  - Assign participants to tasks

 #### Wrap-Up

  - Ask for feedback
  - Show what has been achieved
  - Explain what the next steps would be and how they could be involved further if the wanted to be

### Tutorial

To the point steps for users to get up to speed with the necessities of using the MCF. Given the fact that you are familiar with QGIS editing of features.

1. Install QGIS [Link](https://qgis.org/en/site/forusers/download.html)
We use QGIS to
2. Download the [Project 1672](https//link_to_stuff) project file and double click *.map* file
3. Zoom to tutorial area (you signed up to a specific area, e.g. 1ste Kom)
4. Decide who is picking up which hydrologic feature (there are eight!), for each of these attributes you are able to:
- edit features
- add features
- alter attribute values
5. Add alternative historic maps, for instance from https://www.oldmapsonline.org/, workflow:
- find a place
- in the right pane you find what's there
- choose map close to 1672
- for Dutch maps, you will be most likely reverted to https://uu.georeferencer.com/ (create a login to use as WMS, only if you want to add other layers than the 15+ provided)
- click on the mapname in upper right part the screen (in the part where you also find tools for opacity, editing and settings), when logged in, you find WMTS links.
- enable link with the WMS/WMTS icon in QGIS

For more (illustrated tips and trics, see [tips&trics](QGIS_TipsAndTrics.md))

### Tasks

List of tasks users can perform

-  **Add missing attributes** asdf
-  **Add a new feature** asdf
-  **Mofidy an existing feature** asdf
-  **Nominate feature for deletion** asdf

### Elements

The basic elements of a hydraulic model are

-	Dikes: Used to block water
-	Waterways: Used to transport water
-	Structures: Used to manage water

These elements come in a few basic forms. Learn to recognize them on a map. Each element requires at least the following information:

- Type (see below)
- Naam (feature name)
- Source (wikipedia link, or other source material)
- ~~Year (if known, approximate year it was )~~
- ~~Discussion (link to github issue to discuss an element? E.g. discussion on whether the dike existed in 1672)~~
- Status (e.g. 0-claim, 1-under discussion, 2-closed)

#### Dikes

Types of dikes and how to recognize them:

1. River dikes: can be found next to rivers. Are usually > 5 m high. Defend against flooding
2. Embankment: small-scale feature < 1 m high.


#### Waterways

Types of waterways and how to recognize them:

1. Rivers (rivieren, beken): natural. usually not straight
2. Ditches (sloten): man-made. used for water managament for agriculture
3. Canals (kanaal, wetering, etc.): man-made. Used for shipping by (small) boats.


#### Structures

1. Sluice (sluis, inlaatwerk): part of a dike
2. Dam (dam): located in a waterway
3. Pumps: e.g. windmills used to drain the land

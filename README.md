# Microbes in Spaaaaaaaaaaaaaaaaaaaaaaaaaaaace
### Growth data and analysis for microbial playoffs in space
#### Project MERCCURI

This repository contains all the raw data from both the ground based
and in-orbit growth experiments.  The insturments used were SpectraMax
M5e plate readers, with the device aboard the International Space
Station modified by Nanoracks, Inc. All measurements are optical
density at 600 nm (OD600).

### What is all this stuff?

*There are a lot of files here! What's going on?* Not to worry.

#### Notebooks

* `SpaceGrowthWinners.ipynb` : Generates analytical charts and tables
* `SpectraMax M5e OD600.ipynb` : Generates charts of raw data

#### Raw data

The raw data has been plotted in 12x8 grids of bar charts. Each grid
cell represents the well on the plate, and each bar represents one of
the nine reads in the well.

#### Raw data from the ground

Ground Plate 1 : 0, 24, 48, 72, 96 hours

* `Groundplate1_0.{txt,png,pdf}`  : raw data, PNG chart, PDF chart
* `Groundplate1_24.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate1_48.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate1_72.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate1_96.{txt,png,pdf}` : raw data, PNG chart, PDF chart

Ground Plate 2 : 0, 24, 48, 72, 96 hours

* `Groundplate2_0.{txt,png,pdf}`  : raw data, PNG chart, PDF chart
* `Groundplate2_24.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate2_48.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate2_72.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate2_96.{txt,png,pdf}` : raw data, PNG chart, PDF chart

Ground Plate 3 : 0, 24, 48, 72, 96 hours

* `Groundplate3_0.{txt,png,pdf}`  : raw data, PNG chart, PDF chart
* `Groundplate3_24.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate3_48.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate3_72.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Groundplate3_96.{txt,png,pdf}` : raw data, PNG chart, PDF chart

#### Raw data from Space

Space Plate 1 : 0, 24, 48, 72, 96 hours

* `Spaceplate1_0.{txt,png,pdf}`  : raw data, PNG chart, PDF chart
* `Spaceplate1_24.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate1_48.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate1_72.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate1_96.{txt,png,pdf}` : raw data, PNG chart, PDF chart

Space Plate 2 : 0, 24, 48, 72, 96 hours

* `Spaceplate2_0.{txt,png,pdf}`  : raw data, PNG chart, PDF chart
* `Spaceplate2_24.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate2_48.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate2_72.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate2_96.{txt,png,pdf}` : raw data, PNG chart, PDF chart

Space Plate 3 : 0, 24, 48, 72, 96 hours

* `Spaceplate3_0.{txt,png,pdf}`  : raw data, PNG chart, PDF chart
* `Spaceplate3_24.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate3_48.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate3_72.{txt,png,pdf}` : raw data, PNG chart, PDF chart
* `Spaceplate3_96.{txt,png,pdf}` : raw data, PNG chart, PDF chart

#### Plate mapping files

* `platemap_ground1.csv` : Map for Ground Plate 1
* `platemap_ground2.csv` : Map for Ground Plate 2
* `platemap_ground3.csv` : Map for Ground Plate 3
* `platemap_space1.csv`  : Map for Space Plate 1
* `platemap_space2.csv`  : Map for Space Plate 2
* `platemap_space3.csv`  : Map for Space Plate 3

#### Sample metadata

* `spacebugs.tsv` : bug list (index, species, name)
* `spacebugsnames_2.txt` : bug list (index, site, species, name, source)

#### Plots, charts and tables

The event data is plotted in 12x4 grids gathering all observations for
each organism into one grid cell (two experiments of six wells of nine
reads points each of five time points). They are represented as
follows :

* Box plots : space data
* Green line : median values, space data
* Brown line : median values, ground data
* Red line : Least squares fit to exponential model

Best Huddle : Highest optical density achieved

* `BestHuddle.{png,pdf}`      : Charts of all results
* `BestHuddle_top3.{png,pdf}` : Charts of top 3 results
* `BestHuddleRankings.tsv`    : Table of numerical results

Best Tipoff : Largest increase in optical density achieved on the
first day

* `BestTipoff.{png,pdf}`      : Charts of all results
* `BestTipoff_top3.{png,pdf}` : Charts of top 3 results
* `BestTipoffRankings.tsv`    : Table of numerical results

Best Sprint : Largest increase in optical density achieved on any day
of the experiment

* `BestSprint.{png,pdf}`      : Charts of all results
* `BestSprint_top3.{png,pdf}` : Charts of top 3 results
* `BestSprintRankings.tsv`    : Table of numerical results

Space vs. Ground :

The folder 

## Funding

This work was funded by a grant from the Alphred P. Sloan foundation
to Jonathan A. Eisen. Launch costs were supported by Space Florida.
Launch integration was performed by Nanorack, Inc. This project would
not have been possible without the expert help and guidance of Carl
Carruthers at Nanoracks.  

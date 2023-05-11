# napari-micromanager workshop NESM 2023


## Instructors
The instructors for this workshop are

- Ian Hunt-Isaak
- Jason Yu

## Pre-tutorial setup

So that we can best utilize our time together, please do the following before
arriving at the tutorial

1. Install napari and dependencies. Instructions [here](./installation.md).
2. Install the latest nightly build of [Micro-Manager](https://micro-manager.org/Micro-Manager_Nightly_Builds)
2. Download the notebooks and launch the `jupyter lab` application.
  Instructions [here](./notebook_setup.md).

## Goals

The aim of this workshop is to provide an introduction to controlling microscopes
using the `napari-micrmanager` package.


Python and `napari`. By the end of the workshop you should be able to
- use napari as an image viewer
- 
- perform interactive analysis with napari in [jupyter lab](https://jupyter.org/)
- make use of the [napari plugin ecosystem](https://www.napari-hub.org/)
- make simple plugins using the napari hookspecs

## Outline

### Part 1
1. Fixing installation issues
2. 
### Part 2


## Tutorial instructions

1. Do the introduction to viewing images in napari
  (`part_0_viewer_intro.ipynb`).
2. Segment and measure nuclei using the cellpose plugin
  (`part_1_segmenting_and_measuring_nuclei.ipynb`).
3. Perform spot detection using your own spot detection function. There are 3
  versions of this tutorial (see description below). They all cover the same
  content, they just require more or less coding depending on experience level.
    - `part_2_spot_detection_tutorial_beginner.ipynb`: this is the activity
      notebook for people new to image processing with python
    - `part_2_spot_detection_tutorial_advanced.ipynb`: this is the activity
      notebook for people with experience performing image processing with
      python
    - `part_2_spot_detection_tutorial_solution.ipynb`: this is the solution to
      the activity.
4. Turn your spot detection function into a napari plugin.

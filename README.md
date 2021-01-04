ReadImxfile2CalculateSpindleAngle
====
4th, January 2021. 

This program is used in the paper (link). 
The code is written by Takaki Yamamoto and Ritsuko Morita. 

## Description

This program reads an IMARIS imx file of z-stack images in which mitotic spindles and basement membrane in the developing epidermis are marked. Three-dimensional xyz coordinates of the daughter-cell nuclei and the basement membranes are extracted from imx files, and then the cell division angles against the basement membrane are calculated. Finally, we add center of mass of spindles and their nearest-neighbor surface points to imx file "spindle_surface.imx" to confirm the analysis on Imaris. 

## Requirement

Python3

## Usage

Put a target imx file and the ipynb program file (ReadImxfile2CalculateSpindleAngle_ver1.ipynb) in the same directory, and run the program.


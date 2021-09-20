# UCS757:Building Innovative Systems
# Project 1: Mosaic Creator Using Node and Python
## Submitted by:-
### Rohan Dutt
### 101803151
### COE 8

## Introduction
Mosaic creator is a web app which takes the target image as input and generates that image using thousands of small images

## Requirements
1. Python
2. NumPy
3. Pillow
4. NodeJS
5. EJS

## Live Link
https://mosaic-ds.herokuapp.com/

## Home
![Home](home.jpeg)

## Input Interface
![Interface](interface.jpeg)

## Input
![Input](input.jpg)

## Output
![Output](output.jpeg)

## Flowchart
![Flowchart](flowchart.jpeg)

## Novelty
1. Generation of dataset for images(tiles), using extensions and small python scripts  
2. Finding nearest neighbour in terms of colors for each predefined unit of the target image from the data set tiles  
3. Randomization of images to ensure that maximum pixels are covered for each color  
4. Using multiple build packs in Heroku for both Node.js and Python and experimenting with amazon ec2 for deployment

## Limitation
This technique is dependent on the variety of images in the dataset in terms of colors, higher the number of images in each color, better will be the mosaic.


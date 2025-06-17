# Conceptual Document (Developers and Advanced Users)

## Overview

	This overview covers information about the music analysis application ‘MyFavouriteAlbums’ from the perspective of a developer interested in adding functions of their own, or an advanced user who might want to customise the dataset by adding and rating their own favourite albums or removing existing entries. This includes basic information about Shiny and RStudio. It is assumed that readers have interest or have some experience in coding.

## What is MyFavouriteAlbums (MFA)?

	MFA is a simple, modular, and interactive Shiny application written in R for music analytics. MFA utilises several R packages to work. These are extensions to the R language that are shared online and can be downloaded and installed to add functionality to MFA’s code. For example, one of the packages in MFA is ‘dplyr’, which is what gives MFA the functionality to view and arrange our data into smaller subsets.

## Data

	MFA comes pre-configured with these variables : album name, album release year (1993-2024), album rating (1-10) and ranking, band/artist, and vinyl ownership. The data presented is stored in a CSV file (Comma Separated Value). Advanced users and developers interested in modifying the dataset may add or remove entries, change variable values, or even add entirely new variables (genre, favourites, album duration etc).

## 

## R and R Studio

R is a programming language that excels in statistical analysis and data visualisation. Part of why it excels at this are due to what’s called packages. Packages are bundles of code that have already been compiled – think of them as a program within a program. These packages can be downloaded and installed to give your program additional functionality. For example MFA uses two packages from the ‘tidyverse,’ ggplot2 and dplry, which allows your program to plot graphs and manipulate data respectively.  
R Studio is an IDE (integrated development environment) for the language R. An IDE is a software application that facilitates the writing of code by giving you tools integrated into the program. A useful comparison would be trying to write an essay on notepad versus a word processor like Google Docs. Google Docs comes with way more features to edit, format, and generally facilitate the writing process. RStudio specifically comes with useful features like ‘plotting, history, debugging, and workspace management.’

	  
	  

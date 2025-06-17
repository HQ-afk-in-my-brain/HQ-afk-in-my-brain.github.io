# Conceptual Document (Basic Users)

## Overview

	This overview covers information on the music analysis application ‘MyFavouriteAlbums’ from the perspective of a user that is interested in music data analysis. It is assumed that the reader has no interest or experience with coding for use of this application. This will include the application’s dataset, functionality and user interface, as well as tools required.

## What is MyFavouriteAlbums (MFA)? 

MFA is an interactive application that users can use to analyse and display data from existing “best of” music lists from 1993 to 2024\. MFA uses different filters and visualisations to display album entries in meaningful ways. For example, a user interested in music from the year 2000 can use the ‘Top Albums by Year’ function which will display a ranked list of albums of that year. Another user interested in a particular artist, such as Belle and Sebastian, can use the ‘Bands and Artists’ function to see how many albums made it onto a year’s ‘best-of’ list, and the artist’s average rating (in this case, 25, with an average rating of 8.40).   
	  
In this way, users of MFA can discover patterns, trends, artist trajectories and many more insights\!

## Data

Cruically, the data used in MFA is preconfigured into the application from an existing dataset. This data includes: album name, album release year (1993-2024), album rating (1-10) and ranking, band/artist, and vinyl ownership.

## 

## 

## Functionality:

## 

	Figure 1: MFA’s user interface, displaying \#1 albums 

MFA currently supports 5 different views as indicated by the 5 different tabs. These include:

Number One Albums:  using the slider defines a given time period and displays the number one albums in that range, providing a chronological view of annual favourites.

Bands and Artists: selecting an artist from a drop-down menudisplays information about a particular artist, listing any album of theirs that has been rated, total number of albums rated, and their average rating

Top Albums by Year: selecting a year presents a ranked list of albums for that year

Vinyl: focuses on displaying information about vinyl ownership. Includes vinyl ownership by year, and highly-rated albums that are not owned in vinyl form (purchase recommendations)

Band Comparison: plots information about two artists against each other on a graph comparing album ratings across time. 

## MFA limitations

Customisation: MFA does not currently provide built-in support for personal customisation of album entries – adding, removing, and rating personal album entries is not possible. However, hardcore music enthusiasts may be interested in using their own datasets to analyse their own personal music journey. For customisation functionality, please refer to the relevant sections in documentation for developers and advanced users.

Integration: MFA does not currently support interfacing with other music streaming services, web applications, or databases – no information can be directly queried and will have to be formatted manually.

## Tools required

MFA is built using Shiny, which builds a web application from R, a coding language specialising in statistical analysis. For basic users who may not want to download or install anything, MFA can be accessed via an internet connection with a personal web browser. A link is required to access, provided here [MFA](https://cholstro.shinyapps.io/shiny-music/).

# 


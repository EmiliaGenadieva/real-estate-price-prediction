# Real Estate Price Prediction
    This part of the project was completed in a team. This readme file is adjusted accordingly to offer code for completing the challenge of data aquisition. How to assemble the different text files and shape the data in the form we are requested.
## Description
    We are given the task to collect a certain amount of data from a website:
   - Locality
   - Type of property (House/apartment)
   - Subtype of property (Bungalow, Chalet, Mansion, ...)
   - Price
   - Type of sale (Exclusion of life sales) -> Venue of the sale -> Tenement building
   - Number of rooms  -> Bedrooms
   - Living Area	->	Living area
   - Fully equipped kitchen (Yes/No)  -> Kitchen type
   - Furnished (Yes/No) ->	Furnished
   - Open fire (Yes/No)	->	How many fireplaces?
   - Terrace (Yes/No)
    -    If yes: Area -> Terrace surface
   - Garden (Yes/No)
        If yes: Area -> Garden surface
   - Surface of the land -> Surface of the plot
   - Surface area of the plot of land
   - Number of facades	-> Number of frontages
   - Swimming pool (Yes/No)	-> Swimming pool 
   - State of the building (New, to be renovated, ...)	-> Building condition
## Installation
>In this repo one can see a code example how to collect data from a website. Each member of the team has his own techniques how to apply the written code.
>Each member contributed for writing and assembling the code. The code is tested on different OS systems(Mac, Windows, Ubuntu).
>The technologies used are 'Beautiful Soup' and 'Selenium' server. Without these libraries installed on the computer running of this code snippets is not possible.
## Usage
> The code provided can be mainly devided in 2 code divisions:
> The first part is collecting links for individual pages on the website.
> In the second part we collect all the data for the data fields in our dataset. 

## Contributors
   > Emilia, Sheetal, Zakaria, Heritie
## Timeline
  ### Troubleshooting column names and we jointly agreed that:
  > Some of the fields we could clearly identify as above mentioned. The value in the right side after slash '-' is the criteria we see in the English translation of the website. We see bv. by 'Type of sale' that there are mainly 2 values 'Venue of the sale'	and 'Tenement building'. For now we create 2 columns in our dataset and we merge them later to create 1 single column. <br />
  > There is currently bv. only 'Terrace' field and not yet 'Garden'. (Found just 1 'Terrace' as 'Yes' in 1 entry) Garden surface is given, so we asume that there is also a garden. We add later a column and in the row where there is the 'Garden area' given, we specify 'Garden' (Yes) or (0) by cleaning for analysis. <br />
    
  > 'Type/Subtype of property' will be manually added. We can append a column to the dataset after extracting a set of url links. The dataframe is read and this information can be adjusted. <br />
   More particular steps: extract the ID and Locality from the url link of the page. Hopefully this works for all url links.
    
    Further enhancements: Some pages can give very soon 404 error... <br />
    We keep each other updated if code give any kind of error. We also help each other to identify issues.
   
 The last day is for code completion and data gathering. <br />
 Issues : advertisements of new sale properties can't be filtered by search. They are quickly noticed in a file with url links and manually removed. These pages have no valuable information which we can use. We notice quickly these differences in the url links.
    
   ## Personal situation
   Each member of the team expressed that he wants to further improve the code and the quality of the datafields. 
   ## Analysis
   >The project continues with analysing data content. There are many different python libraries to visualize the different fields of the dataset.
   >They display the number of the columns and summarize the values.
   >One can select only a subset of the whole dataset and visualize it.
    
    

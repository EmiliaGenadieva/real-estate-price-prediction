# real-estate-price-prediction

    
    We are given a certain amount of data which we need to collect:
   Locality
    Type of property (House/apartment)
    Subtype of property (Bungalow, Chalet, Mansion, ...)
    Price
    Type of sale (Exclusion of life sales)- Venue of the sale	- Tenement building
    Number of rooms	- Bedrooms
    Living Area	-	Living area
    Fully equipped kitchen (Yes/No)	 - Kitchen type
    Furnished (Yes/No)	-	Furnished
    Open fire (Yes/No)	-	How many fireplaces?
    Terrace (Yes/No)
        If yes: Area		- Terrace surface
    Garden (Yes/No)
        If yes: Area		- Garden surface
    Surface of the land	 - Surface of the plot
    Surface area of the plot of land
    Number of facades	- Number of frontages
    Swimming pool (Yes/No)	- Swimming pool 
    State of the building (New, to be renovated, ...)	- Building condition
    
    Some of the fields we could identify as above mentioned. The value in the right side after '-' is the criteria we see by the English translation of the website.
    We see bv. by 'Type of sale' that there are mainly 2 values 'Venue of the sale'	and 'Tenement building'. For now we create 2 columns in our dataset and we merge them later to create 1 single column.
    There is currently bv. only 'Terrace' field and not yet 'Garden'. (Found just 1 'Terrace' as 'Yes' in 1 entry)
    Garden surface is given, so we asume that there is also a garden. We add later a column and in the row where there is the 'Garden area' given, we specify 'Garden' (Yes) or (0) by cleaning for analysis.
    
    Given is that 'Type/Subtype of property' will be manually added. We can append a column to the dataset after extracting a set of url links. The dataframe is read and this information can be adjusted.
    More particular steps: extract the ID and Locality from the url link of the page. Hopefully this works for all url links.
    
    Further enhancements: Some pages can give very soon 404 error...
    We keep each other updated if code give any kind of error. We also help each other to identify issues.
    
    
    
    
    

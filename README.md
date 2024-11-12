# bangkok_listing_recomm

This project was made as my capstone submission on 2nd Module (alhamdulillah half way to go).
Aiming as more data based influencer, I want to give listing recommendation for people who plans on trip to Bangkok with Airbnb.
Data cleaning and visualization was done in Tableau. I also made Tableau dashboard for better visualization.

Link List:
1. Jupyter notebook is saved in this repository
2. Tableau dashboard >> https://public.tableau.com/app/profile/andita.eka.putri/viz/Tableau_Analysis_17313342693030/Dashboard1?publish=yes
3. Power point >> https://drive.google.com/file/d/1UP2QMAbep24kjZLTP2yTrh-DdF5CNKKf/view?usp=sharing
4. Video presentation >> https://drive.google.com/file/d/1Saiu-RKP5PTyyczTT49sv5gGQ2PzjjuN/view?usp=drive_link

In this analysis I used only descriptive analysis which I think is enough for now to get better recommendation on the listing.
It started with data cleaning on points as below:
1. Dropping null values
2. Dropping zero values in listing price
3. Change last review variables from object to datetime
4. Checking on duplication
5. Removing price outliers
6. Removing minimum_nights outliers
7. Grouping listing based on price

Recommendation was curated based on listing profiling results on
1. Listing distributions in each neighborhood, correlating it with price analysis
2. Listing distributions in each room type, correlating it with price analysis
3. Minimum nights required
4. Listing distributions in each price category
5. When is the peak season

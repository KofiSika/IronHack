# PREDICTING BIKE SHARING USAGE BASED ON WEATHER AND CALENDAR 
![Bike_Sharing_Image](https://user-images.githubusercontent.com/92721547/146390409-09accbf3-190e-4f95-b546-808daf4c0c49.jpg)


## BACKGROUND 
## DATA SOURCE 
The Data was sourced from the UCI repository. It is  a dataset from CAPITAL BIKES based in Washingtong DC. 
## TOOLS USED FOR THE PROJECT
- TRELLO 
- TABLEAU 
- PYTHON 
## STEPS TAKEN IN PYTHON 
### Data Importation and Cleaning 
I imported the csv file ```Hour.csv``` from the UCI website. Performde basic data cleaning steps on the dataset like renaming headers and changind data types to their appropriate formats. 
### Visualisation Of The Data
The data set was visualised using Python tools like ```seaborn``` and ```matplotlib``` to look for outliers and correlations. 
Further used a ```heatmap``` correlation matrix to also check for possible correlations between variables and the target column 
### Feature Engineering 
Then some features were dropped which were considered as too much of a direct correlation to the target cariable. Examples being ```Registered``` users and the ```casual``` bike users column. Also i indexed the dataframe to later allow for a join in tablaeu to be able to plot the predicted points against the actual points. 

![Predicted vrs original](https://user-images.githubusercontent.com/92721547/146392924-4fdf17c7-5772-47d2-b344-e5313a50080b.png)

### Modelling 
First i run three regression model methods which gave the following accuracy and error margins
- Linear Regression 
- Decision Tree 
- Random Forest 
After this in order to imporove the model i run furhter stacked models and the best result of the that was a cocktail of all 3 models which yielded a a percentage accuracy of ```90.2%``` with a margin error of 36 users 

### Web Scraping
## CONCLUSION 
## CHALLENGES 
## POSSIBLE EXPANSION 







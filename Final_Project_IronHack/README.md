# PREDICTING BIKE SHARING USAGE BASED ON WEATHER AND CALENDAR FEATURES
![Bike_Sharing_Image](https://user-images.githubusercontent.com/92721547/146390409-09accbf3-190e-4f95-b546-808daf4c0c49.jpg)


## BACKGROUND 
Bike sharing Apps are rapidly growing in Popularity and Usage. With cities increasingly moving to cleaner methods of transportation and healthy living more people are resorting to using bikes and bike sharing apps for their convenience. This situation presents an opportuinity where the Data generated can be used in analysis to predict mobility and movement in a city and of people. In this example we use a dataset from ```Capital Bikes``` from ```Washington DC``` to build a model and then further expand on this model to scrape live data of the internet and make future predictions of people movemnt as well. 
## DATA SOURCE 
The Data was sourced from the UCI repository. It is  a dataset from CAPITAL BIKES based in Washingtong DC. 
## TOOLS USED FOR THE PROJECT
- [TRELLO](https://trello.com/b/FzIITYV4/final-project) 
- [TABLEAU](https://public.tableau.com/app/profile/kofi.ampomah/viz/Final_Project_IronHack/PredictionVrsOriginal?publish=yes) 
- [PYTHON](https://github.com/KofiSika/IronHack/blob/main/Final_Project_IronHack/Python%20Code/Final_Project_Bikes_Movement.ipynb)
## STEPS TAKEN IN PYTHON 
### Data Importation and Cleaning 
I imported the csv file ```Hour.csv``` from the UCI website. Performed some basic data cleaning steps on the dataset like renaming headers and changind data types to their appropriate formats. 
### Visualisation Of The Data
The data set was visualised using Python tools like ```seaborn``` and ```matplotlib``` to look for outliers and correlations. 
Further used a ```heatmap``` correlation matrix to also check for possible correlations between variables and the target column 
### Feature Engineering 
Then some features were dropped which were considered as too much of a direct correlation to the target cariable. Examples being ```Registered``` users and the ```casual``` bike users column. Also i indexed the dataframe to later allow for a join in tablaeu to be able to plot the predicted points against the actual points. 


### Modelling 
First i run three regression model methods which gave the following accuracy and error margins
- Linear Regression 
- Decision Tree 
- Random Forest  <br> 

After running these models, in order to imporove the model i run furhter stacked models and the best result of the that was a cocktail of all 3 models which yielded a a percentage accuracy of ```90.2%``` with a marginal error of 36 users. Find a plot of the predictions against the actual data below: 

![MLPredictions2](https://user-images.githubusercontent.com/92721547/146447483-c325329c-e53c-44db-a06f-485626c94d7c.png)


### Web Scraping

## CONCLUSION 
In summary an accuracy of ```90.2%``` is a fairly good prediction rate and given more information from the data like location of bikes and stations the model can be imroved to aid distribution of bikes by location as well. 

## CHALLENGES 
- Not being able to scrape large amounts of weather data from the future makes it a difficult to be able to make long term predictions based on this model. '
- Also there is a lack of geographical location information in the data which limits the functionality of such a model

## POSSIBLE EXPANSION 
- Can be expanded upon to place bikes in actual locations needed when merged with location data
- Data can also be utilised to tell movement treands and patterns of users which can be used in lifestyle prediction for marketing 




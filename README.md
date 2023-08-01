## California House Pricing Prediction

### Application Demo Page:
![image](https://github.com/S-shubham08/californiahousepricing/assets/127888794/fd926bca-9232-4c87-a710-4cf49ea73d4b)

### Software and Tools Requirments

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudia.com/)
3. [HerokuAccount](https://heroku.com)
4. [Git CLI](https://git-scm.com/downloads)

### Project Description
This project aims to predict house prices in various regions of California using machine learning techniques. It involves data exploration, preprocessing, feature engineering, model training, and a Flask web application for making predictions.

### Dataset
**Data Set Characteristics:**
California Housing dataset
- Number of Instances: 20640
- Number of Attributes: 8 numeric, predictive attributes and the target
- Attribute Information:
  * MedInc        median income in block group
  * HouseAge      median house age in block group
  * AveRooms      average number of rooms per household
  * AveBedrms     average number of bedrooms per household
  * Population    block group population
  * AveOccup      average number of household members
  * Latitude      block group latitude
  * Longitude     block group longitude


### Installation:

1. Create a new Environment
```
conda create -p venv python=3.8 -y
```
2. Install the required packages
```
pip install -r requirements.txt
```
### Usage
1. Run the Flask application:
```
python app.py
```
2. Open your web browser and go to http://localhost:5000 to access the web application.
3. Enter the necessary features (e.g., number of rooms, location, etc.), and the application will display the predicted house price.








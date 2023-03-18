# Rule Based Customer Segmentation 
## Gezinomi Dataset

![image](https://user-images.githubusercontent.com/98966968/226106631-2920e13e-53b0-4c00-ac8b-7ed956c942b7.png)

### Dropping the variables that are not needed and categorizing the SaleCheckInDiff variable

![image](https://user-images.githubusercontent.com/98966968/226115482-405d8231-6311-4526-b6bd-dc371e9634ec.png)

These variables were dropped because they would not be useful for our purposes. 
Created a new column for categorize SaleCheckInDiff.

### Filling in missing values
Missing values were filled with the mean of other data that met the criteria for missing values.
Thus every missing value has been filled according to their criteria.

### Ourliers

![image](https://user-images.githubusercontent.com/98966968/226110303-50f1a1d4-d79f-4e69-9af9-b2849f442e05.png)
![image](https://user-images.githubusercontent.com/98966968/226110312-db2fe935-9d35-4a8f-b97b-52b42b9c6076.png)


![image](https://user-images.githubusercontent.com/98966968/226110217-b3fecb6a-54e4-4ef7-918f-9a1b870faf1c.png)

Outliers found, reviewed and were replaced by the average of the "All Inclusive" attribute.
There are no outliers anymore.

![image](https://user-images.githubusercontent.com/98966968/226113264-93317f7f-1860-484f-ad64-c8fb901b9ed8.png)

### Creating a column for level based segmenetation
![image](https://user-images.githubusercontent.com/98966968/226113661-8d3bdafc-bd3b-4288-a9e5-60ca9ec62cc5.png)

### Creating a function

Example :

![image](https://user-images.githubusercontent.com/98966968/226113990-5a774a5c-3d09-4575-a298-2d6c08ad929c.png)


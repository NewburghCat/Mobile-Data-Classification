# Mobile Price Classification 

## Classification Analysis

**Author**: JodyAnn Bradford 

### Business problem:

A mobile start wants to estimate its mobile prices based on past sales data from other mobile companies. 

### Data:

Data source: https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

### Content:

A mobile company, wants to give a tough fight to big companies like Apple,Samsung etc.

They do not know how to estimate the prices for mobile phone in their company. To solve this problem the company collects sales data of mobile phones from various companies.

They want to find out if some relationship exist between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price.

## Methods

- The dataset used for model building contained 2000 rows of 21 columns. 

- The methods used are data cleaning, visualization graphs, preprocessing, imputing(simple imputer), and various classification methods in python. Specifically logistic regression, K-Nearest neighbors, Feature engineering(PCA) and Confusion metrics


## Data Library 

1. ID: ID Number of Customers.

2. Battery Power: Total energy a battery can store in one time measured in mAh.

3. Blue: Has bluetooth or not.

4. Clock Speed: Speed at which microprocessor executes instructions.

5. Dual Sim: Has dual sim support or not.

6. FC: Front Camera mega pixels

7. Four_G: Has 4G or not

8. Int Memory: Internal Memory in Gigabytes

9. M_DEP: Mobile Depth in CM

10. Mobile WT: Weight of mobile phone

11. N_Cores: Number of cores of processor

12. PC: Primary Camera mega pixels

13. PX_Height: Pixel Resolution Height

14. PX_Width: Pixel Resolution Width

15. RAM: Random Access Memory in Megabytes

16. SC_H: Screen Height of mobile in CM

17. SC_W: Screen Width of mobile in CM

18. Talk_Time: Longest time that a single battery charge will last when you are

19. Three_G: Has 3G or not

20. Wifi: Has wifi or not

21. Price Range 

## Results

### Here are examples of how to embed images from your sub-folder


#### Price Range vs Wifi

<img width="624" alt="Screen Shot 2022-10-04 at 3 59 43 PM" src="https://user-images.githubusercontent.com/101212659/193960145-984cb2d1-3b20-4397-add5-af1c97d2424e.png">

> Sentence about visualization.

#### Price Range vs Ram Speed

<img width="623" alt="Screen Shot 2022-10-02 at 4 04 43 PM" src="https://user-images.githubusercontent.com/101212659/193474887-5c40bd9b-eaa7-45b5-acc9-c1907c153401.png">

## Model

The final model chosen is the decision tree classifier without PCA. The mobile price range for all new companies is critical to their branding, and quality matters to consumers. The stakeholder's interest in the ram speed with correlation to the price range is noteworthy. It turns out that the better ram speed in a phone equates to better, faster data. In addition to switching between apps(gadgetsnow.com). I chose the accuracy of the model to be the deciding factor for the stakeholders. Out of the logistic regression model, KNN means model and the decision tree model. 

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

The final model selected is the decision tree classifier. It performed the best out of both KNN means and logistic regression with PCA. The poorest model was the knn means with a testing accuracy of 0.5 and the f1 score of 0.6.  The logistic regression model was not for of with an accuracy score of 0.6. I mention the accuracy score because the customer's main concern is to decide if this model could predict a good price range for their phones.  The decision tree does perform the best with an accuracy score of 0.7 but based on the limited info shared. This model would not be recommended. For instance, phone prices vary from year to year and there is no known date or year feature given to accurately determine if this model would be of any benefit. 

## Limitations & Next Steps

Lack of information for data source. 

### For further information


For any additional questions, please contact **email**

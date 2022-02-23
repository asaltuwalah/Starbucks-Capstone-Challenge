# Starbucks-Capstone-Challenge

### Libraries used in the project
- pandas
- numpy
- math
- json
- sklearn
- matplotlib
- seaborn

### About Datasets

The data is contained in three files:

- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.) <br>
- profile.json - demographic data for each customer <br>
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

<b> portfolio.json

- id (string) - offer id <br>
- offer_type (string) - type of offer ie BOGO, discount, informational<br>
- difficulty (int) - minimum required spend to complete an offer<br>
- reward (int) - reward given for completing an offer<br>
- duration (int) - time for offer to be open, in days<br>
- channels (list of strings)

<b> profile.json

- age (int) - age of the customer<br>
- became_member_on (int) - date when customer created an app account<br>
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)<br>
- id (str) - customer id<br>
- income (float) - customer's income

<b> transcript.json

- event (str) - record description (ie transaction, offer received, offer viewed, etc.)<br>
- person (str) - customer id<br>
- time (int) - time in hours since start of test. The data begins at time t=0<br>
- value - (dict of strings) - either an offer id or transaction amount depending on the record
  
  
  
 ### Problem Statement 
The purpose of this project would be to see how various demographic groups respond to the offers and to seek to forecast whether or not a consumer would responds to Starbucks offers.
  
 ### Metrics
 For measuring the performance of models I used the accuracy score for each models to see how accurate are the models.
 

### Summary of the project
 
I was interested to know what are the features that effecting customer decision to response to Starbucks offers. 
I built multiple models like: <br>
 - KNN
 - Random Forest 
 - Decision Tree 
 
I used these algorethoms to predict whether the new customers will responds to Starbucks offers or not.
 
Where the best model accuracy was Decision tree with 77% accuracy.
 
 
### Acknowledgement
 
- Udacity for providing such a complete Data Science Nanodegree Program
- Starbucks for providing the datasets
  

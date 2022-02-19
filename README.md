# Starbucks-Capstone-Challenge

### About Datasets

The data is contained in three files:

 portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.) <br>
 profile.json - demographic data for each customer <br>
 transcript.json - records for transactions, offers received, offers viewed, and offers completed

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
 I'm intrested to know what are the features that effcting customer decisian to respons to starbucks offers.Therfoer, I built multible models such as KNN, Random Forest and   Decision Tree to predict whether the new customers will responds to starbucks offers or not. 
  
 ### Metrics
  I used both Accurcy and F1-score. I used F1-score since it is a weighted average of the precision and recall metrics
  
  
  
  

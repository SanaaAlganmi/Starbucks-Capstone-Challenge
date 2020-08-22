# Starbucks-Capstone-Challenge
## Table of Contents
1. [Installation](#installation)
2. [Introducing ](#dataset-introduction)
5. [File Descriptions](#files)
4. [Results](#results)
5  [Licensing, Authors, Acknowledgements] (#Acknowledgements)

### Installation <a name="installation"></a>
For running this project, the most important library is Python version of Anaconda Distribution. It installs all necessary packages for analysis and building models. 
 
### Introducing <a name="dataset-introduction"></a>
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

Your task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

Every offer has a validity period before the offer expires. As an example, a BOGO offer might be valid for only 5 days. You'll see in the data set that informational offers have a validity period even though these ads are merely providing information about a product; for example, if an informational offer has 7 days of validity, you can assume the customer is feeling the influence of the offer for 7 days after receiving the advertisement.

You'll be given transactional data showing user purchases made on the app including the timestamp of purchase and the amount of money spent on a purchase. This transactional data also has a record for each offer that a user receives as well as a record for when a user actually views the offer. There are also records for when a user completes an offer.

Keep in mind as well that someone using the app might make a purchase through the app without having received an offer or seen an offer.t.



### File Descriptions <a name="files"></a>
There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions
1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json - demographic data for each customer
3. transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Results<a name="results"></a>
The main observations of the code are published [here](https://medium.com/@sanaaalghanmi/starbucks-capstone-challenge-9245fbbad9f).

## Licensing, Authors, Acknowledgements <a name="Acknowledgements"></a>
I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and Starbucks for the dataset..

# **Bajaj Allianz Hackathon**

## **Create segments for insurance products**


## **How customers buy insurance?**
World is still recovering from COVID-19 pandemic that brought many industries to a standstill for almost two years. However, it had an opposite effect on life insurance penetration in India. It took India’s life insurance penetration level from 2.82% in 2019 to 3.2% in 2020, which is close to the global average. The pandemic also gave push to online sales of life insurance. In financial year 2019-20, 12.5% of overall term policies by premium were purchased by Indians online. However, on savings side, it is still muted with less than 1% of total premium by channel.

For most Indians, insurance agents still are the ones who introduced the concept of life insurance to them and they remain an important part of customer’s policy purchase decision. But, with or without COVID, trends suggest that India is rapidly shifting to digital channels for purchase of financial products and insurance is not untouched by this phenomenon. Where agent influence remains a dominant influencing factor when it comes to insurance policy purchase, a lot of people are doing their own research and opting for direct purchase from online platforms. In such scenario, it becomes important to understand how they make purchase decision and how they select right policy for themselves.


## **The Challenge**
There are various factors that affect customer’s policy purchase decisions in addition to the vast number of channels - digital or otherwise. In this hackathon we want you to:

Create segments of customers based on their persona. The segments should be defined clearly and should not be too similar to each other,
Evaluate weightage of product features for each of the customer segments created,
Create a recommender systems (statistical based model or algorithm) to find the attributes influencing the customer’s preference for product features
Identify effect of market factors affecting these segments
The model needs to be specific to Indian life insurance market, hence, if you are using any data from public sources, ensure that it is relevant to India market.


## **Dataset Description**

### **Data for analysis:**
Dummy data containing demographic information and relevant product category has been provided by BALIC.
Marker attributes for relevant time period can be fetched by participants using public sources. The model needs to be specific to Indian life insurance market, hence, if you are using any data from public sources, ensure that it is relevant to India market.


### **Input parameters:**
The customer segmentation problems requires the following input parameters:

- Customer attributes, made available in the dataset.

- Market attributes - The policy issuance month has been made available in the data. Basis this, participants are free to create features on macro-economic indicators that may be relevant to the problem statement. For instance, on particular month, is NIFTY50 index affecting the customer’s choice? Similarly, other macro factors relevant to the Indian Market can used from external data sources as well, such as India Stock Market. The external sources of data must be explicitly mentioned in the documentation.

- Location intelligence - The pincode of customer will be shared in the data

- Product Features - The product category will be given with the data. Using this, features can be created. e.g. if ULIP is the product category, risk category of the customer can be defined.


### **Files**

**train.csv** - the training dataset

**test.csv** - the test dataset

**sample_submission.csv** - a sample submission file in the correct format

**data_dictionary.csv** - This contains the definitions for the various acronyms that you will need to understand each variable.

### **Columns**

ID - Customer ID

AGE - Age of customer when policy is bought

EDUCATION - Education of customer

OCC - Occupation of customer (professional are Doctors, CA), business is Self-employed

PINCODE - Customer residence pincode

PROD_CATEGORY - Product Type (ulip - Market linked insurance policy, trad - non-market linked policy, term - term product)

INCOME_SEGMENT - Customer Income segment

PROSPERITY_INDEX_BAND - Prosperous location

QUALITY_SCORE_BAND - Customer Quality

ISSUANCE_MONTH - Policy issuance month


# OVERVIEW
  - **EDA (Exploratory Data Analysis)** done for a *Global wealth management* bank's dataset to understand the parameter's that **strongly correlate** to the Financial Analysts (FAs) performance with increase in amount of managed wealth or “New Net Money” (NNM).
  - Used tree based model **(decision tree and random forest)** and non tree based ML models **(Lasso with normalisation and standardisation,randomized Lasso and recursive feature elimination)**  to find the important features on which the FA should focus to increase the "new net money".
 
# DATA DESCRIPTION
Financial Analyst (FA) performance data is provided in a single Excel sheet with about 120 features for each analyst(4186 analysts). Features belong to one of these categories:

  - FA Details 
  - Branch Detail
  - Product Mix (Rev)
  - Product Mix (Assets)
  - Product Penetration
  - Client Acquisition Details
  - Net New Money Details
  - Marketing Details
  - Wealth/Financial Planning
  - Client Retention
  - Digital Tools
  - Banking and Lending
  - Client Age Distribution
  - Segment Index Score
  
“Attribute Description” sheet contains description for each of the features.

# FINDINGS
List of features which strongly correlate to the FA performance are:
  - Client Acquisition Details-YTD $1m+ QNRs (March-2018)
  - Net New Money Details-FA Comp. NNM 2015
  - Net New Money Details-FA Comp. NNM 2016
  - Product Mix (Assets)-CASH 
  - Net New Money Details-FA Comp. NNM 2014
  - Product Mix (Rev)-EQUITIES
  - Product Mix (Rev)-ADVISORY
  - Product Mix (Rev)-MUNICIPALS
  - -# accts enrolled in MTP

Points 2,3,5 (related to NNM) from the above list is something that the FA can't improve as it's a past record. He can focus to improve upon other features to increase the NNM.

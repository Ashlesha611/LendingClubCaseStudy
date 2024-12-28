# Lending Club Case Study
> The aim of this case study is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This case study uses the techniques in EDA for getting the outcomes to understand the driving factors (or driver variables) behind loan default, i.e. the 
    variables which are strong indicators of default.
- Background : This dataset is of a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a 
    loan application, the company has to make a decision for loan approval based on the applicant’s profile.
- Business probem : Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by 
    the lender when the borrower refuses to pay or runs away with the money owed. In this case, the customers labelled as 'charged-off' are the 'defaulters'.   
    To identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such 
    applicants using EDA is the aim of this case study.
- Dataset : Dataset contains the complete loan data for all loans issued through the time period 2007 t0 2011 and contains information about past loan applicants 
    and whether they ‘defaulted’ or not

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
  The major driving factors behind loan default prediction and to reduce credit loss are-
  1)  DTI
  2)  Verification_status
  3)  Interest rates
  4)  pub_rec_bankrupties
  5)  Grades

  Recommendations-
      Applicants should not have high DTI ratio.
      Applicants should not be from California(CA), Florida(FL), New York (NY) and Texas (TX) states and applications should be verified properly.
      Interest rate should not be higher as that increases charged off.
      Public record of bankruptcies for applicant’s should be checked properly.
      Grade should be higher for the loan approval as that means low risk.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy          -version 1.20.3
- pandas         -version 1.3.4
- seaborn        -version 0.11.2
- matplotlib     -version 3.4.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Upgrad IIT Bangalore as a case study for MS in AIML

## Contact
  Created by [@Ashlesha611] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

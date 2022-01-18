# Credit Risk: Classification Modeling "Probability of Default"

<p align="center">
  <img width="700" height="400" src="https://user-images.githubusercontent.com/67468718/149666189-fbae54b6-b123-4905-8348-e59ec94cdb1c.png">
</p>

## Introduction:

If you've ever applied for a credit card or loan, you know that financial firms process your information before making a decision. This is because giving you a loan can have a serious financial impact on their business. But how do they make a decision? In this porject+, we will wrangle and prepare credit application data. After that, we will apply machine learning and business rules to reduce risk and ensure profitability. we will use two data sets that emulate real credit applications while focusing on business value.

**So, what exactly is credit risk?** 

* The possibility that someone who has borrowed money will not repay it all
* Calculated risk di(erence between lending someone money and a government bond
* When someone fails to repay a loan, it is said to be in default
* The likelihood that someone will default on a loan is the probability of default (PD)

**Expected loss**

* The dollar amount the firm loses as a result of loan default
* Three primary components:
  * Probability of Default (PD): is the likelihood someone will default on a loan.
  * Exposure at Default (EAD): is the ratio of the exposure against any recovery from the loss.
  * Loss Given Default (LGD): is the ratio of the exposure against any recovery from the loss.

```
Formula for expected loss:

Expected loss= PD * EAD * LGD
```

## Dataset 

For modeling probability of default we generally have two primary types of data available:

* Application data: which is data that is directly tied to the loan application like loan grade. 
* Behavioral data: which describes the recipient of the loan, such as employment length.

The data we will use for our predictions of **probability of default** includes a mix. This is important because application data alone is not as good as application and behavioral data together. Included are two columns which emulate data that can be purchased from credit bureaus. Acquiring external data is a common practice in most organizations. These are the columns available in the data set. Some examples are: personal income, the loan amount's percentage of the person's income, and credit history length. Consider the percentage of income. This could affect loan status if the loan amount is more than their income, because they may not be able to afford payments.




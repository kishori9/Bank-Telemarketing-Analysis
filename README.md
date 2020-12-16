# Bank-Telemarketing-Analysis

Name: Bank Marketing Data Set
Source Link: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
Dataset Download Link: https://archive.ics.uci.edu/ml/machine-learning-databases/00222/
Abstract: The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution.
Classification Goal: Predict if the client will subscribe to a term deposit (variable y).
 
https://www2.1010data.com/documentationcenter/beta/Tutorials/MachineLearningExamples/index_frames.html?q=BankMarketingDataSet.html
https://hrdailyadvisor.blr.com/2012/08/07/understanding-eeo-job-categories-for-the-eeo-1-report/
 
Ref Links:
 
https://support.sas.com/resources/papers/proceedings17/2029-2017.pdf
https://www.kaggle.com/janiobachmann/bank-marketing-dataset
https://medium.com/@jameschen_78678/which-customers-are-more-likely-to-respond-to-banks-marketing-campaigns-3f00c512268d


 
 
Attribute Information:
Input variables:
# bank client data:
1 - age (numeric)
2 - job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
Self-employed, student, unemployed, unknown
3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
School, University, Illiterate, Unknown
5 - default: has credit in default? (categorical: 'no','yes','unknown')
6 - housing: has housing loan? (categorical: 'no','yes','unknown')
7 - loan: has personal loan? (categorical: 'no','yes','unknown')
# related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: 'cellular','telephone')
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
# other attributes:
12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
14 - previous: number of contacts performed before this campaign and for this client (numeric)
15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
# social and economic context attributes
16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)
17 - cons.price.idx: consumer price index - monthly indicator (numeric)
18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)
19 - euribor3m: euribor 3 month rate - daily indicator (numeric)
20 - nr.employed: number of employees - quarterly indicator (numeric)
 
Output variable (desired target):
21 - y - has the client subscribed a term deposit? (binary: 'yes','no')

Predicted potential customers to subscribe to a term deposit from a Portuguese banking institution by analyzing the  data related to the bank’s direct marketing campaign with a high accuracy of 90.25% 

# Bank-Marketing-Effectiveness-Prediction
Banks generally do an advertising cmpaign to get more funds from customers or give more loans.

In this project a bank of Portugal is trying to enroll customers in a Term Deposit by runnaing a marketing Campaign.

# Problem Description
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe a term deposit (variable y).

# Data Description
Input variables:

Bank Client data: age (numeric) job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown') marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed) education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown') default: has credit in default? (categorical: 'no','yes','unknown') housing: has housing loan? (categorical: 'no','yes','unknown') loan: has personal loan? (categorical: 'no','yes','unknown')

Related with the last contact of the current campaign: contact: contact communication type (categorical: 'cellular','telephone') month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec') day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri') duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

Other attributes: campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact) pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted) previous: number of contacts performed before this campaign and for this client (numeric) poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success') Social and economic context attributes emp.var.rate: employment variation rate - quarterly indicator (numeric) cons.price.idx: consumer price index - monthly indicator (numeric) cons.conf.idx: consumer confidence index - monthly indicator (numeric) euribor3m: euribor 3 month rate - daily indicator (numeric) nr.employed: number of employees - quarterly indicator (numeric)

Output variable (desired target): y - has the client subscribed a term deposit? (binary: 'yes','no')

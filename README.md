# Fraud_Detection_Credit_Card_Account_Origination

### Before we start

I took the course taught by Prof. Stephen Coggeshall (https://www.linkedin.com/in/stephen-coggeshall-14908a2/). He is one of the smartest individual in the field of consumer risk. In my GitHub repositories, I have three projects on fraud detection. 

### Why, What, How?

###### This project commissions to examine the 100,000 credit card application data, detect abnormality and potential fraud in the dataset. All data manipulation and analysis are conducted in R. Featured analysis methods include Principal Component Analysis (PCA), Heuristic Algorithm and Autoencoder.

###### Nowadays, Synthetic Identity Theft has been emerging as a major fraud activity over the past decade. Usually, fraudsters will use this fictitious identity to apply for credit card, open deposit accounts or obtain other important identity documents.The size of the synthetic identity theft business is estimated to be in the billions per year across North America.

###### Synthetic identity theft is fraud involving the use of a fictitious identity. Identity thieves create new identities using a combination of real and fabricated information, or sometimes entirely fictitious information. Typically, fraudsters will use a real Social Security Number (SSN) and pair it with a name not associated with that number, but there are also other ways. In some cases, an identity fraudster may create a completely fake identity with a phony SSN, name and address.

###### This report commissions to examine the 100,000 credit card application data, detect abnormality and potential fraud in the dataset. All data manipulation and analysis are conducted in R. Featured analysis methods include Principal Component Analysis (PCA), Heuristic Algorithm and Autoencoder. Major steps of analysis include:
* Data manipulation and Creating new informative features
* Dimensionality reduction through PCA process
* Calculating fraud score using both heuristic algorithm and Autoencoder

###### Using both Autoencoder and Heuristic Algorithm, we selected top 10 abnormal records by each method with highest fraud scores, which could be classified as underlying synthetic identity frauds.

###### Further investigation into those suspicious records indicates that the abnormality is mainly due to frequent and repeated occurrence in the past. Our assumption of these latent fraud records are mainly:
* Fraudsters tend to submit more applications than real applicants. It might because that they want to have a higher chance of being approved.
* Although fraudsters may forge information such as name and SSN and change them time to time, but they also tend to keep inputting same real information for contact purpose, such as phone number and address that they have access to.

###### The report, however, may include following limitations:
* Not using the full dataset since we can only calculate fraud scores from Jan 21st going forward 
* The overlapping rate of top records between 2 methods is not high enough

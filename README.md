# Email_Campaign_Effectiveness_Prediction(Classification-Supervised) - ML

![image](https://github.com/VishalSinhaRoy/Classification-Email_Campaign_Effectiveness_Prediction-ML/assets/162811130/44ea6123-0e51-487f-baa9-610500fc365d)

**Objective:**

Small and medium-sized business owners are converting potential clients into leads through email marketing methods based on Gmail; however, they are not able to monitor whether emails are being read, ignored, or acknowledged by the recipient. In order to better track and characterize these emails, they wish to develop a machine learning model. The principal aim is to enhance the efficacy of their email marketing endeavors and augment client retention.

**Methods Used:**

Data Wrangling

Descriptive Statistics

Data Visualization

Machine Learning

**Dataset Variables:**

Email_Id: Email id of customer

Email_Type: There are two categories 1 and 2. We can think of them as marketing emails or important updates and notices like emails regarding business

Subject_Hotness_Score: It is the email's subject's score on the basis of how good and effective the content is

Email_Source_Type: It represents the source of the email like sales and marketing or important admin mails related to the product

Email_Campaign_Type: The campaign type of the email.

Customer_Location: Contains demographical data of the customer, the location where the customer resides.

Total_Past_Communications: This columns contains the total previous mails from the same source, the number of communications had.

Time_Email_sent_Category: It has three categories 1,2 and 3, Time of the day when the email was sent, either morning, evening and night time

Word_Count: Total count of word in each email

Total_links: Total number of links in the email

Total_Images: Total Number of images in the email

Email_Status: Our target variable which contains whether the mail was ignored, read, acknowledged by the reader

**Conclusion:**

It sounds like analyzing the effectiveness of different types of email campaigns based on their impact and engagement rates. From our observations:

*  Campaign Type 1: Few emails sent, high likelihood of being read.
*  Campaign Type 2: Most emails sent, but many ignored.
*  Campaign Type 3: Fewer emails sent, high read and acknowledgment rates.
Additionally, I've noted that in general, shorter and more concise emails tend to receive better engagement compared to longer ones.

XGBoost Algorithm worked in the best way possible with such imbalanced data with outliers with F1 Score of 0.74 on the test set, hence best performance with 74% train score and 75% test score for F1.

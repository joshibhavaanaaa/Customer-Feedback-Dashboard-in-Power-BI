# Customer-Feedback-Dashboard-in-Power-BI
# Dashboard Overview:
1.Customer feedback dashboard  you can easily track feedback in real-time and perform keyword searches to target specific areas of customer concern. Basically, it enables you to recognize and integrate insights gained from survey results to benefit your organization. But in this case this customer feedback dashboard is used for hotel guests.

2. Slicers  this are used to drill down data for the purpose of visit like business, function, vacation, other and gender (male, female). Also, for the year which can be selected accordingly.

3. Purpose of visit & Gender Visual  This visual indicates what are the different purposes for visiting the hotels gender wise whether its male or female.

4. NPS Score / NPS Category  The NPS Category is separated into three groups: Detractors category gave from 1 to 6 on the scale out of 10; Passives category gave 7 or 8; whereas Promoters gave 9 or 10. Then simply I have subtracted % of promoters by the % of detractors and hence the NPS Score is shown as 9.75 and Promoters category is higher around 926.

NPS Formula  (NPS = % PROMOTERS - % DETRACTORS)
(This will give an idea of how customers interact and see your brand. Having a good NPS score demonstrates good customer loyalty and is highly correlated to business growth).

5. Feedback  The feedbacks are given by the guest as per the quality and service of the hotels which includes (staff’s behaviours, room service, facilities provided by the hotels and restaurant).

6. Source of Information  Here, source of information includes various sources like, organisation hotel booking sites, word of mouth, search engine, newspaper etc.

7. Overall Ratings  The overall rating of hotels is displayed on the dashboard using star ratings. These ratings give hotel owners and managers a quick snapshot of their performance and enable them data-driven decisions to improve guest experiences, increase revenue and meet business objectives. 

# Datasheets Overview
The feedback data created for the dashboard is randomly generated data but you can create it will the help of google forms as show in the video below.
#  The first five columns are by default columns. 
1st column == is ID, which represents a sequence of feedback.
2nd column == is the date and time of the start of the survey.
3rd column == is the survey completion date and time.
4th column == The email column, it is mentioned anonymous 
5th column == and the name column is blank.
Note: (If the survey Creator and feedback provider belongs to the same office organization account then the email and name will be Auto filled But, in this case, the feedback providers will be hotel guest. so, it will not be auto-generated That's the reason why we added the full name to the questionnaire itself. The rest of the fields are self-explanatory).

# Import data to Power BI:
 Open a blank Power BI report and simply you can import the Excel data by clicking on “Get data” drop-down or directly on the report you have the option “Import data from excel”.  
 Select and load the 3 tables, (Feedback, Feedback Category and Rating Range).

# Steps to set up survey in MS Forms or Google Forms and collect customer feedback:
(You can refer YouTube for more learnings on how to create google forms).

 I have used the hotel guest feedback for the demonstration, and there are 9 questions that I have set up in the survey. 
1. The name of the guest 
2. Gender 
3. Date of birth.
4. Hotel checkout date
5. The purpose of the booking. like, a business visit, vacation, function, or for some other reason.
6. Is the source of information. like: learn from someone or book by an organization or found us on a hotel booking website Etc
7. Is about General feedback. like, how was the staff Behaviour? how was the check-in process? how was the room service? Etc
8. The overall rating on a scale of one to five. 
9. The Net Promoter Score, which we will discuss in detail later during dashboard design.
Note (Also, you can change the questionnaire as per your requirement or the type of customers).
# After collecting feedbacks from google form you can check out the result (guest responses) and then accordingly use the same data for analysis. But here, I have created dashboard using random data and below I have shared the GitHub link where you can find the dataset).

 I have used the hotel guest feedback for the demonstration, and there are 9 questions that I have set up in the survey. 
1. The name of the guest 
2. Gender 
3. Date of birth.
4. Hotel checkout date
5. The purpose of the booking. like, a business visit, vacation, function, or for some other reason.
6. Is the source of information. like: learn from someone or book by an organization or found us on a hotel booking website Etc
7. Is about General feedback. like, how was the staff Behaviour? how was the check-in process? how was the room service? Etc
8. The overall rating on a scale of one to five. 
9. The Net Promoter Score, which we will discuss in detail later during dashboard design.
Note (Also, you can change the questionnaire as per your requirement or the type of customers).
# After collecting feedbacks from google form you can check out the result (guest responses) and then accordingly use the same data for analysis. But here, I have created dashboard using random data and below I have shared the GitHub link where you can find the dataset).
NPS == (Net Promoter Score is a customer loyalty benchmark that measures how likely your customers are to recommend your business to a friend. You can check out more about NPS on YouTube).


# Customer_Segmentation
This project was proposed as a competition in the **Datacamp** learning platform in July 2022 and it was titled: _Can you find a better way to segment your customers?_ My personal aim is to get a proposal by using practicing different tools with the initial data. The main tools to work with are **SQL**, **Power BI** and **Python**.
    

### Background
You work for a medical device manufacturer in Switzerland. Your company manufactures orthopedic devices and sells them worldwide. The company sells directly to individual doctors who use them on rehabilitation and physical therapy patients.

Historically, the sales and customer support departments have grouped doctors by geography. However, the region is not a good predictor of the number of purchases a doctor will make or their support needs.

Your team wants to use a data-centric approach to segmenting doctors to improve marketing, customer service, and product planning.

The company stores the information you need in the following four tables. Some of the fields are anonymized to comply with privacy regulations.


### The Data
**Doctors** contains information on doctors. Each row represents one doctor.
     "DoctorID" - is a unique identifier for each doctor.
    "Region" - the current geographical region of the doctor.
    "Category" - the type of doctor, either 'Specialist' or 'General Practitioner.'
    "Rank" - is an internal ranking system. It is an ordered variable: The highest level is Ambassadors, followed by Titanium Plus, Titanium, Platinum Plus, Platinum, Gold Plus, Gold, Silver Plus, and the lowest level is Silver.
    "Incidence rate" and "R rate" - relate to the amount of re-work each doctor generates.
    "Satisfaction" - measures doctors' satisfaction with the company.
    "Experience" - relates to the doctor's experience with the company.
    "Purchases" - purchases over the last year.


**Orders** contains details on orders. Each row represents one order; a doctor can place multiple orders.
"DoctorID" - doctor id (matches the other tables).
"OrderID" - order identifier.
"OrderNum" - order number.
"Conditions A through J" - map the different settings of the devices in each order. Each order goes to an individual patient.


**Complaints** collects information on doctor complaints.
"DoctorID" - doctor id (matches the other tables).
"Complaint Type" - the company's classification of the complaints.
"Qty" - number of complaints per complaint type per doctor.


**Instructions** has information on whether the doctor includes special instructions on their orders.
"DoctorID" - doctor id (matches the other tables).
"Instructions" - 'Yes' when the doctor includes special instructions, 'No' when they do not.

**Competition challenge**
Create a report that covers the following:

1. How many doctors are there in each region? What is the average number of purchases per region?
2. Can you find a relationship between purchases and complaints?
3. Define new doctor segments that help the company improve marketing efforts and customer service.
4. Identify which features impact the new segmentation strategy the most.
5. Your team will need to explain the new segments to the rest of the company. Describe which characteristics distinguish the newly defined segments.

### Judging Criteria

**Category** / Weighting (%) / Details

**Recommendations**	35%
* Clarity of recommendations - how clear and well presented the recommendation is.
* Quality of recommendations - are appropriate analytical techniques used & are the conclusions valid?
* Number of relevant insights found for the target audience.

**Storytelling**	35%	
* How well the data and insights are connected to the recommendation.
* How the narrative and whole report connects together.
Balancing making the report in-depth enough but also concise.

**Visualizations**	20%	
* Appropriateness of visualization used.
* Clarity of insight from visualization.

**Votes**	10%	
Up voting - most upvoted entries get the most points.
# Project1
This repo entails my CodeYou EmPowerUp Power BI Certification course capstone project from fall/winter of 2023.
There are 2 versions of the Power BI Dashboard, and there are also my notes on what the client was looking for in the Word document attached.
The file with 2 at the end of the name was the final version of the dashboard.
Check that one out!

##The Client
For every 10 min away someone lives from a dentist, it’s a 10% higher chance they won’t see a dentist within a year. 
Someone who lives 1hr from a dentist office has a 40% chance they won't see a dentist within the next year.
There are 68 Million people in cities/locations that don't have dental healthcare within a reasonable distance from where they live - they live in what are called dental deserts.

The client is Kare Mobile, a Louisville, KY-based company that does ***free*** screenings in various US locations at retailers, as well as offering them in-home, and out of a traveling van (hence the "mobile" in the name).
Their vision is to provide folks in dental deserts with dental checkups, allowing dental healthcare to be more within reach for disenfranchised folks.
Their website is listed below.

https://karemobile.com/

* The client explained that they wanted to expand the business geographically, and add more locations they have not serviced yet to their reach.
* To do that, they needed help telling a story about the impactful work they've been doing to show it to stakeholders.
* What can be concluded overall when looking at the data for multiple locations & dates altogether?
* What trends in demographics, zip codes, or different retail chains might exist in the data?

##The Data
* Data received (csv files) included the screening location and basic patient info for each dental screening performed by the client per day.
* The data includes Demographics, Symptoms/Patient History, Patient Behaviors, and Insurance info.
* The final data received covers 363 mobile screenings events across 5 locations, all during weekends (Saturday & Sunday).
* Each of the 5 files was one weekend and one location, and each line in the file is one screening.
* The client said these csv files were partly pulled from google forms filled out by the patient (demographics) & symptoms/patient history/screening results were provided by the medical professionals.
* The client did some data cleaning in Microsoft Excel before sending us the files.
* Some questions in the form had single-select options, while others allowed multiple options to be selected, and others had text boxes.
* I cleaned blanks, invalid values, "Not Provided" and "N/A"'s in the data mostly via Microsoft Excel upon clarifying some of the meanings with the client.
* There was further cleaning, as well as identification of column types done via Power Query in Power BI.

##Methodology/Questions
A relational database was created inside Power Query - 3 tables for Behaviors, Demographics, and Symptoms/Patient History.

* Are there trends around zip code?
* Are there trends around gender?
* Are there trends around age?
* Are there trends around pain levels?
* Are there trends around specific retailer chains?
* Are there trends around specific days of the week?

##Conclusion
<ins>In dashboard<ins>

pg1 - Trends in Gender and Insurance
pg2 - Trends in Patient History, Gender, and Pain
pg3 - Impact
Pg4 - Sources
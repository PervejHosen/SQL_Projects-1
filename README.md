#Description of the Dataset:
Airbnb, Inc. is an American San Francisco-based company operating an online marketplace for short- and long-term homestays and experiences. The company acts as a broker and charges a commission from each booking.
You will be working with their European Booking Dataset. This is a merged dataset of 9 famous cities in Europe:
Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, Paris, Rome, and Vienna.
The original Dataset was messy and lacked describing appropriate information. But, this one was first cleaned. 

#Variables Names and Descriptions are:
City: Name of the City/
Price: Price of Airbnb/
Day: If it is a weekday or weekend/
Room Type: Type or Airbnb - Entire Apt, Private Room, Shared Room/
Share Room: If the Room in Airbnb is shared by anyone/
Private Room: If the Stay has a Private room available/
Person Capacity: The Person Capacity of Airbnb/
Superhost: If the Airbnb host is Superhost or not/
Multiple Rooms: If the Airbnb has multiple rooms (2-4) rooms/
Business: If the Business has more than 4 offers/
Cleaningness Rating: Cleanness Ratings of the Places/
Guest Satisfaction: Guest Satisfaction Score they left/
Bedrooms: Number of Bedrooms in the facility/
City Center (km): Distance to the center of the City from the staying place/
Metro Distance (km): Distance to the Metro Service from the staying place/
Attraction Index: Attraction Index of the Place/
Normalised Attraction Index: Normalised value of the Attraction Index/
Restraurant Index: Restaurant Index of the Place/
Normalised Restraurant Index: Normalised value of the Restaurant Index/

#Task:

Perform exploratory data analysis using Snowflake SQL and tell a story you'd like to tell with this dataset.
Create a Database in Snowflake named "TOURISM"
Create a Schema under that Database named "EUROPE"
Create a Table under that Database and Schema named "AIRBNB" [Be careful with the Field Names and Field Types]
Create an Appropriate File Format to Bulk insert the CSV file (Airbnb Europe Dataset.csv)
Insert the dataset using the created file format [K]
If you see any error, then work on that. You must try until you see no error.
Proof Check: The number of Records should be 41,714
Perform Descriptive Analysis and Frequency Distribution [Build Charts as well in your result if you find the output important enough]
Check if there is any outlier in the "PRICE" Field; If so, then report the observations and then remove the outliers
Apart from the descriptive analysis, try to Explore which Fields/Variables have a Causal Relationship with "Guest Satisfaction".

Build a Simple Dashboard using Snowflake [Keep one or two filters on top; whatever field you find most important ones to look at]

Write a Short Report based on your findings [Report should be written in Microsoft Word File and the Analyses, Charts should be included in the report; Add a Screenshot of your dashboard as well]

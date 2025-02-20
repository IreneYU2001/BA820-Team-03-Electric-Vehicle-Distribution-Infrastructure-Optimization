# BA820-Team-03-Electric-Vehicle-Distribution-Infrastructure-Optimization

Team 3 members: Haojiang Wu, Fangzhou Zheng, Yixi Yu, Pranaya Bindu Buyya

Data Source:
The dataset used in this project is called the Electric Vehicle Population Data, which provides a comprehensive record of electric vehicles registered in Washington State through Washington State Department of Licensing. As an official government dataset, it provides reliable and up-to-date information about registered electric vehicles. The dataset is public and can be accessed through the following link:
Dataset Link:
https://drive.google.com/file/d/1iLFacW1f3ENf4u6t4VgsW6GaeNn99za_/view?usp=drive_link

Data Repository Link:
https://catalog.data.gov/dataset/electric-vehicle-population-data
https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2/about_data

Data Description:
Data Size: 51.7 MB
There are 17 columns and 22392 rows in this dataset.
Columns are: “VIN (1-10)”, “County”, “City”, “State”, “Postal Code”, “Model Year”, “Make”, “Model”, “Electric Vehicle Type”, “Clean Alternative Fuel Vehicle (CAFV)
Eligibility”, “Electric Range”, “Base MSRP”, “Legislative District”, “DOL Vehicle ID”, “Vehicle Location”, “Electric Utility”, “2020 Census Tract”
Specific Column/Features: “Electric Vehicle Type”, “Clean Alternative Fuel Vehicle (CAFV) Eligibility”, “Vehicle Location”, “Electric Utility”.
Types of data include: Numeric, Categorical, String
More specific descriptions of the columns can be found at: https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2/about_data
Proposed Methodology： This project will adopt unsupervised machine-learning techniques to analyze the distribution
patterns and characteristics of electric vehicles (EVs) in Washington State. The following
methodologies will be employed:
1. Clustering Analysis:
Group EVs based on geographical distribution (county, city, postal code) to detect high-density areas and optimize charging station locations.
Segment users by vehicle type (model, range, price) to understand regional preferences and inform car brands’ marketing strategies.
Predict future charging demand by identifying areas with concentrated EV growth trends.
2. Principal Component Analysis:
Analyze the columns in the dataset, including vehicle characteristics, policy labels, and geographical information, to identify key factors influencing EV distribution.
Determine the most impactful variables (e.g., vehicle range, price, policy eligibility) that affect EV adoption in different regions.
3. Association Rule Mining:
Analyze the relationship between EV brands, types, and geographical locations to inform car brands about region-specific consumer behavior.
Investigate the impact of policy factors (e.g., Clean Alternative Fuel Vehicle eligibility) on EV purchase trends to help policymakers optimize incentives.
Uncover charging demand patterns by identifying correlations between vehicle range and regional charging requirements.

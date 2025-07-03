# Data-Analysis-Capstone-Project-1-Amazon-Product-Review-Analysis
The excel file will be attached to this readme file. It contains 4 spreadsheets, "Amazon Original" (contains the raw data), Tables" (contains the cleaned data: custom columns, ...), Pivot Tables (contains the pivot tables for each question), "Dashboard" (representing some of the results in bar charts for clarity and better understanding). Few of the dashboards were screenshot and they were also uploaded as jpeg files.

#### Summary of the procedure used in analysing the data set.
The data set is an excel spreadsheet having a total of 1465 rows and 16 columns. The data was cleaned as follows before analysis was conducted. The names were too long as this will not allow good visibility when creating the dashboard for visualization.
#### Step 1: Covert the dataset to a table using "CTL + T"
#### Step 2: Duplicated data set were removed by using the "PRODUCT ID" column, then click on "remove duplicates".
#### Step 3: The category name column was splitted and part of it was used for the analysis and in this case, the column was renamed "Main Category" while others were renamed "Category 1, Category 2, Category 3, Category 4. The column used for the analysis 
#### Step 1 - 5 above reduces the number of rows to 1350 for proper analysis.
#### The category name was splitted in order to give good credibility to the dataset.
#### Custom columns, calculated columns, pivot tables were used in analysing the dataset.

## Q1: What is the average discount percentage by product category?
|Category	|Average of discount_percentage|
|---|---|
|Car&Motorbike|	42%|
|Computers&Accessories|	53%|
|Electronics|	50%|
|Health&PersonalCare|	53%|
|Home&Kitchen|	40%|
|HomeImprovement|	58%|
|MusicalInstruments	|46%|
|OfficeProducts	|12%|
|Toys&Games	|0%|
|Grand Total	|47%|
![image](https://github.com/user-attachments/assets/28834baa-00ef-4f79-a4dc-d5f468fd77c4)

## Q2: How many products are listed under each category?	
|Category	|Count of product_name|
|---|---|
|Car&Motorbike|	1|
|Computers&Accessories|	375|
|Electronics|	490|
|Health&PersonalCare|	1|
|Home&Kitchen|	448|
|HomeImprovement|	2|
|MusicalInstruments|	2|
|OfficeProducts|	31|
|Toys&Games|	1|
|Grand Total|	1351|
![image](https://github.com/user-attachments/assets/9ee12af8-436b-493e-8863-6c6504252e1b)

## 3: What is the total number of reviews per category?
Q3: Number of Review per Category		
|Category	|Count of review_title|
|---|---|
|Car&Motorbike|	1|
|Computers&Accessories|	375|
|Electronics|	490|
|Health&PersonalCare|	1|
|Home&Kitchen|	448|
|HomeImprovement|	2|
|MusicalInstruments|	2|
|OfficeProducts|	31|
|Toys&Games|	1|
|Grand Total|	1351|
![image](https://github.com/user-attachments/assets/3b53e70d-4987-4693-bc38-817842bb9bdd)

## Q4: Which products have the highest average ratings?
	
|Product Name	|Average of rating|
|---|---|
|Syncwire LTG to USB Cable for Fast Charging Compatible with Phone 5/ 5C/ 5S/ 6/ 6S/ 7/8/ X/XR/XS Max/ 11/12/ 13 Series and Pad Air/Mini, Pod & Other Devices (1.1 Meter, White)|	5|
|REDTECH USB-C to Lightning Cable 3.3FT, [Apple MFi Certified] Lightning to Type C Fast Charging Cord Compatible with iPhone 14/13/13 pro/Max/12/11/X/XS/XR/8, Supports Power Delivery - White|	5|
|Amazon Basics Wireless Mouse  2.4 GHz Connection, 1600 DPI  Type - C Adapter  Upto 12 Months of Battery Life  Ambidextrous Design  Suitable for PC/Mac/Laptop	|5|
![image](https://github.com/user-attachments/assets/e9e3fb74-e660-4449-acc3-19eddf3a3355)

## Q5: What is the average actual price vs the discounted price by category?
		
|Category	|Average of actual_price|	Average of discounted_price|
|---|---|---|
|Car&Motorbike|	4,000.00|	2,339.00|
|Computers&Accessories|	1,857.75|	947.49|
|Electronics	|10,418.08|	6,225.87|
|Health&PersonalCare|	1,900.00	|899.00|
|Home&Kitchen|	4,162.07|	2,330.62|
|HomeImprovement	|799.00	|337.00|
|MusicalInstruments|	1,347.00	|638.00|
|OfficeProducts|	397.19|	301.58|
|Toys&Games	|150.00	|150.00|
|Grand Total	|5,691.18|	3,304.80|
![image](https://github.com/user-attachments/assets/370f30f9-504c-462d-a7f4-83935fbd0daf)

## Q6. Which products have the highest number of reviews?
|Product	|Count of review_content|
|---|---|
|Fire-Boltt Ninja Call Pro Plus 1.83" Smart Watch with Bluetooth Calling, AI Voice Assistance, 100 Sports Modes IP67 Rating, 240*280 Pixel High Resolution	|5|
|Samsung Galaxy M13 5G (Aqua Green, 6GB, 128GB Storage)  5000mAh Battery Upto 12GB RAM with RAM Plus|	3|
|Fire-Boltt Phoenix Smart Watch with Bluetooth Calling 1.3",120+ Sports Modes, 240*240 PX High Res with SpO2, Heart Rate Monitoring & IP67 Rating|	3|
![image](https://github.com/user-attachments/assets/9c894fa6-c935-4dbe-a76d-cd5b19004461)

## Q7. How many products have a discount of 50% or more?
|Q7: NUMBER OF PRODUCT WITH DISCOUNT OF 50%OR MORE|
|---|
|662|
![image](https://github.com/user-attachments/assets/20c73f1f-28f1-48e7-8a61-d7de700ef618)

## Q8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
|Product Rating	|Count of rating|
|---|---|
|4	|225|
|4|	209|
|4|	207|
|4	|159|
|4|	114|
|4	|114|
|4|	84|
|5|	68|
|Grand Total	|1350|
![image](https://github.com/user-attachments/assets/19e774e2-adf2-4fa9-b258-769008cddbb0)


## Q9. What is the total potential revenue (actual_price × rating_count) by category?
|Product Category	|Sum of actual_price	|Sum of rating_count	|Total Potential Revenue|
|---|---|---|---|
|Car&Motorbike	| 4,000.00 |	 1,118.00 	| 4,472,000.00 |
|Computers&Accessories	| 696,654.62 |	 6,335,177.00 |	 4,413,430,325,567.74 |
|Electronics	| 5,104,861.00 	| 14,208,406.00 	| 72,531,937,661,566.00 |
|Health&PersonalCare|	 1,900.00 	| 3,663.00 	| 6,959,700.00 |
|Home&Kitchen	| 1,864,609.00| 	 2,991,069.00| 	 5,577,174,177,021.00 |
|HomeImprovement	 |1,598.00 	| 8,566.00 	| 13,688,468.00 |
|MusicalInstruments|	 2,694.00| 	 88,882.00 |	 239,448,108.00| 
|OfficeProducts	| 12,313.00 |	 149,675.00 	| 1,842,948,275.00 |
|Toys&Games	| 150.00 |	 15,867.00 	| 2,380,050.00 |
|Grand Total	| 7,688,779.62 |	 23,802,423.00 |	 82,524,652,060,755.70 |
![image](https://github.com/user-attachments/assets/ea386a25-8464-49a6-a48c-65bb54ea90f6)

## Q10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?

#### Q11. How does the rating relate to the level of discount?
The rating of a product relates to the level of discount in the sense that a product that is rated high or good means the product satisfies the customer's need and this in turn will give rise a good level of discount on such a particular product. As discount level increases, it gives rise to more demand for such a product and thereby increasing the revenue that obtained from such product and vice versa.

## Q12. How many products have fewer than 1,000 reviews?


## Q13. Which categories have products with the highest discounts?
Product Categories that has the highest discounts is **"Electronics"**	
|Product Category	|Sum of discounted_price|
|---|---|
|Car&Motorbike	| 2,339.00 |
|Computers&Accessories	| 355,308.36 |
|Electronics|	 3,050,676.00 |
|Health&PersonalCare	| 899.00 |
|Home&Kitchen|	 1,044,115.81 |
|HomeImprovement	| 674.00 |
|MusicalInstruments	| 1,276.00 |
|OfficeProducts|	 9,349.00 |
|Toys&Games	| 150.00 |
|Grand Total|	 4,464,787.17 |
![image](https://github.com/user-attachments/assets/356b8e0f-9cbd-488d-8950-b115e148b388)

## Q14 Top 5 products in terms of rating and number of reviews combined.
|S/N|Product Category|	Average of rating	|Count of review_id|
|---|---|---|---|
|1|Fire-Boltt Ninja Call Pro Plus 1.83" Smart Watch with Bluetooth Calling, AI Voice Assistance, 100 Sports Modes IP67 Rating, 240*280 Pixel High Resolution	| 4.20 |	 5.00 |
|2|Samsung Galaxy M13 5G (Aqua Green, 6GB, 128GB Storage)  5000mAh Battery  Upto 12GB RAM with RAM Plus	| 4.10 |	 3.00 |
|3|Fire-Boltt Phoenix Smart Watch with Bluetooth Calling 1.3",120+ Sports Modes, 240*240 PX High Res with SpO2, Heart Rate Monitoring & IP67 Rating|	 4.30 |	 3.00 |
|4|Samsung Galaxy M33 5G (Emerald Brown, 6GB, 128GB Storage)  6000mAh Battery Upto 12GB RAM with RAM Plus Travel Adapter to be Purchased Separately	| 4.10 	 |2.00 |
|5|Smashtronics¬Æ - Case for Firetv Remote, Fire Stick Remote Cover Case, Silicone Cover for TV Firestick 4K/TV 2nd Gen(3rd Gen) Remote Control - Light Weight/Anti Slip/Shockproof (Black)	| 4.20 |	 2.00| 
![image](https://github.com/user-attachments/assets/f4b1770b-2b7a-4ad4-bbeb-5119d01dff5b)


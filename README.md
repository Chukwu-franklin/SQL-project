# SQL-project
# Analysis-of-cars-from-Cars45.com
## by Franklin Chukwueke


## About Cars45.com
Cars45.com is an E-commerce platform that offers automobile services such as buying, selling and grading of cars. Cars to be purchased by Cars45 are sought for online where the car owner submits thier vehicle information for a free quote. An inspection date is booked and the inspection is carried out one of the inspection centres in Nigeria. After inspection, which covers the engine, breaks, tires and road test an offer is made by Cars45 and if accepted payment is made into the owner's account.
After a digital service history is created, Cars45 offers the autos it acquires to a private network of buyers.

### Dataset
The datatset that was used in the analysis was obtained [Here](https://www.kaggle.com/datasets/makindekayode/nigerian-car-prices-dataset). The original dataset was web scrapped from the Cars45 website and transformed into a csv file to make it easier to perform analysis on the dataset. The dataset contains 20 columns and 3273 rows.

### Design
The data was in a csv format, it was cleaned, transformed and visualized throuhgh the following steps
1. Removed duplicate and blank cells, this was done to ensure that no data points impacts incorrectly on the analysis and to maintain the integrity of the data.
2. Added a seperator to the price column.
3. Pivot tables were created to capture specific insights.
4. Insights were visualized using Microsoft Excel.
    
    
## Dashboard
Created a dashboard to summarize the findings made from the analysis
   ![Dashboard](https://user-images.githubusercontent.com/120729134/212563907-7acad4e6-b019-4f96-a4c0-44bc5fcd5d15.jpg)
   
## Breakdown of the Dashboard

### The most expensive car
   ![Most_expensive_car-1](https://user-images.githubusercontent.com/120729134/212564319-16ac8157-5245-4f5f-9853-8d3b750fdc46.jpg)
### The most affordable car
   ![Most_affordable_car](https://user-images.githubusercontent.com/120729134/212549064-d01ccddf-02a1-42c7-a48d-557726a957dd.png)
### The average Price of a car
   ![Average_price_of_a_car-1](https://user-images.githubusercontent.com/120729134/212667764-e0fc9707-0325-4d96-9aa6-380f5bb05430.jpg)
### Number of cars bought by year of production 
   ![Number_of_cars_bought_by_year-1](https://user-images.githubusercontent.com/120729134/212565399-78082dae-06ec-43d7-994b-023b1af75f99.jpg)
### Average mileage by car condition
   ![Average_mileage_by_car_condition-1 jpg-1](https://user-images.githubusercontent.com/120729134/212669493-cce57337-a788-473e-ba56-a5556057d8e9.jpg)
### Number of cars bought by gear type
   ![Number_of_cars_bought_by_gear_type-1](https://user-images.githubusercontent.com/120729134/212670915-ca1b7626-8ad7-444f-8d5c-6d2c5935c37b.jpg)
### Number of cars bought by colour
   ![Number_of_cars_by_colour-1](https://user-images.githubusercontent.com/120729134/212666486-c090b2dd-a211-456e-8f2f-f5fa094c28e1.jpg)
### Number of cars bought  by fuel type
   ![Number_of_cars_bought_by_fuel_type-1 jpg-1](https://user-images.githubusercontent.com/120729134/212672128-2c37567e-e667-46d1-8528-296c24a17cc9.jpg)
   
## Findings
* The most expensive car on Cars45 is the 2015 Mercedes Benz S-Class that costs 62,400,000 naira while the most affordable car is the 2000 Honda Civic that costs 550,000 naira as at the time that this dataset was extracted from the Cars45 website.
* Different car makes and models are sold on Cars45 ranging from the Acura ILX to Volvo S80 and the price displayhed on the dashboard shows how much each car costs on average.
* On Cars45, cars manufactured in 2017 are the most bought whereas cars manufactured in 2022 are the least bought.
* Automatic gear cars were the most purchased, followed by manual gear type and CVT gear type.
* New cars have the least mileage, while foreign cars have the most mileage.
* By colour, black cars sell more while pink and ivory cars sell the least.
* Hybrid (electric) powered cars are the lowest purchased, followed by disel powered cars and at the top are petrol powered cars.

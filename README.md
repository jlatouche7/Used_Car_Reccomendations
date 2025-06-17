# Used_Car_Reccomendations
Vehicle Features – What Drives the Price of a car?
 
Introduction: In attempt to identify which features of a vehicle drive the eventual sale price, I built a model to identify the features that determine a vehicles price and predict future prices of un-sold vehicles. I parsed through thousands of rows of data to build and identify an effective model. After tuning and fitting several different models I found a model which was able to predict the price of a car with an average of $5472 off the eventual sale price of the vehicle. Below I have broken down which features the model identified as most and least important to it's price.

Linked Here is a Jupyter Notebook with my data cleaning, modeling and selection process: https://github.com/jlatouche7/Used_Car_Reccomendations/blob/f7a2374565d9a12fccb67974292e534d907a306a/What%20Drives%20The%20Price%20of%20a%20Car%20-%20Modeling%20(1).ipynb

Most Important Features:

•	Condition: In the data-the condition of the vehicle falls into one of several categories: new, like new, excellent, good, fair and salvage. We found that for each change in condition (for ex. "new” to “like new”), on average, there is about a $1,360 difference. This means that if the condition of a vehicle is in ‘salvage’ condition compared to the exact same vehicle in ‘new’ condition, the model predicts that, on average, there is about an $8,000 difference between the two vehicles.

•	Cylinders – The number of cylinders is integral to the eventual sale price of the vehicle. As the number of cylinders increases, the price of the car.
              I used a 10-cylinder vehicle as a baseline to show how the number of cylinders effects the price.
              
                  o	4 Cylinders – $5700 less than a 10-cylinder vehicle on average
                  
                  o	6 Cylinders- $4500 less than a 10-cylinder vehicle on average
                  
                  o	8 Cylinders - $2500 less than a 10-cylinder vehicle on average
                  
•	Odometer- The odometer reading is essential to the price of the vehicle. As the odometer’s mileage increases, the price of the car decreases significantly.

•	Manufacturer / Luxury Vehicles- Luxury Brands, on average, sold for almost $2,000 more than non-luxury brands. 
                                  Certain brands-specifically Aston-Martin on average, sold for nearly a $14,000 more than our baseline brand, Ford.
                                  
•	Vehicle Type - The type of vehicle also has a significant impact on the sale price. I performed my analysis by using SUVs as the baseline. 
                  Here is how much, on average, the following types of vehicles are sold in comparison to SUVs: 
                                    o	Trucks: $4,273.18 more than SUV’s
                                    
                                    o	Sedans: $1250.86 less than SUV’s
                                    
                                    o	Pickup Trucks: $2,450.16 more than SUV’s
      
Least Important Features:

    •	Year – the year of the vehicle has very little impact on the eventual sale price of the vehicle. The model shows that an increase of 1 year (for ex. 2024 to 2025) would add about $227 to the eventual sale price of the vehicle.
    
    •	Paint Color- Paint color does not tend to have much of an effect on how much the vehicle sells for. Using cars with black paint as the baseline, the model finds that most of the paint colors have less than a $1000 effect on the eventual sale price of the vehicle. The model found that even custom paint colors did not have much effect on the eventual sale price.

 




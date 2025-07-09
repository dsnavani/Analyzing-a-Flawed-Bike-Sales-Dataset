# Analyzing a Flawed Bike Sales Dataset
## Project Overview
This project aimed to analyze a dataset containing Indian bike sales data to uncover trends in pricing, mileage, and consumer behavior. 
However, during data exploration, several inconsistencies and unrealistic distributions were found, making the dataset unreliable for meaningful analysis.

## Dataset Description
Fields: Price, Year of Manufacture, Engine, Capacity, Mileage, Brand, Model, Category, Fuel Type, Insurance Status

## Highlights
+ Year of Manufacture Distribution<br/>
  <img src="https://github.com/user-attachments/assets/2fe258bc-3382-49db-8fcf-ceb72df62af1" alt="Year of Manufacture Distribution" width="400" height="300" align="left"/><br><br><br><br><br><br><br><br><br><br><br><br>
+ Year of Registration Distribution<br/>
  <img src="https://github.com/user-attachments/assets/1ad31169-a979-4458-9a25-4ae76ad09036" alt="Year of Registration Distribution" width="400" height="300" align="left"/><br><br><br><br><br><br><br><br><br><br><br><br>
+ Mileage Distribution<br/>
  <img src="https://github.com/user-attachments/assets/d2a99028-7aeb-48d2-b41c-d4cdddcc01a7" alt="Mileage Distribution" width="400" height="300" align="left"/><br><br><br><br><br><br><br><br><br><br><br><br>
+ Mileage vs. Price<br/>
  <img src="https://github.com/user-attachments/assets/5018e4b4-d80d-452f-acf2-4b9fa8b53e33" alt="Mileage VS Price" width="400" height="300" align="left"/><br><br><br><br><br><br><br><br><br><br><br><br>

## Inconsistencies
+ Several numerical fields, such as Price, Engine Capacity and Mileage, show unrealistically uniform distributions.
+ Distribution of the Year of Manufacture histogram is uniform but the year of registration shows increased trend. 
+ Petrol bikes have a mileage range of 30–60 km/l, while electric and hybrid bikes range from 60–100 km/l, which seems unusually consistent.
+ Overall, mileage for all bike types ranges narrowly between 25–100 km/l, lacking expected variation.
+ These patterns suggest poor data collection, making the dataset unreliable for in-depth analysis.

# Software_velocity_assignment
This project analyzes historical climate data from Boston between 1970 and 1999. It includes seasonal categorization, statistical aggregation, and command-line-based filtering options. The dataset is used to explore long-term climate trends and patterns using Python.
## Features
1) Loads and cleans Boston weather data from 1970 to 1999
2) Adds seasonal tags (Winter, Spring, Summer, Fall)
3) Computes seasonal averages and yearly aggregates

### Supports CLI filters:

-p: Filter data for prime years

-a <int>: Filter data for years divisible by a given integer

Adds extra columns: Season, IsLeapYear, and DayCategory (e.g., Weekday/Weekend)
## 🧠 Key Functions
- `is_prime(year)`: Checks if a year is prime  
- `is_leap_year(year)`: Checks if a year is a leap year  
- `assign_season(month)`: Maps month to season  
- `compute_seasonal_averages(df)`: Aggregates seasonal metrics  

## 📌 Requirements
- Python 3.7+
- pandas
- numpy

## 🏫 Author
**Abhay Ramamurthy**  
Master’s Student, Northeastern University  
Email: ramamurthy.ab@northeastern.edu 




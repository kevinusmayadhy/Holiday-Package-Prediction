# Holiday Package Prediction

- Dataset: Sourced from [kaggle](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction).
- Programming Language: Python Version 3.12.3
- Library:
    - pandas version 2.2.2
    - matplotlib version 3.8.4
    - seaborn version 0.13.2
    - numpy version 1.26.4
    - math

## Business Understanding

**"Trips & Travel.com"** company wants to enable and establish a viable business model to expand the customer base. Currently, the company offers five types of packages: Basic, Standard, Deluxe, Super Deluxe, and King. *Last year's data found that 18% of customers purchased these packages. However, the marketing costs were high due to random customer outreach without utilizing available information.* The company now plans to launch a new product: the Wellness Tourism Package. Wellness Tourism involves travel that helps maintain, enhance, or start a healthy lifestyle, boosting one's overall well-being. *This time, the company intends to use existing data on current and potential customers to optimize marketing expenses efficiently.*

Based on this, we can determine the goals, objectives, and key metrics for this project:

**Goals:**
- Increase the customer purchase rate
- Reduce marketing costs

**Objective:**
- Utilize available data to target potential customers more effectively.
- Optimize marketing strategies to ensure cost-efficiency and higher conversion rates.

**Key Metrics**
- Customer purchase rate: Measure the percentage increase in package purchases.
- Return on investment (ROI): Assess the financial returns from the new Wellness Tourism Package and overall marketing efforts.

## Data Understanding

The dataset used in this analysis is sourced from Kaggle, titled [Holiday Package Prediction](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction). It contains 4888 rows and 20 columns. The dataset includes the following columns:

1. **CustomerID**: Unique identifier for each customer.
2. **ProdTaken**: Indicates whether the product was taken (True/False).
3. **Age**: Age of customer.
4. **TypeofContact**: How customer was contacted (Company Invited or Self Inquiry).
5. **CityTier**: City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered.
6. **DurationOfPitch**: Duration of the pitch by a salesperson to the customer.
7. **Occupation**: Occupation of customer.
8. **Gender**: Gender of customer.
9. **NumberOfPersonVisiting**: Total number of persons planning to take the trip with the customer.
10. **NumberOfFollowups**: Total number of follow-ups has been done by the salesperson after the sales pitch.
11. **ProductPitched**: Product pitched by the salesperson.
12. **PreferredPropertyStar**: Preferred hotel property rating by customer.
13. **MaritalStatus**: Marital status of customer.
14. **NumberOfTrips**: Average number of trips in a year by customer.
15. **Passport**: Indicates if the customer has a passport (0: No, 1: Yes).
16. **PitchSatisfactionScore**: Satisfaction score of the sales pitch.
17. **OwnCar**: Indicates if the customer owns a car (0: No, 1: Yes).
18. **NumberOfChildrenVisiting**: Total number of children with age less than 5 planning to take the trip with the customer.
19. **Designation**: Job title of the customer in their current organization.
20. **MonthlyIncome**: Gross monthly income of the customer.
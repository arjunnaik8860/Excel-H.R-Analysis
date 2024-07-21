
# ADECCO INDIA Customer Analysis

## Problem Statement :

Adecco India is experiencing high employee turnover, particularly in the sales department among junior-level employees. This turnover is costly and disrupts team dynamics, leading to decreased productivity and morale

## Leading To :

High attrition rates can lead to significant costs associated with recruitment, onboarding, and training of new employees. It also affects the company's ability to maintain consistent performance and achieve long-term goals. Improving employee retention will enhance productivity, reduce costs, and foster a more stable and motivated workforce.

## Steps followed : 

- Load data  into MS EXCEL 

         " HR-Employee-Attrition "dataset is a CSV file.

## Meta Data :

        Column                  Description
        Age                      Age of the employee
        Attrition               Whether the employee has left the company (Yes/No)
        BusinessTravel          Frequency of business travel
        DailyRate               Daily salary rate of the employee     
        Department              Department in which the employee works
        DistanceFromHome        Distance of the employee's home from the workplace
        Education               Education level of the employee (1-5 scale)
        EducationField          Field of education
        EmployeeCount           Always 1 (as the data is individual-specific)
        EmployeeNumber          Unique identifier for each employee
        EnvironmentSatisfaction   Employee's satisfaction with the work environment (1-4 scale)
        Gender                  Gender of the employee
        HourlyRate              Hourly salary rate of the employee
        JobInvolvement          Employee's involvement in their job (1-4 scale)
        JobLevel                Job level of the employee (1-5 scale)
        JobRole                 Role of the employee within the company
        JobSatisfaction         Employee's satisfaction with their job (1-4 scale)
        MaritalStatus           Marital status of the employee
        MonthlyIncome           Monthly salary of the employee
        MonthlyRate             Monthly rate of the employee
        NumCompaniesWorked      Number of companies the employee has worked for
        Over18                  Whether the employee is over 18 years old
        OverTime                Whether the employee works overtime (Yes/No)
        PercentSalaryHike       Percentage increase in salary
        PerformanceRating            Performance rating of the employee (1-4 scale)
        RelationshipSatisfaction        Employee's satisfaction with relationships at work (1-4 scale)
        StandardHours                   Standard working hours (80 for all employees)
        StockOptionLevel                 Stock option level of the employee (0-3 scale)
        TotalWorkingYears                Total number of years the employee has worked
        TrainingTimesLastYear            Number of training sessions attended by the employee last year
        WorkLifeBalance                  Employee's work-life balance (1-4 scale)
        YearsAtCompany                   number of years the employee has been with the company 
        YearsInCurrentRole               Number of years the employee has been in their current role
        YearsSinceLastPromotion         Number of years since the employee's last promotion
        YearsWithCurrManager            Number of years the employeehas been with their current manager


          


* After in navigator tab check for any NOISE and Check the pre set delimeter as "comma"

-  Also since by default, DATA TYPE DETECTION will be set only for 200 rows so you need to select  "based on entire dataset".


- using formulas :

      Sumif() , Counta(), Countif(), Ifelse(), Ifs() , Average()

 - Using Visualizations :    

        Pivot Tables , Barcharts , Pie Charts , Line Charts , Scatter plots , Trendlines


### Divising formula for calculating Atrrtion Rate 

        Attrition Rate = Number of Employees Who Left / Total Number of Employees × 100
        
* Analyzing all Factors for Overall and Particular  Higher Atrrition Rate in various Departments .


## KEY INSIGHTS :

## 1 - Average Woring Years

### Employees Work on Average for 5 YRS 

![img_04](https://github.com/user-attachments/assets/d9aa649d-8dab-4528-be42-6e7ac4ec836f)

## 2 - Top-3  Departments With Highest Atrrtion Rate

### Most - Research & Development

![img_05](https://github.com/user-attachments/assets/a73bb60b-21a6-46b7-840f-95d1e2d83338)

### Suprisingly Avg Job Satisfaction for Research & Development is 2nd Highest

![img_5 5](https://github.com/user-attachments/assets/fd5d87b7-4749-4f79-99fe-e0d49654d1b6)

## 3 -  Marital Status affecting Attrition

### Employees with Marital Status as "SINGLE" are MOST PRONE on Departing

![img_03](https://github.com/user-attachments/assets/70c9506a-2d03-4065-92f8-2bd0bd6ed3a1)

## 4 - Performance and Yrs Since Promotion

### Sum of Performance DECREASES after a INCREASE in Num of Yrs Since Promotion 

### while the Avg Performance Per Employee on AVERAGE remains CONSTANT
![img_01](https://github.com/user-attachments/assets/cb2b5f09-ed09-4187-8d7f-7e81ea504639)

## 5 - Avg Performance and Work Life Balance

### Avg Performance INCREASES (0.16^) as a INCREASE in Work Life Balance - Former Employee

### Avg Performance SLIGHTLY DECREASES (0.4 ↓ ) as a INCREASE in Work Life Balance - Former Employee
![IMG_02](https://github.com/user-attachments/assets/820b3748-f7a9-4327-a848-0633b7fdaa3b)

# **DemographicData_Analyzer**

## **Project Overview**
This project analyzes demographic data from the **"adult.data.csv"** dataset and extracts meaningful insights, including:
- The distribution of different races.
- The average age of men.
- The percentage of people with a **Bachelor’s degree**.
- Income disparities based on education level.
- The relationship between working hours and income.
- Countries with the highest percentage of high-income earners.
- The most common occupation among high earners in India.

## **Dataset Description**
The dataset used contains census data, where each row represents an individual with various attributes such as age, education level, occupation, native country, and salary level (>50K or <=50K).

### **Features Used**
- `age` - Age of the individual
- `race` - Race category
- `sex` - Gender
- `education` - Level of education
- `hours-per-week` - Working hours per week
- `native-country` - Country of residence
- `salary` - Income category (`>50K` or `<=50K`)

## **Installation and Usage**
### **Prerequisites**
- Python 3.x
- Pandas library

### **Setup**
1. Clone this repository or download the script.
2. Install required dependencies:
   ```bash
   pip install pandas
   ```
3. Ensure that the dataset `adult.data.csv` is in the same directory as the script.
4. Run the script:
   ```bash
   python demographic_analyzer.ipynb
   ```

## **Code Explanation**
The script performs the following calculations:
1. **Counts the number of each race** using `value_counts()`.
2. **Finds the average age of men** by filtering the dataset and computing the mean.
3. **Calculates the percentage of people with a Bachelor's degree**.
4. **Determines the income disparity between people with advanced education and those without**.
5. **Finds the minimum hours worked per week** and analyzes how many of those individuals earn more than 50K.
6. **Identifies the country with the highest percentage of high earners**.
7. **Finds the most common occupation among high earners in India**.

## **Expected Output**
When the script runs, it prints key demographic statistics and returns them as a dictionary.

## **License**
This project is open-source and available for modification and distribution.

## **Author**
Victor Iheanacho


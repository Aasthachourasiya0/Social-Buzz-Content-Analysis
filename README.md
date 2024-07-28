# Social Buzz Content Analysis

This project involves analyzing the content categories of Social Buzz to determine the top-performing categories and other insights. The project is powered by Accenture.

## Project Overview

Social Buzz is a social media platform emphasizing anonymous content sharing and varied user reactions. This analysis aims to provide insights into the most popular content categories and other key metrics.

## Steps and Analysis

### 1. Data Cleaning
The initial step was to clean the provided data to ensure accuracy and relevance. This involved:
- Removing rows with missing values.
- Changing the data type of some values within columns.
- Removing irrelevant columns.

### 2. Data Integration
Three datasets were provided: Content, Reactions, and Reaction Types. The steps included:
- Merging these datasets using VLOOKUP to create a final comprehensive dataset.

### 3. Top 5 Content Categories
To determine the top 5 performing categories:
- Calculated the total scores for each category using the `SUMIF` formula.
- Identified the top 5 categories based on the aggregate popularity.

### 4. Additional Insights
Further analysis provided additional insights:
- **Top 5 Categories**: ![Screenshot 2024-07-28 132900](https://github.com/user-attachments/assets/9f8f08ee-4168-48bc-91f5-c2832afdde7a)

  
- **Popularity Persentage share for top 5 category**: ![Screenshot 2024-07-28 133320](https://github.com/user-attachments/assets/d5bff5e1-3072-45c4-976c-4117e70cf8ab)

 
- **Reactions to the Most Popular Category**: ![Screenshot 2024-07-28 162039](https://github.com/user-attachments/assets/2362bde0-f15b-4db4-9359-772bc5a43c74)


- **Month with the Most Posts**: Identified the month with the highest number of posts using PivotTables.![Screenshot 2024-07-28 162051](https://github.com/user-attachments/assets/925004a8-3a50-4950-a04f-228bb199c6cf)


### 5. Visualization
Created visual representations to highlight key insights:
- Bar charts to display the top 5 content categories.
- Line charts to show monthly posts and reactions.
- Slicers to enable interactive filtering by month and category.

## Detailed Steps

### Data Cleaning
1. **Open the Cleaned Data File**:
   - Use the `Cleaned_data_sheet.xlsx` file for all cleaning operations.

2. **Remove Rows with Missing Values**:
   - Identify and delete rows where any column has missing data.

3. **Change Data Types**:
   - Ensure all dates are in the correct date format.
   - Convert numeric columns to appropriate data types.

4. **Remove Irrelevant Columns**:
   - Analyze the relevance of each column and retain only those pertinent to the business question.

### Data Integration
1. **Use VLOOKUP for Merging**:
   - Merge Content, Reactions, and Reaction Types datasets.
   - Use the Reaction table as the base table.
   - Join relevant columns from the Content dataset.
   - Join relevant columns from the Reaction Types dataset.

### Top 5 Content Categories
1. **Calculate Total Scores**:
   - Use `SUMIF` to add up scores for each category.

2. **Identify Top 5 Categories**:
   - Rank categories based on total scores.

### Additional Insights
1. **Number of Unique Categories**:
   - Use the `COUNTIF` function to count distinct categories.

2. **Reactions to Most Popular Category**:
   - Sum reactions for the top category.

3. **Month with Most Posts**:
   - Extract the month from post dates.
   - Use PivotTables to count posts per month.

### Visualization
1. **Create Charts**:
   - Insert bar charts for the top 5 categories.
   - Insert line charts for monthly data.

2. **Add Slicers**:
   - Insert slicers for interactive filtering.
   - Connect slicers to charts and PivotTables.

### Files in Repository
- `Cleaned_data_sheet.xlsx`: The cleaned and integrated dataset.
- `README.md`: This README file.
- `charts/`: Folder containing all visualizations.

## How to Use
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/social-buzz-analysis.git
   ```

2. **Open the Excel File**:
   - Open `Cleaned_data_sheet.xlsx` in Excel to view the cleaned data and analysis.

3. **View Visualizations**:
   - Open the `charts/` folder to view all visualizations.

4. **Interactive Analysis**:
   - Use Excel's interactive features such as slicers to filter data dynamically.

## Conclusion
This project provides valuable insights into Social Buzz's content performance, highlighting the most popular categories and key metrics. The analysis is comprehensive, leveraging data cleaning, integration, and visualization techniques.

## Acknowledgments
This project is powered by Accenture.

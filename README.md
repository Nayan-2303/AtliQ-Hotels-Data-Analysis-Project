# AtliQ Hospitality Data Analysis Project

This project focuses on analyzing AtliQ Hotels’ booking data to understand occupancy trends, revenue generation, and customer behavior. The insights generated aim to support data-driven decision-making.

---

## Project Overview

The goal of this project is to analyze and interpret booking and operational data from AtliQ Hotels. By examining key metrics across hotel properties and room types, we aim to uncover trends that inform strategic planning and enhance customer satisfaction.

---

## Project Structure

### Step 1: Data Loading and Exploration
   - **Objective**: Load all datasets and perform an initial exploration.
   - **Actions**:
     - Import data files (e.g., bookings, rooms, hotels).
     - Inspect data types, dimensions, and general statistics.
     - Identify any initial issues, such as missing or inconsistent values.

### Step 2: Data Cleaning
   - **Objective**: Clean and preprocess the data to ensure consistency and accuracy.
   - **Actions**:
     - Handle missing or incorrect values.
     - Convert data types (e.g., date fields).
     - Remove duplicates and any irrelevant columns.
   - **Outcome**: Prepared datasets ready for in-depth analysis.

### Step 3: Data Analysis
   - **Objective**: Conduct exploratory data analysis (EDA) to derive insights.
   - **Key Questions**:
     - Which room types and hotels have the highest booking and occupancy rates?
     - Are there seasonal trends or peak times for bookings?
     - What are the main revenue drivers for different locations and room types?

### Step 4: Insights and Recommendations
   - **Objective**: Summarize key findings and propose actionable strategies.
   - **Insights**:
     - **Revenue Analysis**: Identify top revenue-generating room types and locations.
     - **Occupancy Patterns**: Determine high-demand times and adjust pricing accordingly.
     - **Customer Preferences**: Understand room type and location preferences to guide marketing.
   - **Recommendations**:
     - Optimize pricing based on seasonal demand.
     - Target marketing efforts towards high-occupancy periods.
     - Improve services in high-demand hotels or rooms to boost customer satisfaction.

---

## How to Run the Project

1. **Clone the Repository**:
    ```bash
    gh repo clone Nayan-2303/AtliQ-Hotels-Data-Analysis-Project
    ```

2. **Install Required Libraries**:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

3. **Run the Jupyter Notebook**:
    Open and execute `AtliQ Hospitality Data Analysis Project.ipynb` to follow the analysis.

---

## Dataset Information

The analysis utilizes the following datasets:
- **dim_date.csv**: Date information for time-based analysis.
- **dim_hotels.csv**: Details about hotel properties.
- **dim_rooms.csv**: Room types and features.
- **fact_aggregated_bookings.csv**: Aggregated booking data.
- **fact_bookings.csv**: Detailed booking records.

---

## Key Business Questions

This project answers key questions such as:
1. Which room types and hotels are most profitable?
2. What are the peak booking periods?
3. What are the main factors influencing customer booking behavior?

---


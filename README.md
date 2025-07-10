
# POSITION SALARY
## Overview:
      This dashboard provides a detailed analysis of employee salary distribution based on position,   gender, experience, and location. It visually represents how salary and experience vary across different demographic and geographical dimensions using various chart types and a map.

![image](https://github.com/user-attachments/assets/14bbab9a-3b4d-4255-9ff7-0e317b5b105c)


## Dashboard Components:
### 1. Map Visualization (Gender by Location)
    TYPE: Filled Map with data points
    DETAILS: Shows gender distribution across Indian cities such as New Delhi, Bengaluru, Noida, Pune, Hyderabad, Gurugram, and Mumbai.
    PURPOSE: Helps identify gender presence by location, with colored dots representing Male, Female, and NA (unspecified).

### 2. Experience by Gender (Bar Chart)
   TYPE: Horizontal stacked bar chart
   DETAILS:
      * Male: 35,522 years
      * Female: 21,386 years
      * NA: 452 years
  PURPOSE: Compares total years of experience contributed by each gender.

### 3. Experience by Location (Vertical Bar Chart)
     TYPE: Vertical bar chart
     DETAILS: Displays the sum of experience (in years) grouped by cities.
     INSIGHT: Some cities like have notably high experience totals.

### 4. Salary by Gender (Bar Chart)
     TYPE: Horizontal bar chart
     DETAILS:
       * Male salary exceeds others (approximately ₹4 billion).
       * Female salary is lower, followed by NA category.
     PURPOSE: Provides insight into salary disparity across genders.

### 5. Position Filter (Slicer)
     TYPE: Checkbox slicer
     DETAILS: Lets users filter visuals by specific job positions (e.g., .Net Developer, Ab Initio Developer,          Java/J2EE, etc…).
    PURPOSE: Enables role-specific analysis.

## Data Fields Used:
   From the position salary table:
     * Education
     * Experience (Years)
     * Gender
     * Location
     * Position
     * Salary


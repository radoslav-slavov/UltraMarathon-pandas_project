# Ultra Marathon Race Data Analysis

This project analyzes a dataset of ultra marathon races, focusing on events in the USA for the year 2020 with distances of 50km or 50mi. The dataset is sourced from Kaggle's [The Big Dataset of Ultra Marathon Running](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running/data).

## Data Preparation and Cleaning

1. **Filtering Data:**
   - Selected races in the USA from the year 2020 with distances of 50km or 50mi.
   - Extracted relevant race details.

2. **Data Cleaning:**
   - Standardized event names by removing location suffixes.
   - Converted athlete birth years to integer type and calculated athlete ages.
   - Removed unnecessary columns and handled missing values.
   - Ensured data types were appropriate for analysis.

3. **Data Refinement:**
   - Removed records with athlete ages over 100.
   - Reset DataFrame indices.
   - Renamed columns for clarity and reordered them for better readability.

## Analysis

### Visualizations
- **Distribution of race lengths.**
- **Performance comparison by gender for each race length.**
- **Speed distributions for 50mi races.**
- **Relationship between age and average speed by gender.**

### Insights
- Calculated the average speed differences between male and female athletes for 50km and 50mi races.
- Identified the best-performing age groups in 50mi races with a minimum participation of 20 races.
- Determined the worst-performing age groups in 50mi races with a minimum participation of 10 races.

## Key Findings

- **Gender Performance:** Notable differences in average speeds between male and female athletes.
- **Age Performance:** Specific age groups consistently outperform others in 50mi races.

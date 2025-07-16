# WHO Immunization Coverage Analysis

## Project Overview
This project simulates the role of a Junior Data Clerk at the **World Health Organization (WHO)**, analyzing immunization data across settlements. Using population data from **"WEEK 3 DATA B"**, the project estimates vaccination targets and measures coverage levels.

## Dataset
The dataset includes:
- Target population per settlement
- Immunized male and female children
- Calculated target groups: Under-1s, Under-5s, and Pregnant Women

## Key Metrics Calculated
- **Target Under 1 children** (20% of total population)
- **Target Pregnant Women** (70% of Under 1 children)
- **Target Under 5 children** (80% of Under 1 children)
- **Total Immunized Males & Females**
- **Coverage percentage** under each category
- **Gender-specific coverage** of Under 5 children

## Tools Used
- Microsoft Excel
- Excel Functions: `=SUM()`, `=IF()`, `=ROUND()`, `=PERCENTAGE()`
- Data customization

## Sample Calculations
```excel
=Target_Population * 0.2                    // Under-1 Children
=Under_1_Target * 0.7                       // Pregnant Women
=Under_1_Target * 0.8                       // Under-5 Children
=(Immunized / Target) * 100                 // Coverage %

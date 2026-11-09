
# Electric Vehicle Population Analysis – Washington State

An interactive Tableau dashboard exploring electric vehicle (EV) population data in Washington State, with a focus on vehicle characteristics, manufacturers, model years, and EV types.

## Project Overview

This project uses Tableau to analyze electric vehicle population data and present key insights through an interactive dashboard.

The dashboard brings together summary KPIs, manufacturer comparisons, model-year analysis, EV type distribution, and detailed vehicle information to support exploratory analysis of the dataset.

## Dashboard Preview

![Electric Vehicle Population Analysis Dashboard](images/ev_dashboard.png)

## Objectives

- Analyze the electric vehicle population in Washington State.
- Compare vehicle manufacturers based on vehicle counts.
- Explore the distribution of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
- Examine vehicle population patterns across model years.
- Build an interactive dashboard that allows users to explore the data through filters and selection controls.

## Dataset

**Source:** [Electric Vehicle Population Data – Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/electric-vehicle-population)

- **Records:** 130,443
- **Columns:** 17
- **Geographic coverage:** Washington State, USA

The dataset includes information such as vehicle make, model, model year, electric vehicle type, electric range, MSRP, and other vehicle-related attributes.

## Tools & Technologies

- **Tableau:** Data visualization and dashboard development
- **Kaggle Dataset:** Data source
- **Descriptive Analytics:** Exploratory analysis and KPI development

## Dashboard Features

### Key Performance Indicators
- Total EV Vehicles
- Average Range per Vehicle
- Average MSRP
- Total EV Manufacturers

### Visualizations
- **Model-Wise EVs:** Bubble chart displaying vehicle counts by make and model.
- **Manufacturer Comparison:** Bar chart comparing manufacturers based on vehicle count.
- **Year-Wise EV Population:** Line chart exploring vehicle counts across model years.
- **EV Vehicle Type Distribution:** Donut chart comparing EV categories.
- **Detailed Vehicle Table:** Tabular view of vehicle attributes.

### Interactivity
- Model Year selection
- Electric Vehicle Type filtering
- Manufacturer selection for highlighting within the manufacturer comparison chart

The manufacturer selection control highlights the selected manufacturer in the comparison chart; it does not act as a global dashboard filter.

## Key Metrics

The dashboard displays the following summary metrics in its current default view:

| KPI | Value |
|---|---:|
| Total EV Vehicles | 130,443 |
| Average Electric Range | 76.71 miles |
| Average MSRP | $57,080 |
| Total EV Manufacturers | 35 |

*Displayed KPI values reflect the dashboard’s current default view and may change when filters are applied. The Average MSRP calculation excludes records with MSRP values below $1.*

## Analytical Scope

This project focuses on the EV population represented in the Washington State dataset. The analysis explores vehicle population by model year and manufacturer; it should not be interpreted as annual vehicle sales or as a direct measure of nationwide or global EV adoption.

## Project Files

- **Tableau Workbook:** Interactive dashboard and worksheets
- **Dataset:** Source data used for analysis
- **Dashboard Screenshot:** Static preview of the dashboard
- **Project Report:** Supporting documentation covering the project, methodology, analysis, limitations, and post-project review

## Limitations & Future Improvements

- The analysis is limited to the available Washington State dataset.
- The dataset represents vehicle population records rather than annual sales figures.
- Axis scaling, metric consistency, and clearer communication of dashboard controls were identified as potential areas for improvement during a post-project review.
- Further analysis could explore geographic patterns, manufacturer comparisons over time, and more detailed vehicle segmentation.

## Author

**Gaurang Gupta**

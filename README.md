# 📊 Global Salary Prediction & Analysis
**Machine Learning 1 final project exploring factors that influence salary disparities across countries and demographics**

<img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/403120/header.jpg?t=1734531141" width="100%">

## Author List :black_nib:
Micah Thompson 
* LinkedIn: https://www.linkedin.com/in/micah-thompson-/
* Github: https://github.com/MThompson384

Morgan Silvis
* LinkedIn: https://www.linkedin.com/in/morgansilvis/?trk=opento_nprofile_details
* Github: https://github.com/mo-silvis
  
Quentin Phillips
* LinkedIn: https://www.linkedin.com/in/quentin-phillips-01b95215/
* Github: https://github.com/QuentinPhil
  
Tony Afuti
* LinkedIn: https://www.linkedin.com/in/tony-afuti/
* Github: https://github.com/tafuti6

## Company :office:

### Objective: 
This project, which we titled "The Game of Life," focuses on analyzing various factors such as education, age, gender, and location to assess their impact on salary disparities across different countries. Taking inspiration from the classic Game of Life board game, the name reflects how these life choices and circumstances directly influence earning potential, much like how decisions in the board game determine your path and outcomes. We developed predictive models to understand compensation patterns and created interactive data visualizations to effectively communicate our findings to our audience.
### Key Areas of Focus:

* **Cost-of-Living Adjustments:** Analyze and implement fair salary comparisons across countries with different economic conditions using purchasing power parity indices.
* **Demographic Impact Analysis:** Utilize statistical modeling to assess how age, gender, education level, and seniority status influence earning potential.
* **Predictive Modeling:** Enhance salary forecasting through advanced regression techniques including log-log transformations for improved accuracy.
* **Interactive Visualizations:** Create compelling visual representations to present findings and enable real-time salary predictions for different scenarios.

### Expected Outcomes: 

:chart_with_upwards_trend: **Development of robust predictive models** that accurately forecast salary potential based on demographic and geographic factors.

:chart_with_upwards_trend: Creation of an **interactive analysis framework** that enables the audience to explore salary patterns across different countries and demographics.

:chart_with_upwards_trend: Through the exploration of these factors, this project aims to provide valuable insights into **global compensation** disparities and support data-driven decision-making for job seekers.

## Project Details :computer:
### Dataset Description: 
This project utilizes a comprehensive salary dataset from Kaggle containing 6,684 records across 5 countries (USA, UK, Canada, China, Australia). The dataset includes demographic information such as age, gender, education level, years of experience, job titles, race, and seniority status, along with corresponding salary information.
To ensure fair international comparisons, we incorporated cost-of-living indices from Numbeo to create adjusted salary metrics that account for purchasing power differences across countries. This adjustment allows for meaningful analysis of compensation patterns regardless of local economic conditions.

* [Cleaned_Dataset](https://github.com/MThompson384/Game_of_Life.ML-Project/blob/main/Final%20Project%20Data.csv)

### Project Description & Features:

Following our analysis of global salary patterns, our team developed a comprehensive statistical model designed to predict adjusted salaries based on key demographic and geographic factors. This model leverages advanced regression techniques to provide accurate salary forecasting and insights.
The Salary Prediction Model incorporates the following features:

- **Cost-of-Living Adjustment:** The model incorporates purchasing power parity indices to create fair salary comparisons across different countries, ensuring that geographic differences in living costs are properly accounted for.
- **Advanced Regression Modeling:** We implemented log-log transformations to capture non-linear relationships between age and salary, achieving improved model performance with 67% adjusted R-squared.
- **Demographic Analysis:** The system analyzes the impact of gender, education level, and seniority status on earning potential, providing insights into compensation disparities across different groups.
- **Interactive Predictions:** Our model generates salary predictions for individuals based on their demographic profile, enabling exploration of earning potential across different countries and scenarios.
- **Model Validation:** We employed Leave-One-Out Cross-Validation (LOOCV) and comprehensive diagnostic testing to ensure robust model performance and reliable predictions.


## Model Performance :round_pushpin: 
Our final log-log regression model achieved strong predictive performance:

* **Adjusted R-squared:** 67.01% - indicating the model explains approximately 67% of salary variation
* **Cross-Validation:** LOOCV RMSE of 0.371 on log-transformed scale
* **Diagnostic Tests:** Breusch-Pagan test results showed improved heteroscedasticity compared to linear models
* **VIF Analysis**: Multicollinearity assessment confirmed model stability (though interaction terms showed expected higher values)

[Game_of_Life Code](https://github.com/MThompson384/Game_of_Life.ML-Project/blob/main/notebook.ipynb)

## Sample Predictions :lock_with_ink_pen: :
To demonstrate model capabilities, we generated salary predictions for our team members across different countries:

:chart_with_upwards_trend: **USA Baseline:** Team predictions ranged from $63K-$98K based on age and gender differences

:chart_with_upwards_trend: **Education Scenarios:** "Game of Life" analysis showing salary progression from high school ($29K-$31K) to PhD level ($84K-$91K)

:chart_with_upwards_trend: **Cross-Country Comparison:** Consistent ranking patterns across all geographic markets with China offering highest adjusted compensation

The model successfully captures both demographic and geographic factors while providing actionable insights for compensation planning and career decision-making across international markets.

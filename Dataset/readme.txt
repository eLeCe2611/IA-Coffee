Description:
The GlobalCoffeeHealth dataset contains 10,000 synthetic records reflecting real-world patterns of coffee consumption, sleep behavior, and health outcomes across 20 countries. It includes demographics, daily coffee intake, caffeine levels, sleep duration and quality, BMI, heart rate, stress, physical activity, health issues, occupation, smoking, and alcohol consumption.

The dataset captures realistic correlations observed in research—such as caffeine’s impact on sleep, stress, and health—making it ideal for statistical analysis, predictive modeling, and lifestyle or wellness studies.

Columns / Features
Column	Type	Description
ID	Integer	Unique record ID (1–10000)
Age	Integer	Age of participant (18–80 years)
Gender	Categorical	Male, Female, Other
Country	Categorical	Country of residence (20 countries)
Coffee_Intake	Float	Daily coffee consumption in cups (0–10)
Caffeine_mg	Float	Estimated daily caffeine intake in mg (1 cup ≈ 95 mg)
Sleep_Hours	Float	Average hours of sleep per night (3–10 hours)
Sleep_Quality	Categorical	Poor, Fair, Good, Excellent (based on sleep hours)
BMI	Float	Body Mass Index (15–40)
Heart_Rate	Integer	Resting heart rate (50–110 bpm)
Stress_Level	Categorical	Low, Medium, High (based on sleep hours and lifestyle)
Physical_Activity_Hours	Float	Weekly physical activity (0–15 hours)
Health_Issues	Categorical	None, Mild, Moderate, Severe (based on age, BMI, and sleep)
Occupation	Categorical	Office, Healthcare, Student, Service, Other
Smoking	Boolean	0 = No, 1 = Yes
Alcohol_Consumption	Boolean	0 = No, 1 = Yes


Usage & Insights
Explore correlations between coffee intake, sleep quality, and health outcomes.
Analyze lifestyle factors like physical activity, smoking, and alcohol consumption.
Build predictive models for sleep quality, stress levels, or health risks.
Compare demographic and country-level patterns in caffeine consumption.
Use as a benchmark dataset for wellness, lifestyle, or health informatics research.
Phase 1 project
Aircraft Risk Analysis Project

Project Overview
The Aircraft Risk Analysis project focuses on assessing aviation risks using accident data from the National Transportation Safety Board (NTSB) to help a business stakeholder identify low-risk aircraft for purchase and operation. This project is essential as the company is expanding into the aviation industry and needs data-driven insights to make informed decisions about which aircraft models pose the least risk.

Business Problem
Your company is diversifying its portfolio by expanding into the aviation industry. The challenge is to determine which aircraft models are the safest to operate for both commercial and private use. The goal is to identify the aircraft with the lowest risk of accidents and incidents, thus minimizing financial, operational, and safety risks.

The findings from this analysis will provide actionable insights for the new aviation division to guide aircraft purchasing decisions. These insights will highlight key risk factors such as the type of aircraft, purpose of flight, weather conditions, and accident severity.

Data Understanding
The research project used data from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.This dataset contains summaries of aviation accidents and incidents spanning multiple decades, providing detailed information on various aspects of civil aviation accidents.

The dataset contains two files:

Dataset: AviationData.csv Description: This is the main dataset that contains detailed records of aviation accidents and incidents. Each row represents a unique aviation event with attributes such as the aircraft type, accident date, location, severity, weather conditions, and details of injuries or fatalities Relationship to data analysis:This file provides the data necessary for analyzing various risk factors such as aircraft type, flight conditions, and injury outcomes.

Dataset 2: AviationAccidentNarratives.csv Description: This file contains textual summaries or narratives of aviation accidents and incidents. These narratives are written descriptions of the events, typically including information about what led to the accident, the conditions at the time, and any relevant findings from investigations.

Description of relevant columns

Event Id: A unique identifier for each aviation accident or incident
Event Date:The date on which the accident or incident occurred.
Location:The city or general area where the accident or incident took place.
Country: The country where the accident or incident occurred.
Injury Severity: Describes the severity of injuries sustained in the event.
Aircraft Damage: Indicates the extent of the damage sustained by the aircraft.
Make: The manufacturer or company that produced the aircraft.
Model: The specific model of the aircraft involved in the event.
Amateur Built: Indicates whether the aircraft was built by an amateur or a certified manufacturer.
Number of Engines: The number of engines on the aircraft.
Engine Type: The type of engine used by the aircraft.
Purpose of Flight: Describes the intended mission of the flight.
Total Fatal Injuries: The total number of fatal injuries resulting from the accident or incident.
Total Serious Injuries: The total number of serious but non-fatal injuries resulting from the accident.
Total Minor Injuries: The total number of minor injuries resulting from the event.
Total Uninjured: The total number of people on board the aircraft who were uninjured.
Weather Condition: The weather conditions at the time of the accident or incident.
Data Preparation
Summary of Key Steps:

Missing Data Handling: Imputation for categorical and numerical fields, with a focus on critical fields like Injury Severity and Aircraft Damage.

Transformation: Date parsing, encoding of categorical data, creation of new composite risk features.

Data Validation: Consistency checks and removal of erroneous data.

Aggregation: Summarizing data by aircraft model, time, and location.

Visualization Preparation: Aggregating data and transforming features for effective exploratory data analysis and visualization.


Analysis and Insights
The analysis focuses on uncovering trends and risk factors related to aviation accidents. Key insights include:

Accident Trends Over Time: Analyzing accident frequency by year to identify patterns in aviation safety indicates a reducing trend
Aircraft Risk by Make and Model: Identifying aircraft types with higher accident rates.
Impact of Weather Conditions: Assessing how weather affects the likelihood and severity of accidents.
Flight Purpose and Risk: Comparing the safety of different flight types, such as commercial vs. private flights.

Visualizations
Several visualizations were created to highlight important trends:

Accident Trends: A time-series plot showing the number of accidents over the years.
Injury Distribution: Visualizing the severity of injuries for different aircraft models and flight purposes.
Aircraft Risk Comparison: Bar charts comparing accident rates across aircraft makes and models.

Tableau visualization: https://public.tableau.com/app/profile/immaculate.kithei/viz/AircraftInteractiveVisualization/Dashboard1?publish=yes

Based on the analysis of the aviation accident dataset, the following recommendations are made to minimize risk and enhance safety for the company's new aviation division:

Focus on Proven, Low-Risk Aircraft Models:

Aircraft models with a lower history of accidents should be prioritized for acquisition. A data-driven analysis of the Make and Model fields will reveal which aircraft have the best safety records. Commercially established models from trusted manufacturers may present a lower operational risk.
Avoid Aircraft with High Accident Rates:

Certain aircraft models, particularly those that are amateur-built or have a history of mechanical failures, should be avoided. The analysis of the Amateur Built and Engine Type fields can help in identifying these aircraft.
Consider the Purpose of Flight:

The company should carefully consider the intended use of each aircraft (e.g., personal, cargo, or business flights). Aircraft that have been involved in fewer accidents for commercial purposes should be prioritized, as certain models may perform better in cargo or personal flights than in commercial passenger flights.
Weather Preparedness:

Historical data shows that adverse weather conditions (e.g., IMC) significantly increase accident risk. Aircraft models that are better equipped for poor weather conditions (e.g., aircraft with advanced instrumentation and multi-engine systems) should be favored.
Pilots should be trained and certified for Instrument Flight Rules (IFR) to ensure safety during adverse weather conditions.
Select Aircraft Based on Flight Requirements:

Engine Type and Number of Engines: Aircraft with multiple engines may offer increased safety in the event of engine failure, particularly for longer and riskier flights. Aircraft with turbofan or turboprop engines are generally more reliable and should be considered for commercial flights.
Focus on Safety-Enhancing Features:

Look for aircraft models that have been upgraded with modern safety features, such as terrain avoidance systems, weather radars, and enhanced navigation technologies. These features can significantly reduce the risk of accidents.
Continual Risk Monitoring:

Regularly review the accident data to stay updated on emerging risks and trends. Routine maintenance checks should be enforced, especially for aircraft models that historically show higher accident rates due to mechanical failures.
By following these recommendations, the company can make informed decisions that minimize operational risks, ensure safety compliance, and optimize investment in the aviation industry.

Future Improvements
Machine Learning Models: Train predictive models to forecast accident likelihood based on aircraft type and weather conditions.
Real-Time Data Integration: Incorporate real-time aviation data for continuous risk assessment.
Additional Features: Expand the analysis by integrating more external datasets (e.g., maintenance records, pilot experience) for a more holistic risk ass

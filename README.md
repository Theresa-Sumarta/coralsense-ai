# CoralSense

**CoralSense** is a machine learning-powered platform designed to forecast coral reef health under various environmental scenarios. By integrating predictive analytics with an interactive global map, it empowers stakeholders—including conservationists, policymakers, and local communities—to make informed, data-driven decisions to protect one of the planet’s most vital ecosystems.

## Problem

Coral reefs are facing an existential threat due to climate change, overfishing, pollution, and coastal development. These ecosystems support 25% of marine life and protect over 45,000 miles of coastline, yet up to 90% could vanish by 2050 without intervention.

## Solution

CoralSense combines predictive modeling and intuitive visualization to:

- **Forecast coral reef health** using both classification and time series models
- **Simulate environmental scenarios** (e.g., temperature rise, pollution)
- **Visualize** outcomes through an interactive global map
- **Guide conservation strategies** using actionable insights

## Key Features

- **Predictive Analytics**: Identifies at-risk regions and forecasts future reef health
- **Scenario Testing**: Explore how changes in variables (e.g., SST, pollution) impact reefs
- **Interactive Visualization**: Global map for exploring predictions and trends
- **Actionable Insights**: Helps prioritize conservation actions effectively

## Datasets Used

CoralSense utilizes a variety of datasets to predict coral reef health under different environmental scenarios:

- **Bleaching and Environmental Data for Global Coral Reef Sites (1980-2020)** (Biological and Chemical Oceanography Data Management Office): Contains global environmental factors affecting coral health, including sea surface temperature, water quality, sunlight exposure, and hard coral cover percentage.

- **MODIS Aqua Level-3 Remote Sensing Reflectance Dataset** (NASA Earthdata): Measures reflectance in multiple spectral bands, providing insights into water quality and ecosystem health.

- **50 Reefs Global Coral Ocean Warming, Connectivity, and Cyclone Dataset** (University of Queensland): Focuses on reef connectivity and coral larvae dispersal, helping understand coral resilience.

- **Human Development Index (HDI)** (UNDP): Provides data on the relationship between human development and reef health.

- **World Database on Protected Areas** (Protected Planet): Assesses the health of reefs within marine protected areas.

- **Reefs at Risk Revisited** (World Resources Institute): Evaluates threats like overfishing and pollution to coral reefs.

- **Global Distribution of Coral Reefs** (UN World Conservation Monitoring Center): Maps tropical and subtropical coral reefs worldwide.

- **CMIP5 Climate Projections Dataset** (Copernicus Climate Data Store): Offers climate scenario data to forecast the impact of global warming on reefs.

These datasets enable CoralSense to predict coral reef health and provide actionable insights for conservation.

## Models Used

### Classification
- Logistic Regression
- Random Forest Classifier (**Best**: F1-score & Accuracy = **0.84**)
- XGBoost
- Support Vector Machine
- K-Nearest Neighbors
- Multi-Layer Perceptron (Neural Network)

### Time Series Forecasting
- SARIMA
- LSTM (Long Short-Term Memory Network)

## Evaluation

- **Cross-validation** to ensure generalizability
- **Historical alignment** for real-world validation
- **Metrics used**: Accuracy, F1-score, RMSE

## Deployment

The CoralSense system is deployed using modern MLOps and web technologies:

- **Model Deployment**:
  - Trained models are saved as `.pkl` files
  - Served through a **Flask REST API**
  - Containerized and deployed using **Docker**
  - Hosted on **Google Cloud Run** for scalable access

- **Frontend**:
  - Built using **React.js** with interactive map features
  - Backend integration using **Node.js**
  - Hosted and deployed using **Vercel**

## Visualization

CoralSense includes a dynamic, interactive map that:

- Displays reef health predictions for 2030, 2035, and 2040
- Allows users to adjust environmental variables and test conservation strategies
- Highlights at-risk areas based on forecasted scenarios

## Tech Stack

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow, SARIMA)
- **Flask** (for REST API)
- **Docker** (containerization)
- **Google Cloud** (for hosting models & services)
- **React** (frontend)
- **Node.js** (backend integration)
- **Vercel** (hosting the website)

## Live Demo

[Click here to view the live CoralSense demo](https://lnkd.in/gW2-mBud)

## Acknowledgments

We express our heartfelt gratitude to the individuals and organizations who made this project possible:

- **University of California, Berkeley School of Information**: For supporting our research and development.
- **Kira Wetzel and Puya Vahabi**: For their unwavering guidance and mentorship throughout the project.
- **Data Providers**:
  - **NOAA**
  - **Coral Reef Alliance**
  - **Allen Coral Atlas**
  - And other organizations for providing open access to vital environmental data.
- **Dr. Helen Fox** (*Coral Reef Alliance*): For her guidance and expertise on coral reef conservation.
- **Megan Howson** (*Department of Oceanography, Texas A&M University*): For her subject matter expertise and invaluable insights.
- **Our Mentors and Peers**: For their continuous encouragement and support.

## Project Team

- **Theresa Sumarta**
- **Kiara Monahan**
- **Nigel Lewis**
- **Ted Johnson**
- **Tigran Poladian**


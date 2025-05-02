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


Amazon User Segmentation & Interactive Dashboard

This project provides an end-to-end solution for customer segmentation, combining a Python-based data analysis script with a single-page interactive web dashboard for visualizing the results. By analyzing user behavior, the project groups customers into distinct segments, enabling targeted marketing strategies and personalized user experiences.

📋 Project Overview:
The project has two main components:

Python Analysis Script: A script that performs the core data science tasks. It generates a synthetic customer dataset, conducts exploratory data analysis (EDA), applies the K-Means clustering algorithm to segment users, and interprets the results.

Interactive HTML Dashboard: A single-page web application that presents the findings from the analysis in an intuitive, visual, and interactive format. It allows stakeholders to easily explore customer segments and understand the recommended business strategies.

🛠️ Tech Stack:

Data Analysis
Language: Python 3.x

Libraries:

Pandas & NumPy: For data manipulation and numerical operations.
Scikit-learn: For machine learning (K-Means clustering).
Matplotlib & Seaborn: For static data visualization during the analysis phase.
Environment: Jupyter Notebook, Google Colab, or any Python environment.

Interactive Dashboard
Structure: HTML5

Styling: Tailwind CSS (loaded via CDN).

Interactivity: Vanilla JavaScript.

Charting: Chart.js (loaded via CDN).

🚀 How to Run
1. Running the Python Analysis
Prerequisites: Ensure you have Python installed.

Install Libraries: Open your terminal and install the required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab

Execute: Open the Python script (.py or .ipynb) in your preferred environment (e.g., JupyterLab) and run it. This will perform the data analysis and print the results and static plots to your console or notebook.

2. Viewing the Interactive Dashboard
No Setup Needed: The dashboard is a single index.html file with no dependencies to install.
Open in Browser: Simply open the HTML file in any modern web browser (like Chrome, Firefox, or Edge) to view and interact with the dashboard.

📂 Project Workflow
The project follows a structured data science workflow:

Data Generation & Preprocessing: A synthetic dataset is created to simulate customer attributes. The data is cleaned and prepared for modeling.
Exploratory Data Analysis (EDA): Initial visualizations are generated to understand the data's structure and feature distributions.
Clustering with K-Means: The Elbow Method is used to find the optimal number of clusters. The K-Means algorithm then segments the users.
Segmentation Analysis: The characteristics of each segment are analyzed to create distinct customer profiles.
Interactive Visualization: The final segments, insights, and recommended strategies are embedded into the HTML dashboard for dynamic exploration.

✨ Dashboard Features
The interactive dashboard is designed for clarity and ease of use:

Narrative Structure: Guides the user from the high-level project overview to a deep dive into the customer segments.
Interactive Segment Explorer: Click on a customer segment to dynamically update charts and detailed descriptions, allowing for easy comparison.
Dynamic Radar Chart: Visualizes the key characteristics of each selected segment across multiple dimensions (e.g., spending, age, purchase frequency).
Actionable Insights: Clearly presents the profile and recommended marketing strategy for each segment, translating data into business value.
Fully Responsive: The layout adapts seamlessly to desktop, tablet, and mobile devices.

📄 License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code for any purpose.

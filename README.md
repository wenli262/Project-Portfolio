# Project-Portfolio

# Hi, I'm Ayu Wen Li! 👋

### Data Analytics Graduate | Aspiring Data Analyst

Welcome to my GitHub portfolio! I'm a recent Data Analytics graduate from Sunway University, Malaysia where I deepened my knowledge and skills in transforming data into meaningful insights through data analysis, machine learning and visualisation.

---

## 👩🏻‍💻 About Me

I am a recent **Bachelor of Information Systems (Hons) (Data Analytics)** graduate from **Sunway University, Malaysia**.

With a background in data analytics and hands-on experience through academic projects and industry internship, I enjoy exploring datasets, identifying patterns and developing data-driven solutions to real-world problems.

I have experience working on projects involving predictive modelling, big data analytics, data visualisation and geospatial analysis. I also completed an internship at **NielsenIQ (NIQ)**, where I gained exposure to retail measurement, customer success and FMCG market research.

I am currently exploring opportunities in data analytics, business intelligence and data-related roles where I can continue developing my technical skills and contribute to data-driven decision-making.

---

## 🌱 Interests

- **Data Analytics & Business Intelligence** – Exploring data to identify trends and support informed decision-making.
- **Machine Learning & Predictive Modelling** – Applying machine learning techniques to solve real-world problems.
- **Data Visualisation** – Presenting analytical findings through interactive dashboards and visual storytelling.
- **Environmental & Sustainability Analytics** – Exploring the use of data and geospatial technologies for environmental monitoring and conservation.
- **Research & Data Exploration** – Discovering patterns, investigating problems and translating findings into actionable insights.

---

## 🛠️ Skills & Technologies

| Category | Skills & Tools |
|---|---|
| Programming Languages | Python, SQL (Basic), Java, R |
| Data Analysis | Pandas, Microsoft Excel |
| Data Visualisation | Power BI, Streamlit |
| Machine Learning | Scikit-learn, Random Forest, XGBoost, SVM |
| Big Data Analytics | Apache Spark |
| Geospatial Analysis | Google Earth Engine, Geemap |
| Development Tools | Google Colab, Jupyter Notebook, VS Code |
| Other Tools | GitHub, Figma, SAS |

---

## 📂 Featured Projects

### 🌳 1. Predictive Spatial Analysis of Deforestation Risk Using Machine Learning and Remote Sensing Data

**Final Year Capstone Project | 2026**

- Developed a machine learning project to identify and visualise potential deforestation risk in Gua Musang, Kelantan.
- Integrated remote sensing data and environmental variables to support spatial analysis.

**The Challenge:**
- Deforestation is influenced by multiple environmental factors and land-use pressures.
- Identifying areas with a higher risk of forest loss requires analysing spatial and historical data.
  
**The Approach:**
- Applied supervised machine learning classification to distinguish forest-loss and non-forest-loss areas.
- Compared Random Forest, XGBoost and Support Vector Machine (SVM) models.
- Used remote sensing indicators and environmental variables as model features.
  
**The Execution:**
- Collected and processed satellite imagery and forest-loss data using Google Earth Engine.
- Conducted data preprocessing, feature engineering, model training and evaluation using Python.
- Developed an interactive Streamlit dashboard to display deforestation risk maps, model validation and socioeconomic context.

**The Results:**
- Selected Random Forest as the final model based on model evaluation.
- Evaluated performance using accuracy, precision, recall, F1-score and ROC-AUC.
- Produced an interactive dashboard to help users explore potential deforestation risk areas.

**Technologies:** Python, Google Earth Engine, Google Colab, Scikit-learn, XGBoost, Streamlit

🔗 [View Machine Learning Repository](https://github.com/wenli262/Capstone_22017867_Streamlit_Dashboard)
🔗 [View Dashboard Repository](https://github.com/wenli262/Capstone_22017867_machine_learning)

---

### 📊 2. Big Data Analytics: Yelp Business Success Analysis

**Sunway University | 2026**

- Analysed the Yelp Open Dataset to investigate factors associated with business success.
- Implemented a business success scoring approach using customer reviews and engagement data.
  
**The Challenge:**
- The Yelp dataset contains millions of customer reviews, making data integration and processing computationally demanding.
- A consistent scoring method was needed to compare businesses using multiple performance indicators.
  
**The Approach:**
- Used Apache Spark to process and integrate business and review datasets.
- Developed a Business Success Score based on average ratings, review volume and user engagement.
- Reimplemented the analysis using Pandas to compare its performance with Spark.
  
**The Execution:**
- Cleaned and integrated business and review data.
- Applied data transformations and calculated the composite Business Success Score.
- Compared the results and execution time of the Spark and Pandas implementations.

**The Results:**
- Identified and ranked businesses based on their calculated success scores.
- California recorded the highest state-level ranking in both implementations.
- Compared the processing performance and results of Spark and Pandas.

**Technologies:** Python, Apache Spark, Pandas, Jupyter Notebook

🔗 [View Project Repository](https://github.com/wenli262/Business-Intelligence-Files-and-Code)

---

### 🤖 3. Predictive Modelling of Child Mortality Risk Among Teen Mothers

**Sunway University | 2025**

This project focuses on developing and evaluating predictive models to estimate the risk of child mortality among children born to teenage mothers in Western Kenya. Using a dataset from the Harvard Dataverse, the study applies several machine learning algorithms to identify key socio-economic and health-related factors that influence under-five mortality, contributing to better-targeted health interventions for high-risk populations.

**The Challenge:**
Child mortality among teenage mothers remains a severe issue in developing regions due to limited education, healthcare access, and economic hardship. Most existing studies only describe mortality trends instead of predicting risks. The challenge was to shift from descriptive statistics to predictive modelling, enabling early detection of high-risk cases for proactive intervention.

**The Approach:**
- A quantitative, comparative design was used to build and evaluate multiple models including Logistic Regression, Decision Tree, Random Forest, SVM, Naive Bayes, and XGBoost.
- The dataset was filtered for teenage mothers and included key predictors such as marital status, education, wealth index, food insecurity, mental health, and loan burden.
- Models were assessed using metrics suitable for imbalanced data including precision, recall, F1-score, and confusion matrix to ensure meaningful results in identifying rare but critical outcomes.

**The Execution:**
- Conducted data preprocessing: filtering, cleaning, encoding, and normalization.
- Implemented models using Python (Google Colab) with libraries such as pandas, scikit-learn, matplotlib, and seaborn.
- Addressed class imbalance using SMOTE and class weighting.
- Validated results using 5-fold cross-validation and GridSearchCV.
- Visualized performance using bar charts and heatmaps for interpretability.

**The Results:**
- The Logistic Regression model achieved the best overall performance with 67.9% precision, 66.8% recall, and a 67.3% F1-score, outperforming more complex models that suffered from imbalance bias.
- The project demonstrated that recall and F1-score are more reliable metrics than accuracy for health-related datasets and provided practical insights for developing early warning systems to reduce child mortality in vulnerable regions.

**Technologies:** Python, Pandas, Scikit-learn, SMOTE

🔗 [View Project Report](https://github.com/wenli262/Project-Portfolio/blob/main/Predictive%20Modelling%20and%20Model%20Evaluation%20of%20Child%20Mortality%20Risk%20Among%20Teen%20Mothers%20in%20Western%20Kenya%20Report.pdf)

---

### 💡 4. Smart Waitlist System Enhancement

**Sunway University | 2025**

At Sunway University, the subject enrollment process caused recurring stress among students due to limited class slots and inconsistent communication about seat availability. Many students spent hours refreshing pages or messaging lecturers in hopes of securing a spot.

Our project aimed to design a **Smart iZone Waitlist System**, a digital prototype that could make the process more transparent, fair, and efficient, allowing students to join waitlists automatically and receive real-time updates through a dashboard.

**The Challenge:**
- Students often missed out on preferred classes due to unclear or delayed slot information.
- Manual checking and communication made the process time-consuming.
- Lack of transparency in waitlist status caused frustration and anxiety.
- There was no central platform for both students and staff to manage enrollment efficiently.

**The Approach:**
- Applied the **Waterfall System Development Life Cycle (SDLC)** to guide each stage including  planning to testing.
- Conducted requirement analysis to understand user pain points and administrative needs.
- Designed the system prototype using **Figma**, with dashboards, notifications, and queue features.
- Developed **UML diagrams** (Use Case, Sequence, State Transition) to model system flow and interactions.
- Planned and executed **usability testing** to evaluate user experience and satisfaction.

**The Execution:**
- Collaborated as a 6-member development team, each responsible for design, testing, or documentation.
- Created a high-fidelity Figma prototype that simulated real-time enrollment and waitlist actions.
- Developed user dashboards for both students (to track queue positions) and staff (to manage seat approvals).
- Conducted usability testing with 10 participants, collecting both qualitative and quantitative data.
- Measured user satisfaction using the System Usability Scale (SUS), with scores calculated from survey responses.

**The Results:**
- Achieved a **System Usability Score of 80.75**, rated as *“Excellent”*.
- Participants praised the **clarity**, **real-time updates**, and **reduction in manual workload**.
- Demonstrated how digital queue management can **improve fairness** and **reduce stress** during course enrollment.
- The project was awarded the second runner up in the BIS2102 Project Pitching Competition 2025 presented in front of a line of industry panelists.

**Technologies:** Figma

🔗 [View Figma Prototype](https://www.figma.com/proto/AlRvWYK8g5C3TqoSxjjj4A/iZone-Waitlist-System?node-id=502-246&t=v5LCb6JIeTzVDUA0-1&starting-point-node-id=502%3A246)
🔗 [View Report](https://github.com/wenli262/Project-Portfolio/blob/main/BIS%202-4%20Final%20Report.pdf)

### 💡 5. DreamHaven: End-to-End Relational Database Design for an Online Property Booking Platform

**Sunway University | 2024**

DreamHaven is a simulated lodging marketplace similar to Airbnb. The goal of this project was to design and implement a complete relational database system that enables data consistency, secure transactions, and database querying for business insights. The system includes core functional components such as user registration, property listings, bookings, payments, and reviews

**The Approach:**
- **Conceptual Design:** Created a detailed case scenario and **Entity-Relationship Diagram (ERD)**
- **Logical Design:** Developed a Relational Database Model with correct primary keys, alternate keys, and foreign keys
- Implemented **CHECK constraints, triggers, UNIQUE constraints** to enforce business rules (e.g., age ≥ 18)
- Created indexes to improve search performance
- Inserted sample data and developed **SQL queries** for business questions

**The Execution:**
- Designing constraints — **age validation triggers**, payment methods, status restrictions
- Writing & executing SQL queries including:
    - Low-rating property review extraction
    - Booking revenue aggregation
    - Customer behavior analysis (high-value frequent guests) Print - Final Assessment
- Generated a full ERD with cardinalities and business rules
- Fully implemented all 8 relational tables (Host, Guest, Property, Booking, Review, Payment, Facility, PropertyFacility)
- Answered operational questions using JOINs, GROUP BY + HAVING, date functions, subqueries, and MINUS operations

**The Results:**
- Successfully delivered a **complete, functioning database system** with enforced rules and optimized performance
- Queries produced meaningful business insights, including:
    - Identification of properties with declining performance
    - Matching experienced and new hosts for guidance programs
    - Understanding customer satisfaction and spending trends
- Demonstrated capability to manage backend operations similar to a commercial booking platform

**Technologies:**  Oracle SQL Developer, Draw.io / Lucidchart for ERD

🔗 [View Report](https://github.com/wenli262/Project-Portfolio/blob/main/DreamHaven%20Database%20Design.pdf)
🔗 [View Database Script](https://github.com/wenli262/Project-Portfolio/blob/main/DBscript.txt)

---

## 💼 Professional Experience

### NielsenIQ (NIQ)
**Sales Force Activation Intern | Customer Success, Retail Measurement Success**

*January 2026 – April 2026*

- Gained exposure to retail measurement services, FMCG market research and customer success operations.
- Supported data preparation and organisation using Microsoft Excel.
- Developed an understanding of retail measurement services and sales force activation processes.
- Researched and prepared a presentation on Coca-Cola as an FMCG manufacturer.

---

## 🤝Leadership & Volunteer Experience

### Sunway Student Volunteers
**Project Coordinator – Data Collection Department** | April 2025 – Present

- Recruited and coordinated volunteer tutors for a tutoring initiative supporting B40 students.
- Developed and maintained data tracking systems using Google Sheets to monitor student progress.
- Analysed session data to identify areas for improvement in tutoring activities.

### AIESEC in Sunway
**Director of Project Management – Youth Volunteer Programme** | April 2025 – October 2025

- Led a team of three to organise a four-week community project aligned with SDG 3: Good Health and Well-being.
- Coordinated with local communities and health-related organisations.
- Managed volunteer recruitment, event planning, partnerships, budgeting and fundraising activities.

---

## 🎓 Education

**Sunway University, Malaysia**

Bachelor of Information Systems (Hons) (Data Analytics)  
September 2023 – September 2026  
CGPA: 3.72

**Sunway College, Malaysia**

Foundation in Arts  
July 2022 – August 2023  
CGPA: 3.98

---

## 📫 Connect With Me

- 💼 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/wen-li-ayu/)
- 💻 GitHub: [GitHub Profile](https://github.com/wenli262)
- 📧 Email: wenli.ayu1308@gmail.com

---

*Thank you for visiting my portfolio! Feel free to explore my projects and connect with me.*

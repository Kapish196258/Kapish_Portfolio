# 🚀 Projects Portfolio – Kapish Gupta  

This repository presents a collection of **end-to-end data science and analytics projects** completed during my internship at LabMentix.  
Each project demonstrates the application of **theoretical concepts, technical implementation, and business-driven insights** across multiple domains.

---

## 📌 About Me  
- 🎓 BTech & MTech Graduate  
- 📊 Aspiring Data Analyst / Data Scientist  
- 🧠 Strong foundation in Machine Learning, Data Analysis, and Visualization  
- 📈 Focused on solving real-world business problems using data  

---

# 📂 Data Science Projects Overview  

| Project | Domain | Core Methodology |
|--------|--------|----------------|
| Brain Tumor Classification | Healthcare | Deep Learning (CNN, Transfer Learning) |
| Yes Bank Stock Prediction | Finance | Time Series Modeling |
| PhonePe Transaction Insights | FinTech | Data Engineering & Dashboarding |
| Shoppers Spectrum Analysis | Retail | Exploratory Data Analysis |

---

# 🧠 1. Brain Tumor Classification using CNN & VGG16  

## 📌 Project Overview  
This project involves the development of a **deep learning-based image classification system** designed to detect and classify brain tumors from MRI scans into four categories: Glioma, Meningioma, Pituitary, and No Tumor.

---

## 📚 Conceptual Framework  

### Convolutional Neural Networks (CNNs)  
CNNs are a class of deep learning models specifically designed for image data. They operate by applying convolutional filters to extract spatial features such as edges, textures, and shapes. These features are progressively combined across layers to form high-level representations.

### Feature Extraction and Hierarchical Learning  
Lower layers capture basic patterns (edges, gradients), while deeper layers capture complex structures (tumor shapes and boundaries). This hierarchical feature learning is critical for medical image classification.

### Transfer Learning (VGG16)  
Transfer learning involves leveraging a pre-trained model (trained on large datasets like ImageNet) and fine-tuning it for a specific task. This approach:
- Reduces training time  
- Improves model generalization  
- Is especially effective for smaller datasets  

### Softmax Activation  
The final classification layer uses the Softmax function to convert model outputs into probability distributions across multiple classes.

---

## 🎯 Problem Statement  
To develop an automated system capable of accurately classifying brain tumors from MRI images, thereby reducing diagnostic time and minimizing human error.

---

## 🔍 Data Preparation and Preprocessing  
- Standardized image dimensions to 224×224  
- Normalized pixel values  
- Applied data augmentation techniques (rotation, flipping, zooming)  
- Addressed class imbalance through augmentation strategies  

---

## 🛠 Tools and Technologies  

### Python  
Served as the primary programming language for implementing the entire pipeline, including preprocessing, modeling, and evaluation.

### TensorFlow / Keras  
Utilized for designing, training, and evaluating deep learning models. Keras provided a high-level API for rapid model development, while TensorFlow enabled efficient computation.

### OpenCV  
Applied for image preprocessing tasks such as resizing, normalization, and transformation.

### NumPy  
Used for numerical operations and efficient manipulation of multi-dimensional image arrays.

### Pandas  
Handled dataset organization, labeling, and metadata management.

### Matplotlib and Seaborn  
Used to visualize training performance metrics such as accuracy, loss curves, and confusion matrices.

---

## 📊 Key Findings  
- Image intensity and texture variations play a significant role in tumor classification  
- Data augmentation significantly improved model robustness  
- Transfer learning enhanced performance compared to a basic CNN  

---

## 📈 Results and Performance  
- Achieved high classification accuracy across all tumor categories  
- Demonstrated strong generalization on unseen test data  
- Reduced overfitting through regularization and augmentation  

---

## 💡 Insights  
The integration of transfer learning with CNN architectures significantly improves performance in medical imaging tasks, especially when working with limited datasets.

---

## 🚀 Business Impact  
- Enables faster and more reliable medical diagnosis  
- Reduces dependency on manual image analysis  
- Provides a scalable AI-based healthcare solution  

---

# 📈 2. Yes Bank Stock Price Prediction  

## 📌 Project Overview  
This project focuses on predicting the **closing stock prices of Yes Bank** using historical financial data through machine learning techniques.

---

## 📚 Conceptual Framework

### Time Series Analysis  
Time series data consists of observations recorded over time. Key components include:
- Trend (long-term movement)  
- Seasonality (periodic patterns)  
- Noise (random variations)  

### Feature Engineering in Time Series  
Lag variables and rolling statistics are used to capture temporal dependencies and smooth fluctuations in the data.

### Regression Modeling  
Regression algorithms are used to model relationships between input variables (features) and the target variable (stock price).

---

## 🎯 Problem Statement  
To predict future stock prices based on historical data patterns, enabling informed financial decision-making.

---

## 🔍 Data Processing  
- Converted date column into datetime format  
- Established time-based indexing  
- Generated lag features and rolling averages  

---

## 🛠 Tools and Technologies  

### Python  
Used for implementing the complete data processing and modeling workflow.

### Pandas  
Enabled efficient manipulation of time-series data, including indexing and feature creation.

### NumPy  
Handled numerical computations required for modeling.

### Matplotlib and Seaborn  
Used to visualize stock price trends, correlations, and model performance.

### Scikit-learn  
Applied for building regression models and evaluating predictive performance.

---

## 📊 Key Findings  
- Identified strong upward and downward trends in stock performance  
- High correlation observed among price-related variables  
- Market volatility significantly impacts predictions  

---

## 📈 Results and Performance  
- Successfully captured stock price trends  
- Feature engineering improved predictive accuracy  
- Model aligned well with historical price movements  

---

## 💡 Insights  
Time-series forecasting relies heavily on feature engineering, and preserving volatility is essential for realistic predictions.

---

## 🚀 Business Impact  
- Assists investors in making informed decisions  
- Supports financial forecasting and risk analysis  

---

# 💳 3. PhonePe Transaction Insights Dashboard  

## 📌 Project Overview  
This project involves building a **data pipeline and interactive dashboard** to analyze digital payment transactions across India.

---

## 📚 Conceptual Framework 

### ETL (Extract, Transform, Load)  
A structured data pipeline process:
- Extract raw data  
- Transform into structured format  
- Load into database  

### Relational Database Systems  
Used to store structured data efficiently and enable complex queries.

### Data Visualization  
Transforms raw data into meaningful insights through graphical representation.

### Dashboarding  
Interactive dashboards allow users to explore data dynamically and make decisions.

---

## 🎯 Problem Statement  
To analyze digital payment trends and derive insights related to user behavior and regional performance.

---

## 🔄 Data Pipeline  
- Extracted JSON data  
- Transformed into structured format  
- Stored in MySQL database  
- Queried using SQL  
- Visualized using Streamlit  

---

## 🛠 Tools and Technologies  

### Python  
Used for data extraction, transformation, and integration with the database.

### Pandas  
Performed data cleaning and transformation operations.

### MySQL  
Used as a relational database to store and manage structured data.

### SQL  
Enabled querying, aggregation, and analysis of large datasets.

### Streamlit  
Developed an interactive dashboard for real-time data exploration.

### Plotly  
Created dynamic and interactive visualizations.

### Git and GitHub  
Managed version control and project collaboration.

---

## 📊 Key Findings  
- Higher transaction volumes in South and West India  
- Urban regions exhibit higher engagement  
- Device brands influence user adoption patterns  

---

## 📈 Results and Performance  
- Developed a fully functional interactive dashboard  
- Extracted actionable insights for decision-making  

---

## 💡 Insights  
Digital payment adoption is strongly influenced by regional development and technology accessibility.

---

## 🚀 Business Impact  
- Helps fintech companies identify high-growth regions  
- Supports strategic expansion and marketing decisions  

---

# 🛒 4. Shoppers Spectrum – Retail Data Analysis  

## 📌 Project Overview  
This project analyzes large-scale retail transaction data to uncover insights related to sales, customer behavior, and revenue patterns.

---

## 📚 Conceptual Framework 

### Exploratory Data Analysis (EDA)  
EDA is used to summarize and visualize data to uncover patterns, detect anomalies, and test hypotheses.

### Data Cleaning  
Ensures data quality by handling missing values, removing inconsistencies, and eliminating invalid records.

### Customer Behavior Analysis  
Focuses on identifying purchasing patterns and customer preferences.

### Revenue Analysis  
Examines sales trends over time to identify peak periods and growth opportunities.

---

## 🎯 Problem Statement  
To derive actionable insights that help optimize sales performance and customer targeting.

---

## 🔍 Data Cleaning  
- Removed missing and invalid entries  
- Filtered cancelled transactions  
- Ensured dataset consistency  

---

## 🛠 Tools and Technologies  

### Python  
Primary language used for data analysis.

### Pandas  
Handled data cleaning, transformation, and aggregation.

### NumPy  
Performed numerical operations efficiently.

### Matplotlib  
Used for basic data visualization.

### Seaborn  
Provided advanced statistical visualizations.

---

## 📊 Key Findings  
- Majority of transactions originate from the United Kingdom  
- A small number of products contribute significantly to total revenue  
- Strong seasonal sales patterns observed  

---

## 📈 Results and Performance  
- Identified top-performing products  
- Detected revenue peaks and seasonal trends  
- Extracted meaningful customer insights  

---

## 💡 Insights  
Accurate data cleaning is essential for reliable analysis, and seasonality plays a major role in retail performance.

---

## 🚀 Business Impact  
- Improves inventory planning  
- Enhances targeted marketing strategies  
- Supports revenue forecasting  

---

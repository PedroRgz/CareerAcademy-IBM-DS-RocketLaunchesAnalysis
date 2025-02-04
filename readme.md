# SpaceX Analysis & Machine Learning Insights

## About

This repository is the result of an extensive project that combines data collection, exploratory analysis, and machine learning techniques to extract meaningful insights from SpaceX data. It demonstrates advanced skills in data analysis, visualization, and predictive modeling, while also showcasing the ability to design interactive dashboards. The project is organized into three main stages, each represented by its respective Jupyter notebooks and supporting files.

## Index

1. **Stage 1: Information Collection & Data Wrangling**  
   - [Data-collection-SpaceX_API.ipynb](notebooks/Data-collection-SpaceX_API.ipynb)  
   - [Data-collection-webscraping-Wiki.ipynb](notebooks/Data-collection-webscraping-Wiki.ipynb)  
   - [Data-wrangling.ipynb](notebooks/Data-wrangling.ipynb)

2. **Stage 2: Exploratory Data Analysis (EDA) & Data Visualization**  
   - [EDA-DataVisualization.ipynb](notebooks/EDA-DataVisualization.ipynb)  
   - [EDA-Visualization-Maps-Folium.ipynb](notebooks/EDA-Visualization-Maps-Folium.ipynb)  
   - [EDA-SQLite.ipynb](notebooks/EDA-SQLite.ipynb)

3. **Stage 3: Machine Learning & Dashboard Integration**  
   - [MachineLearning-Training&Predicting.ipynb](notebooks/MachineLearning-Training&Predicting.ipynb)
   - The machine learning stage and dashboard functionalities are implemented in the project code, including the main application file: [main.py](main.py)

4. **Conclusion**  
   - Reflections on the learning outcomes, the enhancement of technical skills, and the development of new workflow strategies.

---

## Stage 1: Information Collection & Data Wrangling

In this first stage, the main goal is to acquire raw data from different sources and then process it into a clean, usable format. This stage is crucial as it forms the base for all subsequent analyses and modeling, demonstrating proficiency in data acquisition, cleaning, and preparation – skills that are highly valued in any data-driven role.

### Inside the notebooks...

- **Data-collection-SpaceX_API.ipynb**  
  - **Summary:**  
    This notebook connects to the SpaceX API to retrieve data about launches, rockets, and other relevant information directly from an official source. It involves sending HTTP requests, handling JSON responses, and parsing the retrieved data.  
  - **Acquired Skills:**  
    - API integration and utilization  
    - JSON parsing and data serialization  
    - Automating data retrieval workflows  
  - **Relevance:**  
    Working with APIs is a fundamental skill in the industry, enabling professionals to integrate and use real-world data streams for analysis and decision-making. This notebook shows practical experience in interacting with live data sources.

- **Data-collection-webscraping-Wiki.ipynb**  
  - **Summary:**  
    This notebook focuses on extracting supplementary information from Wikipedia through web scraping techniques. It gathers additional context and metadata that enrich the dataset, such as historical background or descriptive details on launch sites and spacecraft.  
  - **Acquired Skills:**  
    - Web scraping using libraries (e.g., BeautifulSoup, Requests)  
    - Parsing and cleaning HTML content  
    - Data enrichment from unstructured web sources  
  - **Relevance:**  
    Web scraping skills are essential for situations where APIs or pre-structured data are not available. This notebook underscores an ability to derive value by extracting and processing information directly from web pages, a common real-world requirement.

- **Data-wrangling.ipynb**  
  - **Summary:**  
    In this notebook, the raw datasets obtained from various sources are transformed into a consistent, structured format. It involves cleaning the data, handling missing values, merging datasets, and preparing the data for analysis.  
  - **Acquired Skills:**  
    - Data cleaning and preprocessing using Pandas  
    - Data transformation techniques  
    - Merging and aggregating multiple data sources  
  - **Relevance:**  
    Data wrangling is the backbone of any data science project. The ability to clean and prepare data is critical because it directly impacts the accuracy and reliability of any analysis or predictive model. This notebook demonstrates practical experience in data preparation, a skill indispensable in the labor market.

## Stage 2: Exploratory Data Analysis (EDA) & Data Visualization

This stage focuses on extracting insights from the cleaned dataset and presenting them through various visualization techniques. The EDA process not only uncovers hidden patterns and trends in the data but also validates the assumptions made during data preparation. The combination of analytical and visualization skills demonstrated here is highly valued in the labor market.

### Notebooks:

- **EDA-DataVisualization.ipynb**  
  - **Summary:**  
    - Explores the dataset through statistical summaries and visual plots.
    - Utilizes libraries such as Matplotlib and Seaborn to create graphs that illustrate key metrics, trends, and relationships.
    - Helps in identifying patterns, outliers, and correlations among variables.  
  - **Acquired Skills:**  
    - Data visualization techniques.
    - Statistical analysis with Python.
    - Effective communication of data insights through charts.  
  - **Relevance:**  
    - The ability to transform complex data into intuitive visualizations is crucial for data storytelling and decision-making in any professional environment.

- **EDA-Visualization-Maps-Folium.ipynb**  
  - **Summary:**  
    - Leverages Folium to create interactive maps that display geospatial information related to launch sites.
    - Integrates custom markers, pop-ups, and icons to highlight specific details (e.g., NASA JSC).
    - Enhances spatial understanding of the dataset by visualizing locations on a map.  
  - **Acquired Skills:**  
    - Geospatial data visualization using Folium.
    - Customizing map markers and integrating interactive elements.
    - Combining data analysis with location-based insights.  
  - **Relevance:**  
    - Geospatial visualization is a powerful tool in many industries such as logistics, urban planning, and marketing, showcasing the ability to handle and present spatial data meaningfully.

- **EDA-SQLite.ipynb**  
  - **Summary:**  
    - Demonstrates how to load, query, and analyze data from a SQLite database.
    - Executes SQL queries within the notebook environment, bridging the gap between traditional SQL and Python-based data analysis.
    - Provides a practical approach to handling datasets stored in relational databases.  
  - **Acquired Skills:**  
    - SQL query execution and database management.
    - Integration of SQL with Python for streamlined data analysis.
    - Handling relational data to derive actionable insights.  
  - **Relevance:**  
    - Proficiency in SQL and database interaction is essential in many data-centric roles, making it a highly marketable skill that complements modern data science workflows.

- **MachineLearning-Training&Predicting.ipynb**  
  - **Summary:**  
    This notebook guides you through the complete machine learning workflow using SpaceX data. It begins with comprehensive data preprocessing, including feature engineering and data splitting, and advances to model training, evaluation, and prediction. Various algorithms are tested and compared using cross-validation and performance metrics (accuracy, precision, recall, and F1-score). Visualizations are also provided to interpret and compare model performance effectively.
  - **Deep Insights:**  
    - Establishes a clear, reproducible pipeline for data preparation and transformation, ensuring the models are built on sound data foundations.  
    - Demonstrates the application of multiple machine learning algorithms, highlighting the methodology behind model selection and hyperparameter tuning.  
    - Provides a balanced evaluation of different predictive models, discussing trade-offs between complexity, interpretability, and performance.  
    - Integrates visualization techniques to aid in understanding the behavior of the models and diagnosing potential issues with the predictions.
  - **Acquired Skills:**  
    - Building end-to-end machine learning pipelines, from data preprocessing to model evaluation.  
    - Utilizing scikit-learn for model training, cross-validation, and performance analysis.  
    - Critical assessment of model results to derive actionable insights for real-world predictive tasks.
  - **Relevance:**  
    - These competencies are crucial in the industry, where deploying robust and interpretable predictive models can drive significant business decisions. The notebook reflects a practical, well-rounded approach to machine learning that is highly valued by recruiters.

## Dashboard Integration & Web Application

The dashboard is built using [Dash](https://dash.plotly.com/) and [Plotly Express](https://plotly.com/python/plotly-express/), which were chosen for their simplicity, versatility, and interactive visualization capabilities. These technologies allow for rapid development of web-based data applications that can provide real-time insights and dynamic user interactions, making them highly relevant in today’s market.

### Key Points:

- **Technologies Used:**  
  - *Dash & Plotly:* Enable creation of interactive visualizations, responsive layouts, and real-time data updates.  
  - *Python & Pandas:* Streamline data manipulation and cleaning, ensuring that the application is built on solid data foundations.

- **Why They Were Chosen:**  
  - **Rapid Prototyping:** Dash allows for quick iteration and testing of ideas in a notebook environment before porting to a standalone app.
  - **Interactivity:** Plotly’s interactivity enhances user engagement by allowing dynamic filtering of data via dropdowns, sliders, and real-time chart updates.
  - **Scalability:** Porting the dashboard from a notebook to a single Python file (`main.py`) helps in creating a modular, production-ready application that can be easily maintained and deployed.

- **Market Usability & Relevance:**  
  - Interactive dashboards are in high demand as companies emphasize data-driven decision making.
  - The skills developed through this project—data visualization, UI/UX design, and web app deployment—are highly sought after in professional data science and business intelligence roles.

- **Deployment & Access:**  
  - The dashboard has been deployed to an Azure App Service using GitHub Actions for continuous integration and deployment.  
  - You can interact with the live dashboard here: [SpaceX Launch Records Dashboard](https://ibm-ds-rocket-launches-analysis-gscza3f6h6fkg3as.mexicocentral-01.azurewebsites.net)

This integration not only demonstrates the ability to build sophisticated visual analytics tools but also the proficiency to bring a data project from exploratory analysis to a fully functional, deployed web application.

## Conclusion

Throughout this project, I have gained a comprehensive understanding of the entire data analytics pipeline—from collecting raw data via API integrations and web scraping to cleaning, visualizing, and ultimately building predictive models. I have learned to manipulate and process complex datasets, transform them into actionable insights, and communicate these findings through interactive dashboards developed with Dash and Plotly.

This journey has significantly enhanced my technical abilities and broadened my expertise in data analysis, machine learning, and web application deployment. I now feel more confident in my ability to tackle real-world data challenges and contribute effectively to data-driven decision-making processes.

The skills and knowledge I have acquired not only boost my career prospects but also empower me to create scalable, production-ready solutions that are highly relevant in today’s market. I am excited about leveraging these experiences in my next role, and I am confident that my practical and innovative approach will be a valuable asset to any organization.


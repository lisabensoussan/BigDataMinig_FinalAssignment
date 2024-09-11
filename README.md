### Part 1: BigQuery & SQL 

This part focuses on querying **BigQuery** using its Python API and performing data analysis on public datasets hosted on Google Cloud. The tasks include writing optimized SQL queries, loading the results into Pandas DataFrames, and generating insightful visualizations.

#### Overview

- **Platform**: Google BigQuery (Serverless Data Warehouse)
- **Goal**: Perform SQL queries on public datasets using the BigQuery Python API.
- **Environment**: Jupyter Notebook (e.g., Google Colab)
- **Key Tools**: BigQuery, Pandas, Matplotlib

#### Topics Covered

1. Querying public datasets using BigQuery SQL.
2. Loading query results into Pandas DataFrames.
3. Visualizing query outputs using Pandas' `plot` method.
4. Analyzing San Francisco public datasets (film locations, police, and fire department data).
5. SQL optimization and resource management in BigQuery.

#### Tasks

1. **Basic SQL Queries**: Query 1000 rows from the San Francisco film locations dataset and analyze the data.
2. **DataFrame Analysis**: Load the SQL query results into Pandas DataFrames, perform data cleaning, and extract key insights.
3. **Visualization**: Plot trends of film productions in San Francisco, including the most popular filming locations.
4. **Incident Analysis**: Analyze police and fire department incidents and visualize daily trends.

#### Requirements

- Google Cloud authentication (`gcloud auth application-default login`).
- Libraries: `google-cloud-bigquery`, `pandas`, `matplotlib`.
- Submit the executed Jupyter notebook with outputs, including visualizations.

---

### Part 2: Networks [42 pts]

This part involves analyzing **Wikipedia's 2002 network dataset** by extracting and processing the network graph, conducting PageRank analysis, simulating a random network, and using community detection algorithms.

#### Overview

- **Platform**: NetworkX for Python
- **Goal**: Analyze a directed network of Wikipedia pages, compute PageRank, simulate a random graph, and detect communities.
- **Dataset**: English Wikipedia Network from 2002.
- **Environment**: Jupyter Notebook

#### Topics Covered

1. **Network Analysis**:
   - Compute in-degree and out-degree distributions.
   - Identify nodes with the highest degrees.
   - Compare the real network with a simulated Erdos-Renyi random network.
2. **PageRank Algorithm**:
   - Run the PageRank algorithm and identify top-ranked Wikipedia pages.
   - Perform Topic-Specific PageRank (e.g., sports, atheism pages).
3. **Community Detection**:
   - Use the **Louvain algorithm** to detect communities in the undirected network.
   - Visualize and interpret the community structure.
4. **Text Analysis**:
   - Analyze the most frequent words in HTML content for the top 5 largest communities.

#### Tasks

1. **Network Degree Analysis**: Compute and plot the degree distributions (in and out-degree).
2. **Random Network Simulation**: Generate an Erdos-Renyi random graph and compare the degree distribution with the real network.
3. **PageRank**: Run PageRank and Topic-Specific PageRank on the directed network.
4. **Community Detection**: Detect and visualize communities using the Louvain algorithm and analyze their structures.

#### Requirements

- Libraries: `networkx`, `matplotlib`, `pandas`, `community`, `nltk`, `wordcloud`.
- Submit the fully executed Jupyter notebook, including visualizations and results.

---

### Part 3: Spark [24 pts]

In this part, you'll perform data analysis using **Apache Spark** by leveraging RDDs and DataFrames to manipulate and analyze a large dataset of loan information.

#### Overview

- **Platform**: Apache Spark (Big Data Processing)
- **Goal**: Use Spark's RDD and DataFrame APIs to process a large dataset and perform distributed computations.
- **Dataset**: Lending Club loan data (multiple CSV files).
- **Environment**: Jupyter Notebook (Databricks, Google Colab, etc.)

#### Topics Covered

1. **RDD Operations**:
   - Map-Reduce operations to calculate loan amounts, filter based on conditions, and compute aggregates like max, min, and average values.
2. **DataFrame Operations**:
   - Use Spark DataFrames to perform SQL-like queries and aggregations on loan data.
3. **Data Cleaning**:
   - Remove missing values, clean data fields (e.g., interest rates), and handle data formatting issues.
4. **Data Visualization**:
   - Use Matplotlib and Seaborn to visualize the insights obtained from Spark DataFrame operations.

#### Tasks

1. **RDD Operations**:
   - Compute total loan amounts, filtered by conditions like home ownership.
   - Calculate average interest rates for different loan grades.
   - Analyze the distribution of loan purposes.
2. **Interesting Trends**:
   - Perform exploratory analysis on the dataset and generate interesting statistics or visualizations.
3. **DataFrame Aggregations**:
   - Analyze loan purposes, average loan amounts, and interest rates across different states.
   - Visualize loan status distribution by grade using a stacked bar chart.

#### Requirements

- Libraries: `pyspark`, `pandas`, `matplotlib`, `seaborn`.
- Submit the fully executed Jupyter notebook, including results and visualizations.


# Oberon's Datascience Wiki

## What is this?
During my bachelor I learnt a lot, but never took the time to relate all concepts to eachother. Which I now see as a missed opportunity.
So as I started my new Data Science study, I thought it would be a good idea to try to organise the concepts in one place.

Currently, the list below is more of a braindump of concepts and terms related to Data Science that crossed my path last year.
It's obviously a work in progress 😬

## Buzzword Bingo
and what they might actually mean ...
- Big Data
- The Cloud
- Machine Learning
- Algorithm
    - Time Complexity
    - Space Complexity

## Data Engineering, ETL & Tools
- Kimball data modelling theory
- Information retrieval
	- Web Scraping
		- BeautifulSoup
		- Scrapy
		- Selenium
	- API formats
		- REST
		- SOAP
		- GraphQL
- Data pipeline orchestration
    - Concepts
        - Directed acyclic graphs
        - Idempotency
    - Tools
        - Batch scripts
        - Luigi
        - Airflow
- Data storage
    - File formats
        - CSV
        - JSON
            - Preprocessing: JSON 2 CSV -> jq cli tool (brew install jq)
        - XML
        - Pickle
        - HD5
        - Parquet
    - Databases
        - Relational / SQL
            - Data modelling
            - SQL basics
        - Non-Relational / NoSQL
            - MongoDB
            - Cassandra
            - ElasticSearch
            - Neo4J (Graph)
    - Datalakes
- Distributed computing
    - MapReduce pattern
	- DASK
	- Hadoop
		- HDFS
	- Spark
		- PySpark
    - Kafka (streaming data)

## Data Types (+ Preprocessing)
- Images
	- Image Augmentation
- Sound
- Time Series
- NLP / Text processing
	- Stemming
	- Tokenization
- Trees / Structures / Hierarchies
	- Graph theory
- Geo data
	- Raster data
	- Vector data
    - Sattelite data
    - GPS Coordinates
- Streaming data (of various kinds)

## Machine learning / Statistical learning methods
- Bias-Variance Trade-Off
- Feature extraction
- Dimensionality reduction
    - PCA
- Unsupervised vs. Supervised Learning
- Supervised learning
    - Regression
        - Linear regression
        - Logistic regression
    - Classification
        - Naive Bayes
        - Decision Trees
            - Simple Decision Trees
            - Bagging & Boosting
            - Random Forests
            - XGBoost
        - K-NN
        - Support Vector Machines (SVM)
- Unsupervised learning
    - Clustering
        - K-means
        - Fuzzy C-means (Soft K-means)
        - Expectation Maximization
        - DBSCAN
- Reinforcement Learning
- Recommender systems
	- Collaborative filtering
- Hidden Markov Models
- Gradient Descent

## Statistics
- Statistics, big data and modern data science
    - Statistics alone is old data science?
    - With big data, are samples still needed?
    - Role of statistics in modern data science
- Bayes Theorem
- Distributions
	- Normal / Guassian
	- Exponential
	- Gamma
	- Uniform
	- Poisson
	- Binomial
	- t-distribution
	- Chi-squared
- Probability
- Confidence intervals
	- One-sides / two-sided
- Tests
	- Shapiro Wilkx (Normality)
	- Chi-squared
    - ...
- ROC curves
- Coding examples
	- R
	- Python

## Neural nets
- Basic theory
- Turi for images

## Optimalisation & Simulation
- Mathematical Optimalisation (Operations Research)
    - (Non-)Linear programming
	- Heuristics
	- Multi-Criteria Decision Making
- Simulation
	- Monte-Carlo
	- Agent-Based Modelling
	- (Refer to Decision Science 2 for type of simulation?)


## Programming
- Programming languages
	- Python
	- Go lang
	- Scala
	- Lua
	- C++
	- Java
	- Swift
- Design patterns
- Important concepts
	- Object Oriented Programming / Functional programming
	- GIT / Version Control
	- Interpreted vs Compiled
	- Data structures & typing
- Security basics
	- OWASP top10
- Building a simple (data) webservice 101
	- Servers: Apache & Nginx [Apache vs Nginx: Practical Considerations @ DigitalOcean](https://www.digitalocean.com/community/tutorials/apache-vs-nginx-practical-considerations)
	- Code: Go example, Python example, Nginx static example
	- Design Patterns (direct calculation, jobs with queue, pre-calculated caches)

## Visualisation & Communication
- Visualisation theory basics
- Frameworks for plotting
	- Matplotlib (Py)
	- Seaborn (Py)
	- ggplot (R)
	- Shiny (R)
	- D3.js (JS)
	- Processing(.js) (JS)
- Plotting geographical data
	- Python: gdal / shapely / descartes / geopandas
- Storytelling

## Data Science Process
- Scientific method
- Research methods
	- Qualitative research
	- Quantitative research
- Data Science lifecycle / process 
	- models (comparisson)
		- CRISP-DM model
		- Harvard Data Science model
		- Microsoft Data Science Lifecycle
		- Sacha 2014
- Problem recognition & formulation
- Critical thinking 101
- Scenario thinking
- Information analysis & information (system) ecosystems
- Data-driven Decision making


## Cloud providers
And what kind of tools they offer...
- AWS
- Google
- Microsoft Azure

## Other
- Data Privacy laws (GDPR)
- Emergent properties of data and what data science can actually bring you
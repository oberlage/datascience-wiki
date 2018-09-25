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
    1. Time Complexity
    2. Space Complexity

## Data Engineering, ETL & Tools
- Kimball data modelling theory
- Information retrieval
	- Web Scraping
		1. BeautifulSoup
		2. Scrapy
		3. Selenium
	- API formats
		1. REST
		2. SOAP
		3. GraphQL
- Data pipeline orchestration
    - Concepts
        1. Directed acyclic graphs
        2. Idempotency
    - Tools
        - Batch scripts
        - Luigi
        - Airflow
- Data storage
    - File formats
        - CSV
        - JSON
            1. Preprocessing: JSON 2 CSV -> jq cli tool (brew install jq)
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
- Text processing / NLP
	- Lemmatization (Stemming)
	- Tokenization
- Trees / Structures / Hierarchies
	- Graph theory
- Geo data
	- Raster data
	- Vector data
    - Sattelite data (Spectra)
    - GPS Coordinates & Projections
- Streaming data (of various kinds)

## Machine learning / Statistical learning methods
- Bias-Variance Trade-Off
- Dimensionality reduction
    - Feature extraction
        - PCA
    - Feature selection
- Unsupervised vs. Supervised Learning
- Supervised learning
    - Regression
        - Linear regression
        - Logistic regression
    - Classification
        - Naive Bayes
			1. `Naive` is because it assumes all features are independent
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
		- Hierarchical Clustering
			1. Ward Linkage
			2. Average Linkage
			3. Complete Linkage
        - DBSCAN
- Reinforcement Learning
- Recommender systems
	- Collaborative filtering
- Hidden Markov Models
- Gradient Descent
- Topic Modelling
	- Term Frequency Inverse Document Frequency (TF-IDF)
	- Latent Dirichlet Allocation (LDA)
	- Non-Negative Matrix Factorization (NNMF)

## Statistics
- Statistics, big data and modern data science
    1. Statistics alone is old data science?
    2. With big data, are samples still needed?
    3. Role of statistics in modern data science
- Frequentist Statistics vs. Bayesian Statistics
	1. Frequentist Probability
	2. Bayes Theorem
- Bias
	1. Inductive bias
	2. Postdiction & Hindsight bias
	3. ...
- Distributions
	1. Normal / Guassian
	2. Exponential
	3. Gamma
	4. Uniform
	5. Poisson
	6. Binomial
	7. t-distribution
	8. Chi-squared
- Probability
- Confidence intervals
	- One-sides / two-sided
- Tests
	1. Shapiro Wilkx (Normality)
	2. Chi-squared
    3. ...
- ROC curves
- Coding examples
	1. R
	2. Python

## Neural nets
- Basic theory
- Turi for images

## Optimalisation & Simulation
- Mathematical Optimalisation (Operations Research)
    1. (Non-)Linear programming
	2. Heuristics
	3. Multi-Criteria Decision Making
- Simulation
	1. Monte-Carlo
	2. Agent-Based Modelling
	3. (Refer to Decision Science 2 for type of simulation?)


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
	1. Matplotlib (Py)
	2. Seaborn (Py)
	3. ggplot (R)
	4. Shiny (R)
	5. D3.js (JS)
	6. Processing(.js) (JS)
- Plotting geographical data
	- Python Tools
		1. gdal
		2. shapely
		3. descartes
		4. geopandas
- Storytelling

## Data Science Process
- Scientific method
	1. Occam's Razor
	2. Scientific Modelling
- Research methods
	1. Qualitative research
	2. Quantitative research
- Data Science lifecycle / process 
	- models (comparisson)
		1. CRISP-DM model
		2. Harvard Data Science model
		3. Microsoft Data Science Lifecycle
		4. Sacha 2014
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

## Nice links to articles/etc
- [Stanford Machine Learning Cheatsheet: Supervised learning](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning)
- [Stanford Machine Learning Cheatsheet: Unsupervised learning](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-unsupervised-learning)
- [Stanford Machine Learning Cheatsheet: Machine Learning Tips&Tricks](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks)
- [Stanford Machine Learning Cheatsheet: Deep Learning](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-deep-learning)

## Links to Data Science blogs 
- [Towards Data Science](https://towardsdatascience.com)
- [Datascience Central](https://www.datasciencecentral.com)
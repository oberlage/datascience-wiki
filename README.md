# Oberon's Datascience Wiki

## What is this?
During my bachelor I learnt a lot, but found that the overview between concepts in different courses is lacking. 
So as I started a new study, I'll try to organise the concepts and (try to) summarize my knowledge.

Currently, the list below is more of a braindump of concepts and terms related to Data Science that crossed my path last year.


## Buzzword Bingo
- Big Data
- The Cloud
- Machine Learning
- Algorithm

## Data Engineering Tools
- Kimball data modelling
- Datalakes
- Data pipeline orchestration
	- Luigi (Job scheduler / pipelines)
	- Airflow
- Databases
	- Relational Databases / SQL
		- Data modelling
		- SQL basics
	- NoSQL
		- MongoDB
- Information retrieval
	- Web Scraping
		- BeautifulSoup
		- Scrapy
		- Selenium
	- API formats
		- REST
		- SOAP
		- GraphQL
- Data storage
	- CSV
	- JSON
		- Preprocessing: JSON 2 CSV -> jq cli tool (brew install jq)
	- XML
	- Pickle
	- HD5
	- Parquet
- Distributed computing
	- DASK
	- Hadoop
		- HDFS
	- Spark
		- PySpark

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
- Streaming data (of various kinds)

## Machine learning / Statistical learning methods
- Feature extraction
- Unsupervised vs. Supervised Learning
- PCA
- Regression
    - Linear regression
    - Logistic regression
- Decision Trees
    - Simple Decision Trees
    - Random Forests
    - XGBoost
- Recommender systems
	- Collaborative filtering
- Hidden Markov Models
- Gradient Descent

## Statistics
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
	- Python
	- R

## Neural nets
- Basic theory
- Turi for images

## Optimalisation & Simulation
- Mathematical Optimalisation (Operations Research)
    - (Non-)Linear programming
	- Multi-Criteria Decision Making
	- Heuristics
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
	- (Un)typed data structures
- Security basics
	- OWASP top10
- Building a simple (data) webservice 101
	- Servers: Apache & Nginx [Apache vs Nginx: Practical Considerations | DigitalOcean](https://www.digitalocean.com/community/tutorials/apache-vs-nginx-practical-considerations)
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
- How to publish a site on Github Pages
- Data Privacy laws (GDPR)
- Emergent properties of data and what data science can actually bring you
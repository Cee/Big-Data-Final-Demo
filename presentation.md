footer: CS9233 - Programming for Big Data<br/>Tianyu Wang (tw1707), Yida Zhou (yz4499)
slidenumbers: true

# [fit] Business Performance Estimate 
### [fit] How To Start New Businesses Based On Customers' Reviews

---

# Outline 

- Introduction
- Data Source
- Workflow
- Result
- Conclusion & Future Work

---

# Outline 

- **Introduction**
- Data Source
- Workflow
- Result
- Conclusion & Future Work

---

# Why *location* is so important?

- Directly affect the source of actual audience
- Hard to estimate w/o actual practice and testing
- Time and money consuming
- Risky for new openings
- Also, difficult to figure out key attributes strongly affecting the rating

^ Location is an important factor that directly affect the source of actual audience. But it has always been a difficult problem to estimate a certain consumer-facing business’ performance without actual practice and testing. Which, it is both time consuming and risky for business to seek for new openings locations.

---

# What can *big data* do?

- Suggest a potential opening in designated area
- Estimate performance and rating based on the given location
- Find out the most important factors combined with *machine learning*

^ By utilizing big data approach and machine learning, it is possible to estimate a business’ performance based on the given location, population demographic and nearby similar or supporting facilities. For instance, this product will enable corporate businesses finding new potential opening opportunities in designated area. 

---

# Target Audience?

- Startup or individuals, the ones whom have little or no experience, that willing to take less risks 
- Corporate businesses companies, which want to expand their businesses

---

# Outline 

- Introduction
- **Data Source**
- Workflow
- Result
- Conclusion & Future Work

---

# Data Source

- Yelp / FourSquare
	- 200k businesses
	- 5.2m ratings
- Financial statements from related corporate businesses
- data.gov: statistics of U.S. businesses

---

# Outline 

- Introduction
- Data Source
- **Workflow**
- Result
- Conclusion & Future Work

---

# Workflow

<!-- ![](Workflow.jpg) -->

---

![](Workflow.jpg)

---

# Workflow (Cont.)

1. Formatter: convert `.csv`, `.json` and `.html` file into `.csv` 
	- `nodeJS` & `npm`: `json2csv` package
	- Manually collect some useful info from the document
2. Import `.csv` files into `Spark`:
	- Flatten attributes
	- Generate Spark DataFrames

---

# Workflow (Cont.)

<ol start="3"> 
	<li>Data Preprocessing:</li>
	<!-- - Reduce dimensionality: 
		- Feature selection & extraction
		- Principal Component Analysis (PCA) 
		- Avoid overfitting
	- Clean data -->
</ol>

---

# Workflow (Cont.)

3. Data Preprocessing:
	- Export into multiple `.csv` files:
		- Different categories
		- Different cities
		- etc.

---

# Workflow (Cont.)

4. Big Data Analysis:
	- Spark SQL module
	- H<sub>2</sub>O Machine Learning
5. Final Result:
	- Chart
	- Analysis

---

# Outline 

- Introduction
- Data Source
- Workflow
- **Result**
- Conclusion & Future Work

---

# Top 10 Categories For Each State

[Example](./Graph/top-10-categories-Arizona.html)

---

# Top 10 Cities For Chinese Restaurant

---

# Compare Machine Learning Methods

---

# Find the Best Location For Opening

---

# Attributes

---

# Result

Estimate Rating Using Machine Learning Model

---

# Outline 

- Introduction
- Data Source
- Workflow
- Result
- **Conclusion & Future Work**

---

# Conclusion - Estimated Objectives

- For Individuals:
	- New businesses opening suggestions
	- Given category / area
- For Corporate Businesses:
	- Where to expand
	- How to improve ratings

---

# Conclusion - Estimated Objectives

- For Both:
	- Key attributes affecting on ratings

---

# Future Work

- If given more data:
	- Time lapse: trends
	- More city data
- Rating vs. Profit
	- Long-term eyesight

---

# Q&A

---

# Thank you!
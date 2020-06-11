

## What is Data Science?
**Data science** is an inter-disciplinary field that uses scientific methods, computer science, algorithms, and systems to extract knowledge and insights from many structural and unstructured data at small and large scales. 

### The Data Science Process:
![Figure 1: ETL --> Data Analysis --> Data Products](res_bin/media/data_science_process.png)


### ETL (Extract, Transform, Load)
Data rarely starts out in the format, standard, or schema that we need it in.  The first step for a data scientist (after project management) includes researching the correct schemas and data types to answer your question and moving the data into that format

 1.  **Research** previous existing tools and data pipelines that apply to your scale, problem, and available data types
 2.  **Plan** out how your data will flow into your methodology and which software and system req uirements you'll need to accomplish this
 3.  **Execute** iterative data analysis methods
 4.  **Evaluate** the validity of your data sources
 
#### Key concepts: 
 **Scale**:  The level of data aggregation.  An intrinsic, meta-data characteristic of each piece of quantitative  data that tells you about the precision at which your data point was collected. Geographic data could be collected at the neighborhood or country-level scale.
 
 **Data Type**: In computer science, an attribute of virtual information which tells the compiler or database how the programmer intends to use the data.   All data falls into four categories:
 1.  **Nominal Scale**: All the data points which are qualitative in nature falls in this category. These are also referred to as categorical variables. Ex: Marital Status (Single, married, etc.). No arithmetic operation (addition, subtraction, multiplication or division) can be performed on such variables.
2.  **Ordinal Scale**: All the data points from the ordered set falls in this category. Ex: Ratings on a 1–5 scale (5 being highest and 1 being lowest). Here the order of the set is fixed, but no arithmetic operation can be performed such as we know, rating 4 is better than 2, but two 2 ratings cannot be equaled to rating 4.
3.  **Interval Scale**: All the data points which have been taken from some fixed interval set. Ex: Temperature (in centigrade), IQ level. In such variables, addition or subtraction can be performed but division doesn’t make sense. As you can say Mumbai has 10 centigrade more than Bangalore, but you saying that Mumbai is twice hotter than Bangalore is not right, thus ratios don’t make sense here.
4.  **Ratio Scale**: All the data points which are quantitative in nature falls in this category. Ex: Sales of a product, the salary of an employee, etc. Here all the arithmetic operations can be performed and comparison can be made as such that Ram earns twice of what Shyam earns, thus ratios make sense.

Thus, by looking at the data, one can infer what kind of data is available like nominal, ordinal, etc. which eventually helps a data analyst/scientist, while building any analytics model for understanding different variables, doing exploratory data analysis, doing data imputation, and performing one-hot encoding.  

 **Data Validation**:  automated and/or rules-based processes that correct, remove, or flag inaccurate or anomalous information, leaving behind a clean data.   Three strategies include:
	- Reject Known Bad Data (Okay)
	- Sanitize Bad Data (Better)
	- Accept Only Known Valid Data (Best)
#### Watch:

 - Scale in Geographic Analysis by   GeoMindz :
   [https://www.youtube.com/watch?v=z1JHqVhsCB0](https://www.youtube.com/watch?v=z1JHqVhsCB0)
  
  - Scales of Measurement - Nominal, Ordinal, Interval, Ratio (Part 1) - Introductory Statistics
   [https://www.youtube.com/watch?v=KIBZUk39ncI](https://www.youtube.com/watch?v=KIBZUk39ncI)

#### Read:
* **Short**: Beginners guide: Data types and their measurement scale [https://towardsdatascience.com/beginners-guide-data-types-and-their-measurement-scale-194033b86b6d](https://towardsdatascience.com/beginners-guide-data-types-and-their-measurement-scale-194033b86b6d)
* **Short**: [https://www.dnb.com/resources/what-is-data-validation.html](https://www.dnb.com/resources/what-is-data-validation.html)
* **Short**: [https://en.wikipedia.org/wiki/Data_validation](https://en.wikipedia.org/wiki/Data_validation)
* **Long**: Methodology for data validation 1.0 - [https://ec.europa.eu/eurostat/cros/system/files/methodology_for_data_validation_v1.0_rev-2016-06_final.pdf](https://ec.europa.eu/eurostat/cros/system/files/methodology_for_data_validation_v1.0_rev-2016-06_final.pdf)

More:
[https://www.cgisecurity.com/owasp/html/ch10.html](https://www.cgisecurity.com/owasp/html/ch10.html)

### Data Analysis
Next you'll use the [scientific method](https://en.wikipedia.org/wiki/Scientific_method) to visualize descriptive and inductive characteristics of your data and identify algorithms that accurately and reliably predict future data points.  

#### Watch:
* "[What is Data Science Part 1](https://www.youtube.com/watch?v=c27EwKNIanQ)" by by Acadgild 
* "[What is Data Science Part 2](https://www.youtube.com/watch?v=y4ZLfS-Dt9g)" by by Acadgild 

###  Data Products
#### Read:
Designing Data Products :[https://towardsdatascience.com/designing-data-products-b6b93edf3d23](https://towardsdatascience.com/designing-data-products-b6b93edf3d23)


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgzNzQ2Mjg5Ml19
-->
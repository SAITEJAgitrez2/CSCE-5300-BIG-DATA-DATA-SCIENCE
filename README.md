# Agricultural Big Data Processing with Hadoop and Spark

## Overview
This project explores the application of big data processing techniques in agriculture using **Apache Spark** and **Hadoop**. The research focuses on efficiently analyzing agricultural data to improve **crop yield prediction** and compares the performance of both frameworks.

## Abstract
Every day, various agricultural devices collect **environmental data** that influences crop growth. Proper analysis of this data can provide **valuable insights** for better decision-making. This research utilizes **Spark MLlib** to build **linear regression** and **Random Forest regression models** for crop yield prediction. The study compares **Hadoop** and **Spark** in handling large-scale agricultural data.

## Key Findings
- **Apache Spark outperforms Hadoop** in processing large agricultural datasets.
- **Spark's in-memory computation** significantly reduces execution time compared to Hadoop’s disk-based architecture.
- A **multivariate linear regression model** built with **Spark MLlib** provides accurate yield predictions.
- Experimental evaluations confirmed that **Spark is more scalable and efficient** than Hadoop.

## Methodology
1. **Data Collection**: Agricultural data was collected from multiple sources.  
2. **Framework Implementation**:  
   - **Hadoop MapReduce** for distributed computing.  
   - **Apache Spark** using Resilient Distributed Datasets (RDDs).  
3. **Machine Learning Model**:  
   - Built **linear regression** and **Random Forest regression** models for yield prediction using **Spark MLlib**.  
4. **Performance Comparison**:  
   - Evaluated Hadoop vs. Spark in terms of **execution speed, scalability, and accuracy**.  

## Results
| Framework | Processing Speed | Memory Usage | Scalability |
|-----------|----------------|--------------|------------|
| Hadoop    | Slower         | Higher       | Moderate  |
| Spark     | Faster         | Optimized    | High      |

- Spark's **in-memory processing** provided **faster execution times**.
- The yield prediction model produced **more accurate results** using Spark MLlib.

## Conclusion
The study demonstrated that **Apache Spark is a superior choice** for processing large-scale agricultural data compared to Hadoop. Future work will explore **advanced deep learning models** for even better yield prediction accuracy.

## Future Research
- Integrating **deep learning models** for yield prediction.
- Expanding analysis to include **real-time agricultural data streams**.
- Utilizing **additional Spark capabilities** beyond MLlib and SQL.

## References
Y. Cheng, Q. Zhang, and Z. Ye, **"Research on the Application of Agricultural Big Data Processing with Hadoop and Spark,"** 2019 IEEE International Conference on Artificial Intelligence and Computer Applications (ICAICA), Dalian, China, 2019, pp. 274-278.  
DOI: [10.1109/ICAICA.2019.8873519](https://doi.org/10.1109/ICAICA.2019.8873519)

---

**License**: MIT  
This research is conducted under the University of North Texas.  

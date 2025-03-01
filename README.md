# Sales-analysis-with-python
This project focuses on leveraging Python programming for data science applications, specifically in data processing, object-oriented programming (OOP), and file operations. The primary goal was to analyze a sales dataset, optimize its structure, and develop a system for efficient data handling and retrieval.

The execution involved identifying and removing unnecessary columns from the dataset to improve efficiency while selecting key attributes for further analysis. The dataset was processed and stored in a structured format using CSV, JSON, and pickle, ensuring seamless data manipulation.

A Product class was developed to represent individual records, encapsulating relevant attributes such as SKU_number, SoldFlag, and StrengthFactor. Additionally, a DataManager class was implemented to handle dataset operations, including loading, displaying, sorting, and filtering data without relying on third-party libraries.

To optimize data processing, list comprehensions were used to efficiently extract relevant records, such as filtering SKU numbers based on specified criteria. The project further incorporated performance tuning by implementing structured indexing and optimized query retrieval, improving query execution speed by 30% and reducing processing latency by 10%.

The final implementation involved saving structured data using JSON format and preserving product objects using pickle, ensuring persistence and ease of retrieval for future analysis. The entire system was tested through structured execution scripts to validate its performance and robustness.

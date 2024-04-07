# Frequent-Itemset-Detector-AMD
The project goal is to implement a system finding frequent itemsets of skills in the LinkedIn Jobs &
Skills dataset (https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024). 

The detector considers as baskets the sets of skills required for each job announcement and uses the A-Priori algorithm to find all the
k-size frequent itemsets. 
All the code is implemented to promote scalability,
in a Spark-Hadoop enviroment, with the API for Python, PySpark.
The data are loaded in a Resilient Distributed Dataset. 

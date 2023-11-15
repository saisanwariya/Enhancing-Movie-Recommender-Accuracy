### Title
Enhancing Movie Recommender Accuracy - A Comprehensive Study on Hyperparameter Optimization and Genre-Specific Error Analysis in Spark

### Overview
This project by Sai Sanwariya Narayan aims to enhance the accuracy of a movie recommendation system built in Apache Spark. It focuses on optimizing hyperparameters of an ALS (Alternating Least Squares) model and conducting a detailed error analysis by genre. The study includes tasks like computing average prediction error for movies and genres, analyzing the impact of review count on prediction error, and employing Spark DataFrame and RDD transformations for effective data processing.

### Program Functionality
1. **Data Preparation**: Load and preprocess movie and ratings data into Spark DataFrames and RDDs.
2. **Model Building**: Construct an ALS model using the best hyperparameters identified in a previous study.
3. **Model Evaluation**: Use the ALS model to generate predictions, calculate prediction errors, and join RDDs/DataFrames for analysis.
4. **Analysis**: 
   - Compute average prediction error for each movie.
   - Examine the correlation between the number of reviews and prediction error.
   - Analyze prediction errors by movie genres.
   - Use Spark’s `persist()` and `unpersist()` methods for performance optimization.
5. **Output Generation**: Save the analyzed data in a CSV format for further examination and insights.

### Notes
- The project utilizes PySpark, Pandas, NumPy, and related libraries for data handling and analysis.
- A Jupyter Notebook environment is used for development and testing purposes.
- Careful attention is given to error handling and resource management in Spark to ensure efficient performance.
- The results are stored in CSV format for easy access and further research or development.

---

# Academic Integrity Statement

Please note that all work included in this project is the original work of the author, and any external sources or references have been properly cited and credited. It is strictly prohibited to copy, reproduce, or use any part of this work without permission from the author.

If you choose to use any part of this work as a reference or resource, you are responsible for ensuring that you do not plagiarize or violate any academic integrity policies or guidelines. The author of this work cannot be held liable for any legal or academic consequences resulting from the misuse or misappropriation of this work.

Any unauthorized copying or use of this work may result in serious consequences, including but not limited to academic penalties, legal action, and damage to personal and professional reputation. Therefore, please use this work only as a reference and always ensure that you properly cite and attribute any sources or references used.

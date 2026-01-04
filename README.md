Stroke Dataset ETL Processor

This project is a simple ETL (Extract, Transform, Load) application designed to preprocess a stroke prediction dataset. It helps clean, transform, and prepare raw healthcare data into a machine-learning-ready format using an easy-to-use graphical interface.

The application allows the user to upload a CSV file containing stroke-related data. Once uploaded, the system automatically performs data cleaning by removing unnecessary columns, handling missing values, scaling numerical features, and encoding categorical variables. These transformations ensure the dataset is consistent and suitable for further analysis or model training.

The ETL process is implemented using Scikit-learn pipelines and column transformers, which makes the preprocessing steps structured, reusable, and less error-prone. Numerical features are standardized, while categorical features are imputed and one-hot encoded to preserve information without introducing bias.

After processing, the transformed dataset is saved as a new CSV file in the same directory as the original file. A Tkinter-based graphical user interface makes the tool user-friendly and removes the need for manual coding or command-line usage.

This project demonstrates a practical data engineering workflow, combining data preprocessing, pipeline-based transformations, and basic desktop application development. It is useful for preparing healthcare datasets for machine learning tasks such as stroke prediction.

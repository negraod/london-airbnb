# london-airbnb
Data Science personal project, using Kaggle's dataset: London Sep2022 Airbnb.  
This project started with an EDA and now it has a Machine Learning module too.

Dataset was acquired from Kaggle (link below):  
https://www.kaggle.com/datasets/mrnabiz/detailed-airbnb-listing-data-london-sep-2022  
This public dataset is part of Airbnb and can be accessed at the original source link: http://insideairbnb.com/

This dataset contains information about Airbnb properties in the London region as of September 2022. As a snapshot in time, it does not provide information on price variations over months. The dataset includes details such as nightly prices, locations, host information, reviews, property types (private or shared), amenities, and more.

<br>

## Project Structure:
### Exploratory Data Analysis
* **EDA - LondonAirbnb.ipynb**  
  Comprehensive exploratory data analysis including:
    * Addressing 8 business questions with detailed answers.
    * Visualizing the dataset for intuitive insights.
    * Detecting and analyzing outliers.
    * Creating new features to enhance analysis.
### Machine Learning
* **ML01_Baseline.ipynb**  
  Establishing a framework for model evaluation and baseline reference, including the creation of tools:
    * A versatile feature engineering transformer enabling testing of various configurations within scikit-learn's pipeline.
    * Automatic column type detection, facilitating integration with the feature engineering transformer by accommodating dynamically created columns.






<br><br><br>  
<sup>**Note**:
This project is primarily intended for learning purposes. Initially, the EDA phase encompassed the entire dataset because there was no plan for a subsequent machine learning component. As per best practices, EDA should ideally be conducted exclusively on the training dataset to ensure model validity and reliability for production deployment. Conducting EDA on the entire dataset may lead to evaluation metrics that overestimate the model's generalization to new, unseen data. Despite this initial approach, the project continues with awareness of these implications, prioritizing learning and understanding.
</sup>

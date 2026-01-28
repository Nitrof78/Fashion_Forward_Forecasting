# Fashion Forward Forecasting
Through this project we aim at developping a machine learning algorithm able to predict if a comment posted by a customer after buying clothe is a positive one or not.
To do so, we'll use a database of over 18000 reviews, containing the following information :
- Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.  
- Age: Positive Integer variable of the reviewers age.  
- Title: String variable for the title of the review.  
- Review Text: String variable for the review body.  
- Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.  
- Division Name: Categorical name of the product high level division.  
- Department Name: Categorical name of the product department name.  
- Class Name: Categorical name of the product class name.  
- Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.  

## Files available
`reviews.csv` : CSV file containing reviews with associated features  
`Pipeline_Project.ipynb` : code for the project in a Jupyter Notebook  
`README.md` : Instructions to consult before starting project
  
## Installation
Please clone the GitHub repository before using it and feel free to do any improvment once done.  
```
$ git clone https://github.com/Nitrof78/Fashion_Forward_Forecasting  
$ cd Fashion_Forward_Forecasting
```  
Be also sure to have SpaCy installed or do it manually if necessary
```
pip install spacy
python -m spacy download en_core_web_sm
```

## Necessary libraries
For this project, we'll use the following libraries, first step of the project consists in importing them :  
- Pandas - Python Data Analysis Library   
- Matplotlib - Visualization with Python  
- NumPy - Scientific computing with Python  
- Scikit-learn - machine learning in Python  
- SpaCy - Natural Language Processing in Python    

## Usage Guidelines
### Project structure
Project is deployed in a Jupyter Notebook. Steps have to be applied in chronological order.  
Datasource is a `CSV` file stored in the repository and named `reviews.csv`. 

## Current results
In its present configuration, the anlysis shows an accuracy of the model close to 89%. We chose to use a Random Forest Classifier for our model. Other models might have better results, feel free to test. In order to limit the updating time (already around 30 minutes), we chose to fine-tune on only 2 different parameters. With a better computer power and time available, fine tuning process should probably lead to better results.

## License Type
Project in itself is a public work, designed to practice on World Bank Databank Website, feel free to clone it and improve it as you wish.

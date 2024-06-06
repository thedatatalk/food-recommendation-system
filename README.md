# food-recommendation-system
Developing a food recommendation system using the Amazon Fine Food review dataset, incorporating both popularity-based and collaborative recommendation methods.

# Requirements
Python 3.8+ Jupyter Notebook - Kaggle Notebook is preferrable.

# Dataset
Amazon fine food review Dataset : https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

# How to Run The Notebook.
1. Login to Kaggle.com
2. Visit https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
3. Click on "New Notebook" Option Available on the top of the screen.
4. Download the ".ipynb" File attached in the current repository, select the right version
5. Upload On the New Notebook place by clicking on Import Notebook option.
6. Run The Notebook program

# Run the program in virtual envrionment python
1. Create virtual environment
2. Activate virtual environment
3. Install requirements.txt 
4. Run jupyter notebook and Open the .ipynb notebook file on the localhost:8888

# Key Data Insights

1. Build the recommendation based on popularity of food.

2. Using the scipys csr_matrix build the sparse matrix, basically it stores the explicit indices and values at those indices. So for example, since row=0 and col=0 corresponds to 1 (the first entries of all three arrays in your example). Hence, the [0,0] entry of the matrix is 1.

3. Then build the collaborative system.Model-based Collaborative Filtering is a personalised recommender system, the recommendations are based on the past behavior of the user and it is not dependent on any additional information.The Popularity-based recommender system is non-personalised and the recommendations are based on frequecy counts, which may be not suitable to the user

4. In popularity based model we saw that for userid 44 and 46 it has recommended the same set of 5 products for both  but Collaborative Filtering based model has recommended entire different list based on the user past purchase history.

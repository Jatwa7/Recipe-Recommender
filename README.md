# Recipe-Recommender
The Recipe Recommender is a Python application that suggests recipes based on user-inputted ingredients. It utilizes TF-IDF (Term Frequency-Inverse Document Frequency) to assign weights to each word in the ingredients list and calculates the cosine similarity using the linear_kernel function from scikit-learn to determine the similarity between user-inputted ingredients and the ingredients of available recipes.

<h2>TF-IDF (Term Frequency-Inverse Document Frequency)</h2>
TF-IDF is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents. In the context of the Recipe Recommender, TF-IDF is applied to the list of ingredients. Here's how it works:

<ul>Term Frequency (TF): Measures the frequency of a word in a document. In this case, it calculates how often each ingredient appears in a recipe.</ul>
<ul>Inverse Document Frequency (IDF): Measures the importance of a word by considering how many documents contain that word. Rare ingredients that appear in fewer recipes are given higher IDF scores, indicating their importance.</ul>
<ul>TF-IDF Weighting: Combines TF and IDF to assign weights to each word (ingredient) in the ingredients list. This weighting scheme allows the recommender to prioritize ingredients that are both frequent within a recipe and rare across recipes, thus capturing their significance in recipe recommendations.</ul>
<h2>Credits</h2>
scikit-learn: Used for calculating cosine similarity.
NumPy: Dependency for array manipulation.
Pandas: Used for data manipulation.
Python: Programming language used for development.

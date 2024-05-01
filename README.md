<h1>Recipe Recommender</h1>

<h2>Description</h2>
<p>The Recipe Recommender is a Python application that suggests recipes based on user-inputted ingredients. It utilizes TF-IDF (Term Frequency-Inverse Document Frequency) to assign weights to each word in the ingredients list and calculates the cosine similarity using the linear_kernel function from scikit-learn to determine the similarity between user-inputted ingredients and the ingredients of available recipes.</p>

<h3>TF-IDF (Term Frequency-Inverse Document Frequency)</h3>
<p>TF-IDF is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents. In the context of the Recipe Recommender, TF-IDF is applied to the list of ingredients. Here's how it works:
<ul>
<li><strong>Term Frequency (TF)</strong>: Measures the frequency of a word in a document. In this case, it calculates how often each ingredient appears in a recipe.</li>
<li><strong>Inverse Document Frequency (IDF)</strong>: Measures the importance of a word by considering how many documents contain that word. Rare ingredients that appear in fewer recipes are given higher IDF scores, indicating their importance.</li>
<li><strong>TF-IDF Weighting</strong>: Combines TF and IDF to assign weights to each word (ingredient) in the ingredients list. This weighting scheme allows the recommender to prioritize ingredients that are both frequent within a recipe and rare across recipes, thus capturing their significance in recipe recommendations.</li>
</ul></p>

<h2>Features</h2>
<ul>
<li><strong>Ingredient-Based Recommendation</strong>: Recommends recipes based on user-inputted ingredients.</li>
<li><strong>TF-IDF Weighting</strong>: Utilizes TF-IDF to assign weights to ingredients.</li>
<li><strong>Cosine Similarity</strong>: Calculates cosine similarity to determine the similarity between user-inputted ingredients and available recipes.</li>
</ul>



<h2>Credits</h2>
<ul>
<li><a href="https://scikit-learn.org/">scikit-learn</a>: Used for calculating cosine similarity and TF-IDF.</li>
<li><a href="https://pandas.pydata.org/">Pandas</a>: Used for data manipulation.</li>
<li><a href="https://www.python.org/">Python</a>: Programming language used for development.</li>
</ul>

<h2>Acknowledgements</h2>
<p>Special thanks to <a href="https://scikit-learn.org/">scikit-learn</a> for providing the tools necessary for cosine similarity calculation and TF-IDF implementation.</p>


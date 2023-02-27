<h1>Product Recommendation System</h1>

I have implemented a recommendation system based on Matrix Factorization using LightFM's library. It allow's to build a hybrid recommendation system based on user and/or item embeddings (meta features). This also improves upon the traditional ALS (Alternating Least Squares) method by using a much efficient WARP / BPR loss and optimization method.

To start, Please install pipenv / virtualenv and create a virtual environment and activate it.

if using pipenv,
<code> pipenv install --python=3.9
<code> pipenv shell

Otherwise,
<code> pip install -r requirements.txt

All the code for recommendation system is in `Recommendation System.ipynb` file.
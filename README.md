

🎬 Movie Recommendation System (MovieLens 100K)

Dataset Url:https://grouplens.org/datasets/movielens/100k/

This project builds a Movie Recommendation System using the MovieLens 100K dataset.
It explores multiple machine learning techniques including:

* ✅ User-Based Collaborative Filtering (KNN)
* ✅ Linear Regression
* ✅ Neural Networks
* ✅ KNN Regression
* ✅ Data Visualization & Correlation Analysis

⸻

📂 Dataset

We use the MovieLens 100K dataset from GroupLens:

* 100,000 ratings
* 943 users
* 1682 movies

Files used:

* u.data → Ratings data
* u.user → User demographics
* u.item → Movie details & genres

⸻

⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

⸻

📊 Data Preprocessing

* Loaded datasets from URLs
* Merged:
    * User data
    * Movie data
    * Ratings data
* Cleaned and renamed genre columns
* Removed unnecessary columns (e.g., timestamp)

⸻

🤖 Models Implemented

1. KNN Recommender System (Collaborative Filtering)

* Created user-item matrix
* Used cosine similarity
* Found similar users
* Recommended movies based on neighbors

📌 Example Recommendations:

* Star Wars (1977)
* Pulp Fiction (1994)
* Fargo (1996)
* The Usual Suspects (1995)

⸻

2. Linear Regression

* Used genre features to predict ratings
* Tested with:
    * 3 features
    * 5 features
    * 10 features

📉 RMSE Results:

* 3 Features → 1.1176
* 5 Features → 1.1164
* 10 Features → 1.1139

⸻

3. Neural Network (MLP Regressor)

* Architecture: (64, 32)
* Standardized input features

📉 RMSE Results:

* 3 Features → 1.1172
* 5 Features → 1.1096
* 10 Features → 1.0987 (Best)

⸻

4. KNN Regression

* Used Euclidean distance
* Compared different feature sizes

📉 RMSE Results:

* 3 Features → 1.2277
* 5 Features → 1.2061
* 10 Features → 1.1629

⸻

📈 Evaluation Metric

We used:

RMSE (Root Mean Squared Error)

* Lower RMSE → Better performance

⸻

📊 Visualizations

* 📌 RMSE Comparison Graph
* 📌 Actual vs Predicted Ratings
* 📌 Error Distribution
* 📌 K vs RMSE Plot
* 📌 Correlation Heatmaps (3, 5, 10 features)

⸻

🔍 Key Insights

* Neural Networks performed best among all models
* Increasing number of features improved performance
* KNN Collaborative Filtering gives meaningful recommendations
* Genre features alone have limited predictive power

⸻

🚀 How to Run

# Clone repository
git clone https://github.com/your-username/movie-recommender.git
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn
# Run notebook / script
python main.py

Or open in Google Colab and run all cells.

⸻

📌 Future Improvements

* Add Content-Based Filtering
* Hybrid Recommendation System
* Use Deep Learning (Autoencoders)
* Deploy as Web App (React + Flask)

⸻

🙌 Acknowledgements

* GroupLens Research for the dataset
* Scikit-learn library


<!---LeetCode Topics Start-->
# LeetCode Topics
## Array
|  |
| ------- |
| [0001-two-sum](https://github.com/Akhilkumar-28/MLMODELS/tree/master/0001-two-sum) |
## Hash Table
|  |
| ------- |
| [0001-two-sum](https://github.com/Akhilkumar-28/MLMODELS/tree/master/0001-two-sum) |
<!---LeetCode Topics End-->
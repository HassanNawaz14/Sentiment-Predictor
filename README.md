<h1 align="center">🎭 Sentiment Analysis Project</h1>

<p align="center">
  <em>A machine learning pipeline for sentiment classification with TF-IDF and handcrafted features</em>
</p>

<hr/>

<h2>📌 Overview</h2>
<p>
This project demonstrates a complete <strong>sentiment analysis pipeline</strong> built in Python.  
It covers preprocessing, feature engineering, model training, evaluation, and prediction.  
The models are trained on textual reviews using a combination of <strong>TF-IDF features</strong> and 
simple <strong>handcrafted linguistic features</strong> (e.g., length, punctuation, sentiment lexicons).
</p>

<hr/>

<h2>📂 Project Structure</h2>

<pre>
Sentiment-Project/
│
├── data/                  # (not included) Place datasets here
│   ├── raw/               # Raw source data
│   └── processed/         # Processed CSVs used in notebooks
│
├── models/                # Saved vectorizer & trained models (.pkl)
│
├── notebooks/             # Jupyter notebooks
│   ├── 01_EDA.ipynb
│   ├── 02-Preprocessing.ipynb
│   ├── 03-Modeling.ipynb
│   └── Sentiment Predictor.ipynb
│
├── images/                # Sample Images 
│   └── sample Images
│
├── .gitignore             # Ignored files (data, virtualenv, etc.)
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
</pre>

<hr/>

<h2>⚙️ Features</h2>
<ul>
  <li>Data cleaning & preprocessing</li>
  <li>TF-IDF vectorization (10k vocab size)</li>
  <li>Custom handcrafted features:
    <ul>
      <li>Review length</li>
      <li>Exclamation mark count</li>
      <li>Positive/negative word lexicons</li>
    </ul>
  </li>
  <li>Model training with:
    <ul>
      <li>Logistic Regression</li>
      <li>Multinomial Naive Bayes</li>
      <li>Linear SVM</li>
    </ul>
  </li>
  <li>Confusion matrix visualization</li>
  <li>Reusable <code>Sentiment Predictor</code> function for quick demos</li>
</ul>

<hr/>

<h2>🚀 Quick Start</h2>

<ol>
  <li><strong>Clone the repository:</strong>
    <pre><code>git clone https://github.com/your-username/Sentiment-Project.git
cd Sentiment-Project</code></pre>
  </li>

  <li><strong>Create and activate a virtual environment:</strong>
    <pre><code>python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate</code></pre>
  </li>

  <li><strong>Install dependencies:</strong>
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>

  <li><strong>Download dataset:</strong>  
    This repo does not include data.  
    Please download the <a href="https://www.kaggle.com/datasets/iarunava/imdb-movie-reviews-dataset">IMDB Movie Reviews Dataset</a> (or your dataset of choice)  
    and place it inside <code>data/raw/</code>.
  </li>

  <li><strong>Run notebooks:</strong>
    <pre><code>jupyter notebook</code></pre>
  </li>
</ol>

<hr/>

<h2>📊 Example Predictions</h2>

<pre>
"I love this movie!"        → Positive
"I'll wtach this again for sure."        → Negative
"Worst movie ever!."           → Negative
"Movie was just okay."      → Neutral/Negative
</pre>

<hr/>

<h2>🛠 Tech Stack</h2>
<ul>
  <li>Python 3.9+</li>
  <li>Pandas, NumPy</li>
  <li>scikit-learn</li>
  <li>Matplotlib, Seaborn</li>
  <li>Jupyter Notebook</li>
</ul>

<hr/>

<h2>📜 License</h2>
<p>
This project is licensed under the <a href="LICENSE">MIT License</a>.
</p>

<hr/>

<h2>🤝 Contributing</h2>
<p>
Contributions, issues, and feature requests are welcome!  
Feel free to check the <a href="https://github.com/your-username/Sentiment-Project/issues">issues page</a>.
</p>

<hr/>

<h2>🌟 Acknowledgements</h2>
<ul>
  <li><a href="https://scikit-learn.org/">Scikit-learn</a></li>
  <li><a href="https://pandas.pydata.org/">Pandas</a></li>
  <li><a href="https://www.kaggle.com/">Kaggle</a></li>
</ul>


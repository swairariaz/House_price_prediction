<div align="center">
  <h1>🏠 Advanced House Price Prediction</h1>
  <p><strong>XGBoost-powered real estate valuation system with 91% accuracy</strong></p>
  
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/ML-XGBoost-FF6F00?logo=xgboost" alt="XGBoost">
  <img src="https://img.shields.io/badge/Optimization-Optuna-394EFF" alt="Optuna">
  <img src="https://img.shields.io/badge/Deployment-Gradio-FF4A4A" alt="Gradio">
</div>

<h2>🔧 Technical Stack</h2>
<ul>
  <li><strong>Core ML:</strong> XGBoost Regressor (Optuna-tuned hyperparameters)</li>
  <li><strong>Feature Engineering:</strong> 80+ dimensions including:
    <ul>
      <li>Structural: Square footage, room counts, quality ratings</li>
      <li>Temporal: Year built/remodeled</li>
      <li>Geospatial: Neighborhood zoning</li>
    </ul>
  </li>
  <li><strong>Key Libraries:</strong>
    <code>xgboost==1.7.5</code>, 
    <code>optuna==3.2.0</code>, 
    <code>scikit-learn==1.2.2</code>,
    <code>pandas==2.0.3</code>
  </li>
</ul>

<h2>📊 Performance Metrics</h2>
<table>
  <tr>
    <th>Metric</th>
    <th>Score</th>
  </tr>
  <tr>
    <td>RMSE</td>
    <td>$24,907</td>
  </tr>
  <tr>
    <td>R²</td>
    <td>0.91</td>
  </tr>
  <tr>
    <td>Training Time</td>
    <td>2.8 mins (M1 Pro)</td>
  </tr>
</table>

<h2>🚀 Deployment</h2>
<pre><code class="language-bash"># Launch prediction interface
pip install gradio==3.36.1
</pre>

<h2>📂 Repository Structure</h2>
<pre>
house-price-prediction/
├── data/                   # Raw datasets
│   ├── train.csv           # 1460 training samples
│   └── test.csv            # 1459 test samples
├── main.ipynb              # Complete analysis notebook
└── requirements.txt        # Dependency specifications
</pre>

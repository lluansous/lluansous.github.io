---
layout: page
permalink: /publications/index.html
title: Publications
---

![](/images/Outliers.png)

## Conference Papers

<div class="publication">
  <h3>Zero-adjusted Inverse Gamma Regression Model</h3>
  <div class="authors">Luan Sousa, Manoel Santos Neto~</div>
  <div class="venue">25º SINAPE - Simpósio Nacional de Probabilidade e Estatística, Fortaleza, Brazil (August 2024)</div>
  <div class="summary">
    <p>The analysis of data containing zero observations presents challenges in econometrics, biological sciences, and actuarial studies, where variables of interest often assume null values in significant portions of the dataset. This phenomenon is common in insurance claim frequency studies (where some clients report no claims) or ecological surveys (where species may be absent from samples). Traditional regression models like gamma regression fail to accommodate this zero-inflation characteristic.</p>
    <p>Zero-adjusted regression models (zero-inflated or hurdle models) address this by separately modeling the probability of zero vs. positive observations. While Vitorino (2024) recently proposed a zero-adjusted inverse gamma distribution for descriptive analysis, it lacked regression capabilities. Our work extends this into a full regression framework, allowing covariate analysis for both the binary (zero vs. positive) and continuous (positive values) components. This provides researchers with a more flexible tool for zero-inflated positive continuous data with heavy-tailed characteristics.</p>
    <a href="/mypaper/poster/Artigo_ZAIGA.pdf" class="pdf-button">View Full Paper</a>
  </div>
</div>

<div class="publication">
  <h3>Zero-adjusted Inverse Gamma Regression Model</h3>
  <div class="authors">Luan Sousa, Manoel Santos Neto~</div>
  <div class="venue">XLIII Encontro de Iniciação Científica - UFC, Fortaleza, Brazil (August 2024)</div>
  <div class="summary">
    <p>Extended version presented at the undergraduate research symposium, featuring additional simulation studies comparing our model's performance with Tweedie and zero-inflated gamma alternatives under varying zero-inflation scenarios (10%-90% zeros).</p>
    <a href="/mypaper/poster/Poster_n2.pdf" class="pdf-button">View Extended Version</a>
  </div>
</div>

## Thesis

<div class="publication">
  <h3>Predictive Modeling of League of Legends Matches Using Supervised Learning</h3>
  <div class="authors">Luan Sousa (Advisor: Manoel Santos Neto)</div>
  <div class="venue">Undergraduate Thesis, Federal University of Ceará (March 2025) - <strong>Maximum grade</strong></div>
  <div class="summary">
    <p>This study applies supervised learning models to predict match outcomes in <em>League of Legends</em>, one of the world's most popular esports. We evaluated K-Nearest Neighbors (KNN), Logistic Regression, Gradient Boosting, and Decision Trees using data from Oracle's Elixir (10,784 competitive matches from 2022-2023 seasons).</p>
    <p>Methodology involved: (1) strategic feature engineering (early-game gold differentials, champion pick synergies), (2) elimination of non-predictive metadata, and (3) validation via AUC-ROC and accuracy metrics. Key findings:</p>
    <ul>
      <li>Logistic Regression and KNN achieved peak performance (AUC=0.930, accuracy=87.2%)</li>
      <li>First 8-minute game state metrics were 3.4× more predictive than late-game features</li>
      <li>Champion selection contributed 62% of model predictive power</li>
    </ul>
    <p>The framework demonstrates how machine learning can quantify strategic decision-making in competitive gaming.</p>
    <a href="/mypaper/thesis/LuanSousa_Thesis.pdf" class="pdf-button">View Thesis</a>
  </div>
</div>

<style>
  .publication {
    margin-bottom: 2.5rem;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid #eee;
  }
  .authors {
    color: #555;
    font-size: 0.95rem;
    margin: 0.3rem 0;
  }
  .venue {
    color: #666;
    font-size: 0.9rem;
    font-style: italic;
    margin-bottom: 0.8rem;
  }
  .summary {
    background: #f9f9f9;
    padding: 1.2rem 1.5rem;
    border-radius: 8px;
    font-size: 0.95rem;
    line-height: 1.6;
  }
  .summary p, .summary ul {
    margin: 0.6rem 0;
  }
  .summary ul {
    padding-left: 1.2rem;
  }
  strong {
    color: #2c3e50;
  }
  .pdf-button {
    display: inline-block;
    background: ##b2c1cf;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    font-size: 0.9rem;
    margin-top: 0.5rem;
    text-decoration: none;
    transition: background 0.2s ease;
  }
  .pdf-button:hover {
    background: #2c3e50;
  }
</style>

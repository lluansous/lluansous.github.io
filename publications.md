---
layout: page
permalink: /publications/index.html
title: Publications
---

![](/images/Outliers.png)

##  Conference Papers

<div class="publication">
  <h3><a href="/mypaper/poster/Artigo_ZAIGA.pdf" class="pdf-link">Zero-adjusted Inverse Gamma Regression Model</a></h3>
  <div class="authors">Luan Sousa, Manoel Santos Neto~</div>
  <div class="venue">25º SINAPE - Brazilian Symposium on Probability and Statistics, Fortaleza (August 2024)</div>
  <div class="summary">
    <p>Analysis of zero-inflated data presents challenges in econometrics, biological sciences, and insurance. Traditional regression models like gamma regression cannot directly handle datasets with both positive values and exact zeros.</p>
    
    <p>This work proposes a regression extension of Vitorino's (2024) zero-adjusted inverse gamma distribution, which originally lacked regression capabilities. Our model separately handles:</p>
    <ul>
      <li>The probability of zero occurrence (logit link)</li>
      <li>The distribution of positive values (inverse gamma with log link)</li>
    </ul>
    <a href="/mypaper/poster/Artigo_ZAIGA.pdf" class="pdf-button">View Full Paper (PDF)</a>
  </div>
</div>

<div class="publication">
  <h3><a href="/mypaper/poster/Poster_n2.pdf" class="pdf-link">Zero-adjusted Inverse Gamma Regression Model: Applications</a></h3>
  <div class="authors">Luan Sousa, Manoel Santos Neto~</div>
  <div class="venue">XLIII Undergraduate Research Symposium - UFC, Fortaleza (August 2024)</div>
  <div class="summary">
    <p>Extended analysis of zero-inflated data in actuarial science and ecology, featuring:</p>
    <ul>
      <li>Case study 1: Auto insurance claims (32% zeros) showing 18% better fit than Tweedie models</li>
      <li>Case study 2: Species abundance data with 41% zeros in ecological surveys</li>
      <li>Simulation study comparing performance under 10%-90% zero inflation</li>
    </ul>
    <p>The regression framework allows analyzing covariate effects on both the zero-generating process and positive outcomes, providing more interpretable results than existing zero-inflated models.</p>
    <a href="/mypaper/poster/Poster_n2.pdf" class="pdf-button">View Extended Version (PDF)</a>
  </div>
</div>

##  Thesis

<div class="publication">
  <h3><a href="/mypaper/thesis/LuanSousa_Thesis.pdf" class="pdf-link">Predictive Modeling of League of Legends Matches Using Supervised Learning</a></h3>
  <div class="authors">Luan Sousa (Advisor: Manoel Santos Neto)</div>
  <div class="venue">Undergraduate Thesis, Federal University of Ceará (March 2025) - <strong>Maximum grade</strong></div>
  <div class="summary">
    <p>This study applies machine learning to predict outcomes in <em>League of Legends</em> matches using:</p>
    <ul>
      <li>Dataset: 10,784 professional matches (Oracle's Elixir)</li>
      <li>Key features: Early-game gold differentials, champion synergies</li>
      <li>Best model: Logistic Regression (AUC=0.930, accuracy=87.2%)</li>
    </ul>
    <p>The framework demonstrates how strategic decisions in esports can be quantified through supervised learning.</p>
    <a href="/mypaper/thesis/LuanSousa_Thesis.pdf" class="pdf-button">View Thesis (PDF)</a>
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
    background: #2c3e50;
    color: white;
    padding: 0.4rem 0.8rem;
    border-radius: 4px;
    font-size: 0.85rem;
    margin-top: 0.5rem;
    text-decoration: none;
  }
  .pdf-button:hover {
    background: #1a252f;
  }
  h3 a.pdf-link {
    color: #2c3e50;
    text-decoration: none;
  }
  h3 a.pdf-link:hover {
    text-decoration: underline;
  }
</style>

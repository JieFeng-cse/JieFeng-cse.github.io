---
title: "Bridging Transient and Steady-State Performnace in Voltage Control"
permalink: /BTS/
author_profile: false
---
<html>
  <head>
    <meta charset="utf-8">
    <title>Bridging Transient and Steady-State Performance in Voltage Control: A Reinforcement Learning Approach with Safe Gradient Flow</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
      }
      header {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 20px;
      }
      h1 {
        margin: 0;
        font-size: 36px;
      }
      h2 {
        font-size: 24px;
        margin-top: 30px;
      }
      p, ol {
        font-size: 18px;
        line-height: 1.5;
      }
      figure {
        margin-top: 30px;
        text-align: center;
      }
      img {
        max-width: 100%;
      }
      figcaption {
        font-size: 16px;
        margin-top: 10px;
        text-align: center;
      }
      footer {
        background-color: #eee;
        padding: 20px;
        text-align: center;
        font-size: 16px;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Bridging Transient and Steady-State Performance in Voltage Control: A Reinforcement Learning Approach with Safe Gradient Flow</h1>
      <p>Authors: Jie Feng, Wenqi Cui, Jorge Cortes, Yuanyuan Shi</p>
    </header>
    <div class="content">
      <h2>Abstract</h2>
      <p>Deep reinforcement learning approaches are becoming appealing for the design of nonlinear controllers for voltage control problems, but the lack of stability guarantees hinders their deployment in real-world scenarios. This paper constructs a decentralized RL-based controller featuring two components: a transient control policy and a steady-state performance optimizer. The transient policy is parameterized as a neural network, and the steady-state optimizer represents the gradient of the long-term operating cost function. The two parts are synthesized through a safe gradient flow framework, which prevents the violation of reactive power capacity constraints. We prove that if the output of the transient controller is bounded and monotonically decreasing with respect to its input, then the closed-loop system is asymptotically stable and converges to the optimal steady-state solution. We demonstrate the effectiveness of our method by conducting experiments with IEEE 13-bus and 123-bus distribution system test feeders.</p>
      <h2>Introduction</h2>
      <p>Introduction Text</p>
      <figure>
        <img src="/images/transient+steady.png" alt="Figure 1">
        <figcaption>Figure 2: Description of the figure.</figcaption>
      </figure>
      <h2>Related Work</h2>
      <p>Related Work Text</p>
      <h2>Methods</h2>
      <p>Methods Text</p>
      <h2>Results</h2>
      <p>Results Text</p>
      <h2>Conclusion</h2>
      <p>Conclusion Text</p>
      <h2>References</h2>
      <footer>
        <p>Contact: <a href="mailto:jif005@ucsd.edu">jif005@ucsd.edu</a></p>
      </footer>
    </div>
  </body>
</html>





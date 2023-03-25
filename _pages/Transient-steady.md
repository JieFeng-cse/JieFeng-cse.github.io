---
# title: "Bridging Transient and Steady-State Performnace in Voltage Control"
permalink: /Transient-Steady/
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
      Voltage Safety is one of the primary concerns of power system operation, which requires the voltage magnitude to stay in an acceptable range under all working conditions. In recent years, we witnessed the proliferation of distributed energy resources (DERs) such as roof-top solar and electric vehicles, those DERs have led to rapid and unpredictable fluctuations in the load and generation profiles of the grid, and thus placing challenges in voltage control.

      We are aiming to use reinforcement learning for future power system control. The current RL method can do a good job with the transient performance, as RL can optimize the trajectory cost for a finite horizon. However, no optimality guarantee is offered for the steady state, which is critical because the system will stay at the steady states for a long time. The following diagram illustrates the transient state and steady state for voltage control problem. 
      <figure>
        <img src="/images/transient+steady.png" alt="Figure 1">
        <figcaption>Figure 2: Description of the figure.</figcaption>
      </figure>
      <p>Related Work Text</p>
      <h2>Methods</h2>
      <p>Methods Text</p>
      <h2>Results</h2>
      <p>Results Text</p>
      <h2>Conclusion</h2>
      <p>Conclusion Text</p>
      <h2>References</h2>
      Paper is available at ArXiv.
      <a href="https://arxiv.org/abs/2303.11417">Bridging Transient and Steady-State Performance in Voltage Control: A Reinforcement Learning Approach with Safe Gradient Flow</a>
      <footer>
        <p>Contact: <a href="mailto:jif005@ucsd.edu">jif005@ucsd.edu</a></p>
      </footer>
    </div>
  </body>
</html>





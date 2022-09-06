---
title: Developing ANN Surrogate Models to Replace High-fidelity Pressure Swing Adsorption Process Simulations 
date: 2022-07-25
draft: false
featured: True
image:
  filename: featured
  focal_point: center
  preview_only: false
authors: ["conor-cleeton"]
---
Pressure Swing Adsorption (PSA) processes are used extensively for many important gas separations. One of the advantages of PSA is routed in it's cyclic nature: one can configure a variety of 'cycles' with different sequences and steps to achieve the best separation performance using a given adsorbent material. Designing such cycles, however, can be rather complex due to the combined heat- and mass-transfer fronts that arise within the adsorption columns. As such, numerical simulation and optimisation are used extensively to search for the optimal process configuration and operating conditions. For a single operating condition, it is entirely possible that hundreds of cycles need to be simulated in order to reach the cyclic steady state. This means that optimising the process performance for large databases of adsorbents - which requires thousands of process evaluations per material - becomes computationally intractable. As the separation potential of an adsorbent can only be accurately assessed using detailed process simulation and optimisation, there is a substantial need to expedite these simulations for high-throughput applications. Recent efforts have turned towards machine learning. In one approach, an artificial neural network (ANN) model can be trained to predict the key performance indicators of a PSA process using the operating conditions and features of the adsorbent as the inputs. In this way, one can potentially predict the performance of any arbitrary adsorbent at a fraction of the computational cost (from thousands of CPU hours to a few CPU minutes). In our work, we leverage this idea to predict the performance of thousands of metal-organic frameworks with the objective of understanding uncertainties in multiscale high-throughput screening workflows, exploring adsorbent structure-property-process relationships, and much more! 
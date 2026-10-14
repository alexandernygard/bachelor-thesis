# Improving the Accuracy of Federated Learning Simulations

**Using Traces from Real-world Deployments to Enhance the Realism of Simulation Environments**

Alexander Nygård · Bachelor of Computer Science and Engineering, Delft University of Technology · June 23, 2024

[Read the paper (PDF)](bachelor-thesis.pdf)

## Abstract

Federated learning (FL) is a machine learning paradigm where private datasets are distributed among decentralized client devices and model updates are communicated and aggregated to train a shared global model. While providing privacy and scalability benefits, FL systems also face challenges such as client and data heterogeneity, where the training resources and different datasets are non-Independent and Identically Distributed (non-IID). When testing novel FL algorithms or configurations, simulators are used to create controlled environments without needing costly deployments. However, it is important to understand how representative FL simulators are of real-world deployments, and what steps can be taken to bridge the gap between theoretical results and practical implementations. In this paper, we investigate the effects of incorporating traces from a pseudo-real heterogeneous FL deployment in simulated environments. We compare four non-IID attributes, including batch sizes, local epochs, data volume, and data labels, to determine the most influential factors for reproducing the deployment results in simulations. We show that there is an inherent difference between deployments and simulations, despite incorporating identical non-IID conditions. Furthermore, we show that including non-IID data labels in simulations has the most significant impact on recreating the deployment outcome. We also demonstrate that incorporating the other mentioned factors has negligible impact, resulting in similar training performance compared to fully IID simulations. Our results are derived from a 20-client single-server synchronous FL configuration, and additional research is necessary to confirm our findings for larger-scale systems.

# Heart-Disease-Prediction-using-DNN

I have employed Federated learning for my Self-project titled "Heart Disease Prediction". It is a different approache to training machine learning models as compared to Centralized learning. Federated learning involves training models across multiple decentralized devices without exchanging raw data samples

A few reasons why federated learning gives lesser accuracy compared to centralized learning: **Data Heterogeneity**, **Limited Communication**, **Limited Computational Resources**, **Differential Privacy(1)** & **Model Aggregation Challenges(2)**.

**(1)**'Differential Privacy' is a technique to ensure privacy protection for individual data contributors. These privacy-preserving mechanisms can introduce noise or randomness into the training process, which may degrade the accuracy of the resulting model compared to centralized learning.
**(2)**Federated learning requires aggregating model updates from multiple devices to produce a global model. This aggregation process introduces additional complexities, such as dealing with communication delays, network failures, and synchronization issues, which can impact the final model's accuracy.

Despite these challenges, I would prefer federated learning because it addresses the issues of data privacy and security in centralized learning. By keeping data localized and minimizing data movement, federated learning can help address privacy regulations and mitigate risks associated with centralized data storage. 
Additionally, federated learning enables collaborative model training across distributed devices, allowing for broader data representation and potentially better generalization to diverse user populations.

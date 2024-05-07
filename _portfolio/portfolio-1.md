<!-- ---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---

This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->

---
title: "Efficient LLM Project"
excerpt: "Exploring advanced tuning methods for enhancing performance in NLI tasks.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

## Efficient LLM Project

This project investigates the integration of context distillation with parameter-efficient tuning methods like LoRA, QLoRA, and traditional fine-tuning on Facebook’s pre-trained OPT 125M model to enhance performance in Natural Language Inference (NLI) tasks. Using the QQP and RTE datasets from the GLUE benchmark, it measures performance metrics such as loss, accuracy, and resource utilization. The results indicate that context distillation combined with QLoRA significantly improves both accuracy and efficiency on test datasets. This study validated the effectiveness of context distillation in optimizing large language models for classification tasks.

- [Report](#)
- [Github](#)

---
title: "Beyond FLuID"
excerpt: "Enhancing federated learning frameworks for better performance and efficiency.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

## Beyond FLuID

In this project, we enhanced the federated learning framework FLuID by integrating Invariant Dropout and exploring its synergy with federated optimizers like FedAdam and FedAvg. We conducted a series of experiments to assess performance enhancements through benchmarking optimizer efficiencies, implementing sparsity thresholds to optimize data transmission to straggler devices, and quantizing model layers to evaluate trade-offs in accuracy. Our findings revealed that FedAdam, combined with Invariant Dropout, offers a robust alternative to FedAvg, showing significant improvements in convergence rates. While sparsity thresholds enhanced system efficiency, quantization slightly reduced accuracy, highlighting the complex balance between model performance and computational efficiency in federated learning environments.

- [Github](https://github.gatech.edu/HML8803-Spring24/Beyond-FLuID)
- [Report](#)

---
title: "Pulmonary Embolism Detection"
excerpt: "Leveraging machine learning to predict pulmonary embolism using EHR data.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

## Pulmonary Embolism Detection

This project aimed to develop and refine machine learning models to predict and diagnose pulmonary embolism (PE) using only electronic health records (EHR), addressing the challenge of limited CT scan accessibility in low- and middle-income countries. We employed supervised learning techniques such as Support Vector Machines (SVM) and CatBoost, alongside unsupervised methods like K-Means clustering and DBSCAN, to analyze EHR data. The models were evaluated based on accuracy, F1 score, and AUROC metrics, with SVM and CatBoost showing substantial promise in both binary and multi-class classifications. The unsupervised learning models were assessed using silhouette scores to understand cluster quality, aiming to enable personalized treatment strategies based on patient data segmentation.

- [YT](https://www.youtube.com/watch?v=Wt91ZVylIGM)
- [Code](https://github.gatech.edu/kramakrishna3/cs7641_group15/tree/final_report)
- [Website](https://github.gatech.edu/pages/kramakrishna3/cs7641_group15/#background)

---
title: "Graph Neural Networks"
excerpt: "Optimizing GNN inference for better scalability and efficiency.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

## Graph Neural Networks

In this project, I developed and implemented an optimized strategy for Graph Neural Network (GNN) inference called "Staged Neighbor Aggregation" to address the challenge of neighborhood explosion, a common issue that leads to increased computational and memory demands during model execution. This approach incorporates synchronous layer-wise execution and staged neighbor aggregation between layers, coupled with static node batching, to enhance memory efficiency. The focus of the project was to evaluate the performance of node-wise and layer-wise inference techniques using the newly developed sync and degree-balanced data loader. This method not only improves the scalability of GNNs but also offers insights into more efficient graph processing techniques, crucial for applications in complex networked systems.

- [PPT](#)

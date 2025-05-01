Network Traffic Analysis for Malicious Activity Detection

Overview

This project focuses on identifying malicious activity in network traffic by mining data patterns and drawing correlations, especially for attacks that rely on volume and/or iteration, such as:

- Denial of Service (DoS) attacks  
- Network scanning  

To achieve this, we apply supervised machine learning techniques, specifically a **Decision Tree** classifier, to detect and classify suspicious network behaviour.

Objectives

- Extract and preprocess network traffic data
- Identify key features that indicate malicious activity
- Train and evaluate a Decision Tree model to classify network traffic
- Visualize patterns and detection results

Key Features

- Supervised learning approach using Decision Tree algorithm
- Focused detection on volume-based attacks (e.g., DoS)
- Correlation and pattern analysis within network traffic data
- Modular codebase for reproducibility and experimentation

Benchmark dataset used:
- NSL-KDD dataset—a benchmark dataset widely used in cybersecurity research.

References 


M. Tavallaee, E. Bagheri, W. Lu and A. A. Ghorbani, "A detailed analysis of the KDD CUP 99 data set," 2009 IEEE Symposium on Computational Intelligence for Security and Defense Applications, Ottawa, ON, Canada, 2009, pp. 1-6, doi: 10.1109/CISDA.2009.5356528.

www.unb.ca. (n.d.). NSL-KDD | Datasets | Research | Canadian Institute for Cybersecurity | UNB. [online] Available at: ttps://www.unb.ca/cic/datasets/nsl.html. 

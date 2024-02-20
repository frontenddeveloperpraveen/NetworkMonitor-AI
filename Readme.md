# Data Usage Monitoring App

### Members - Praveen , Shreyas , Jayapradeep , Aritra

## Idea

Creating a Windows app using Tkinter that monitors and displays which applications or processes are using the internet can be a useful tool for diagnosing and managing internet speed issues on the network.

### AI Integration

1. **Anomaly Detection (Security Idea):**
   - Train a machine learning model to recognize patterns of normal network usage.
   - Use the model to detect anomalies or unusual behavior that may indicate network issues or security threats.
   - Highlight or alert the user when unexpected network activity is detected.
2. **Automatic Bandwidth Allocation:**
   - Identifying Application Urgency: Defining and accurately determining which application is "more urgent" for a user can be subjective and context-dependent. Factors like user intent, real-time needs, and application criticality must be considered.
   - Real-time Monitoring and Analysis: Continuously monitoring application activity and network traffic to assess urgency demands significant processing power and efficient algorithms.

## Requirements

- Display a list of active applications/processes using the internet.
- Show the amount of data consumed by each application/process.
- Allow the user to stop or limit the bandwidth of specific applications/processes.

## Programming Language and GUI Framework

- Tkinter (Python) for GUI application.

### Necessary Libraries for Data Usage Analysis

- `Pysutil`: for retrieving information about system utilization.
- `Speedtest-cli`: for checking the internet speed.

### Libraries for AI Integration in Project

1. **Scikit-learn:** A simple and effective tool for data analysis and machine learning in Python.
2. **TensorFlow and PyTorch:** Powerful libraries for building and training neural networks.
3. **Pandas:** Useful for data manipulation and analysis.
4. **NumPy:** Ideal for numerical operations in Python.

## Pre-training Data Sets for AI-assisted Anomaly Detection

- [Intrusion Detection Dataset](https://www.unb.ca/cic/datasets/ids-2017.html) (labelled)
- [Network Intrusion Detection Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection) (labelled as normal or under attack)

- 

### Additional Useful Links

- [Network Intrusion Detection with PyTorch and PCA](https://www.kaggle.com/code/elirizk/network-intrusion-detection-with-pytorch-and-pca)

Working Kaggle link for cicids 2017: https://www.kaggle.com/datasets/cicdataset/cicids2017/data
possible code for ideas : https://www.kaggle.com/code/omrastogi/cicidsclassifiers
And : https://www.kaggle.com/code/kooaslansefat/cicids2017-safeml

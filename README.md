# SIMPAC-2025-45
ICMP-Flood-SDN: A Python based machine learning application for ICMP Flood DDoS attack detection in Software Defined Networks

The application uses six different machine learning classifiers—both parametric and non-parametric—to classify traffic as either benign or malicious. Developed on the Jupyter Notebook environment, this tool is particularly tailored for SDN environments simulated via Mininet, using the Ryu controller and hping3 for traffic generation.

1. Features

SDN-based ICMP flood dataset generation using Mininet and real-world browsing traffic.

Dataset captured with Wireshark and processed via CIC Flowmeter to convert pcap to CSV.

Data preprocessing including cleaning, normalization, and feature selection using correlation-based thresholds.

Trains six classifiers: Logistic Regression, SVM, KNN, Random Forest, Gaussian Naive Bayes, and Decision Tree.

Achieves high accuracy (~99.9%) in DDoS detection.

2. Dataset Details

Kumar, Sudesh (2025), “SDN ICMP Flood Dataset ”, Mendeley Data, V1, doi: 10.17632/zdczzpkd8z.1

Dataset link
https://data.mendeley.com/drafts/zdczzpkd8z

Dataset Visualization
![dataset](https://github.com/user-attachments/assets/623dda10-25e3-4ea6-81c4-0317872df722)

Correlation Heat Matrix 
![hea_t](https://github.com/user-attachments/assets/badcf3fb-4001-49fd-b21d-5e0834d9d694)


3. Dependencies and setup requirements

A.Languages and Libraries  
(i). Python v3.11
(ii) Scikit-learn
(iii) pandas

B. Network tools requirements 
(i) Mininet Emulator	V 2.3.0
(ii) Hping3 tool	V 3.0.0-alpha-2
(ii) Wireshark tool	(v3.0.2)

4. Screenshots
(i). Configuration Stage
![Screenshot from 2021-12-22 11-17-31](https://github.com/user-attachments/assets/f15131b1-4b26-42ad-bf4e-c757829d0ac8)

(ii). Before ICMP Flood Attack

![Screenshot from 2021-12-25 16-41-59](https://github.com/user-attachments/assets/4b10544b-e9ca-413f-a237-f919dffff0d2)

(iii). After ICMP Flood Attack
   
![Screenshot from 2021-12-25 16-43-46](https://github.com/user-attachments/assets/4e08f83a-9534-49ff-a99d-0ed96922893d)

For any querries contact me at: sudesh.bhadu@smvdu.ac.in

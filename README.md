FruadShield.html
A graph-based system that uses TigerGraph to detect hidden fraud patterns by analyzing relationships between transactions, accounts, and devices in real time.

 Problem:
Traditional systems fail to detect complex fraud patterns like loops, fake accounts, and shared devices because they cannot track relationships between     transactions.

 Solution:
 Convert transaction data into a graph network and use TigerGraph to identify suspicious patterns based on connections instead of isolated data.

Features :

Detects money loops & fraud chains
Identifies multiple accounts on same device
Real-time fraud alerts
Visual graph dashboard with highlighted suspicious nodes

How to Run :

Set up TigerGraph database
Run backend using FastAPI server
Launch frontend using React app
Input transaction data and view results on dashboard

Technology Used :

Backend: FastAPI
Frontend: React.js
Visualization: D3.js
Database: TigerGraph
Query Language: GSQL
 Future Scope :
 
Integrate AI/ML for advanced prediction
Real-time integration with banking systems
Mobile app for instant alerts
Expand to cybersecurity & insurance fraud detection

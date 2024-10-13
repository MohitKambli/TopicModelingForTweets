# Topic Modeling For Tweets 

A full-stack web application designed to **collect, preprocess, and store tweets data**. This project integrates **React.js (frontend)**, **AWS Lambda**, **EC2**, **Netlify**, and **S3** to provide a seamless user experience with efficient serverless processing and scalable data storage.  

---

## 🚀 Key Features  
1. **Frontend (React.js + Netlify):**  
   - User-friendly interface to trigger data collection and processing.  
   - Deployed on **Netlify** for continuous integration and minimal downtime.  

2. **Backend (Flask + EC2):**  
   - Hosted on **AWS EC2** to handle API requests and long-running processes.  
   - Manages interaction with AWS Lambda and S3.  

3. **Serverless Processing (AWS Lambda):**  
   - Preprocesses tweets asynchronously using **pandas** and **nltk** libraries.  
   - Handles data cleaning and transformation before storing in S3.  

4. **Data Storage (AWS S3):**  
   - Processed tweets are stored as **CSV files** in **AWS S3**.  
   - S3 ensures scalable, reliable, and cost-effective data storage.

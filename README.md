Sales Data Processing Pipeline 🚀

A scalable data pipeline for processing and analyzing sales data using Google Cloud Platform (GCP), Python, and BigQuery. This project automates data ingestion, transformation, and visualization to enable real-time business insights.

📌 Features
✅ Web-Based Upload – Built using Flask, allowing users to upload sales data files.
✅ Cloud Storage – Uploaded files are stored securely in Google Cloud Storage (GCS).
✅ Automated ETL – Google Cloud Functions trigger ETL processing upon file upload.
✅ BigQuery Integration – Stores and processes structured sales data efficiently.
✅ Looker Studio Dashboards – Interactive reports for sales trends and business insights.

🔧 Tech Stack
Cloud: Google Cloud Platform (GCP) – GCS, BigQuery, Cloud Functions

Data Processing: Python (Pandas, Flask), SQL

Automation: Cloud Pub/Sub, Cloud Scheduler

Visualization: Looker Studio

🚀 Setup & Installation
1️⃣ Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/sales-data-pipeline.git
cd sales-data-pipeline
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Set up GCP credentials and configure .env file.
4️⃣ Deploy Cloud Functions and test data upload.
5️⃣ View interactive dashboards on Looker Studio.

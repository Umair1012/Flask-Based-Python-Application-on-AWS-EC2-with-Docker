# Flask-Based-Python-Application-on-AWS-EC2-with-Docker

# 🛡️ Internal Audit Dashboard - Version 1

A simple Flask-based web application that serves as the foundation for the Internal Audit Dashboard.

## 📁 Project Structure

- app.py
- requirements.txt


## 🚀 Getting Started

Follow these steps to set up and run the application on your local machine.

### ✅ Prerequisites

Ensure you have Python 3.7 or higher installed.

Check Python version:

```bash
python --version
```bash

📦 Step 1: Clone the Repository
git clone https://github.com/your-username/internal-audit-dashboard.git
cd internal-audit-dashboard
🐍 Step 2: Create Virtual Environment (Recommended)

python -m venv venv
source venv/bin/activate    # On Linux/Mac
venv\Scripts\activate       # On Windows
📥 Step 3: Install Dependencies

pip install -r requirements.txt
🏃 Step 4: Run the Application

python app.py
The application will start running at:
🌐 Flask will start at http://0.0.0.0:8000

Access from Browser
Open:
http://<your-ec2-public-ip>:8000

🖥️ Output
Once running, you should see the message:

Welcome to the Internal Audit Dashboard - Version 1
🛠️ Technologies Used
Python 3

Flask 2.3.3

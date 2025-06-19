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

<pre>python --version</pre>


### 📦 Step 1: Clone the Repository

<pre>git clone https://github.com/your-username/internal-audit-dashboard.git
cd internal-audit-dashboard</pre>

### 🐍 Step 2: Create a Virtual Environment (Recommended)

<pre>python -m venv venv</pre>

Activate the environment:

On Linux / macOS:

source venv/bin/activate
### 📥 Step 3: Install Dependencies

pip install -r requirements.txt
### 🏃 Step 4: Run the Application

python app.py
The Flask app will start on:
🌐 http://0.0.0.0:8000

### 🌍 Access the Application in Browser
If running on a server (e.g., EC2), open the app at:


http://<your-ec2-public-ip>:8000
Ensure port 8000 is allowed in your security group/firewall.

🖥️ Expected Output
Once the application is running, you’ll see this message in your browser:


Welcome to the Internal Audit Dashboard - Version 1
🛠️ Built With
Python 3

Flask 2.3.3

### 📄 License
This project is open-source and available under the MIT License.

### 📬 Contact
For questions, feedback, or contributions, feel free to open an issue or submit a pull request.

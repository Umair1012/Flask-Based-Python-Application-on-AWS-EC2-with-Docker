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


📦 Step 1: Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/internal-audit-dashboard.git
cd internal-audit-dashboard
🐍 Step 2: Create a Virtual Environment (Recommended)
bash
Copy
Edit
python -m venv venv
Activate the environment:

On Linux / macOS:

bash
Copy
Edit
source venv/bin/activate
On Windows:

cmd
Copy
Edit
venv\Scripts\activate
📥 Step 3: Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
🏃 Step 4: Run the Application
bash
Copy
Edit
python app.py
The Flask app will start on:
🌐 http://0.0.0.0:8000

🌍 Access the Application in Browser
If running on a server (e.g., EC2), open the app at:

cpp
Copy
Edit
http://<your-ec2-public-ip>:8000
Ensure port 8000 is allowed in your security group/firewall.

🖥️ Expected Output
Once the application is running, you’ll see this message in your browser:

pgsql
Copy
Edit
Welcome to the Internal Audit Dashboard - Version 1
🛠️ Built With
Python 3

Flask 2.3.3

📄 License
This project is open-source and available under the MIT License.

📬 Contact
For questions, feedback, or contributions, feel free to open an issue or submit a pull request.

🚀 Features

Upload an image and detect objects using AWS Rekognition.
Returns labels with confidence scores and bounding boxes.
Reads AWS credentials securely from a .env file.
Lightweight Flask API, easy to extend and deploy.

📦 Installation
1. Clone the repository
git clone https://github.com/your-username/object-recognition-api.git
cd object-recognition-api

2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

3. Install dependencies
pip install -r requirements.txt

🔑 Configuration
Create a .env file in the project root:
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_REGION=ap-south-1
Add .env to your .gitignore to prevent leaking credentials.
▶️ Usage
Run the API
python app.py
The server will start at:
http://127.0.0.1:5000


🛠 Deployment
For local testing, use python app.py.

📌 Requirements
See requirements.txt
 for dependencies:
Flask
boto3

python-dotenv

werkzeug

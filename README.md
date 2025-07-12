# Clone the repo
git clone https://github.com/your-username/ChatFusion.git
cd ChatFusion

# Create a virtual environment (Python 3.8+)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install core dependencies
pip install django djangorestframework redis channels

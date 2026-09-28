What is included

Project: CardioTwin

Synthetic EHR / historical health data
Synthetic wearable time-series data
Feature fusion
Random Forest ML model
Cardiovascular-risk demonstration score
7-day wearable visualization
Clinician-style Streamlit dashboard
Feature-importance visualization
README documentation
Architecture diagram documentation
MIT License
.gitignore
requirements.txt

//code // 

cd CardioTwin_Digital_Twin_POC

python3 -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt

streamlit run app/app.py

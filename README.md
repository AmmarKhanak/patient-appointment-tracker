# patient-appointment-tracker
Cloud Based App to manage patient appointments for hospitals and doctors office
This is my very first project on my own I'm excited to start my journey towards something I believe in which is ease and accessecibility in health care and health tech
The main Objectives include Patients making an appointment, Admin being able to confirm or reject the appointment and storeing of data in the cloud

# Patient Appointment Tracker API

A simple RESTful API built with Flask to manage patient appointments.

## Features
- Add new appointments
- View all appointments

## Tech Stack
- Python 3
- Flask

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/AmmarKhanak/patient-appointment-tracker.git
cd patient-appointment-tracker

### 2. Setup virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

###Install Dependencies
pip install -r requirements.txt
### Run the app
python app.py

### Then go to http://localhost:5000 in your browser or test endpoints using Postman.

###Json Example
{
  "patient_name": "John Doe",
  "time": "2025-06-01T14:30"
}



### yaml example Next Steps:
1. Copy these files into your GitHub repo (`patient-appointment-tracker`).
2. Make your first commit:  
   ```bash
   git add .
   git commit -m "Initial Flask backend for patient appointment tracker"
   git push origin main

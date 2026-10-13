# ENR106 – Facial Recognition Attendance System

A Python-based facial recognition attendance system developed as part of the ENR106 academic project. The system uses computer vision to recognize registered faces and support attendance management.

## Overview

Manual attendance recording can be time-consuming and prone to errors. This project explores an automated approach using facial recognition to identify registered users and streamline the attendance process.

The application is built using Python and organized into modules for application initialization, graphical user interface, face recognition, user management, and class management.

## Features

- **Facial Recognition:** Identify registered faces using computer vision.
- **User Registration:** Support face registration through the application's registration module.
- **Graphical User Interface:** Interact with the system through a GUI.
- **User Management:** Manage user-related operations.
- **Class Management:** Organize class-related information.
- **Attendance Workflow:** Support a facial recognition-based attendance process.

## Technology Stack

- **Language:** Python
- **Computer Vision:** OpenCV
- **Face Detection:** Haar Cascade Classifier
- **Face Recognition:** Project-specific recognition and training modules
- **Interface:** Python GUI
- **Data Storage:** CSV files
- **Version Control:** Git and GitHub

## Project Structure

```text
ENR106-Facial-Recognition-Attendance-System/
│
├── Data/
│   ├── Users/
│   └── classes.csv
│
├── Scripts/
│   ├── GUI.py
│   ├── recognize.py
│   ├── register.py
│   └── haarcascade_frontalface_default.xml
│
├── Utils/
│   ├── account_manager.py
│   ├── class_manager.py
│   └── helpers.py
│
├── Initialise.py
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

*Note: The structure above represents the main application modules. Some data files and supporting files may differ depending on the local setup.*

## Requirements

- Python 3.x
- pip (Python package manager)
- A webcam or compatible camera
- Required Python packages listed in `requirements.txt`

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/diyan07-ctrl/ENR106-Facial-Recognition-Attendance-System.git
cd ENR106-Facial-Recognition-Attendance-System
```

### 2. Create a virtual environment

**Windows:**

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

If PowerShell blocks environment activation, you can install dependencies using the virtual environment's Python executable directly.

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run the application

Start the main application using:

```bash
python main.py
```

If the project requires initial setup before launching, run:

```bash
python Initialise.py
```

Follow the application's on-screen instructions.

## Usage

1. Set up the project and install the required dependencies.
2. Complete any required initialization.
3. Register users through the application's supported registration workflow.
4. Allow the system to access the camera when required.
5. Use the available interface to perform facial recognition and attendance-related operations.

The exact workflow depends on the application's implementation and configuration.

## Data and Privacy

This project processes facial data and may use attendance or account records.

- Do not upload real facial images or personal attendance records to a public repository.
- Never commit passwords, access tokens, or other credentials.
- Use dummy data when sharing the project for academic evaluation.
- Obtain appropriate consent before collecting or processing anyone's facial data.
- Restrict access to stored data and delete it when no longer needed.

## Academic Context

**Course:** ENR106  
**Project:** Facial Recognition Attendance System  
**Institution:** Ahmedabad University  
**School:** School of Engineering and Applied Science (SEAS)

## Future Improvements

Potential improvements include:

- Database integration instead of CSV-based storage.
- Improved recognition accuracy under different lighting conditions.
- More robust authentication and role-based access control.
- Attendance reports and export functionality.
- Improved data protection and privacy controls.
- Automated testing and deployment.

## Contributors

Developed as an academic project for ENR106 at Ahmedabad University.

## License

No license has been specified yet. Unless a license is added to the repository, the project should not be assumed to be available for unrestricted reuse or redistribution.

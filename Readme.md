DOS Attack Simulation Project

Project Overview

This project is a Denial of Service (DOS) attack simulation tool developed in Python.It is designed for educational and testing purposes to simulate network traffic overload on a server in a controlled environment. This project should never be used on live or unauthorized systems, as performing DOS attacks on real servers is illegal and unethical.

The project includes a Python-based server (app.py) and a simulation module (simulation/simulator.py) to generate traffic patterns that mimic DOS attacks. The front-end interface (templates/index.html) allows monitoring and interacting with the simulation.

Folder Structure

.
├── app.py                  # Main Flask server script
├── config.py               # Configuration settings for the project
├── __pycache__             # Python cache files
├── requirements.txt        # Project dependencies
├── setup_fix.sh            # Fix script for setup issues
├── setup.sh                # Initial setup script
├── simulation              # Simulation module
│   ├── __init__.py
│   └── simulator.py        # DOS traffic simulator
├── templates               # HTML templates for Flask
│   └── index.html
├── test_server.py          # Script for testing server functionality
└── venv                    # Python virtual environment

Requirements

Python 3.12 or later

Virtual environment (venv)

Linux-based system recommended for full compatibility

Required Python packages are listed in requirements.txt

Setup Instructions

Clone the repository (if not already done):

git clone <repository-url>
cd <project-folder>

Activate virtual environment:

source venv/bin/activate

Upgrade pip (optional):

pip install --upgrade pip

Install dependencies:

pip install -r requirements.txt

Run setup scripts (if needed):

bash setup.sh
# Or if some fixes are required
bash setup_fix.sh

How to Run

Start the main server:

python app.py

This will start the Flask server and load the web interface available at http://127.0.0.1:5000/.

Test the server functionality:

python test_server.py

Run the DOS simulation module directly:

python -m simulation.simulator

This command ensures the simulation module runs as a Python package.

Usage Instructions

Open the browser and navigate to http://127.0.0.1:5000/.

Use the interface to configure parameters for the DOS simulation, such as:

Number of simulated requests

Target URL (local server only for testing)

Delay between requests

Monitor the server response in real time using the interface.

Stop the simulation by pressing CTRL+C in the terminal or using the stop button in the web interface (if implemented).

Screenshots

(Add screenshots here to show the interface, server output, and simulation running)

Server Home Page

Simulation in Progress

Notes

This project is only for learning and testing DOS attacks in a controlled environment.

Never run this tool against public or unauthorized servers.

Always use the virtual environment to prevent conflicts with system Python packages.

Make sure Python 3.12+ is installed and active.

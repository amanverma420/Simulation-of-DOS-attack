# DOS Attack Simulation Project

This is a **Denial of Service (DOS) attack simulation tool** developed in Python. It is designed for **educational and testing purposes** to simulate network traffic overload on a server in a controlled environment.  

⚠️ **Important:** Never use this tool on live or unauthorized systems. Performing DOS attacks on real servers is illegal and unethical.

---

## 🌐 Project Overview
The project includes:  
- `app.py` – Main Flask server  
- `simulation/simulator.py` – DOS traffic simulator  
- `templates/index.html` – Web interface to monitor and interact with the simulation  
- `test_server.py` – Script to test server functionality  

---

## 📁 Folder Structure

```plaintext
DOS-Attack-Simulation/
├── app.py                  # Main Flask server script
├── config.py               # Configuration settings
├── __pycache__/            # Python cache files
├── requirements.txt        # Project dependencies
├── setup_fix.sh            # Fix script for setup issues
├── setup.sh                # Initial setup script
├── simulation/             # Simulation module
│   ├── __init__.py
│   └── simulator.py        # DOS traffic simulator
├── templates/              # HTML templates for Flask
│   └── index.html
├── test_server.py          # Script for testing server functionality
└── venv/                   # Python virtual environment
```
---

## 🚀 Tech Stack
- **Python 3.12+** – Programming language  
- **Flask** – Web framework  
- **HTML/CSS** – Frontend templates  
- **Linux-based system recommended** – For full compatibility  

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/amanverma420/Simulation-of-DOS-attack.git
cd Simulation-of-DOS-attack$ 

```
2. Activate virtual environment
```bash
source venv/bin/activate
```
4. Upgrade pip (optional)
```bash
pip install --upgrade pip
```
5. Install dependencies
```bash
pip install -r requirements.txt
```
6. Run setup scripts (if needed)
```bash
bash setup.sh
# Or, if fixes are required
bash setup_fix.sh
```
🏃 How to Run
Start the main server
```bash
python app.py
```

This will start the Flask server and load the web interface at:
http://127.0.0.1:5000/

Test the server functionality
```bash
python test_server.py
```
Run the DOS simulation module directly
```bash
python -m simulation.simulator
```
This runs the simulation module as a Python package.

📝 Usage Instructions
Open your browser and navigate to http://127.0.0.1:5000/.

Use the interface to configure:

Number of simulated requests

Target URL (local server only for testing)

Delay between requests

Monitor server response in real-time using the interface.

Stop the simulation with CTRL+C or the stop button in the interface (if implemented).


⚠️ Notes
Only use this project in a controlled testing environment.

Always use a virtual environment to prevent conflicts with system Python packages.

Ensure Python 3.12+ is installed and active.

📬 Contact

👨‍💻 Name: Aman Verma

📧 Email: amanv2225@gmail.com

🔗 GitHub: [Aman Verma](https://github.com/amanverma420)

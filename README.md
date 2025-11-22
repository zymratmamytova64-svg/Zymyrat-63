Car Wash (simple demo)

This is a minimal Flask-based demo of a car wash simulator.

Quick start (Windows PowerShell):

1. Create a virtual environment (optional):
   python -m venv .venv
   .\\.venv\\Scripts\\Activate.ps1
2. Install dependencies:
   pip install -r car_wash/requirements.txt
3. Run the server:
   .\\run-server.ps1

Open http://localhost:5000 in your browser.

Files of interest:
- `car_wash/app.py` - Flask app routes
- `car_wash/services/wash_process.py` - simulated background wash
- `car_wash/templates/index.html` - web UI
- `car_wash/static/status.js` - client polling code

If you want, I can add unit tests, Dockerfile, or improve the UI.
# README.md
cat > README.md <<'RD'
PlantGuard - Flask + React scaffold

Structure:
- src/backend: Flask backend (app.py + inference.py)
- src/frontend: React frontend skeleton (App.js, index.js)
- data/: place demo images/audio/text here
- models/: place your trained model files (resnet/audio/bert) here

Quickstart (Linux/macOS):
1) python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

2) Populate data/ and models/

3) Run backend:
python src/backend/app.py

4) Start frontend (requires Node.js):
cd src/frontend
npm install
npm start

Or use Docker:
docker-compose up --build

Notes:
- inference.py contains placeholders — replace with your real model code.
- Frontend is minimal; it posts files to the Flask backend endpoints.
RD
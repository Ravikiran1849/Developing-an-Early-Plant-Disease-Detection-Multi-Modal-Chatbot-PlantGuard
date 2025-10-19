# BACKEND README
cat > src/backend/README_backend.md <<'BREAD'
Backend README
--------------
Place trained model files in 'models/'.
Endpoints:
- POST /predict_image (form-data 'file')
- POST /predict_audio (form-data 'file')
- POST /qa (JSON {'question': '...'})
Replace inference.py with actual model loading/inference logic.
BREAD

# Heart Stroke Prediction — Run Instructions

Quick steps to run locally:

```
python -m venv .venv
.venv\Scripts\Activate.ps1  # PowerShell
python -m pip install --upgrade pip
pip install -r requirements.txt
streamlit run 1_Heart_Disears.py
```

Fix for deployment (Streamlit Cloud): commit and push `requirements.txt` to your GitHub repo. Streamlit will install the listed packages during deploy.

Files that must be in the repo root:

- `1_Heart_Disears.py`
- `KNN_heart.pkl`
- `scaler.pkl`
- `columns.pkl`
- `requirements.txt`

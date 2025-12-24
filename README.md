# CENT — Face Detection Software for Banks

CENT is a Python-based project that demonstrates a face-detection and recognition prototype tailored for banking use-cases (e.g., customer identification at counters, fraud prevention, and access control).

Features
- Face detection using a pre-trained DNN (Caffe model).
- Simple face recognition pipeline for matching known customers.
- Minimal Flask backend and static frontend for demo purposes.

Quick start
1. Create a virtual environment and install dependencies (example using pip):

```bash
python -m venv venv
venv\Scripts\activate    # Windows
pip install -r requirements.txt
```

2. Run the demo backend (from project root):

```bash
python "FULL UPDATED FILES OF PROJECT/bank app/backend/app.py"
```

Project structure (important files)
- `FULL UPDATED FILES OF PROJECT/bank app/backend/app.py`: Flask demo backend.
- `FULL UPDATED FILES OF PROJECT/bank app/backend/database.py`: Simple CSV-backed data access.
- `FULL UPDATED FILES OF PROJECT/bank app/face_detection_model/`: DNN model files (`deploy.prototxt`, `.caffemodel`).
- `FULL UPDATED FILES OF PROJECT/bank app/frontend/`: Static demo frontend.
- `FULL UPDATED FILES OF PROJECT/bank app/models/face_recognition.py`: Recognition helpers.

Notes
- This repository contains example data and model files for demonstration only. Do not use this as-is in production.
- If you intend to run the demo, ensure large binary/model files are present (they are included in the `FULL UPDATED FILES OF PROJECT` folder in this workspace).

Contributing
- Improvements, bug fixes, and documentation updates are welcome. Open an issue or pull request on GitHub.

License
- Add a license file if you plan to release this publicly.

Contact
- Maintainer: Parth (see GitHub profile)

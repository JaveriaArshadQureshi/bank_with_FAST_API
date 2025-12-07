smart_attendance_eyes/
│
├─ app.py
├─ train.py
├─ recognizer.py
├─ db.sqlite       # will be auto-created
│
├─ models/
│   ├─ __init__.py
│   ├─ base.py
│   ├─ student.py
│   └─ attendance.py
│
├─ utils/
│   ├─ __init__.py
│   └─ cv_utils.py
│
├─ templates/
│   ├─ index.html
│   ├─ register.html
│   └─ live.html
│
└─ data/
    ├─ students/    # student images
    └─ models/      # trained LBPH model

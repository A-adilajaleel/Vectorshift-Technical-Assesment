# VectorShift Technical Assessment

A modern AI workflow pipeline builder built using React, ReactFlow, Zustand, and FastAPI.

---

## Features

* Drag and drop pipeline builder
* Dynamic node creation
* Reusable BaseNode architecture
* Dynamic text variable handles
* DAG (Directed Acyclic Graph) validation
* Modern dark themed UI
* FastAPI backend integration
* Real-time node and edge parsing

---

## Tech Stack

### Frontend

* React
* ReactFlow
* Zustand

### Backend

* FastAPI
* Python

---

## Project Structure

```bash
vectorshift-technical-assessment/
│
├── frontend/
├── backend/
├── README.md
└── .gitignore
```

---

## Running Frontend

```bash
cd frontend
npm install
npm start
```

---

## Running Backend

```bash
cd backend
pip install fastapi uvicorn
uvicorn main:app --reload
```

---

## DAG Validation

The backend validates whether the pipeline forms a Directed Acyclic Graph (DAG) and returns:

* Number of Nodes
* Number of Edges
* DAG Status

---

## Screenshots

### Pipeline Builder UI

(Add your screenshot here)

---

## Author

Adila Jaleel

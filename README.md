# NHAI FaceGuard Offline

A fully offline facial recognition and liveness detection web application built for NHAI Innovation Hackathon 7.0.

## Overview

NHAI FaceGuard Offline is designed for zero-network highway and infrastructure environments. It combines local face embedding enrollment, live recognition, and advanced anti-spoofing using edge-friendly AI models.

## Architecture

- Frontend: React + TypeScript + Tailwind CSS
- Backend: Node.js + Express + SQLite
- AI Layer: ONNX Runtime Web + MediaPipe Face Mesh + local offline embeddings
- Security: AES-encrypted local database, role-based access control, audit logs

## Features

- Offline face enrollment and identification
- Liveness detection with blink, head motion, and texture cues
- Admin, Supervisor, and Field Officer roles
- Dashboard with attendance logs, recognition analytics, and failed authentication reports
- Secure local storage with encrypted SQLite database
- Light mode and dark mode with government-style UI
- Offline QR fallback and risk scoring for suspicious authentications

## Getting Started

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## Deployment

For offline deployment, bundle the frontend assets and run the Express API locally on the target machine. The database file is stored locally and encrypted using AES.

## Documentation

See `docs/architecture.md` for data flow diagrams, schema design, and offline deployment notes.

# VISGEN STEM Learning

VISGEN is an interactive STEM learning site with Mathematics, Physics, Biology,
and Chemistry labs. The project uses Flask to serve the pages and static files.

## Run locally

1. Install Python 3.10 or later.
2. Install dependencies:

   ```powershell
   python -m pip install -r requirements.txt
   ```

3. Start the app from this folder:

   ```powershell
   python app.py
   ```

4. Open <http://127.0.0.1:5000>.

The Biology lab uses a local copy of Three.js in `JS/three.min.js`. Its optional
chat endpoint reads `GEMINI_API_KEY` from the environment; no key is required to
use the learning labs.

## Routes

- `/` — VISGEN subject hub
- `/maths` — MathVerse
- `/physics` — Physics lab
- `/biology` — BioVerse
- `/chemistry` — ChemVerse

This repository contains the app source. GitHub Pages does not run Flask; use a
Python-capable hosting service to publish a live version.

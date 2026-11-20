# Balochistan Smart Highway & Weather Intelligence System

A tactical government command-and-control dashboard for real-time highway weather monitoring, corridor risk visualization, multilingual driver alerts (Urdu, Pashto, Balochi), and QR checkpoint verification across Balochistan.

## Authentication & Security
- **Sign In / Sign Up Portal**: Built-in operator authentication stored in SQLite (`users` table with SHA-256 password hashing).
- **Default Admin Account**: Username `admin` | Password `admin123`
- **Officer Registration (Sign Up)**: New PDMA, NHA, Levies, and Highway Police officers can register their own accounts directly from the login portal.

## Run Instructions
```bash
pip install -r requirements.txt
streamlit run app.py
```

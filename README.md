#🧙 WitchCast

A magical weather forecasting app that predicts temperature thresholds using historical data and real-time Meteomatics API. Built with FastAPI and React.

*Stack*: FastAPI (backend), React (frontend), Meteomatics API (weather data)

This app lets users query historical weather data for a specific location and date, and calculates the probability of exceeding a temperature threshold. It visualizes the results with a histogram and allows CSV export.

---

## 🛠 Backend Setup (/backend)

### ✅ Technologies
- FastAPI
- Uvicorn
- NumPy, Pandas
- Meteomatics API
- Python-dotenv

### 📂 Key Files
- main.py: FastAPI app with /api/query and /api/query/csv endpoints
- meteomatics.py: Fetches real weather data using Meteomatics API
- .env: Stores credentials and config

### 🔐 Environment Variables
```env
METEOMATICS_USER=manipalacademyofhighereducation_aafreen_amina
METEOMATICS_PASSWORD=1h4sYI3dS92UrlZRB63j
DATA_PROVIDER=meteomatics and NASA POWER Daily Point API
YEAR_START=1985
YEAR_END=2024

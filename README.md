# Fraud Detection API

Real-time transaction fraud detection API built using XGBoost, FastAPI, Docker, and deployed into Google Cloud Run with full CI/CD.

## Architecture
- **Model:** XGBoost (with SHAP explainability)
- **API:** FastAPI with async endpoints
- **Experiment Tracking:** MLflow
- **CI/CD:** GitHub Actions
- **Cloud:** Google Cloud Run
- **Monitoring:** Evidently AI (data drift detection)

## Project Structure
\```
src/        - Core application code
notebooks/  - EDA and model experimentation
tests/      - Automated test suite
monitoring/ - Drift detection reports
.github/    - CI/CD pipeline
\```

## Status
In Progress
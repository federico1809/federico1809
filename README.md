### Federico Ceballos Torres
**Data & Machine Learning Engineer - Currently serving as Tech Lead at PhysaFlow**

Python · SQL · AWS · DevOps · LLMs

I build end-to-end data and machine learning solutions with a focus on validation, reproducibility, and production readiness. My background combines 5+ years in QA Engineering and Scrum Master roles — including a Scrum Master certification — which shaped a systems mindset and structured approach to both engineering and team facilitation, with a Political Science degree that strengthened my research and quantitative reasoning.

Currently **Tech Lead & Machine Learning Engineer at PhysaFlow**, a climate-tech AI startup optimizing data centers in real time using biomimicry and edge-native AI. PhysaFlow is part of the Harvard Alumni Entrepreneurs Accelerator (2026 cohort) and is benchmarking against NERSC telemetry at Lawrence Berkeley National Lab.

- **As Scrum Master** (official role): sprint planning and facilitation, ceremony ownership, and onboarding of new team members.
- **As Tech Lead**: technical escalation point for the engineering team, architecture and delivery decisions across the RAG and infrastructure stack.
- **As Data Engineer**: built and operate the production RAG pipeline — semantic chunking, SBERT embeddings, vector database integration, MMR-based retrieval, and automated evaluation pipelines.
- **As DevOps**: sole owner of the AWS environment, scaled from 20 to 29 production tenants — EC2 fleet, Docker deploy pipelines, CI/CD with self-hosted runners, AWS Bedrock, and observability as code.

Concurrently working as Data Analyst at Bethel Legal Solutions, and as a Teaching Assistant for an 8-month Data Science bootcamp at Henry, supporting students through SQL, databases, and EDA modules.

### Featured Projects

**🏆 World Cup 2026 Predictor — XGBoost + Monte Carlo Simulation**
End-to-end ML pipeline for tournament outcome prediction.
- XGBoost model trained on 93 features built from 150 years of international football.
- Features include: Elo ratings recalculated from 1872, form windows (5/10/20 matches), H2H with temporal decay, transitive H2H encoding, squad market value, rest days, and tournament importance tiers.
- 10,000 Monte Carlo simulations of the full 48-team bracket (~10 min, optimized from ~100 min via batch precomputation of all 2,256 team permutations).
- Live interactive Streamlit dashboard with symmetric neutral-ground predictions.
- Pre-match predictions committed before kick-off as portfolio proof of concept.
- **Tech:** Python · XGBoost · Monte Carlo · Streamlit · pandas · scikit-learn

**💳 Credit Risk Modeling — $17.5M Business Impact Optimization**
End-to-end ML system for loan default prediction.
- EDA, feature engineering, and model development with XGBoost.
- Threshold optimization framed as a business cost minimization problem (threshold 0.228).
- Probability calibration via Isotonic Regression — reduced ECL estimation error from 133% (baseline) to 2.6% (optimized).
- SHAP explainability, Optuna tuning, and Docker-based reproducibility.
- Projected 39.1% cost reduction ($17.5M).
- **Tech:** Python · XGBoost · SHAP · Optuna · Docker · scikit-learn

**🛒 Insight Commerce — Next-Basket RecSys · Deployed on AWS**
Production-grade recommendation system built on the Instacart dataset (~2M transactions).
- LightGBM model with Optuna tuning: F1 0.42 · AUC-ROC 0.82 · +296% uplift vs. popularity baseline.
- REST API deployed on AWS ECS Fargate · Streamlit app · MLflow experiment tracking.
- CI/CD via GitHub Actions · automated drift monitoring (PSI/KS) with auto-retraining.
- Dual inference logic with cold-start fallback for full service availability.
- SonarCloud A ratings across all quality gates (84.6% coverage).
- **Tech:** Python · LightGBM · FastAPI · Streamlit · MLflow · Docker · AWS · PostgreSQL

### Tech Stack

**Languages & Data:** Python · SQL · Pandas · NumPy · Jupyter Notebook

**Machine Learning:** scikit-learn · LightGBM · XGBoost · CatBoost · Optuna · SHAP · Feature Engineering · Model Validation

**AI & LLMs:** LangChain · ChromaDB · pgvector · SBERT · RAGAS · AWS Bedrock (Llama 3.1 8B) · OpenAI API

**MLOps & Deployment:** Docker · GitHub Actions (CI/CD) · FastAPI · Streamlit · MLflow · AWS ECS Fargate · AWS S3 · AWS RDS · AWS EC2

**Data Analysis & BI:** EDA · Statistical Analysis · Power BI · Tableau · Excel

**Engineering & Team Practices:** Git · Linux · Agile/Scrum · Jira · Reproducible Pipelines · Drift Monitoring (PSI/KS) · Prompt Engineering

### Contact

**LinkedIn:** linkedin.com/in/federico-ceballos-torres
**Email:** federico.ct@gmail.com

If you're reviewing my profile for a Data Science, Data/ML Engineering, DevOps, MLOps, or Scrum Master role, my resume is available on LinkedIn.

# Tomás Escobar Rivera — Data Scientist

Científico de la Computación (Universidad Nacional de Colombia, 2026). Construyo soluciones de datos de punta a punta: consolidación y calidad de datos, modelos de ML en producción, dashboards y automatización con IA generativa.

**Stack:** Python · SQL · Power BI · AWS (Redshift, S3, Feature Store, SageMaker) · XGBoost / Scikit-learn / TensorFlow · LLMs (Anthropic, Bedrock, DeepSeek)

---

## Experience

**Data Scientist Intern — Puntos Colombia** *(Jan 2026 – Jun 2026, Medellín)*
- Designed and implemented an impact measurement framework for ML models and business rules (value, cost and impact KPIs by area), **adopted by the data science area to measure 20+ models** across marketing, product, fraud and operations, and to prioritize investment and each model's continuity.
- Built a segmentation of ~150 marketplace sellers (clustering + SQL) deployed on **AWS Feature Store**, and a customer out-of-ecosystem consumption segmentation in production; marketing uses both for targeted campaigns.
- Created an LLM-based documentation automation (Anthropic, DeepSeek): **1–2 days → ~2 hours per project**, adopted for all of the team's projects.
- Developed Power BI dashboards and reports with KPIs for stakeholders, and used Azure DevOps (repos, CI/CD) to version the team's work.

## Projects

**[Riesgo Contratistas — public procurement due diligence](https://github.com/tscobarr/riesgo-contratistas)** · Python, XGBoost, FastAPI
Platform that scores risk (0–100) for 1.2M Colombian public contractors. Processed ~5.5M SECOP II contracts, built ~50 features and integrated RUES, SuperSociedades and OFAC. XGBoost model (AUC 0.927, AP 0.409) blended 70/30 with a heuristic score; REST API + frontend + PDF reports.

**[PolicyQA — RAG assistant over documents](https://github.com/tscobarr/policyqa)** · Amazon Bedrock, Glue/PySpark, Athena, FAISS
Question-answering over policies and manuals: S3 → Glue ETL (PySpark) → Parquet catalog + Athena → FAISS retrieval → LLM (Nova/Claude). Answers in natural language citing the source document.

**[Uplift Modeling for Email Campaigns](https://github.com/tscobarr/uplift-modeling)** · [Demo](https://uplift-modeling-d8kksx5aquge9anu8rbcac.streamlit.app)
End-to-end A/B testing and causal inference on 64K customers. Meta-learners (S/T/X), Qini/AUUC evaluation, business simulator dashboard.

**[Credit Risk Scorecard with Neural Networks](https://github.com/tscobarr/RNA_G4_Prediccion_Riesgo_Crediticio)** · [Demo](https://rna-g4-prediccion-riesgo-crediticio.streamlit.app)
268K LendingClub records. Neural network (Keras/TensorFlow): AUC 0.718, recall 0.68. FICO-style scorecard with SHAP, automated triage and Streamlit app.

## Tech Stack

- **Languages:** Python, SQL (CTEs, window functions, joins)
- **ML / DL:** Scikit-learn, TensorFlow/Keras, PyTorch (fundamentals), XGBoost, SciPy
- **Data:** Pandas, NumPy, Redshift, S3, Feature Store, data quality & validation
- **Cloud:** AWS (SageMaker basics, Redshift, S3, Feature Store, Bedrock, Glue, Athena), Azure DevOps (repos, CI/CD)
- **Visualization & BI:** Power BI (production), Streamlit, Matplotlib, Plotly
- **Generative AI:** LLMs (Anthropic, DeepSeek), prompt engineering, agents, RAG

## Education

**Científico de la Computación** — Universidad Nacional de Colombia, Medellín (2022 – 2026, graduated November 2026)
ICPC South America North Finals 2025.

## Connect

[LinkedIn](https://www.linkedin.com/in/tomas-escobar-rivera-079815356/) · [Email](mailto:escobar.tomas2004@gmail.com)

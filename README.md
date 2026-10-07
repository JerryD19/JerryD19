# Hi, I'm Jeremiah Dibie 👋

**Data & AI Engineer** in the UK. I build AI and data systems that people can trust, and do the requirements, process mapping and change work that gets them adopted. My work spans clinical research, data consulting and retail banking.

-  Currently: Data Analyst / Engineer at **Bliss Clinical Research**, where I built an **agentic AI pre-screening assistant** on a large language model and am delivering a Clinical Trial Management System (CTMS)
-  Strengths: LLMs and agentic AI · explainable AI · machine learning · NLP · Python · SQL Server · Power BI · Power Platform · requirements and process mapping · digital transformation
-  MSc Big Data Analytics (**Distinction**, incl. Natural Language Processing), University of Derby · BSc Mathematics (2:1), Delta State University
-  Interested in: trustworthy and secure machine learning, explainable AI, and data poisoning
-  Open to: AI, machine learning, data engineering and business analysis roles

---

###  Experience and impact

- **Bliss Clinical Research** · Data Analyst / Engineer · 2026 – present<br>
  Delivering AI and digital transformation for a company that previously ran recruitment on Microsoft Forms alone. I designed and built an **agentic AI pre-screening assistant** on Anthropic's Claude LLM: it screens people who respond to social media adverts, answers only from approved study information, and books eligible people through the Microsoft Graph API. Its decisions are **explainable and auditable**: the LLM works through **5 tools** with strict input schemas, a deterministic rules engine decides eligibility, uncertain cases go to staff, and every record traces to its approved question version (Node.js, **26 automated tests**, privacy by design under GDPR).<br>
  I also built the company's data foundations **from scratch**: a **12-table** SQL Server warehouse and an executive Power BI dashboard (**26 DAX measures**). I am delivering a CTMS on Power Apps and Power Automate across **5 trial stages** for **10–50 staff** and **2,000 active participants**, from requirements workshops, Visio process maps and user stories to user acceptance testing, and I demonstrated both systems to the CEO and managers. *The assistant's code is private company work, so it is not published here.*
- **JB3 Tech** · Data Consultant · 2024 – 2026<br>
  Data analysis, reporting and data engineering for **10+ clients**: Power BI and Excel dashboards, databases, data models and pipelines, plus advice on KPIs and process improvements.
- **University of Derby** · Postgraduate Researcher, MSc Big Data Analytics · 2023 – 2024<br>
  Applied research on real-world datasets, including modules in Natural Language Processing and Ethics, Trust and Governance. I presented a research poster at the university (see projects below).
- **Zenith Bank PLC, Lagos** · Big Data Analyst / Card Business Developer · 2022 – 2024 (study leave 2023–24)<br>
  Worked with designers, engineers and testers to launch **3 self-service features** on mobile and internet banking, and with Mastercard and suppliers to launch **3 card products**. Led Zenith's side of the **Visa** FIFA World Cup 2022 partnership, which lifted card adoption **25%** across 390+ branches. My **50+ partnerships** added **1,000,000 cards** in 2023 (**+28%** year on year), and I supported change management by training **5,000+ staff**. I also used SharePoint to share documents, build lists and manage permissions.

---

###  What I work with

- **AI & LLMs:** large language models · agentic AI and tool calling · explainable AI (LIME) · natural language processing · Anthropic Claude API
- **Machine learning:** scikit-learn · imbalanced-learn (SMOTE) · LIME · classification and regression · time-series forecasting (SARIMA) · model evaluation and leakage auditing · data poisoning
- **Software & APIs:** JavaScript (Node.js, Express) · web APIs · Microsoft Graph API · SQLite · automated testing · cloud deployment (Render)
- **Data governance:** GDPR (consent, data minimisation, retention) · EU AI Act principles (human oversight, transparency, record-keeping) · role-based and least-privilege access
- **Business analysis:** requirements workshops · user stories and acceptance criteria · functional and non-functional requirements · current and future-state process mapping (Visio) · solution options appraisal · vendor evaluation · test cases and UAT · change management, user guides and training
- **Languages & querying:** Python · SQL (T-SQL) · JavaScript · SAS · R · DAX · PySpark
- **Data engineering:** SQL Server · data modelling & normalisation · ETL pipelines · Amazon Redshift · Azure Synapse
- **BI & low-code:** Power BI · Excel · Tableau · Power Apps · Power Automate · Microsoft Forms · Microsoft 365 · SharePoint
- **Tools:** Microsoft Visio · JIRA · Trello · Microsoft Planner · Jupyter · Git · Pandas · NumPy · Matplotlib · Seaborn

---

###  Featured projects

| Project | What it shows and why it matters | Stack |
|---|---|---|
| [**Autism risk detection in toddlers**](https://github.com/JerryD19/autism-risk-detection-ml) | **Explainable AI and model evaluation.** MSc dissertation: 7 models on 1,016 Q-CHAT screening records, with LIME explanations. Later I audited my own pipeline, traced the original 99% accuracy to label leakage and SMOTE applied before the split, and rebuilt it leakage-free (best ROC AUC 0.77). | Python, scikit-learn, imbalanced-learn |
| [**Does SMOTE amplify data poisoning?**](https://github.com/JerryD19/smote-data-poisoning) | **AI security risk.** Research pilot on AI model security. I poisoned training data with label flips and measured how SMOTE spreads the poison into synthetic samples (36% → 52% of the minority class), and when that doubles the damage. | Python, scikit-learn, imbalanced-learn |
| [**ChatGPT in medical chatbots: governance**](https://github.com/JerryD19/chatgpt-medical-chatbot-governance) | **Regulatory compliance.** Paper mapping 5 critical risks of LLM medical chatbots against the EU AI Act, GDPR and HIPAA, with a governance framework so healthcare organisations can close gaps before launch. | AI ethics & governance |
| [**Flight price analytics**](https://github.com/JerryD19/flight-price-analytics) | **Pricing insight for decision-makers.** Analysed 300,153 flight bookings in Python and SAS. Linear regression explains 90% of price variance (test R² = 0.90). Economy fares booked 1 day out cost about 3x those booked 3+ weeks ahead. | Python, SAS, scikit-learn |
| [**Barclays stock prediction**](https://github.com/JerryD19/barclays-stock-prediction) | **Model risk control.** Linear Regression vs Random Forest for Barclays share price, 2020–2024. Random Forest won on MAE and RMSE, and I traced its near-perfect fit to same-day inputs before it could mislead an investment decision. | Python, scikit-learn |
| [**LA crime patterns & forecasting**](https://github.com/JerryD19/la-crime-analysis-forecasting) | **Operational and resource planning.** Analysed ~897,000 LAPD records and ~70,000 assaults. Found a hotspot with 50% more incidents than the next area and a 2.6-day average reporting delay, and forecast monthly volumes with SARIMA for staffing decisions. | Python, statsmodels |
| [**Cloud data warehouse & PySpark**](https://github.com/JerryD19/cloud-data-warehouse-pyspark) | **Vendor platform appraisal.** Compared Amazon Redshift and Azure Synapse on 4 criteria (performance at scale, elasticity, usability and cost) and produced a recommendation framework for choosing between them. Also processed and modelled 18,500 customer records with PySpark. | PySpark, Redshift, Synapse |

---

### 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jeremiah--dibie-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeremiah-dibie)

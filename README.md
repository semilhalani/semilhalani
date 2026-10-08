### Hi, I'm Semil 👋

AI and data engineer with an MSc in Computer Science from Queen Mary University of London. I build generative AI features where wrong output is expensive, and data pipelines that keep running when sources fail.

**Currently:**
- Working as a Software Engineer at Grow Infinity Labs on a client's fintech platform. I shipped a production generative AI market-commentary feed, built n8n monitoring workflows with SHA-256 integrity checks and an AWS S3 export pipeline, and audited an undocumented algorithmic trading platform
- Building a US equity screening system: an ETL and scoring engine on Google Apps Script covering 5,300+ tickers, plus a Python earnings scraper running on GitHub Actions

---

### 🔧 Featured projects

**[US Equity Screener & Scoring Engine](https://github.com/semilhalani/us-equity-screener)**
An ETL and scoring system covering 5,300+ US tickers, pulling data from 6 Finnhub API endpoints and Finviz, benchmarking stocks against tiered industry peers, and scoring them with a rule-based multi-factor engine and five hard disqualifier gates. Includes a custom chunked-execution engine with lock-based concurrency control to work around Google Apps Script's 6-minute runtime cap.
`Google Apps Script` `JavaScript` `Finnhub API` `Web Scraping` `ETL`

**[Earnings Scraper (second phase of the equity screener)](https://github.com/semilhalani/earnings-webscraping)**
A Python scraper that uses Selenium on headless Chrome and BeautifulSoup to collect EPS, GAAP EPS, revenue and post-earnings price moves from client-rendered Finviz widgets. Runs every six hours on GitHub Actions with a concurrency group so runs never overlap, a resumable checkpoint every 20 tickers, and an upsert keyed on ticker and quarter.
`Python` `Selenium` `BeautifulSoup` `GitHub Actions` `Google Apps Script`

**[Network Intrusion Detection: ML vs DL (MSc Dissertation)](https://github.com/semilhalani/dissertation-MLvDL)**
Comparative study evaluating machine learning and deep learning approaches for network intrusion detection, using the CSE-CIC-IDS2018 dataset. A feedforward neural network came out on top at 96.64% accuracy and an F1 score of 0.97, after reducing 80 features down to 48 through correlation-based selection.
`Python` `Keras` `TensorFlow` `scikit-learn` `Jupyter`

**[Heart Disease Risk Prediction](https://github.com/semilhalani/heartdiseaseprediction)**
Multi-metric comparison of classification models for predicting heart disease risk, built with scikit-learn.
`Python` `scikit-learn` `pandas` `Jupyter`

**[Motorsport Ontology & Semantic Web Querying](https://github.com/semilhalani/motorsport-ontology)**
An OWL ontology for the motorsport domain built in Protégé, populated from DBpedia with a SPARQL CONSTRUCT query and queried locally with SPARQL SELECT.
`Python` `OWL` `SPARQL` `rdflib`

---

### 🧰 Tech stack

**Languages:** Python, SQL, JavaScript, TypeScript, Google Apps Script
**AI / ML:** OpenAI API, scikit-learn, TensorFlow, Keras, pandas, NumPy
**Data engineering:** ETL pipelines, data ingestion, data validation, web scraping (Selenium, BeautifulSoup), n8n
**Backend / Infra:** FastAPI, Pydantic, PostgreSQL, Docker, REST APIs, AWS (S3, IAM, boto3), Twilio
**DevOps / Frontend:** Git, GitHub Actions, Vercel, React, Next.js

---

### 📫 Reach me

[linkedin.com/in/semilhalani](https://linkedin.com/in/semilhalani) · semilhalani192@gmail.com

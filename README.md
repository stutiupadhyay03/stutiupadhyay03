# Stuti Upadhyay

**AI Engineer · Data Scientist · Sports Analyst** — Chantilly, VA

I build things that actually run in production. Right now that means a multi-modal AI health monitoring system at Ampcus (computer vision + voice + sensor fusion, validated fall detection at precision 1.0), production agentic AI across two platforms and two client engagements, and a 7-agent financial intelligence platform I built on the side to understand how multi-agent systems actually behave under real data conditions.

I also wrote nine published sports analytics pieces covering the EPL 2023 season and did quantitative player performance analysis in grad school — which is what happens when you care about cricket, football, F1, and tennis and also know how to run a regression.

M.P.S. in Data Science from UMBC (GPA 3.67, December 2025). F-1 OPT, open to sponsorship.

---

## What I am working on

**ACTS — AI Caregiver Tracking System** `Ampcus · 2026`  
Multi-modal health monitoring built for the ACL Caregiver AI Prize Challenge. Three data streams: computer vision (YOLOv8-Pose) for fall detection and gait, voice transcription for interaction logging, CNN-LSTM sensor fusion for medication adherence and sleep. Fall detection validated at precision 1.0000 · recall 0.9286 · F1 0.9630 on a 25-scenario benchmark. Corroboration engine 50/50. Docker, GitHub Actions, Claude Code throughout.

**AAIP — Agentic AI Pilot Program** `Ampcus · 2026`  
Program Consultant designing and co-building production multi-agent systems for small business clients across a two-client cohort spanning two platforms. Client 1 (Salesforce Agentforce): fully operational government procurement monitoring agent with SAM.gov API integration, 3-tier instruction architecture, HITL Mode 3 checkpoint, escalation subagent, audit logging to custom Salesforce objects, and confidence-threshold-based guardrails. Client 2 (AWS Bedrock AgentCore): document-to-decision agent parsing inbound business documents, extracting structured fields, drafting output records for account manager review, with HITL Mode 3 approval routing and audit logging. Both Sprint 1 and Sprint 2 confirmed across both engagements.

---

## Projects

| | Project | What it actually does |
|---|---|---|
[Finance Based Agent](https://github.com/stutiupadhyay03/Finance_Based_Agent) | 7-agent financial intelligence system. Stock Analyst, Portfolio Manager, Macro Analyst, Sentiment Analyst and more — each with distinct role, tools, and temperature. 12 custom yfinance tools, Gemini 2.5 Pro via Vertex AI. Built to understand how multi-agent coordination breaks down under real market data. |
[Anomaly Detection Capstone](https://github.com/stutiupadhyay03/AnomalyDetection_Capstone) | Production CV pipeline: YOLOv8 object detection + ResNet18 anomaly classification + CSRNet crowd density. MAE 31.18 on ShanghaiTech Part B. Loss 92.17 → 68.76. [Live Streamlit demo](https://anomalydetectioncapstone-aagua27sjxluyvjretnrul.streamlit.app). |
[EPL Player Performance Analysis](https://github.com/stutiupadhyay03) | Full EDA and linear regression on EPL 2021-22 player stats. Goals-assists correlation by position, top scorer analysis, model to predict goal output from assists, card rates, and age. Key finding: midfielders show the widest variance — projection uncertainty is highest there. UMBC DATA601. |
[Financial Anomaly Detection](https://github.com/stutiupadhyay03/Financial-Anomaly-Detection) | Isolation Forest on 4 years of MSFT stock data + Monte Carlo simulation (1,000 paths, 252-day horizon). Top detected anomalies all map to COVID-19 crash dates Feb–Mar 2020. UMBC DATA690. |
[Maryland Healthcare Equity](https://github.com/stutiupadhyay03/Maryland-Healthcare-Equity) | Epidemiological study across all 24 Maryland counties. t-tests, ANOVA, regression, chi-square, Kruskal-Wallis with full assumption testing. Urban-rural gap: p=0.008, Cohen's d=0.76. 1,404-fold disparity Baltimore vs Somerset. UMBC DATA608. |
[Spotify Streaming Analytics](https://github.com/stutiupadhyay03/Spotify-Streaming-Analytics) | PySpark on Databricks processing ~9M records (1.46 GB). GraphFrames PageRank for artist collaboration network. The Weeknd: 9.88B streams. Rank-streams correlation r=−0.13. UMBC DATA603. |

---

## Skills

**AI and agents** — CrewAI · LangChain · LangGraph · Salesforce Agentforce · AWS Bedrock AgentCore · RAG · HITL design · prompt engineering · multi-agent architecture

**ML and deep learning** — PyTorch · TensorFlow · Scikit-learn · Hugging Face · YOLOv8 · CNN · LSTM · NLP · computer vision

**Data and cloud** — PySpark · Databricks · GraphFrames · AWS (Lambda, S3, EC2, DynamoDB, Bedrock) · GCP (Vertex AI, Dataproc, BigQuery) · Azure Data Factory

**Statistics** — hypothesis testing · regression · ANOVA · Monte Carlo simulation · anomaly detection · time series · effect size estimation · R (spatial regression, spdep)

**Languages and tools** — Python · SQL · R · JavaScript · Flask · Streamlit · Docker · Git · GitHub Actions · Claude Code

---

## Sports writing

Nine analytical pieces published on [GoWorldWide](https://goworldwide.co.in) covering the EPL 2023 season and UEFA Champions League. Transfer market analysis, tactical breakdowns, career trajectory modeling. Byline: Stuti.

Selected: [Harry Kane — Beyond Trophies](https://goworldwide.co.in/harry-kane-transfer-from-spurs-to-bayern-munich/) · [Brighton 3-1 Man United at Old Trafford](https://goworldwide.co.in/epl-23-brighton-conquers-old-trafford/) · [Bellingham's UCL winner vs Union Berlin](https://goworldwide.co.in/real-madrids-secure-victory-over-union-berlin/)

---

## Education

**M.P.S. Data Science** — UMBC · GPA 3.67 · December 2025  
Coursework: Applied NLP · Big Data Processing (PySpark/Databricks) · Data Engineering · AI · Data Science in Finance · Probability and Statistics · Introduction to Data Science (EPL statistical analysis)

**B.Tech Computer Science and Engineering** — GSFC University, India · GPA 3.3 · May 2023  
Specialization: Data Science, AI and ML

**Certifications** — IBM RAG and Agentic AI (9 courses, March 2026) · Transformer Models and BERT (Google Cloud) · Neural Networks and Deep Learning (deeplearning.ai)

---

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=netlify&logoColor=white)](https://stuti-s-upadhyay-portfolio.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/stuti-s-upadhyay)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:stutiupadhyay70@gmail.com)

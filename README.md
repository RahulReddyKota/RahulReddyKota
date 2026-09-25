<p align="center">
  <img src="banner.svg" width="100%" alt="Rahul Reddy Kota. Blueprint of a data pipeline flowing from raw data through transform and training into production." />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rahul-reddy-kota-b55a3a251/"><img src="https://img.shields.io/badge/LinkedIn-12355B?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI0Y1QTUyNCI%2BPHBhdGggZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMSAxIDAtNC4xMjUgMi4wNjIgMi4wNjIgMCAwIDEgMCA0LjEyNXpNNy4xMTkgMjAuNDUySDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAweiIvPjwvc3ZnPg%3D%3D" alt="LinkedIn" /></a>
  <a href="https://rahulreddykota.github.io/"><img src="https://img.shields.io/badge/Portfolio-12355B?style=for-the-badge&logo=githubpages&logoColor=F5A524" alt="Portfolio" /></a>
  <!-- To add email, uncomment and replace the address:
  <a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-12355B?style=for-the-badge&logo=gmail&logoColor=F5A524" alt="Email" /></a>
  -->
</p>

## Spec sheet

```yaml
# rahul-reddy-kota
role: Data scientist and ML engineer
location: Baltimore, MD

education:
  - M.S. Data Science, UMBC (Dec 2026)
  - B.Tech Computer Science, SNIST (2023)

experience:
  - where: UMBC Data Analytics Lab
    role: Research assistant (2025 to now)
    impact: 40% less manual preprocessing for faculty research
  - where: Accenture, Hyderabad
    role: Data analyst (2022 to 2024)
    built: Post-merger migration into a Databricks Lakehouse
    impact: 25% less manual effort through Tableau KPI dashboards

certified:
  - AWS Certified Cloud Practitioner
  - Microsoft Power BI Data Analyst Associate
  - Google Data Analytics Professional Certificate

learning_now: [LLM fine-tuning, distributed systems, cloud-native design]
open_to: [Data scientist, ML engineer, Data analyst, SWE, Solutions architect]
```

<img src="divider.svg" width="100%" alt="" />

## Toolkit, by pipeline stage

| Stage | Tools |
| --- | --- |
| **① Ingest** | <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb" height="36" alt="PostgreSQL, MySQL, MongoDB" /><br>Cosmos DB, Snowflake, Kafka |
| **② Transform** | <img src="https://skillicons.dev/icons?i=azure,aws" height="36" alt="Azure, AWS" /><br>Apache Spark (PySpark), Hadoop, Hive, Azure Databricks, AWS EMR, Oracle Data Integrator |
| **③ Train** | <img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,sklearn" height="36" alt="Python, TensorFlow, PyTorch, scikit-learn" /><br>Keras, Hugging Face, FinBERT, ChromaDB, Ollama |
| **④ Ship** | <img src="https://skillicons.dev/icons?i=docker,git,flask,react" height="36" alt="Docker, Git, Flask, React" /><br>Azure DevOps, CI/CD, Power BI, Tableau, Jira |
| **Languages** | <img src="https://skillicons.dev/icons?i=python,java,scala,js,bash" height="36" alt="Python, Java, Scala, JavaScript, Bash" /><br>SQL |

<img src="divider.svg" width="100%" alt="" />

## Shipped projects

<table>
<tr>
<td width="50%" valign="top">

### [DermaFusion](https://github.com/RahulReddyKota/DermaFusion)
Classifies dermoscopic images from HAM10000 using ResNet50 and VGG16 transfer learning. Grad-CAM heatmaps show which part of each lesion drove the prediction.

![val_acc](https://img.shields.io/badge/val__acc-90%25%2B-F5A524?style=flat-square&labelColor=12355B)
![classes](https://img.shields.io/badge/lesion__types-7-F5A524?style=flat-square&labelColor=12355B)
![award](https://img.shields.io/badge/recognized-AI%20RADA%20%26%20Healthcare%202026-7FD6A4?style=flat-square&labelColor=12355B)

<sub>TensorFlow · Keras · OpenCV · Grad-CAM</sub>

</td>
<td width="50%" valign="top">

### [ARC AI](https://github.com/RahulReddyKota/ARC-AI-Augmented-Reasoning-Core)
Answers Maryland tenant and landlord questions with citations back to official sources. Runs locally and switches between three open models in real time.

![sources](https://img.shields.io/badge/sources-7%20official-F5A524?style=flat-square&labelColor=12355B)
![models](https://img.shields.io/badge/local__LLMs-Llama%20%7C%20Mistral%20%7C%20Qwen-F5A524?style=flat-square&labelColor=12355B)
![eval](https://img.shields.io/badge/evaluated-citations%20%26%20hallucinations-7FD6A4?style=flat-square&labelColor=12355B)

<sub>Python · ChromaDB · Ollama · sentence transformers</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Job Market Analysis
Processes millions of raw job postings on AWS EMR, then surfaces skill demand, salary benchmarks, and regional hiring patterns in Power BI.

![scale](https://img.shields.io/badge/scale-millions%20of%20postings-F5A524?style=flat-square&labelColor=12355B)
![storage](https://img.shields.io/badge/storage-partitioned%20ORC-F5A524?style=flat-square&labelColor=12355B)

<sub>PySpark · Hive · AWS EMR · S3 · Power BI</sub>

</td>
<td width="50%" valign="top">

### Trading on Trends
Predicts next-day stock direction by combining FinBERT sentiment on headlines with RSI, MACD, and Bollinger Band signals.

![signals](https://img.shields.io/badge/signals-sentiment%20%2B%20technicals-F5A524?style=flat-square&labelColor=12355B)
![models](https://img.shields.io/badge/benchmark-LSTM%20vs%20Random%20Forest-F5A524?style=flat-square&labelColor=12355B)

<sub>Python · FinBERT · LSTM · SQL</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Cyberbullying Detection
Sorts messages into six categories with a Bi-LSTM on GloVe embeddings, beating SVM and Naive Bayes baselines on macro F1.

![classes](https://img.shields.io/badge/classes-6-F5A524?style=flat-square&labelColor=12355B)
![beats](https://img.shields.io/badge/beats-SVM%20%26%20Naive%20Bayes-7FD6A4?style=flat-square&labelColor=12355B)

<sub>TensorFlow · Keras · Bi-LSTM · GloVe</sub>

</td>
<td width="50%" valign="top">

### Your project here
Working on something in healthcare AI, RAG, or big data? I'm looking for the next pipeline to build.

[Message me on LinkedIn](https://www.linkedin.com/in/rahul-reddy-kota-b55a3a251/)

</td>
</tr>
</table>

<p align="center">
  <img src="footer.svg" width="100%" alt="Approved to ship. Let's build something that ships." />
</p>

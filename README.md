# Sandeep Manoharan

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

Backend and AI engineer. I build Python services, the data pipelines that feed them, and the cloud infrastructure they run on, mostly for RAG and GraphRAG systems.

Recent work: a customer support assistant that answers from a Bedrock-backed vector store on AWS, a compliance pipeline that reads pull request diffs against security controls, and a real-time traffic pipeline that enriches 1.8M road segments.

## Toolbox

Python, FastAPI, PostgreSQL and pgvector, Docker, GitHub Actions, AWS (Bedrock, EC2, S3, ALB, IAM). React, Next.js and TypeScript when a project needs a front end. Earlier work was data integration with Oracle BIP and ODI.

## Projects

### smart-help-desk-aws

RAG customer support assistant built end to end. A FastAPI service calls Amazon Bedrock for answers, pgvector handles retrieval, and the whole thing runs on EC2 behind an Application Load Balancer. Guardrail tests included.

Python, FastAPI, Amazon Bedrock, pgvector, EC2, ALB, S3

### enterprise-intelligence-agent

GraphRAG compliance pipeline. It reads GitHub PR diffs and checks them against OWASP ASVS v4 and NIST 800-53 Rev5, so a code change gets measured against the controls it might affect.

Python, GraphRAG, LLM pipelines

### smartcity-nyc-traffic-pipeline

Real-time traffic pipeline for New York. Pulls TomTom API data, enriches 1.8M OpenStreetMap road segments using H3 indexing, and drives Slack alerts and dashboards. Layered Bronze, Silver and Gold, with benchmarked optimisations on the enrichment step.

Python, H3, OpenStreetMap, streaming and batch

## Contact

Vancouver, BC

sandeepmanoharan1@gmail.com

LinkedIn: https://www.linkedin.com/in/sandeep-manoharan-5bb81981/

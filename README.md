# Sandeep Manoharan

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

### medical-voice-tester

Test harness for voice prompts. Scripted scenarios, saved transcripts and recordings, a prompt iteration log and a bug report, so a change to a prompt can be measured instead of guessed at.

Python, prompt evaluation

### smart-help-desk-frontend

The front end for the help desk, deployed on Vercel.

HTML, Vercel

## Contact

Vancouver, BC

sandeepmanoharan1@gmail.com

LinkedIn: https://www.linkedin.com/in/sandeep-manoharan-5bb81981/

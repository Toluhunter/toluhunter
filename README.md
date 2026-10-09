# Hi, I'm Tolulope Fakoya (Hunter)

I'm a **DevOps and platform engineer** with 5+ years on AWS. I like infrastructure that's boring
in the best way: it deploys itself, scales when it should, tells you before it breaks, and doesn't
quietly double the bill. Day to day that means Terraform, CI/CD, release engineering,
observability, cost optimization, and lately, getting agentic LLM systems production-ready.

**Open to:** platform, DevOps, site reliability, cloud and AI engineering roles. Contract and
contract-to-hire. Toronto, remote friendly.

[![Website](https://img.shields.io/badge/toluhunter.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://toluhunter.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg)](https://linkedin.com/in/tolulope-fakoya) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:toluhunterdev@gmail.com) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/tolu_hunter)

## Certifications

<p>
  <a href="https://www.credly.com/badges/903530ff-d305-4c6f-8edf-7c459cea45fc"><img src="https://assets.toluhunter.com/certifications/aws-certified-devops-engineer-professional.png" alt="AWS Certified DevOps Engineer – Professional" title="AWS Certified DevOps Engineer – Professional" height="100"></a>
  <a href="https://www.credly.com/badges/07e8216c-1aa2-4d75-847a-c5442d73462e"><img src="https://assets.toluhunter.com/certifications/aws-certified-solutions-architect-associate.png" alt="AWS Certified Solutions Architect – Associate" title="AWS Certified Solutions Architect – Associate" height="100"></a>
  <a href="https://www.credly.com/badges/51d36c94-97ce-4d4c-b286-f98a769f2e71"><img src="https://assets.toluhunter.com/certifications/aws-certified-machine-learning-specialty.png" alt="AWS Certified Machine Learning – Specialty" title="AWS Certified Machine Learning – Specialty" height="100"></a>
  <a href="https://www.credly.com/badges/b41ec3b7-e89b-425a-9a27-1acab75c06f5"><img src="https://assets.toluhunter.com/certifications/comptia-security-ce-certification.png" alt="CompTIA Security+ ce" title="CompTIA Security+ ce" height="100"></a>
  <a href="https://www.credly.com/badges/89c54739-c2c5-4fc0-8bcc-832192d9191d/public_url"><img src="https://assets.toluhunter.com/certifications/certified-in-cybersecurity-cc.png" alt="ISC2 Certified in Cybersecurity (CC)" title="ISC2 Certified in Cybersecurity (CC)" height="100"></a>
</p>

## Impact

- Led AWS migrations for **25+ clients**, cutting each client's monthly AWS bill by about **25%**.
- Cut AWS spend **55%** with Reserved and Spot Instances, then serverless refactors.
- Replaced manual SSH deploys with CI/CD: release time from **20–30 min to 5–7 min**.
- Introduced Terraform to teams that provisioned by hand: environment setup from **a day to 15 minutes**.
- Moved breach detection from user reports to metric alerting on Prometheus and Grafana:
  **30–60 min to 1–5 min**, halving total downtime.

## Selected work

- **[guarded-agentic-chatbot](https://github.com/Toluhunter/guarded-agentic-chatbot)**:
  LangGraph agent with two-layer prompt-injection guardrails inside the graph, on input and
  output. Two Terraform deployment tiers: ECS, RDS (pgvector) and ElastiCache on AWS, or a
  single $24/month server. Load tested at 100 concurrent sessions. Bedrock, OpenAI, Gemini or
  Ollama behind one interface, with Phoenix tracing. It runs the assistant on my site.
- **[Terraform-Lambda-Blue-Green-Canary-No-Codedeploy](https://github.com/Toluhunter/Terraform-Lambda-Blue-Green-Canary-No-Codedeploy)**:
  serverless API (API Gateway, Lambda, DynamoDB) in Terraform, with a reusable Lambda module
  that publishes versions behind a live alias for blue/green releases without CodeDeploy.
- **[portfolio](https://github.com/Toluhunter/portfolio)**: [toluhunter.com](https://toluhunter.com),
  built and run end to end: TypeScript front end, backend API, infrastructure and CI/CD.
- **[LocalRAGify](https://github.com/Toluhunter/LocalRAGify)**: zero-cost local RAG chatbot
  with OpenSearch retrieval and Ollama, packaged with Docker Compose.

## Stack

**Cloud and IaC:** AWS (EC2, ECS, Lambda, API Gateway, RDS, DynamoDB, S3, VPC, IAM, CloudWatch, Bedrock), GCP, Terraform, Ansible

**CI/CD and runtime:** GitHub Actions, Jenkins, CodePipeline, CodeBuild, CodeDeploy, Docker, Linux, Kubernetes (CKA in preparation)

**Observability and security:** Prometheus, Grafana, CloudWatch, Phoenix LLM tracing, Wazuh, IAM least privilege

**AI infrastructure:** LangGraph, RAG with pgvector, guardrails and evaluation suites, Bedrock, OpenAI, Gemini, Ollama

**Languages:** Python, Go, TypeScript, Bash, PowerShell, SQL

---

<sub>Off the clock: storytelling and story-driven games like NieR: Automata and The Witcher 3.</sub>

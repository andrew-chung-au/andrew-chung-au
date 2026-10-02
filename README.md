# Andrew Chung

**AI Engineer building evaluated, evidence-first RAG and agent systems for security-minded and regulated organisations.**

I spent over a decade in higher education in Hong Kong, delivering technical projects at the Hong Kong University of Science and Technology and teaching at City University of Hong Kong. Seeing how quickly AI was developing, I decided to move into the field and build with it myself.

My technical foundation is in cyber security, through a Certificate IV that included a penetration test and a red, blue and purple team exercise. That led into cloud, which I took further by earning the AWS Certified Solutions Architect – Associate.

Alongside that, and since, I've been building AI and data projects. Most are retrieval-augmented generation (RAG) systems in Python, PostgreSQL and AWS, each benchmarked and with its limits documented, and two apply RAG to security work: navigating Australian AI-security guidance and mapping incidents to MITRE ATT&CK techniques. I also finished 2nd of 2,000+ learners in the LLM Zoomcamp.

I'm based in Melbourne, Australia, and open to AI Engineer and cyber security (threat analysis) roles, on-site, hybrid or remote.

[LinkedIn](https://www.linkedin.com/in/andrewchung-cloudai/)

## How I work

- **Evaluation-driven.** In my RAG projects, I benchmark different retrieval approaches, record why I chose a configuration, and document known limitations alongside the results.
- **Considered use of AI tools.** I use AI coding tools where they help, and do more of the work by hand when I'm learning or practising a skill. When I use a coding agent, I work from a written specification and review and test its output.
- **Reproducible environments.** My RAG projects include Docker Compose setups, pinned dependencies and runbooks, so results can be rebuilt and checked.

## Featured projects

| Project | What it does | How it was evaluated | Key result | Status |
|---|---|---|---|---|
| DER RegCheck | RAG assistant for energy-regulation research. Answers carry citations and are rejected if a citation can't be verified. | 100-query benchmark, 5 retrieval methods compared, LLM-as-a-judge plus blinded human review | Full RAG preferred in 9 of 10 blinded comparisons against the same prompt without evidence | Evaluated; trialled on AWS EC2 |
| Cyber Threat Identifier | Maps incident narratives to likely MITRE ATT&CK techniques with two-stage retrieval | 226 expert-derived cases, pairwise LLM-as-a-judge plus blinded human review | Reranking lifted top-3 hit rate from 35% to 42% over vector search | Evaluated; trialled on AWS EC2 |
| AUS AI Security Navigator | Audience-aware RAG over Australian Cyber Security Centre AI-security guidance, filtered by organisation size and role | 27-question benchmark, 4 retrieval methods compared, latency and cost monitoring | Reranking raised exact-passage MRR from 0.75 to 0.89 | Evaluated; trialled on AWS EC2 |
| Amadeus MCP Server | Extension of an open-source MCP server with a fallback engine for API failure, on Terraform-provisioned AWS | Not benchmarked; a deployment and security exercise | On-demand deploy and teardown, localhost behind an SSH tunnel, Secrets Manager and least-privilege IAM | AWS (Terraform) |
| Table Ready | Restaurant waitlist app (FastAPI, PostgreSQL, Docker) built with Claude Code from my spec and under my review | API, integration and browser tests; containerised migrations | Test gate blocks agents from finishing while tests fail | Not yet deployed |

## Tech I work with

Python · SQL · PostgreSQL · pgvector · RAG · LLM evaluation · Agents and MCP · FastAPI · AWS · Terraform · Docker · Linux · Git · Streamlit · Claude Code

## Credentials

- AWS Certified Solutions Architect – Associate
- LLM Zoomcamp 2026 (DataTalksClub): 2nd of 2,000+ enrolled learners
- AI Engineer for Developers Associate (DataCamp)
- Certificate IV in Cyber Security (Holmesglen)
- Python Developer Certification (freeCodeCamp)
- Microsoft Azure AI Fundamentals

## Get in touch

Message me on [LinkedIn](https://www.linkedin.com/in/andrewchung-cloudai/).

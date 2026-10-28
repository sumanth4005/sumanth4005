# Hi, I'm Sumanth Manthena

**AI engineer in financial services: RAG, agents and LLM evaluation, in Python.** Ex-JPMorgan Chase, Cetera Financial Group and Deloitte. PhD student in Enterprise Systems.

At JPMorgan I worked on an internal AI assistant handling 1.2M+ conversations a month: agent workflows that call internal APIs and recover from errors, retrieval tuning, and the evaluation framework every release had to pass. Task completion went from 68% to 87% and hallucinations dropped 38%. The projects below are public, smaller versions of that kind of work.

## Projects

| Project | What it shows | Stack |
|---|---|---|
| [**BankBuddy: RAG banking chatbot**](https://github.com/sumanth4005/bankbuddy-chatbot) · [live demo](https://bankbuddy-chatbot.streamlit.app) | Semantic search + Gemini answering only from retrieved FAQs, PII blocking, human handoff. 83% top-1 / 97% top-3 retrieval on unseen questions | Python, sentence-transformers, Gemini API, Streamlit |
| [**LLM eval harness**](https://github.com/sumanth4005/llm-eval-harness) | Go/no-go release gate for two chatbot versions: correctness, groundedness (hallucinated numbers), PII leaks, refusals. v1 NO-GO, v2 GO | Python (standard library), unittest |
| [**RAG retrieval evaluation**](https://github.com/sumanth4005/rag-retrieval-eval) | TF-IDF, BM25 and hybrid retrievers built from scratch; hit@1, hit@3 and MRR on 60 paraphrased questions, with error analysis | Python, NumPy |
| [**Demand forecasting & anomaly detection**](https://github.com/sumanth4005/demand-forecasting-anomaly-detection) | Leak-free time-series features, model comparison vs a seasonal baseline (15% lower RMSE), residual-based anomaly flags, drift check | Python, pandas, scikit-learn |
| [**Banking chatbot pre-launch testing**](https://github.com/sumanth4005/banking-ai-chatbot) | 50-question test plan scoring accuracy, hallucination and tone, with a go/no-go recommendation | Evaluation design |
| [**AI customer review intelligence**](https://github.com/sumanth4005/AI-Customer-Review-Intelligence) | 37,427 Google Play reviews: 36% negative rate for games vs 22% overall, turned into prioritised user stories | Python, pandas, Jupyter |

## What I work with

- **LLM apps:** RAG (chunking, embeddings, vector search), agents and tool calling, prompt design, guardrails, Azure AI Foundry, Gemini API
- **Evaluation:** test sets, groundedness and hallucination checks, PII and safety checks, release gates, monitoring
- **ML & data:** Python, SQL, pandas, NumPy, scikit-learn, forecasting, anomaly detection, Snowflake, Spark
- **Shipping:** REST APIs, Git, Docker, CI/CD, Streamlit

## Experience

- **AI Product Analyst**, JPMorgan Chase (2025–2026)
- **Software Engineer**, Cetera Financial Group (2024–2025)
- **Software Engineer**, Deloitte (2021–2022)

## Education

- PhD, Enterprise Systems, Wayland Baptist University (in progress)
- MS, Information Systems, Trine University

📫 [LinkedIn](https://www.linkedin.com/in/sumanth-manthena) · sumanthrdy4005@gmail.com

# Hey, I'm Sanskaar 👋

I build full-stack apps with AI in them, from model to deployment.
B.Tech in Electronics and Communication with an AI minor, MAIT (2026).

Currently an **AI Engineer Intern at Durbeen Fintech**, where I ship production financial tooling.

---

### What I'm working on

**Durbeen Fintech** | AI Engineer Intern
`Next.js 16` `React 19` `FastAPI` `SQLAlchemy` `Postgres` `TypeScript` `Docker`

- Shipped a full-stack financial planning platform with 5 interactive calculators, used company-wide and deployed on Vercel and Railway
- Ported the authoritative Python calculation engine to client-side TypeScript and validated both against shared test vectors, so on-screen figures provably match the backend
- CI gate on GitHub Actions (18 automated tests plus type checking) that caught a missing production dependency before it shipped
- 5-stage LLM pipeline turning an uploaded portfolio into a narrated report, orchestrating 2 NVIDIA NIM models with token-streamed NDJSON/SSE to the browser
- Self-hosted n8n automation in Docker that scrapes and parses news sources into a structured headline feed used daily by the social media team

---

### Projects

### 📚 [VaultFlow.ai](https://github.com/Ghosty032/Vaultflow-ai)
Multi-format AI knowledge base and learning roadmap generator
`Next.js` `FastAPI` `Supabase` `pgvector` `NVIDIA NIM` `NetworkX`

- Ingests 7 file types (PDF, DOCX, PPTX, VTT, Markdown, YouTube, web articles) plus Google Drive OAuth import
- RAG over heterogeneous academic material using pgvector, matching concepts across documents that use different terminology
- Multimodal agent interprets diagram-only slides, turning visuals into knowledge graph nodes
- Auto-generates prerequisite learning roadmaps with NetworkX, pointing to exact pages, slides and timestamps

### 🛍️ [FashAr-V2](https://github.com/Ghosty032/FashAr-V2)
AI styling and outfit recommendation platform
`Next.js` `FastAPI` `LangGraph` `NVIDIA NIM` `Pinecone` `RAG`

- Multimodal vision pipeline using Qwen2.5-VL-72B to extract clothing metadata from images, sub-10-second analysis
- RAG over a live fashion catalog via Pinecone for shoppable, context-aware recommendations
- 40% reduction in API payload size via automated base64 compression without losing visual fidelity
- Multi-stage LangGraph workflow enforcing strict state transitions, eliminating LLM drift

### 🧠 [Retinal OCT Classifier](https://github.com/Ghosty032/retinal-oct)
Deep learning model for early retinal disease detection
`Python` `CNN` `TensorFlow` `Flask` `Tailwind CSS`

- 92% accuracy on CNV, DME and DRUSEN classification from OCT scans
- Handled class imbalance with SMOTE and custom loss functions, with meaningful F1 gains on minority classes
- Clinical dashboard with secure file upload, replacing a Streamlit prototype for better workflow fit

---

### Stack

**Languages:** Python · TypeScript · JavaScript · Java · SQL
**AI/ML:** RAG pipelines · LangGraph · NVIDIA NIM · Transformers · CNNs · TensorFlow · Scikit-learn
**Backend:** FastAPI · Flask · SQLAlchemy · Postgres
**Frontend:** Next.js · React · Tailwind CSS
**Data:** Supabase · pgvector · Pinecone · PostgreSQL · Pandas · NumPy · NetworkX
**Infra & Tools:** Docker · GitHub Actions · n8n · Vercel · Railway · Git · Jupyter · VS Code

---

### Connect

Open to software engineering roles. Happy to talk about what I'm building or what you're working on.

- 📧 tsanskaar@gmail.com
- [LinkedIn](https://www.linkedin.com/in/sanskaar-thukral-128118253/)
- [Portfolio](https://portfolio-website-wheat-delta.vercel.app/)

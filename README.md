# Hi, I'm Keith 👋

Software Engineering student at Rochester Institute of Technology, building AI applications, developer tools, and full-stack software.

## About Me
- 🎓 B.S. Software Engineering at RIT, with anticipated minors in Artificial Intelligence and Finance
- 🤖 President of the RIT AI Club (GCCIS-affiliated) — leading sponsorship outreach, guest speakers, and member programming
- 🧠 Interested in AI/ML, software engineering, and full-stack development
- 🛠️ Building practical software that combines AI with real-world applications
- 💼 Seeking a Summer 2027 Software Engineering or AI internship

## Featured Projects

### 🧠 [CramAI](https://cram-ai.vercel.app)
**AI-powered study platform that turns course material into flashcards, quizzes, and summaries.**

A deployed full-stack application: upload a PDF, DOCX, TXT, or Markdown file and get back generated study material backed by a real spaced-repetition system.

- **FSRS-4.5 scheduling** — the same algorithm behind modern Anki, modeling each card's memory stability and difficulty to reach target retention with roughly 20–30% fewer reviews than SM-2.
- **Cost-engineered generation** — flashcards, quizzes, and summaries come from a single combined AI call (~3× cheaper than fanning out per content type), and review, quiz, and CSV import/export flows use no AI tokens at all.
- **Production hardening** — fail-closed authentication, per-user quotas, rate limiting, and a budget-reservation guard that refuses generation rather than spending unmetered.
- **Four-job CI pipeline** — backend and frontend test suites, dependency audits, and a database security suite that applies the deployed schema to a live PostgreSQL instance to verify privileges, quotas, and concurrent budgets.

**Tech:** React · Vite · Tailwind · FastAPI · Supabase · PostgreSQL · OpenAI API · Vercel · Railway · pytest · Vitest

🔗 **[Try CramAI](https://cram-ai.vercel.app)**
> Source code is currently private.

---

### 📈 [FinRobot](https://github.com/RIT-AI-Club/FinRobot)
**Multi-model research agent that turns a stock ticker into a print-ready PDF equity report.**

An RIT AI Club team project. A Gemini orchestrator runs an agentic tool-call loop over three MCP servers: Perplexity for live research, Matplotlib for price charts, and Claude for report layout, with Playwright printing the final document.

I built the **report-formatting MCP server** end to end — prompt design, the Claude and Gemini clients, chart injection, and the HTML-to-PDF pipeline. One design detail I'm fond of: rather than sending chart images to the model (~67K input tokens each), the client passes only captions and placeholder tokens, and the server swaps in the real images after generation.

Presented to 200–300 attendees at ImagineRIT 2026.

**Tech:** Python · FastAPI · React · MCP · Gemini · Claude · Perplexity · Playwright · Matplotlib · yfinance

🔗 **[View Repository](https://github.com/RIT-AI-Club/FinRobot)**

---

### 🎬 [CineML](https://github.com/knicolosi313/CineML)
**Progressive machine learning project covering classical ML, NLP, deep learning, and recommendation systems using movie datasets.**

A self-directed run through the ML lifecycle, with every stage on the same 5,000-movie dataset instead of a toy dataset per topic: data wrangling and EDA, supervised and unsupervised learning, scikit-learn pipelines with model persistence, TF-IDF sentiment and multi-label genre classification, and PyTorch neural networks and LSTMs. Recommendation systems are in progress.

**Tech:** Python · PyTorch · scikit-learn · pandas · NumPy · matplotlib · seaborn · Jupyter · NLP

🔗 **[View Repository](https://github.com/knicolosi313/CineML)**

---

### 🌐 [Personal Portfolio](https://keithnicolosi.com)
**Personal portfolio built from scratch with HTML, CSS, and JavaScript.**

Focused on responsive design, accessibility, performance, and custom visual effects.

**Tech:** HTML · CSS · JavaScript

🌐 **[Visit Portfolio](https://keithnicolosi.com)**
🔗 **[View Repository](https://github.com/knicolosi313/knicolosi313.github.io)**

## Technologies
**Languages:** Python · Java · C · JavaScript · HTML · CSS
**AI / ML:** PyTorch · scikit-learn · Model Context Protocol (MCP) · LLM APIs · NLP
**Data:** pandas · NumPy · matplotlib · seaborn · Jupyter
**Web & Tools:** React · FastAPI · Supabase · PostgreSQL · Git · GitHub Actions · pytest · Playwright · VS Code

## Connect
🌐 [keithnicolosi.com](https://keithnicolosi.com)
💼 [LinkedIn](https://www.linkedin.com/in/keith-nicolosi313/)

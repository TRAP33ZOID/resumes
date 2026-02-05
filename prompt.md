# Resume Generation Prompt

I need help optimizing my resume to secure interviews for technical positions.

**IMPORTANT:** Provide the complete, compilable LaTeX code including the full preamble (document class, packages, command definitions) AND the document body content. Do NOT omit the preamble sections.

---

## [PASTE JOB DESCRIPTION HERE]

---

## Instructions

Please update my resume by:

1. Identifying key technical skills, tools, and requirements from the job description
2. Creating compelling experience bullet points that demonstrate these skills
3. Developing a comprehensive skills section aligned with the job requirements
4. Including specific technologies and quantifiable achievements that match the role
5. Updating my professional title if needed to better align with the position
6. Keeping language concise but impactful
7. Do NOT regurgitate the job description and sound generic. Sound human, showcase my unique voice and show that I have done my research. DO NOT COME OUT AS FAKE. Make experience and projects section realistic.
8. **CRITICAL:** I have mid-level software engineering skills despite being a student. I have been building and shipping production systems for a bit

---

## My Background & Skill Level

**Academic Background:**

### Bachelor of Computer Engineering (Toronto Metropolitan University, May 2026)
**Core Skills Gained:**
- Computer Architecture & Digital Systems (Verilog, FPGA, embedded systems)
- Data Structures & Algorithms (O(n) analysis, graph theory, dynamic programming)
- Operating Systems (process management, memory allocation, concurrency)
- Computer Networks (TCP/IP, HTTP/HTTPS, WebSockets, network protocols)
- Database Systems (SQL, normalization, indexing, query optimization)
- Software Engineering (design patterns, OOP, testing, CI/CD)
- Real-time Systems (scheduling algorithms, embedded C)


### Diploma of Data Science (Lighthouse Labs, Oct 2023)
**Core Skills Gained:**
- Machine Learning (supervised/unsupervised learning, feature engineering)
- Statistical Analysis (hypothesis testing, confidence intervals, regression)
- Data Pipelines (ETL processes, data cleaning, pandas, NumPy)
- Data Visualization (Tableau, matplotlib, seaborn)
- Database Management (PostgreSQL, query optimization)
- Python for Data Science (pandas, scikit-learn, Jupyter)

**Key Projects:**
- Customer churn prediction using ensemble methods (85% accuracy)
- SQL-based e-commerce analytics pipeline
- Statistical modeling of bike-sharing demand patterns
- Diabetes prediction using supervised learning algorithms

---

## Contact Information

```
Website: waleedahmed.ca
Email: hello@waleedahmed.ca
LinkedIn: linkedin.com/in/waleed-ahmed-8396a1187
GitHub: github.com/TRAP33ZOID
Location: Toronto, ON, Canada
Phone: 437-450-9195
```

---

## Experience Section

**Select 2-3 experiences based on job fit:**

**IMPORTANT:** When using ZoidAI as a company, make it a clickable link to https://zoid.ca using:
```latex
\vspace{5pt}\cvevent{ROLE}{\href{https://zoid.ca}{ZoidAI}}{DATE}{}
```

### 1. ZoidAI - Co-Founder & CTO (September 2025 - Present)
**CONTEXT:** This is my main SaaS product—a multi-tenant AI voice agent platform for dental clinics. I built this from scratch and it is currently in production at zoid.ca. 

**Technical Architecture:**
- **Framework:** Next.js 14 with App Router, React, TypeScript
- **Database:** PostgreSQL (Supabase) with Row-Level Security (RLS), pgvector for embeddings
- **Voice/AI:** VAPI.ai for phone calls, Google Gemini for text chat, custom RAG pipeline
- **Payments:** Stripe integration with subscription management, webhooks, billing portal
- **Auth:** Supabase Auth with multi-tenant organization support
- **Infrastructure:** Vercel for deployment, serverless functions, edge middleware
- **Testing:** Vitest for unit testing

**Key Features Built:**
- **Multi-tenant SaaS architecture** with complete data isolation per clinic using PostgreSQL RLS policies
- **Dual knowledge base system:** Files sync to both VAPI for phone calls and pgvector for text chat RAG
- **Real-time call handling:** WebSocket-based voice testing, webhook processing for live calls
- **Pay-as-you-go billing:** Credit system with usage tracking, Stripe checkout, customer portal
- **Admin dashboards:** Call analytics, cost tracking, usage monitoring, tenant management
- **Document ingestion:** PDF parsing, chunking with LangChain text splitters, embedding generation
- **Voice configuration:** 20+ voice options, custom system prompts, model selection (GPT-4o, Claude)

**Database Schema Highlights:**
- `tenants` table with per-tenant configuration (voice_id, system_prompt, model settings)
- `organization_members` for RBAC (owner/admin/member roles)
- `documents` table with pgvector embeddings for RAG
- `call_logs` for analytics and monitoring
- `credit_transactions` for billing tracking
- Row-Level Security policies on all tables to enforce tenant isolation

**What I Actually Did:**
- Architected the entire system from database schema to deployment
- Wrote all the core backend logic (API routes, database queries, business logic)
- Implemented complex Stripe webhook handlers for subscription lifecycle
- Built RAG pipeline for knowledge base (embedding, chunking, retrieval)
- Handled voice agent configuration and VAPI integration
- Built admin dashboards with real-time analytics
- Managed multi-tenancy security (preventing data leaks between clinics)
- Deployed and maintained production infrastructure

**Avoid Making This Sound Like:** "I worked on a team that built..." - I built ALL of this myself as as the technical co-founder.


### 2. Zoid Technologies - AI Consultant (May 2024 - Present)
**CONTEXT:** I founded an AI consulting practice working directly with small business owners (dental clinics, wellness centers, professional services). I was the technical founder who identified opportunities, pitched solutions, closed deals, and delivered custom AI systems.I was the entire technical team, sales team, and customer success, albeit not many customers were secured as i was doing it part time while in school

**What I Actually Did:**
- Cold outreach to small business owners, identified pain points in their operations
- Consulted with owners to understand workflows and proposed AI automation solutions
- Designed and built custom voice agents, chatbots, and automation systems
- Handled everything from initial pitch to deployment to ongoing support
- Managed client relationships, expectations, and iterative improvements
- Learned to ship fast and iterate based on real user feedback

**Technical Work:**
- Built production AI voice agents using VAPI, Bland AI, and Twilio
- Created custom RAG knowledge bases for each client's specific domain
- Integrated with client systems (scheduling software, CRMs, phone systems)
- Built internal tools to manage multiple client deployments
- Handled billing, infrastructure costs, and profitability

**Avoid Making This Sound Like:** Generic "backend developer at consulting firm" - emphasize the founder/consultant angle and direct client work.

### 3. Iki Design Studio - Software Engineering Intern (Jan 2024 - Apr 2024)
- Financial modeling web application
- Python Flask APIs, React dashboards
- Data visualization with Chart.js
- AWS S3 integration, RESTful APIs

### 4. Riipen - Data Analyst Intern (Nov 2023 - Dec 2023)
- Insurance policy visualization platform
- Python pandas data pipelines
- Tableau dashboards
- Statistical modeling

---

## Projects Section

Include 1-2 projects based on number of experiences. Make them realistic and learnable within 4 days. can draw from the Github section

**Project Themes:**
- **Backend/DevOps roles:** Distributed systems, message queues, performance optimization
- **AI/ML roles:** LLM fine-tuning, RAG systems, voice AI
- **Full-stack roles:** Real-time systems, API development, multi-tenant SaaS
- **Data roles:** Streaming pipelines, analytics platforms
- anything cool

---

## GitHub Interests & Open Source (110 Repositories)

Based on my own repositories (github.com/TRAP33ZOID), my technical interests include:

**AI Agents & Autonomous Systems:**
- Coding agents: goose, opencode, Auto-Claude, ralphy (multi-agent orchestration)
- Task management: claude-task-master (AI-powered task system)
- Agent frameworks: agent-zero, Fabric (modular AI prompt framework)

**Voice AI & Real-Time Systems:**
- Voice agents: livekit/agents framework for real-time voice AI
- Audio processing: ebook2audiobook (voice cloning, TTS in 1107+ languages)

**Financial Technology & Research:**
- Financial research: dexter (autonomous agent for deep financial research)
- Recommendation algorithms: x-algorithm (X/Twitter feed algorithm)
- the-algorithm (Twitter/X source code)

**AI Infrastructure & RAG:**
- AI platforms: onyx (open-source AI chat platform)
- Web scraping: crawlee (for AI/LLM data extraction)
- LLM fine-tuning: unsloth (70% less VRAM, 2x faster training)
- System prompts: system-prompts-and-models-of-ai-tools (reverse engineering AI tools)

**Workflow Automation & DevOps:**
- Workflow automation: n8n (fair-code platform with 400+ integrations)
- Self-hosting: coolify (PaaS alternative to Vercel/Heroku)
- Infrastructure: sst (full-stack on your own infrastructure)

**Developer Tools:**
- Resume optimization: Resume-Matcher (AI-powered resume tuning)
- UI components: react-bits, blocks (shadcn marketing blocks)
- Video generation: remotion (programmatic video with React)

**MCP (Model Context Protocol):**
- awesome-mcp (curated MCP servers collection)
- python-sdk (official MCP Python SDK)

Note: Most repos are forks showing active exploration of cutting-edge AI/agent technologies. I actively study and experiment with production AI systems.

---

## Skills Section

Organize by relevant categories. Include technologies from job description. Stick to mainstream technologies.

**Core Competencies (assume mid-level proficiency):**
- System design and architecture decisions
- Database design and query optimization
- API design (REST, WebSockets, webhooks)
- Authentication and authorization patterns
- Distributed systems concepts
- CI/CD and deployment pipelines
- Testing strategies (unit, integration)
- Performance optimization
- Security best practices

---

## Achievement Optimization

- Transform each bullet point to emphasize specific impact and outcomes
- Use CAR format: Challenge faced, Action taken, Result achieved
- Include metrics (%, numbers, time saved)
- Show ownership and autonomy (not "assisted with" or "helped")
- Use strong action verbs: Architected, Built, Designed, Implemented, Shipped

---

## ATS Optimization, PASS THE SYSTEM AND GET THE RESUME TO A HUMAN

- Use `\textbf{}` to bold important metrics and keywords matching job description. ALL METRICS SHOULD BE BOLD
- Bold skills throughout resume but NOT in skills section
- Strategically repeat key terms in different contexts
- Include both spelled-out terms and acronyms (e.g., "PostgreSQL (Postgres)")
- Use industry-standard terminology
- Escape `&` with `\&` in LaTeX

---

## Single Page Target (Fill the Page)

**TARGET: Fill the page completely with quality content.**

### Better to Have Slightly Too Much Than Too Little:
- It's easier to REMOVE content to fit one page than to ADD content
- Generate content that would naturally fill 1-1.5 pages
- User will trim if it overflows slightly

### Content Guidelines:
- **2-3 experiences** with **4-5 bullet points each**
- **1-2 projects** with **3-5 bullet points each**
- **Professional Summary: 4-8 lines** (detailed but concise)
- **Skills: Comprehensive categories** (5-6 categories)
- **Education**

### Recommended Combinations:
- **2 experiences + 2 projects** (balanced, may need slight trimming)
- **3 experiences + 1 project** (more experience focus)
- **Avoid 3 experiences + 2 projects** (likely 2 pages, too much trimming needed)

### If Content Overflows:
User will remove weakest bullet points or shorten descriptions

### If Content Underflows (Empty Space):
- Add more bullet points to existing experiences
- Add another project
- Expand Professional Summary
- Add more detail to Skills section

---

## No Bullshit Metrics Rule

**METRICS MUST BE REALISTIC FOR AN ENTRY-LEVEL POSITION.**

### DO NOT Use:
- ❌ "10,000+ API requests daily" (sounds like senior engineer)
- ❌ "$2M+ in revenue data" (sounds like enterprise scale)
- ❌ "15+ businesses" (sounds like founder scale)
- ❌ "60-80% improvement" (too aggressive for entry-level)
- ❌ "99.9% uptime" (not believable for entry-level work)

### USE Realistic Entry-Level Metrics:
- ✅ API calls: "hundreds of requests", "per day/week"
- ✅ Revenue/financial: "thousands", "$Xk in data"
- ✅ Clients/users: "5+ clients", "several users", "small team"
- ✅ Improvement: "20-40% faster", "reduced by half"
- ✅ Scale: "small business", "startup environment", "pilot program"

### If Unsure About Metric:
**OMIT IT.** Better no metric than unbelievable metric.

---

## Critical Considerations

- EVERY skill mentioned must be something I can discuss in an interview
- ALL projects described must be learnable within 4 days with AI assistance. Gage using the users skillset from expereince section
- Focus on foundational understanding rather than expert-level knowledge
- Ensure any metrics claimed are **REALISTIC AND BELIEVABLE**
- **CRITICAL:** Position me as entry-level, NOT senior engineer
- Show ownership and autonomy, but with entry-level appropriate scale

---

## Full LaTeX Template

Use this exact template structure. Fill in your generated content where the LOREM IPSUM placeholders are shown:

```latex
% !TEX TS-program = pdflatex

\documentclass[10pt,letterpaper]{article}

% Basic packages
\usepackage[left=0.4in,right=0.4in,top=0.4in,bottom=0.4in,columnsep=0.4in]{geometry}
\usepackage{xcolor}
\usepackage{hyperref}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{ragged2e}
\usepackage{etoolbox}

% Font settings
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{helvet}
\renewcommand{\familydefault}{\sfdefault}

% Colors
\definecolor{mainblue}{HTML}{1D4ED8}
\definecolor{bodycolor}{HTML}{666666}
\definecolor{bodycolorbold}{HTML}{444444}

% Remove page numbers
\pagestyle{empty}

% Hyperref setup
\hypersetup{
    colorlinks=true,
    linkcolor=black,
    filecolor=black,
    urlcolor=black,
}

% Section formatting
\titleformat{\section}
  {\color{mainblue}\large\bfseries\uppercase}
  {}
  {0em}
  {}

\titlespacing{\section}{0pt}{8pt}{2pt}

% Subsection formatting
\titleformat{\subsection}
  {\normalsize\bfseries}
  {}
  {0em}
  {}

\newlength{\cvsubsectionvsepabove}
\setlength{\cvsubsectionvsepabove}{7pt}

\newlength{\cvsubsectionvsepbelow}
\setlength{\cvsubsectionvsepbelow}{3pt}

\titlespacing{\subsection}{0pt}{\cvsubsectionvsepabove}{\cvsubsectionvsepbelow}

\newlength{\namevsep}
\setlength{\namevsep}{0pt}

% Column layout
\usepackage{paracol}
\columnratio{0.65}

% Itemize settings
\AtBeginEnvironment{itemize}{\small}
\setlist[itemize]{leftmargin=*, topsep=4pt, parsep=0pt, itemsep=3pt}

% Body text command
\newcommand{\bodytext}[1]{%
  \textcolor{bodycolor}{%
    \let\oldtextbf\textbf%
    \renewcommand{\textbf}[1]{\oldtextbf{\textcolor{bodycolorbold}{##1}}}%
    #1%
    \let\textbf\oldtextbf%
  }%
}

% Custom commands
\newcommand{\cvsection}[1]{%
  \section{#1}
}

\newcommand{\cvevent}[4]{%
  \noindent\textbf{#1} --- \textit{#2} --- #3
  #4
}

\newcommand{\cvsubsection}[1]{
  \subsection{#1}
}

\begin{document}
\normalsize

\begin{paracol}{2}

% LEFT COLUMN

\vspace*{\namevsep}
\noindent{\textcolor{mainblue}{\textbf{\fontsize{36pt}{28pt}\selectfont Waleed Ahmed}}}\\[15pt]
\textit{{\fontsize{14pt}{16pt}\selectfont [GENERATED TITLE BASED ON JOB]}}

\vspace{22pt}

\cvsection{RELEVANT EXPERIENCE}

% When using ZoidAI, make it clickable: \href{https://zoid.ca}{ZoidAI}
\vspace{5pt}\cvevent{LOREM IPSUM ROLE}{LOREM IPSUM COMPANY}{LOREM IPSUM DATE}{}
\begin{itemize}
\item \bodytext{LOREM IPSUM BULLET POINT - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua}
\item \bodytext{LOREM IPSUM BULLET POINT - Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat}
\item \bodytext{LOREM IPSUM BULLET POINT - Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur}
\item \bodytext{LOREM IPSUM BULLET POINT - Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum}
\end{itemize}

\vspace{5pt}\cvevent{LOREM IPSUM ROLE}{LOREM IPSUM COMPANY}{LOREM IPSUM DATE}{}
\begin{itemize}
\item \bodytext{LOREM IPSUM BULLET POINT - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore}
\item \bodytext{LOREM IPSUM BULLET POINT - Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo}
\item \bodytext{LOREM IPSUM BULLET POINT - Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla}
\item \bodytext{LOREM IPSUM BULLET POINT - Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim}
\end{itemize}

\cvsection{TECHNICAL PROJECTS}

\vspace{5pt}\cvevent{LOREM IPSUM PROJECT NAME}{LOREM IPSUM TECH STACK}{}{}
\begin{itemize}
\item \bodytext{LOREM IPSUM BULLET POINT - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore}
\item \bodytext{LOREM IPSUM BULLET POINT - Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo}
\item \bodytext{LOREM IPSUM BULLET POINT - Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla}
\end{itemize}

\switchcolumn

% RIGHT COLUMN

\raggedright
\href{http://waleedahmed.ca}{\textcolor{black}{waleedahmed.ca}}\\
\href{mailto:waleed@zoid.ca}{\textcolor{black}{waleed@zoid.ca}}\\
\href{https://linkedin.com/in/waleed-ahmed-8396a1187}{\textcolor{black}{linkedin.com/in/waleed-ahmed}}\\
\href{https://github.com/TRAP33ZOID}{\textcolor{black}{github.com/TRAP33ZOID}}\\
\textcolor{black}{Toronto, ON, Canada}\\
\textcolor{black}{437-450-9195}\\\vspace{25pt}

\cvsection{PROFESSIONAL SUMMARY}
\begingroup
\fontsize{10pt}{11pt}\selectfont
\begin{justify}
\bodytext{LOREM IPSUM PROFESSIONAL SUMMARY - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.}
\end{justify}
\endgroup

\cvsection{SKILLS}\vspace{5pt}

\cvsubsection{LOREM IPSUM CATEGORY}
\bodytext{LOREM, IPSUM, DOLOR, SIT, AMET, CONSECTETUR, ADIPISCING}

\cvsubsection{LOREM IPSUM CATEGORY}
\bodytext{LOREM, IPSUM, DOLOR, SIT, AMET, CONSECTETUR, ADIPISCING, ELIT}

\cvsubsection{LOREM IPSUM CATEGORY}
\bodytext{LOREM, IPSUM, DOLOR, SIT, AMET, CONSECTETUR}

\cvsubsection{LOREM IPSUM CATEGORY}
\bodytext{LOREM, IPSUM, DOLOR, SIT, AMET, CONSECTETUR, ADIPISCING, ELIT, SED}

\cvsubsection{LOREM IPSUM CATEGORY}
\bodytext{LOREM, IPSUM, DOLOR, SIT, AMET}

\cvsubsection{LOREM IPSUM CATEGORY}
\bodytext{LOREM, IPSUM, DOLOR, SIT, AMET, CONSECTETUR, ADIPISCING}

\cvsubsection{LOREM IPSUM CATEGORY}
\bodytext{LOREM, IPSUM, DOLOR, SIT, AMET, CONSECTETUR}

\cvsection{EDUCATION}\vspace{5pt}

\cvevent{Bachelor of Computer Engineering}{Toronto Metropolitan University}{May 2026}{}

\cvevent{Diploma of Data Science}{Lighthouse Labs}{Oct 2023}{}

\end{paracol}
\end{document}
```

---

## Content Guidelines (Fill the Page)

**GOAL:** Fill the page to ~90-95% capacity. It's better to slightly overflow (user will trim) than to underfill.

### Content Structure Guidelines:

**Choose ONE of these combinations based on job fit:**

**Option A: 2 Experiences + 2 Projects** (Most balanced)
- 2 experiences with **4-5 bullets each** (MAX 5)
- 2 projects with **4-5 bullets each** (MAX 5)
- Total: 16-20 bullets in left column

**Option B: 3 Experiences + 1 Project** (Experience-heavy roles)
- 3 experiences with **4-5 bullets each** (MAX 5)
- 1 project with **4-5 bullets** (MAX 5)
- Total: 16-20 bullets in left column

**Option C: 2 Experiences + 1 Project** (Selective focus)
- 2 experiences with **5 bullets each** (MAX 5)
- 1 project with **4-5 bullets** (MAX 5)
- Total: 14-15 bullets in left column

**HARD LIMIT: Maximum 5 bullet points per experience or project**

### Right Column Guidelines:
- **Professional Summary:** 4-5 lines (comprehensive)
- **Skills:** 6-7 categories with detailed lists
- **Education:** Single lines only (no coursework)

### Quality Rules:
1. Write comprehensive, detailed bullets
2. Include specific technologies and metrics
3. Prioritize job-matching keywords
4. If it overflows slightly, user will trim weakest content
5. Better to have comprehensive content than empty space

---

## Output Format

Provide the **complete, compilable LaTeX file** starting from the very first line (`% !TEX TS-program = pdflatex`) through to the end (`\end{document}`). 

Do NOT start from `\begin{document}` — include the full preamble with all packages, colors, commands, and settings exactly as shown in the template above.

Replace all LOREM IPSUM placeholders with your generated content based on my background and the job description. save the resume is .tex file in this directory. name it by company then role

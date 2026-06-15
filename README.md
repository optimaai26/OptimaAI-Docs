# Optima AI — Documentation Site

> Official documentation for the Optima AI platform, built with [Fumadocs](https://fumadocs.vercel.app) and deployed on Vercel.

**Live demo: https://www.optimaai.software/login**
🔗 **Live docs:** [optima-ai-documentation.vercel.app](https://optima-ai-documentation.vercel.app)

---

## What's Documented

| Section | Description |
|---|---|
| **Introduction** | Platform overview, capabilities, and tech stack |
| **Architecture** | System diagram and data flow (training, inference, RAG, LLM) |
| **Backend** | FastAPI setup, full API reference, database schema, caching, datasets |
| **Frontend** | Next.js dashboard pages, features, and API integration guide |
| **Odoo Integration** | Data sources, export instructions, and field mapping |
| **AI & ML** | Model training, XGBoost/Prophet models, LLM prompts, RAG knowledge base |
| **Deployment** | Docker Compose, Nginx, Vercel, and production checklist |

---

## Tech Stack

| Tool | Role |
|---|---|
| [Fumadocs](https://fumadocs.vercel.app) | Documentation framework |
| [Next.js 15](https://nextjs.org) | React framework (App Router) |
| [Vercel](https://vercel.com) | Hosting & CI/CD |
| MDX | Content format |

---

## Local Development

```bash
git clone https://github.com/HassanBassiouny/Optima-AI-Documentation.git
cd Optima-AI-Documentation
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Adding or Editing Pages

All documentation lives in `content/docs/`. Each section has its own folder:

```
content/docs/
├── index.mdx           ← Introduction
├── architecture.mdx
├── backend/
├── frontend/
├── odoo/
├── ai/
└── deployment/
```

To add a new page:
1. Create a `.mdx` file in the relevant folder
2. Add frontmatter `title` and `description`
3. Register the filename in the folder's `meta.json` under `pages`

Every `git push` to `main` auto-deploys to Vercel.

---

## Related

- **Backend repo:** [Optima Ai Backend](https://github.com/optimaai26/Optimaai-Backend)
- **Frontend repo:** [Optima Ai Frontend](https://github.com/optimaai26/optimaai-fe)
- **Odoo repo:** [Optima Ai Odoo](https://github.com/optimaai26/odoo-optimaai)

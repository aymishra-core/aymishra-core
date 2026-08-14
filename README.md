# Hi, I'm Ayush 👋

I build and ship full-stack products end to end — frontend, API, database, auth, payments, and AI — and put them in front of real users.

I care about the whole system, not one corner of it: a thing I build should be **deployed, paid for, and actually used**, not a demo. Below are two products I've taken from zero to live.

---

## 🚀 What I've shipped

### MeetOut — [meetouthq.com](https://meetouthq.com)
**Turn a raw meeting into decisions, action items, a client email, and a follow-up agenda — from pasted text or an audio file.**

A live SaaS with real users. Paste a transcript or upload audio, and MeetOut runs it through a switchable LLM pipeline to produce four structured artifacts. Built entirely end-to-end.

- **Frontend:** React 18 + Vite SPA, Tailwind, deployed on Vercel
- **Backend:** Python + FastAPI, SQLAlchemy 2, Pydantic, rate limiting
- **Database:** Postgres (Supabase) with row-level security
- **AI:** OpenAI (GPT-4o + Whisper) and Anthropic (Claude Sonnet), provider-switchable; audio → transcript → structured output
- **Auth & Payments:** JWT + Google OAuth; Razorpay subscriptions with idempotent webhooks

### BrandKit
**Generate a complete brand kit — palette, font pairings, and logos — in one pass.**

A generator built on real algorithms, not just an API call: color palettes from HSL/color theory, curated Google Font pairings, and logos composed as SVG. AI is used only where it actually helps (copy/taglines), with a templated fallback.

- **Frontend:** React 19 + Vite + TypeScript + Tailwind
- **Backend:** FastAPI + SQLAlchemy + Alembic migrations
- **Core:** algorithmic palette / font / SVG-logo generation, with a single LLM call for copy
- **Database:** Postgres (Supabase) · **Auth:** JWT + Google OAuth · **Payments:** Razorpay

---

## 🧭 How I work

- **End-to-end or not at all** — I build across every layer: UI, API, data, infra, auth, payments, and AI.
- **Ship to real users** — deployed and in production beats polished and hypothetical.
- **AI where it earns its place** — I use LLMs deliberately, and build the non-AI parts properly (algorithms, migrations, idempotent webhooks) rather than wrapping everything in a model.

---

## 🛠️ Stack I reach for

**Frontend** React · Vite · TypeScript · Tailwind
**Backend** Python · FastAPI · SQLAlchemy · Pydantic
**Data** Postgres · Supabase · SQLite
**AI** OpenAI (GPT-4o, Whisper) · Anthropic (Claude)
**Infra** Vercel · Railway · Razorpay · Google OAuth

---

## 📫 Reach me

- **Email:** aymishra.in@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/aymishra01/

*Open to talking with builders, founders, and people working on AI-driven products.*

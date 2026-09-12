# Hi, I'm Ayush 👋

I take products from an empty repo to a live, paid product — frontend, API, database,
auth, payments, and AI — and put them in front of real users.

I care about the whole system, not one corner of it. A thing I build should be
**deployed, paid for, and actually used**, not a demo. I use AI where it earns its
place and build the parts around it properly. Below are the products I've taken from
zero to live.

---

## 🚀 What I've shipped

### MeetOut — [meetouthq.com](https://meetouthq.com)
**AI content repurposing · full-stack product development.** Turn anything you've
read, watched, or noted into a week of publish-ready social posts — from a single
source.

A live SaaS with real users. Drop in a URL, PDF, pasted text, or audio, and MeetOut
runs it through a switchable LLM pipeline to produce platform-native posts for eight
channels — LinkedIn, X, Bluesky, Instagram, Facebook, Threads, newsletter, and
YouTube. Refine each one, attach copyright-safe images, and publish or copy. A second
mode (in rollout) turns uploaded video into trimmed, ready-to-post clips. Built
entirely end to end.

- **Frontend:** React 18/19 + Vite SPA, Tailwind, deployed on Vercel
- **Backend:** Python + FastAPI, SQLAlchemy 2, Pydantic, rate limiting
- **Database:** Postgres (Supabase) with row-level security
- **AI:** OpenAI (GPT-4o + Whisper) and Anthropic (Claude), provider-switchable;
  source → structured, platform-specific output
- **Auth & Payments:** JWT + Google OAuth; Razorpay subscriptions with idempotent
  webhooks
- **Security:** OAuth tokens encrypted at rest, signed-state CSRF protection,
  server-enforced plan limits

### BrandKit
**Generative brand identity · full-stack product development.** Generate a complete
brand kit — palette, font pairings, and logos — in one pass, built on real algorithms
rather than a single API call.

Color palettes derived from HSL/color theory, curated Google Font pairings, and logos
composed as SVG. AI is used only where it actually helps (copy and taglines), with a
templated fallback so the product never breaks when the model is unavailable.

- **Frontend:** React 19 + Vite + TypeScript + Tailwind
- **Backend:** FastAPI + SQLAlchemy + Alembic migrations
- **Core:** algorithmic palette / font / SVG-logo generation, with a single LLM call
  for copy
- **Database:** Postgres (Supabase) · **Auth:** JWT + Google OAuth · **Payments:** Razorpay

---

## 🧭 How I work

- **End-to-end or not at all** — every layer: UI, API, data, infra, auth, payments,
  and AI. The hard parts don't get handed off.
- **Ship to real users** — deployed and in production beats polished and hypothetical.
- **AI where it earns its place** — LLMs used deliberately, with the non-AI parts built
  properly: real algorithms, migrations, idempotent webhooks, encrypted secrets, and
  server-enforced limits — rather than wrapping everything in a model.

---

## 🛠️ Stack I reach for

**Frontend** React · Vite · TypeScript · Tailwind
**Backend** Python · FastAPI · SQLAlchemy · Pydantic
**Data** Postgres · Supabase · SQLite
**AI** OpenAI (GPT-4o, Whisper) · Anthropic (Claude)
**Infra** Vercel · Railway · Razorpay · Google OAuth

---

## 📫 Reach me

- **Email:** <aymishra.in@gmail.com>
- **LinkedIn:** <https://www.linkedin.com/in/aymishra01/>

*Open to talking with builders, founders, and people working on AI-driven products.*

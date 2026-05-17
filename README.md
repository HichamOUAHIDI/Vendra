# Vendra 🚀

**Vendra IA pour vendre plus vite.**

Vendra est une plateforme **IA multi-agents** qui transforme une simple photo + description en une annonce optimisée (titre, prix marché, description persuasive) pour Leboncoin, Vinted et Facebook Marketplace.

> ⚙️ Ce repo vient d'être initialisé. Le scaffold complet du MVP (Next.js + FastAPI + LangGraph + Gemini) est en cours de génération via une Pull Request automatique.

## 🧠 Les 4 agents du MVP

1. 👁️ **Vision Agent** — analyse l'image et détecte catégorie / marque / état
2. 📊 **Market Agent** — récupère les prix d'annonces comparables
3. 💰 **Pricing Agent** — recommande un prix optimal avec justification
4. ✍️ **Ad Generator Agent** — génère titre + description FR optimisés

## 💸 Stack 100% gratuite

- Google Gemini 1.5 Flash (1500 req/jour offertes)
- Vercel (frontend) + Render/Railway (backend)
- LangGraph (open-source) pour l'orchestration multi-agents

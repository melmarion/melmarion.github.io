# MARION MORANETZ

(541) 507-7549 | Marion.m.moranetz@gmail.com | linkedin.com/in/marionmoranetz
github.com/moranetz | Open to Relocation

---

Applied data scientist who builds behavioral prediction systems from research data. Architect of Persuasion-Max: a calibrated 5-layer ML pipeline that predicts persuasive effectiveness from 126K human interactions, with full parameter provenance, ablation analysis, and documented model limitations. Looking for Applied Data Science roles where rigorous behavioral modeling drives real product and business decisions.

---

## ML SYSTEMS & BEHAVIORAL MODELING

### Persuasion-Max — Calibrated Behavioral Prediction Pipeline | 2026

*5-layer ML pipeline predicting persuasive message effectiveness. Each layer independently validated. Full provenance tracking on all 302 parameters. Open-source.*

- **Engineered 5-layer feature architecture**: linguistic surface (12 features: sentence length, question density, emotional valence, readability) → cognitive appraisal (7 dimensions: certainty, pleasantness, attentional activity, control, legitimacy, anticipated effort, situational control) → technique detection (40-class Zeng taxonomy) → recipient modeling (16-dimension Big Five + MFT + ideology profile) → domain-specific circuit prediction.

- **Calibrated on 126K records across 4 datasets**: DailyPersuasion (78K dialogues, 35 domains), HumanChoicePrediction (48K binary decisions), PersuGPT, and PERSUADE 2.0. Train/test splits maintained per domain. Bootstrap confidence intervals on all reported metrics.

- **Discovered key feature importance hierarchy through ablation**: linguistic features contribute +10pp AUC over appraisal-only model. Technique binary detection contributes +0pp (zero incremental signal). Interaction terms (technique x personality) contribute +21.8pp compliance spread. This ablation finding challenges the common assumption that identifying persuasion techniques is the most valuable signal.

- **Built 400-cell interaction matrix** (40 techniques x 10 persona clusters) revealing that the same technique produces dramatically different compliance rates depending on recipient personality. Moral reframing effect quantified at +8.4pp for correctly matched moral foundations (Feinberg & Willer 2015 replication).

- **Validated domain specificity empirically**: cross-domain weight transfer degrades AUC by 10-13pp. Models trained on ecommerce persuasion fail on political persuasion and vice versa. This confirms domain-specific feature engineering is required — no universal persuasion model exists.

- **302 parameters with full provenance**: 1% FITTED from data, 61% CONSTRAINED from published literature, 37% UNCALIBRATED (documented as such). Weight registry audit published. This level of parameter documentation is rare in applied ML and enables reproducibility.

- **329 automated tests** including unit tests, integration tests, and provenance-aware validation that flags when parameter constraints are violated.

- **Stack**: Python, scikit-learn (logistic regression, feature selection, cross-validation), FastAPI (17 endpoints), MCP server (12 tools), Ollama/Claude LLM integration.

### Content Optimization System — Closed-Loop ML Applied | 2026

- **Built closed-loop prediction system**: predicts content engagement → observes actual engagement → auto-updates model weights per platform after 20+ observations per technique. Addresses concept drift without manual retraining.

- **Engineered 12 community linguistic norm profiles** using NLP features (reading difficulty, emotionality, pronoun ratios). Content scoring uses deviation from community norms as a feature — a 1.5 sigma deviation predicts low engagement regardless of content quality.

- **56-tool autonomous agent** with 85 automated tests, fine-tuned 7B LLM on 284 quality-gated training examples (triple quality gate: predicted effectiveness, organic detection pass, linguistic norm compliance).

---

## PRODUCT DATA SCIENCE (80 REPOS)

- **Designed behavioral measurement systems for 34 iOS apps and 39 browser products**: engagement scoring, retention prediction, session architecture analysis, and A/B testing frameworks. Each product has quantified engagement mechanics with documented expected retention lift ranges.

- **27 reusable analytical frameworks** codifying engagement measurement (DOSE neurochemical mapping), gamification impact analysis (tier 1-4 ranked by retention lift), and session architecture scoring (11-minute model with phase-specific reward probability curves).

---

## TECHNICAL PROFICIENCY

**ML & Data Science:** Logistic regression, feature selection (ablation analysis), cross-validation, bootstrap CI, AUC/ROC evaluation, interaction term discovery, NLP feature engineering, concept drift detection, closed-loop model updates, LLM fine-tuning (Ollama/7B), prompt engineering

**Behavioral Modeling:** Cognitive appraisal theory (7-dimension), Moral Foundations Theory (5-foundation), Big Five personality modeling, Elaboration Likelihood Model, persuasion technique taxonomies (40-class Zeng/SemEval)

**Languages & Frameworks:** Python, scikit-learn, FastAPI, SQL, JavaScript/React, Swift/SwiftUI, Canvas API

**Infrastructure:** Git (80 repos, 170+ commits on primary projects), Claude API, MCP protocol, Ollama

---

## EDUCATION

**Southern Oregon University** — B.S. Innovation & Leadership (3.76) | Minor: Rhetoric & Reason | 2025
Coursework: Data-Driven Decision Making, AI/ML Applications, Persuasion & Negotiation (A)

**Southwestern Oregon Community College** — A.S. General Studies (3.8, top 5%) | 2023

---

## KEY METRICS

- 126,288 human interaction records processed across 4 research datasets
- 302 model parameters with documented provenance (fitted vs literature-constrained vs uncalibrated)
- 21.8pp compliance spread in technique x personality interaction matrix
- 10-13pp AUC degradation on cross-domain transfer (empirically validated)
- +10pp AUC from linguistic features; +0pp from technique binary detection (ablation finding)
- 414 automated tests, 329 with provenance-aware validation

# MARION MORANETZ

(541) 507-7549 | Marion.m.moranetz@gmail.com | linkedin.com/in/marionmoranetz
github.com/moranetz | Open to Relocation

---

Applied behavioral scientist who builds detection and measurement systems for online influence. Architect of Persuasion-Max, a 5-layer pipeline that decomposes persuasive content into measurable components — identifying manipulation techniques, predicting recipient vulnerability, and quantifying context-dependent harm. 126K human interactions processed. Looking for Trust & Safety roles where understanding influence mechanics prevents real harm at scale.

---

## INFLUENCE DETECTION & MEASUREMENT

### Persuasion-Max — Influence Detection & Prediction Engine | 2026

*Open-source 5-layer pipeline that detects persuasion techniques in content, models recipient vulnerability, and predicts behavioral impact. Grounded in cognitive appraisal theory (Smith & Ellsworth 1985) and somatic marker hypothesis (Damasio).*

- **Built 40-technique detection layer** using Zeng SemEval taxonomy: identifies emotional appeal, fear/threat framing, logical fallacies, social proof manipulation, authority exploitation, scarcity tactics, whataboutism, and 33 other influence techniques in arbitrary text.

- **Engineered 16-dimension recipient vulnerability model** (Big Five personality, Moral Foundations, cognitive style, ideology profile) that predicts susceptibility to specific techniques. 21.8pp compliance spread across persona types — the same manipulative message affects different people dramatically differently.

- **Quantified defensive technique risk**: crisis PR analysis found that whataboutism triggers 46.5% retaliation probability. Defensive framing backfires more often than it deflects. This type of finding directly informs content moderation policy.

- **Validated domain-specificity of harm models**: cross-domain weight transfer degrades AUC by 10-13pp, confirming that manipulation detection models trained on one context (e.g. political) perform poorly in another (e.g. commercial) without retraining. Universal "toxicity" models miss context-dependent harm.

- **Discovered that technique binary detection adds zero incremental signal** — detecting THAT a technique is present matters less than detecting HOW it's deployed (linguistic surface features). This finding challenges common content moderation approaches that flag technique presence without context.

- **329 automated tests, 302 parameters with provenance** (1% fitted, 61% literature-constrained, 37% uncalibrated). Full ablation analysis. Paper-shaped documentation.

### Influence Detection Tools (Browser-Based) | 2025-2026

- **ClearFrame**: propaganda/influence detection interface that surfaces rhetorical techniques in real-time content.

- **Dead Internet**: social network narrative manipulation detector — identifies propaganda playbooks (Wag the Dog, Overton Window), velocity spikes, and linguistic fingerprints suggesting coordinated inauthentic behavior.

- **SNA Framework**: social network analysis toolkit for mapping influence propagation patterns.

### Content Strategy Platform — Measuring Influence at Scale | 2026

- **Built 12 community linguistic norm profiles** (reading difficulty, emotionality, pronoun ratios) for Reddit communities. Content deviating >1.5 sigma from norms flagged automatically. This same detection logic applies to identifying astroturfing and coordinated manipulation that breaks community norms.

- **284 quality-gated training examples** with triple quality gate: >60% predicted effectiveness, organic-passing on influence detector, platform-appropriate linguistics. The "organic-passing" detector is itself a trust & safety tool — it identifies content designed to evade detection.

### Fractionation Research (Persuasion-Max Core Thesis) | 2026

- **Documented the mechanism of algorithmic emotional sequencing** (fractionation: rapid cycling of emotional states A-J-A-R) and its effect on user decision-making capacity. Research bridges tech (engagement metrics), neuroscience (prefrontal cortex disengagement), and economics (irrational purchasing).

- **Identified that awareness does not prevent effect** — users who understand they're being manipulated are still behaviorally affected. This finding has direct implications for disclosure-based safety interventions.

---

## PRODUCT DEVELOPMENT

- **80 repositories** including 34 iOS apps (persuasion trainers, narrative games), 39 browser projects (influence detection tools, engagement systems), and 7 Python systems.

- **27 behavioral design frameworks** (Claude Code skills) codifying engagement mechanics, gamification architecture, and neurochemical targeting — understanding how these systems work is prerequisite to detecting when they're weaponized.

---

## TECHNICAL PROFICIENCY

**Detection & Analysis:** NLP feature engineering, technique taxonomy classification (Zeng 40-technique), linguistic norm profiling, coordinated behavior detection, statistical significance testing (bootstrap CI), ML evaluation (AUC/ROC), interaction term discovery

**Behavioral Science:** Cognitive appraisal theory, Elaboration Likelihood Model, Moral Foundations Theory, fractionation/emotional sequencing, Big Five vulnerability modeling, persuasion resistance research

**Languages & Frameworks:** Python, JavaScript/React, Swift/SwiftUI, scikit-learn, FastAPI, Canvas API, SQL

**ML/AI:** LLM fine-tuning (Ollama/7B), Claude API, logistic regression, NLP, prompt engineering

**Tools:** Git (80 repos), VS Code, Claude Code, MCP protocol

---

## EDUCATION

**Southern Oregon University** — B.S. Innovation & Leadership (3.76) | Minor: Rhetoric & Reason | 2025
Coursework: Persuasion & Negotiation (A), Data-Driven Decision Making, High-Stakes Communication

**Southwestern Oregon Community College** — A.S. General Studies (3.8, top 5%) | 2023

---

## KEY METRICS

- 40 persuasion techniques detectable with Zeng SemEval taxonomy integration
- 21.8pp compliance spread demonstrating recipient-dependent vulnerability
- 46.5% retaliation probability on defensive whataboutism — quantified backfire risk
- 10-13pp AUC degradation on cross-domain transfer — domain-specific detection required
- 126K human interactions processed with full provenance tracking
- 414 automated tests across primary codebases

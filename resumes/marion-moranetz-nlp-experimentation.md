# MARION MORANETZ

(541) 507-7549 | Marion.m.moranetz@gmail.com | linkedin.com/in/melmarion
github.com/melmarion | Open to Relocation

---

NLP engineer and experimentation specialist who builds language understanding systems for behavioral prediction. Architect of Persuasion-Max: a 5-layer NLP pipeline that decomposes natural language into cognitive, emotional, and persuasive dimensions — calibrated on 126K human interactions with rigorous ablation and cross-validation. Looking for NLP/Experimentation roles where language modeling and experimental design drive product intelligence.

---

## NLP SYSTEMS & EXPERIMENTATION

### Persuasion-Max — Multi-Layer NLP Pipeline | 2026

*5-layer NLP system that extracts behavioral signal from natural language: linguistic features → cognitive appraisal → technique classification → recipient modeling → outcome prediction. Full ablation analysis. Open-source.*

- **Engineered 12-feature linguistic extraction layer**: sentence length distribution, question density, emotional valence (positive/negative ratio), readability index, pronoun usage patterns, hedging frequency, imperative density, specificity score, narrative structure markers, rhetorical question detection, repetition patterns, and lexical diversity. Each feature independently validated for predictive contribution.

- **Built 7-dimension cognitive appraisal classifier** based on Smith & Ellsworth (1985): certainty, pleasantness, attentional activity, control, legitimacy, anticipated effort, situational control. Maps raw text to the cognitive state it's designed to produce in the reader.

- **Implemented 40-class technique classifier** (Zeng SemEval taxonomy): emotional appeal, fear/threat, social proof, authority citation, scarcity, reciprocity, commitment/consistency, storytelling, self-disclosure, evidence-based framing, logical fallacy, whataboutism, and 28 others. Classifier outputs technique probability distribution, not binary presence.

- **Ablation finding: linguistic features +10pp AUC, technique binary detection +0pp.** This is the key NLP insight — HOW something is said (linguistic surface) predicts behavioral response better than WHAT technique is being used (classified intent). The distribution of techniques matters; their binary presence does not.

- **Interaction term discovery**: 400-cell matrix (40 techniques x 10 persona clusters) revealing that technique effectiveness is recipient-modulated. The same text produces 21.8pp compliance spread depending on who reads it. This has direct implications for personalization systems.

- **Cross-domain transfer experiments**: models trained on one domain (ecommerce, political, crisis PR) lose 10-13pp AUC when applied to another. Domain-specific vocabulary, norms, and reader expectations dominate over universal linguistic patterns.

- **302 parameters, 329 tests, full provenance.** Stack: Python, scikit-learn, FastAPI, Ollama/Claude LLM integration.

### Content Experimentation Platform | 2026

- **Built A/B testing framework for content effectiveness** across Reddit, LinkedIn, and Substack. Each piece of content scored by Persuasion-Max pipeline before publication, then correlated with observed engagement. Closed loop updates model weights.

- **Engineered community linguistic norm detector**: 12 pre-computed Reddit community profiles. NLP features (reading level, emotionality, pronoun ratios) establish baseline. Content deviating >1.5 sigma auto-flagged. Tests showed norm deviation is a stronger predictor of low engagement than content quality.

- **Designed triple quality gate for training data**: >60% predicted effectiveness AND organic-passing on influence detector AND platform-appropriate linguistics. 284 examples survived the gate from a much larger candidate pool.

- **Fine-tuned 7B LLM** (Ollama) on 284 curated examples. Evaluated generation quality against human-written baselines using Persuasion-Max scoring as automated evaluation metric.

### NLP-Adjacent Product Work | 2025-2026

- **4 conversation simulation products** (TELLS, SWAY, Read the Room, Charisma Training) — each one is an NLP application: parse user text input, score it against a psychological model of the NPC, generate contextually appropriate branching responses. Text classification + generation in a game wrapper.

- **Influence detection tools** (ClearFrame, Dead Internet, SNA Framework): real-time NLP analysis of social media content for propaganda techniques, linguistic fingerprinting, and coordinated behavior detection.

- **56-tool autonomous content agent** (Social Pilot): NLP pipeline for content generation, scoring, and posting with behavioral optimization loop. 85 automated tests.

---

## TECHNICAL PROFICIENCY

**NLP:** Feature engineering (12-feature linguistic extraction), text classification (40-class taxonomy), cognitive appraisal modeling, community norm profiling, influence technique detection, LLM fine-tuning (7B/Ollama), prompt engineering, Claude API, automated text evaluation

**Experimentation:** A/B testing design, bootstrap confidence intervals, cross-validation, ablation analysis, interaction term discovery, cross-domain transfer evaluation, closed-loop model updates, statistical significance testing

**Languages & Frameworks:** Python, scikit-learn, FastAPI, JavaScript/React, Swift/SwiftUI, SQL

**Infrastructure:** Git (80 repos), MCP protocol, Ollama, Claude Code

---

## EDUCATION

**Southern Oregon University** — B.S. Innovation & Leadership (3.76) | Minor: Rhetoric & Reason | 2025
Coursework: AI/ML Applications, Data-Driven Decision Making, Persuasion & Negotiation (A)

**Southwestern Oregon Community College** — A.S. General Studies (3.8, top 5%) | 2023

---

## KEY METRICS

- 12 linguistic features, 7 appraisal dimensions, 40 technique classes — multi-layer NLP extraction
- +10pp AUC from linguistic features; +0pp from technique binary detection (ablation finding)
- 21.8pp compliance spread from technique x personality interaction terms
- 10-13pp AUC cross-domain degradation (empirical transfer learning result)
- 126K human interactions across 4 NLP datasets
- 284 quality-gated fine-tuning examples with triple evaluation gate
- 414 automated tests with provenance-aware validation

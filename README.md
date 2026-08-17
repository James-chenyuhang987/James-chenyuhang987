# Hi, I'm Chenyuhang (James Chen) 👋

> **Building AI agents, music intelligence systems, and adaptive learning experiences.**

I'm a high school student and developer exploring the intersection of **AI Agents, Music Technology, and Education**.

I am especially interested in how Large Language Models can move beyond simple question-answering systems and become **adaptive reasoning architectures** capable of perception, planning, action, feedback, and long-term personalization.

My projects focus on turning these ideas into real, interactive products — from AI-powered choir training and adaptive education agents to music-driven games and multi-agent reasoning systems.

---

## 🚀 Featured Projects

### 🎵 [PartMate-MTX](https://github.com/James-chenyuhang987/Partmate-MTX)

**AI-powered, part-specific choir practice and creative learning platform**

PartMate-MTX is a browser-based practice system built specifically for **choir sectional rehearsal**. Instead of reducing a performance to a single entertainment-style score, PartMate creates a complete learning loop: **locate the mistake → diagnose why it happened → prescribe a targeted exercise → verify mastery through an unguided retest**.

During practice, the system uses **MusicXML scores and teacher reference recordings** as musical targets, analyzing pitch, entry timing, missed notes, rhythm, note duration, and stability down to individual phrases and measures. **Pitchy / MPM** provides pitch tracking, while RMS energy and spectral flux provide complementary evidence for onset and missed-note detection. Thresholds and scoring rules are centralized in a versioned scoring dictionary, keeping real-time feedback, review, prescriptions, and retests consistent. **Deterministic rules make the musical judgments; the LLM does not score performances, but translates structured results into understandable feedback and encouragement.**

Beyond scoring, PartMate integrates **OMR score digitization**, OSMD-based MusicXML rendering, Web Audio synchronization, and **Chroma + DTW** alignment between teacher demonstrations and sheet music. A personalized growth system tracks performance by **song × vocal part × measure**, dynamically estimates mastery, and gradually removes guidance before unguided retesting. The conductor dashboard aggregates individual results into a **part × measure heatmap**, helping identify shared weaknesses before rehearsal.

The **Create / Harmony Workshop** extends PartMate from practice into musical creation. MVSep separates vocals from accompaniment, pYIN extracts melodic information and supports key, chord, and beat analysis; rule-based logic preserves musical constraints while the LLM directs section-level and vocal-part arrangement. Pitch shifting, **SVC voice conversion**, and multi-track mixing then transform a single vocal line into editable layered harmonies.

The goal is to move users from **learning a song → building personalized practice habits → understanding ensemble relationships → arranging, harmonizing, and creating music themselves**.

**Core Technologies:**
`TypeScript` · `MusicXML / OSMD` · `Web Audio` · `OMR` · `Pitchy / MPM` · `RMS & Spectral Flux` · `Rhythm Analysis` · `Chroma + DTW` · `Rule-based Scoring` · `LLM Feedback` · `MVSep` · `pYIN` · `SVC` · `Multi-track Audio`

---

### 🧭 [Beat-Runner](https://github.com/James-chenyuhang987/Beat-Runner)

Beat-Runner is an original pseudo-3D web rhythm runner built around music-driven interaction. Players control an energy ball across three neon tracks, dodging obstacles and collecting notes in sync with each song's BPM. The game includes three levels, rhythm-based abilities, talent choices, combo and ranking systems, story progression, level unlocking, and responsive controls for both desktop and mobile devices.

**Tech:** `JavaScript` · `HTML5` · `CSS3` · `Web Audio` · `BPM Synchronization`

---

### 🧠 [Pathfinder-AI-Learning](https://github.com/James-chenyuhang987/Pathfinder-AI-Learning)

Pathfinder-AI-Learning is an adaptive education agent that explores how LLMs can support individualized learning rather than simply answer questions. It combines agentic planning, memory-decay modeling, dynamic knowledge graphs, and motivational feedback to transform static learning materials into a responsive learning process. The project focuses on long-term adaptation, personalized pacing, and incentive design for sustained student engagement.

**Tech:** `LLM` · `AI Agents` · `Knowledge Graphs` · `Mathematical Modeling` · `Adaptive Learning`

---

### 🕵️ Terminal_Detective

Terminal_Detective is an experimental AI reasoning game in which the player acts as the **architect behind the detective**. Instead of solving cases directly, players design ReAct-style behavior logic that guides an AI detective through observation, reasoning, tool use, and recovery from mistakes. The project explores multi-agent coordination, controllable reasoning workflows, and fault-tolerant agent design through an interactive game format.

**Tech:** `ReAct` · `Multi-Agent Systems` · `LLM Reasoning` · `Agent Workflow Design`

---

## 🔬 Current Focus

* **AI Agent Architecture** — Perception → Planning → Action → Feedback
* **AI + Music** — Music understanding, rehearsal intelligence, and creative tools
* **Adaptive Education** — Personalized learning systems and long-term learner modeling
* **Multimodal AI** — Combining audio, vision, structured data, and language models
* **Human-AI Interaction** — Designing AI systems that adapt to how people actually learn and create

---

## 💻 Tech Stack

**AI & Agents**

`LLM` · `Prompt Engineering` · `Agentic Workflows` · `ReAct` · `Multi-Agent Systems`

**Music & Signal Processing**

`Audio Analysis` · `Pitch Detection` · `Rhythm Analysis` · `OMR` · `Multimodal Processing`

**Web Development**

`JavaScript` · `TypeScript` · `HTML5` · `CSS3`

**Research & Modeling**

`Mathematical Modeling` · `Knowledge Graphs` · `Behavioral Economics` · `Adaptive Systems`

---

## 🌱 What I'm Exploring

I'm interested in building AI systems that do more than generate answers.

I want to explore systems that can:

**understand users → model their progress → make decisions → adapt over time → help them learn and create better.**

My long-term interest lies in the intersection of **AI Agents, intelligent education, music technology, and human-centered AI**.

---

## 📫 Contact

**Email:** [chenyuhang987@icloud.com](mailto:chenyuhang987@icloud.com)

**Phone number:** +86 13146900226

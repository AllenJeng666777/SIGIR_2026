# SIGIR 2026 — Supplementary Materials

This repository contains supplementary materials for the SIGIR 2026 submission:

**Reducing Perceived Polarisation through Affect-Balanced News Reframing**  
Jia-Hua Jeng, Alain D. Starke, David Elsweiler, Christoph Trattner

The materials document (1) the GPT-based headline reframing procedure and
(2) the headline stimuli used in the agreement studies and the final online user study (RQ2).

---

## Repository structure
```text
SIGIR_2026/
├─ GPT_prompt/
│  └─ SIGIR_Github_GPT_prompt.ipynb
└─ Headlines for user study/
   ├─ Agreement study/
   │  ├─ stance.csv
   │  ├─ group1_emotion.csv
   │  └─ group2_emotion.csv
   └─ Online user study/
      ├─ Q3.csv
      ├─ Q8.csv
      └─ Q16.csv
``` 


## GPT-based reframing (`GPT_prompt/`)

`SIGIR_Github_GPT_prompt.ipynb` contains the prompt and script used to rewrite
Danish news headlines using **GPT-4o** into a **balanced fear–anticipation framing**
(as described in the paper as fear–hope reframing).

Reframed headlines are validated using the same Danish emotion
classifier employed in the log-based analyses, ensuring:
- fear and anticipation signals are both present, and
- non-target emotions remain low.

---

## Headline stimuli (`Headlines for user study/`)

### Agreement study
The `Agreement study/` folder contains the headline sets used in the human
agreement studies validating stance and emotion annotations (Study 2 in the paper).

### Online user study
The `Online user study/` folder contains the final headline stimuli used in the
between-subject user study (RQ2), including:
- original editorial headlines, and
- GPT-reframed fear–anticipation headlines.

Each CSV corresponds to one survey item used in the experiment.

---

## Notes
- Headlines are sourced from EB-NeRD / Ekstra Bladet and are provided for research
  transparency.
- These materials are intended solely as supplementary attachments for review.


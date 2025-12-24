---
title: Validation Checklist
date: 2025-12-16 00:00:00 PST
ver: 1.0.0
author: Sliither
model: claude-opus-4-5-20250514
tags: [validation, quality-assurance, ai-detection, authenticity, checklist]
---

# Validation Checklist for Humanized Writing

Pre-publication authenticity verification protocol.

## Table of Contents

1. [Quick Scan (2 minutes)](#quick-scan)
2. [Deep Analysis (10 minutes)](#deep-analysis)
3. [Adversarial Review Protocol](#adversarial-review-protocol)
4. [Scoring Rubric](#scoring-rubric)

---

## Quick Scan

**Time:** 2 minutes  
**Purpose:** Catch obvious AI signals before deeper review

### Vocabulary Flags

Count occurrences:

| Term | Count | Threshold |
|------|-------|-----------|
| furthermore/moreover/additionally | _ | ≤1 per page |
| leverage/utilize/facilitate | _ | 0 preferred |
| it's worth noting/importantly | _ | 0 |
| delve/navigate/embark | _ | 0 |
| robust/seamless/comprehensive | _ | ≤1 per page |
| groundbreaking/transformative | _ | 0-1 total |

**Action:** If any term exceeds threshold, flag for revision.

### Structure Flags

- [ ] Conclusion starts with "In conclusion/Overall/In summary"
- [ ] All paragraphs similar length (±20 words)
- [ ] Bullets/lists appear mid-document unexpectedly
- [ ] Every paragraph has transition at start

**Action:** If 2+ checked, flag for structural revision.

### Quick Verdict

- **Pass:** 0-1 vocabulary flags, 0-1 structure flags
- **Review:** 2-3 total flags
- **Revise:** 4+ total flags

---

## Deep Analysis

**Time:** 10 minutes  
**Purpose:** Comprehensive authenticity assessment

### Section A: Lexical Analysis

**A1. AI Vocabulary Density**
Scan for all terms in `ai-vocabulary-list.md`

| Category | Count | Notes |
|----------|-------|-------|
| Transitional phrases | _ | |
| Corporate jargon | _ | |
| Hedging language | _ | |
| Grandiose descriptors | _ | |
| Journey metaphors | _ | |

**Score:** ___ / 5 (lower is better)
- 0-5 total: Excellent
- 6-15 total: Acceptable
- 16+: Needs revision

**A2. Vocabulary Diversity**
- Unique words / total words: ___%
- Target: >60% for short text, >40% for long text

### Section B: Structural Analysis

**B1. Paragraph Length Variance**
List word counts for each paragraph:
[ ], [ ], [ ], [ ], [ ], [ ], [ ], [ ]

Calculate:
- Mean: ___
- Range (max - min): ___
- Standard deviation: ___

**Score:**
- SD > 30: Excellent human variance
- SD 15-30: Acceptable
- SD < 15: Too uniform (AI signal)

**B2. Sentence Length Variance**
Sample 10 consecutive sentences, count words:
[ ], [ ], [ ], [ ], [ ], [ ], [ ], [ ], [ ], [ ]

- Shortest: ___
- Longest: ___
- Range: ___

**Score:**
- Range > 25 words: Excellent
- Range 15-25: Acceptable
- Range < 15: Too uniform

**B3. Structural Pattern Check**
- [ ] Participial trailing phrases (", -ing..."): Count ___
- [ ] "From X to Y" constructions: Count ___
- [ ] Semicolon-connected clauses: Count ___
- [ ] Topic-sentence first in every paragraph: Yes/No

### Section C: Voice Analysis

**C1. Personality Markers**
- [ ] First person ("I", "we") present where appropriate
- [ ] Direct reader address ("you") used
- [ ] Opinion/position stated clearly
- [ ] Rhetorical questions included
- [ ] Humor or personality visible
- [ ] Contractions used naturally

**Score:** ___ / 6 checked (higher is better)
- 4-6: Strong voice
- 2-3: Moderate voice
- 0-1: Weak voice (AI signal)

**C2. Hedging Density**
Count qualifying phrases per 500 words:
- "arguably", "perhaps", "it seems"
- "could be", "might be", "may"
- "to some extent", "in a sense"

**Score:**
- 0-2 per 500: Natural
- 3-5 per 500: Moderate hedging
- 6+ per 500: Over-hedged (AI signal)

### Section D: Read-Aloud Test

Read text aloud and note:
- [ ] Natural breathing points exist
- [ ] Rhythm varies (not monotonous)
- [ ] Emphasis falls where intended
- [ ] No awkward word combinations
- [ ] Sounds like a person, not a manual

**Pass:** All checked  
**Review:** 3-4 checked  
**Revise:** <3 checked

---

## Adversarial Review Protocol

**Purpose:** Simulate sophisticated AI detection methods

### Round 1: Pattern Detection

Ask: "What would an AI detector flag?"

1. **Perplexity check:** Is any phrase the "most likely next word" repeatedly?
2. **Burstiness check:** Is sentence length variance sufficient?
3. **Vocabulary check:** Any high-frequency AI terms present?

Document findings: _______________

### Round 2: Human Inconsistency Test

Ask: "Does this feel too polished?"

1. **Perfection paradox:** Is grammar/spelling too perfect?
2. **Balance bias:** Are arguments too evenly balanced?
3. **Structure precision:** Is organization too logical?

Humans make minor imperfections. Too-clean text signals AI.

Document findings: _______________

### Round 3: Personality Presence

Ask: "Could I identify the writer?"

1. **Voice distinctiveness:** Does this sound like anyone in particular?
2. **Opinion presence:** Does the writer commit to positions?
3. **Unique observation:** Are there details only this person would notice?

Document findings: _______________

### Synthesis

Combine findings from all three rounds:
- **Passed all rounds:** Ready for publication
- **Failed 1 round:** Targeted revision needed
- **Failed 2+ rounds:** Substantial revision needed

---

## Scoring Rubric

### Overall Authenticity Score

| Component | Weight | Score (1-5) | Weighted |
|-----------|--------|-------------|----------|
| Vocabulary | 25% | _ | _ |
| Structure | 25% | _ | _ |
| Voice | 30% | _ | _ |
| Read-aloud | 20% | _ | _ |
| **TOTAL** | 100% | | **___** |

### Score Interpretation

| Score | Rating | Action |
|-------|--------|--------|
| 4.5-5.0 | Excellent | Publish |
| 4.0-4.4 | Good | Minor touch-ups |
| 3.0-3.9 | Acceptable | Targeted revision |
| 2.0-2.9 | Weak | Significant revision |
| <2.0 | Poor | Full rewrite |

---

## Final Sign-Off

Before publication:

- [ ] Quick scan passed
- [ ] Deep analysis score ≥3.5
- [ ] Adversarial review passed
- [ ] Read-aloud test passed
- [ ] Reviewer signature: _______________
- [ ] Date: _______________

---

## Document-Type Specific Thresholds

### Academic/Research Papers

**Adjusted voice expectations:**
- First person ("we") expected: ✅
- Direct reader address ("you"): Optional (Discussion sections)
- Rhetorical questions: 1-2 per paper in Discussion
- Contractions: 0-3 acceptable
- Humor/personality: Not expected

**Adjusted voice score thresholds:**
- 3-4/6: Strong voice for academic
- 2/6: Acceptable
- 0-1/6: Weak

**Legitimate patterns (don't flag):**
- "We present/propose/introduce"
- "This paper/study"
- Formal section transitions
- Evidence-based hedging

### Creative/Narrative Writing

**Heightened voice expectations:**
- All 6 personality markers expected
- 5-6/6: Required for publication
- 4/6: Needs more voice

### Technical Documentation

**Adjusted expectations:**
- Contractions: 0 expected
- Personality markers: 2-3/6 acceptable
- Focus on clarity over voice
- Parallel structure acceptable

---

## Validation Notes for Practitioners

> **Important:** These metrics are guidelines, not absolutes. Research shows AI detectors have 10-20% false positive rates on legitimate formal writing. A passing validation score indicates quality improvement, not guaranteed detection evasion.

> **For academic writing:** Many "AI tells" are legitimate academic conventions. Prioritize fixing empty hedging, corporate buzzwords, and structural uniformity. Preserve formal register, explicit structure, and evidence-based hedging.


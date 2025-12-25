---
description: Humanize Writing - Use when text sounds robotic, generic, or AI-generated. Transform formulaic prose into authentic, human-sounding content by removing tell-tale patterns (transitions, hedging, buzzwords) and injecting natural voice, rhythm, and structure.
---

# Humanize Writing

> *Stop sounding like a machine. Start sounding like a person.*

---

## Quick Example

**Before:**
> It is important to note that leveraging innovative solutions can facilitate enhanced productivity. Furthermore, organizations should utilize best practices to optimize their workflows. In conclusion, this approach represents a paradigm shift in operational efficiency.

**After:**
> Good tools make you faster. Use what works. That's it.

---

## Quick Reference

### Profiles

| Profile | Focus | Use Case |
|---------|-------|----------|
| **Lite** | **Vocabulary** | Quick cleanup, emails, short notes |
| **Standard** | **Structure** | Blog posts, marketing copy, **Default** |
| **Deep** | **Voice** | Personal essays, thought leadership, fiction |
| **Technical** | **Precision** | Docs, academic (removes fluff, keeps formality) |

### Mode Detection

| Mode | Trigger | Process |
|------|---------|---------|
| **ANALYZE** | "check", "scan", "rate" | Audit → Score → Report |
| **FIX** | "humanize", "improve", "rewrite" | Identify → Apply → Validate |
| **CREATE** | "write", "draft", "generate" | Plan → Draft (Humanized) → Verify |

### Strategy Detection

| Strategy | Trigger | Behavior |
|----------|---------|----------|
| **SAFE** | "preserve meaning", "minimal changes" | Vocab swaps only, no structural changes |
| **BOLDER** | "make it pop", "engaging" | High sentence variance, rhetorical questions |
| **GHOST** | "match style", "in the voice of" | Deep style analysis + strict pattern matching |

---

## Core Formula

```
H(P, L) = Profile P at Level L
Default: H(Standard, 2)

Execution Pattern:
[Scan] → Vocab Layer → [Check] → Structure Layer → [Check] → Voice Layer → [Final Verify]
```

---

## Phase -1: Target Analysis (Pre-Execution)

When file/text is provided:

```
1. MEASURE content size and type:
   < 5KB      → SMALL    → Process inline
   5-15KB    → MEDIUM   → Create scratch notes
   15-30KB   → LARGE    → Process in 3 chunks
   > 30KB    → MASSIVE  → Mandatory chunking (10KB max per chunk)

2. DETECT content type:
   - Email/Chat -> Lite
   - Blog/Marketing -> Standard
   - Narrative -> Deep
   - Docs -> Technical

3. ESTIMATE AI Score:
   - Transitions/1000 words
   - Hedging density
   - Passive voice %
```

---

## Phase 0: Intent Detection

Infer from user language:

| Signal | Profile | Vector |
|--------|---------|--------|
| "less robotic" | Standard | ISOMETRIC |
| "sound like me" | Deep | ISOMETRIC |
| "clean up" | Lite | ISOMETRIC |
| "expand on this" | Standard | FORWARD |
| "summarize naturally" | Standard | BACKWARD |

**Default if ambiguous**: Standard + ISOMETRIC

---

## Phase 1: Diagnosis (The "AI Tells")

Scan for high-risk patterns before touching text:

| Category | Markers (If found > 3 times, FLAG) |
|----------|-------------------------------------|
| **Lazy Transitions** | "In conclusion", "Furthermore", "Moreover", "It is important to note" |
| **Hedging** | "Arguably", "One could say", "It appears that", "Tends to" |
| **Buzzwords** | "Leverage", "Utilize", "Facilitate", "Tapestry", "Delve", "Landscape" |
| **Structure** | Uniform paragraph length (the "Wall of Text"), Perfect grammar (no fragments) |

---

## Phase 2: Application Layers

Apply changes based on Profile:

### Layer 1: Vocabulary (All Profiles)
*   **Kill:** "In conclusion", "It is worth noting".
*   **Swap:** "Leverage" -> "Use", "Facilitate" -> "Help".
*   **Decrude:** Remove "It is important to..." -> Just say the thing.

### Layer 2: Structure (Standard/Deep)
*   **Variance:** Split long paragraphs. Merge short ones.
*   **Rhythm:** Alternating sentence lengths (Short. Medium. Long flowing sentence. Short.)
*   **Directness:** Drop topic sentences if they just announce what's coming.

### Layer 3: Voice (Deep Only)
*   **Personal:** Inject "I think", "We found".
*   **Colloquial:** Use contractions ("It's", "We're").
*   **Fragments:** "Not always." "Exactly."
*   **Questions:** Rhetorical engagement (Max 1 per 500 words).

---

## Phase 3: Validation Protocol

Check against thresholds:

| Metric | Target (Standard) | Target (Technical) |
|--------|-------------------|---------------------|
| Passive Voice | < 20% | < 30% |
| Hedging Density | < 0.5% | < 1% |
| Sentence Var. | High (Jagged) | Medium |
| AI Banned Words | 0 | 0 |

---

## Content-Type Matrix

| Type | Formality | Personal | Contractions |
|------|-----------|----------|--------------|
| Blog | Low | High | Yes |
| Email | Low | High | Yes |
| Academic | High | Low | No |
| Marketing | Low | High | Yes |
| Technical | Medium | Low | No |

---

## Anti-Patterns

❌ **Over-correction**: Making text *too* colloquial for the context.
❌ **Random Errors**: Adding typos to sound human.
❌ **The "Swapped" Look**: Just finding/replacing words without rhythm changes.
❌ **Lost Meaning**: Removing hedging where uncertainty is scientifically required.

---

## Execution Checklist

```
[ ] 1. Detect MODE (ANALYZE/FIX/CREATE)
[ ] 2. Check size, apply chunking if needed
[ ] 3. Identify Content Type & Select Profile
[ ] 4. Scan for AI Tells (Phase 1)
[ ] 5. Apply Layer 1 (Vocab)
[ ] 6. If Standard+: Apply Layer 2 (Structure)
[ ] 7. If Deep: Apply Layer 3 (Voice)
[ ] 8. Validate against Thresholds
[ ] 9. Return Humanized Output
```

**END OF SLASH COMMAND**

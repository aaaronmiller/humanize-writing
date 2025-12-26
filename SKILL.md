---
name: humanize-writing
description: |
  AUTOMATIC ACTIVATION: Use this skill whenever generating prose, documents, or written content exceeding three paragraphs. Also use when: writing sounds robotic, AI-generated, formulaic, too formal, stiff, awkward, wooden, boring, generic, bland, corporate, doesn't sound like me. Triggers: "make this sound human", "sounds like AI", "humanize this", "more natural", "authentic voice", "less corporate", "more conversational", "remove clichés", "polish my writing", "edit for voice", "make it flow", "too robotic", "stiff writing", "doesn't sound right", "AI tells", "passive voice". Content types: blog posts, emails, marketing copy, essays, documentation, LinkedIn posts, cover letters, articles, reports, proposals, newsletters, social media posts, video scripts, product descriptions. Apply automatically to any substantial written output to ensure human voice.
license: MIT
metadata:
  author: ice-ninja
  version: "1.1"
---

**MANDATORY: Before applying this skill, you MUST read and fully load every file in the `references/` directory.** These files contain vocabulary blacklists, pattern guides, and validation checklists that are required for correct execution. Do not proceed until all reference files have been opened and their contents are in your context.

# Humanize Writing System

Turn robotic AI prose into writing that sounds like you wrote it.

## Core Framework

### What "Humanizing" Means

This system removes three categories of AI tells:

1. **Vocabulary tells** - Overused transitions, hedging language, marketing clichés
2. **Pattern tells** - Repetitive sentence structures, excessive passive voice, artificial rhythm
3. **Tone tells** - Overly formal register, lack of personal voice, generic enthusiasm

Your meaning stays intact. It just sounds like a person wrote it.

## Quick Start

### For Analyzing Text

Ask Claude to:
```
Analyze this text using the humanize-writing validation checklist:

[paste text]

Focus on: [vocabulary/structure/voice]
```

### For Improving Text

Ask Claude to:
```
Please humanize this text:

[paste text]

Current tone: [formal/academic/casual]
Content type: [blog post/essay/technical docs/email]
```

### For Writing New Content

Ask Claude to:
```
Write a [content type] about [topic] using humanize-writing principles.

Target audience: [describe]
Tone: [describe]
```

## The Humanization Process

### Phase 1: Identify AI Patterns

Hunt for these red flags:

- **Transition overuse**: "Furthermore," "In conclusion," "It's important to note," "It's worth mentioning"
- **Hedging language**: "arguably," "one could say," "it's possible that," "tend to," "generally," "tend"
- **Marketing clichés**: "revolutionize," "game-changing," "innovative," "next-generation," "cutting-edge," "state-of-the-art"
- **Passive voice density**: >30% passive constructions in a paragraph
- **Question openings**: >1 rhetorical question per 500 words
- **Overexplained transitions**: "To further illustrate this point," "Building on this idea"

### Phase 2: Apply Humanization Techniques

#### Vocabulary Layer

Swap AI words for human ones:
- "facilitate" → "help," "make it easier"
- "leverage" → "use," "take advantage of"
- "utilize" → "use"
- "paramount" → "critical," "crucial," "essential"
- "illuminate" → "show," "explain," "reveal"
- "synthesize" → "combine," "pull together," "merge"
- "conceptualize" → "imagine," "think of," "picture"

#### Sentence Structure Layer

Vary sentence patterns:
- Mix short punchy sentences with longer flowing ones
- Alternate between active and passive voice (aiming for 70%+ active)
- Break up topic-first patterns: Don't always start with the subject
- Use occasional fragments for emphasis

#### Rhythm & Voice Layer

Make it sound like talking:
- Occasional contractions ("don't," "it's," "we're") in appropriate contexts
- Conversational markers: "Look," "Here's the thing," "Actually," "So"
- Personal perspective: "I notice that," "In my experience," "I've found"
- Concrete examples over abstractions
- Direct address to reader when appropriate

**Colloquialisms (Use Sparingly):**
- Casual: "honestly," "basically," "like," "you know"
- Digital: "tbh," "idk," "ngl" (only for very informal content)
- Emphatic: "totally," "absolutely," "for real"

**Humor Injection (When Appropriate):**
- Self-deprecating asides: "(I learned this the hard way)"
- Mild exaggeration: "about a million times"
- Unexpected specificity: "the 37th email that day"
- Rule: Max 1-2 humor attempts per 500 words; never force it

#### Writer Mimicry Mode

Want to sound like a specific writer? Analyze their patterns:
```
Analyze [Author]'s writing for:
1. Average sentence length
2. Vocabulary tier (simple/complex)
3. Personal pronoun usage
4. Signature phrases or structures
5. Humor style (if any)

Then apply these patterns to the target text.
```

### Phase 3: Validate Against Checklist

Run through this before shipping:

- ✓ No transitions in first sentence of paragraphs
- ✓ Active voice dominates (70%+)
- ✓ Varies sentence length (3-5 word to 20+ word sentences mixed)
- ✓ No paragraph opens with "It is" or "There are"
- ✓ Hedging language <5% of total words
- ✓ No repeated phrases within 500 words
- ✓ Reads naturally when read aloud
- ✓ Personal voice present (pronouns, direct address)
- ✓ No generic enthusiasm ("exciting," "amazing," "incredible" used sparingly)
- ✓ Clichés replaced with specific descriptions

## Validation Checklist (12-Point Scoring)

Use this to verify humanization quality:

### Structure (4 points)
- [ ] No paragraph begins with transition word or "It is/There are"
- [ ] Sentence variety present (short and long mixed)
- [ ] Active voice dominates (70%+)
- [ ] Paragraph length varies

### Vocabulary (3 points)
- [ ] Hedging language minimal (<5% of text)
- [ ] No clichés (checked against blacklist)
- [ ] Technical terms explained when needed, but terminology specific

### Voice (3 points)
- [ ] Personal perspective evident (pronouns used appropriately)
- [ ] Conversational elements present (not excessive)
- [ ] No generic enthusiasm (amazing, incredible, exciting <3 uses total)

### Readability (2 points)
- [ ] Reads naturally when read aloud
- [ ] Clear connections between ideas
- [ ] No repeated phrases within 500 words

**Score**: 12 points total. Aim for 10+.

## Content-Type Specific Guidance

### Blog Posts
Target: 60-70% active voice, conversational tone, personal perspective welcome

Humanization focus:
- Open with specific observation, not broad generalization
- Use "I discovered," "I realized" instead of "Research shows"
- Specific examples before abstract principles
- Direct reader engagement ("here's why this matters to you")

### Academic/Technical Writing
Target: 75%+ active voice, formal but clear, expert without pretense

Humanization focus:
- Replace "It can be argued" with direct statement: "This suggests"
- Avoid "one could say" — just say it
- Use "I," "we," and "you" appropriately
- Technical terms stay, but explain them clearly
- Show your reasoning process, not just conclusions

### Emails
Target: Natural conversation, directness, personality

Humanization focus:
- First sentence answers: Why am I reading this?
- Clear ask/call-to-action (not buried in hedging)
- Contractions encouraged
- Conversational openers fine ("Hope you're doing well")

### Product/Marketing Copy
Target: Enthusiasm without clichés, benefit-focused, specific

Humanization focus:
- Replace "revolutionary" with specific benefit
- "Game-changing" → describe the actual change
- "Next-generation" → "newly built," "recent"
- Concrete details over superlatives

## Common AI Tells & Replacements

| AI Tell | Better Alternative |
|---------|-------------------|
| "In conclusion" | (Just state it. End naturally.) |
| "Furthermore" | "Also," "Plus," or just continue |
| "It is important to note" | Delete this. State the fact. |
| "arguably" | Delete or commit to statement |
| "one could say" | Say it directly |
| "tend to" | Be specific: "often," "usually," or specific percentage |
| "It's worth mentioning" | Delete. Mention it if it's worth it. |
| "revolutionary" | Describe actual change |
| "paradigm shift" | Use specific change description |
| "cutting-edge" | "Recent," "newly developed," be specific |
| "Interestingly" | Show why it's interesting through detail |
| "As mentioned previously" | Reference specifically or delete |
| "In this regard" | Delete. Connect idea directly. |

## Workflow Examples

### Example 1: Blog Post Analysis

**Original (AI-generated):**
> "In conclusion, it's important to note that leveraging social media platforms can facilitate meaningful engagement with target audiences. Furthermore, this approach can revolutionize how companies conceptualize customer relationships. One could argue that this represents a paradigm shift in marketing strategy."

**Humanized:**
> "So here's what I'm getting at: use social media to actually talk to your customers. Most companies treat it like a broadcast channel. But the best ones treat it like a conversation. That changes everything about how you build relationships."

**Changes made:**
- Removed: "In conclusion," "it's important to note," "leverage," "facilitate," "revolutionize," "conceptualize," "paradigm shift," "one could argue"
- Added: Personal voice ("I'm getting at," "here's what"), contractions, specific observation
- Changed: Generic statement → concrete scenario

### Example 2: Email Humanization

**Original:**
> "It is worth mentioning that we have identified several opportunities for optimization regarding your current implementation. The aforementioned strategies could facilitate improved performance metrics. We would appreciate the opportunity to discuss this matter further at your earliest convenience."

**Humanized:**
> "We've spotted a few ways to make your setup faster. I'd love to walk you through them—should take 15 minutes. When works best for you this week?"

**Changes made:**
- Removed: "It is worth mentioning," "aforementioned," "facilitate," "appreciate the opportunity," "at your earliest convenience"
- Added: Specificity, directness, urgency, personal tone

## Quantitative Thresholds

Numbers to hit:

- **Passive voice**: Target <30%. Measure: Count passive constructions, divide by total sentences.
- **Hedging density**: Target <5%. Measure: Count hedging words (arguably, tend to, generally, seem, appear, may), divide by total words.
- **Sentence variety**: Target 3-5 different lengths represented in each 5-sentence chunk.
- **Repetition**: Zero repeated phrases within 500 words.
- **Transitions per paragraph**: 0-1 transitions opening paragraphs (not counting "and," "but," "so").
- **AI vocabulary**: Zero instances of blacklisted high-risk terms.

## When NOT to Humanize Everything

Not everything needs personality:

- Legal documents (maintain precision over personality)
- Formal academic papers (maintain scholarly register)
- Technical specifications (clarity over voice)
- Official announcements (consistency over personality)

For these, just cut the obvious clichés and excess hedging. Keep the formality.

## Integration Tips

### For Claude Web Chat
1. Share this system as Project Knowledge
2. Reference it by name: "Use humanize-writing principles..."
3. Paste content and ask for analysis or improvement
4. Iterate with specific focus areas

### Best Practices
- **Be specific about content type** — Different writing has different standards
- **Provide context** — Audience and purpose guide humanization strategy
- **Iterate** — First pass removes obvious AI tells; second pass refines voice
- **Read aloud** — Ultimate test is whether it sounds natural when spoken
- **Keep meaning** — Humanization preserves all original information and intent

## Reference Files
- `references/ai-vocabulary-list.md`: Comprehensive blacklist of AI words
- `references/content-type-guides.md`: Detailed guides for Blogs, Emails, etc.
- `references/sentence-patterns.md`: Sentence pattern analysis
- `references/rhythm-techniques.md`: Advanced rhythm techniques
- `references/validation-checklist.md`: Full validation rubric

## Ethical Framework
- **Do:** Use this to improve clarity, engagement, and personal voice.
- **Do Not:** Use this to deceive about authorship in academic or regulated contexts where disclosure is required.
---

**System Version**: Web Integration Format  
**Updated**: December 2025  
**For use**: Claude.ai Web Interface  
**Format**: Project Knowledge compatible

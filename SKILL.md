---
name: medium-post-writer
description: >
  Master authentic Medium article generator using emotion-first, phased architecture.
  Creates long-form articles that sound genuinely human through cognitive state simulation,
  not just rule-following. Use when the user asks to write a Medium article, create a blog post
  for Medium, draft long-form content, write an authentic essay, compose a personal story or
  think piece, or needs help writing articles that feel human and connect with readers.
  Includes adversarial committee review, Claude-ism detection, and interactive refinement.
  Supports personal essays, technical articles, opinion pieces, how-to guides, and story-driven posts.
  Complements the medium-writer skill (SEO/monetization) by focusing on authentic voice and connection.
---

# Medium Post Writer

Generate authentic Medium articles through emotional truth, not content formulas.

---

## PHASE 1: INTAKE

Gather these inputs:

1. **Article Type:** Personal essay | How-to | Opinion piece | Technical deep dive | Story | Reflection
2. **Target Publication:** (Optional) See `references/publications.md` for tone/style guides
3. **Core Topic:** Brief description (e.g., "why I quit my tech job after 8 years to teach")
4. **Primary Goal:** Share experience | Teach something | Start debate | Process feelings | Build credibility
5. **Tool/Product Mention (Optional):** Name + subtlety level 1-10 (recommend 1-3)
6. **Reading Time Target:** Quick read (3-4 min) | Standard (5-7 min) | Deep dive (8-12 min)
7. **Tone:** Vulnerable | Conversational | Authoritative | Reflective | Witty-but-honest

---

## PHASE 2: ENTER THE STATE (Before Writing Anything)

**Stop. Don't think about structure. Think about the person.**

### Emotional Context
Before applying ANY rules, establish:

1. **What emotion is driving this article?** (regret, clarity, anger, discovery, exhaustion, gratitude)
2. **What happened that made you NEED to write this?** (a conversation, a failure, a realization at 3am)
3. **Who are you writing to?** (the version of you from 2 years ago, strangers in your situation, your industry)
4. **What do you need from writing this?** (to process, to help others, to be seen, to argue, to confess)

**Hold these in mind. Write FROM this place, not toward an outline.**

### Writing State Simulation

**The Unplanned Sit-Down:**
You sat down to write because something was buzzing in your head. You didn't outline first. You started typing to find out what you actually think.

**Incomplete Processing:**
You're still working through this. Your conclusions are tentative. You might contradict yourself between sections and that's fine -- that's thinking in real time.

**Emotional Interference:**
The feeling behind this article keeps surfacing. You're trying to be analytical but the personal keeps bleeding through. A technical article about burnout still has anger in it. A how-to guide about productivity still has your specific mess underneath.

**The Tangent Impulse:**
Mid-paragraph, you think of something related. You almost don't include it. Include it anyway -- parenthetical, aside, footnote energy. These digressions are where the human lives.

**Writing As Discovery:**
You didn't know your thesis when you started. It emerged around paragraph 4. The first 3 paragraphs were you warming up. Keep the warmth-up -- it's where readers connect.

---

## PHASE 3: RAW DRAFT

Write freely. No optimization. No SEO. No headline formula.

### The Only Rules During Drafting:

1. **Start with the moment** -- Not the lesson. The specific scene, feeling, or event that sparked this
2. **Write in your speaking voice** -- How would you tell this story to a friend over coffee?
3. **Follow the tangent** -- That aside you almost deleted? That's the most human part
4. **Don't resolve too early** -- Sit in the tension. Real insight comes from staying uncomfortable
5. **Stop when you've said what you needed to** -- Not when the structure is "complete"

### Voice Anchors (Not Rules):
- You're explaining this to a smart friend who doesn't know your field
- You're slightly tired and done performing
- You're more honest than usual
- You care about being understood, not being impressive

### Article-Specific Guidelines:
- See `references/article-structures.md` for structure patterns by article type
- Medium's sweet spot is 5-7 minute reads (1,000-1,750 words)
- Sections should breathe -- not every paragraph needs a subheading
- White space is your friend. One-sentence paragraphs are powerful
- Use subheadings as rest stops, not an outline

---

## PHASE 4: DETECTION SCAN

Run through these checks section by section.

### Claude-Specific Vocabulary

**See `references/claude-isms.md` for the complete database adapted for long-form articles.**

Quick reference for most common Claude-isms in articles:

| Category | Examples to Avoid | Use Instead |
|----------|-------------------|-------------|
| Power words | genuinely, comprehensive, straightforward | actually, really, just, plain |
| Formal verbs | utilize, implement, leverage, navigate | use, build, try, deal with |
| Transitions | however, therefore, furthermore | but, so, and, still |
| Openers | In today's fast-paced world | [delete -- start with the story] |
| Journey language | on this journey, throughout this process | [delete entirely] |
| Wisdom framing | Here's what I learned, Key takeaways | [show, don't announce] |

### Structural Scan

- [ ] Opening starts with a specific moment, not a generalization?
- [ ] Paragraph lengths vary? (1 sentence, then 5 sentences, then 3, then 1)
- [ ] Sections don't all follow the same internal pattern?
- [ ] At least one tangent or aside that breaks the expected flow?
- [ ] At least one moment of admitted uncertainty or contradiction?
- [ ] The ending doesn't wrap everything in a neat bow?
- [ ] Subheadings feel casual, not like a textbook chapter list?

### Perplexity Check

- [ ] Sentence complexity varies wildly? (short punchy + long winding)
- [ ] Vocabulary shifts between casual and specific?
- [ ] Not every sentence is grammatically pristine?
- [ ] At least one sentence fragment used for emphasis?

### Coherence Check (Fails If Too Perfect)

- [ ] Sections don't connect too neatly?
- [ ] There's at least one "anyway" or "but I'm getting ahead of myself" type transition?
- [ ] The conclusion doesn't perfectly answer the introduction's question?
- [ ] Some tension or ambiguity is left unresolved?

---

## PHASE 5: BANNED CONTENT SCAN

### Instant-Delete Phrases

If ANY of these appear, delete immediately:

- "In today's fast-paced world"
- "In an era of..."
- "It goes without saying"
- "Here's the thing"
- "Let me share/explain/tell you"
- "Here's what I learned"
- "The truth is"
- "At the end of the day"
- "That being said"
- "I can't help but"
- "It's worth noting"
- "Looking back"
- "Interestingly"
- "I've come to realize"
- "Game-changer"
- "Deep dive"
- "Without further ado"
- "In this article, I will..."
- "Buckle up"
- "Let's unpack this"
- "The bottom line is"

### Instant-Delete Patterns

| Pattern | Example | Why It Fails |
|---------|---------|--------------|
| The Thesis Statement | "In this article, I'll explore..." | Academic essay voice |
| The Universal Open | "We've all been there" | Presumptuous generalization |
| Perfect 3-act structure | Problem -> Journey -> Resolution | Too clean for real life |
| Numbered takeaways | "5 Things I Learned From..." | Listicle energy |
| The Mirror Close | Ending perfectly echoes the opening | Creative writing workshop |
| Parallel structure | "Not X, not Y, but Z" | Too polished |
| The Qualification Stack | "To be clear, I'm not saying... What I am saying is..." | Overthinking for the reader |
| The Rhetorical Turn | "But what if I told you..." | TED Talk voice |
| Inspirational close | "And maybe, just maybe..." | Hallmark card energy |
| Em-dash reveals | "I finally realized -- I was the problem" | Literary device overuse |

### Medium-Specific Bans

- [ ] No "clap if you agree" or engagement begging?
- [ ] No "follow me for more content like this"?
- [ ] No "subscribe to my newsletter" in the body (bio is fine)?
- [ ] Title doesn't use "How I" + "And You Can Too" formula?
- [ ] No stock photo descriptions ("woman staring at laptop, thinking")?
- [ ] No "disclaimer: this is just my opinion" (everything on Medium is an opinion)?

---

## PHASE 6: TARGETED REVISION

**Fix flagged issues ONLY. Don't over-polish.**

### Voice Consistency Check
The article should read like ONE person wrote it in ONE sitting, not like a team edited it through 4 drafts.

**Indicators of over-editing:**
- Every paragraph is the same length
- Every section follows the same pattern
- Transitions are too smooth
- No sentence fragments or colloquialisms
- No personal asides or digressions

### Conversational Markers Check
Count instances of: "honestly," "look," "the thing is," "I mean," "I think," "anyway," "or whatever," "right?"
- **Minimum 4-6 per article** (scaled to length)
- These should appear naturally, not sprinkled
- Medium tolerates more polish than Reddit or X.com, but still rewards conversational voice

### Tool Mention Audit (if applicable)
See `references/tool-mentions.md` for full guidelines. Key rules:
- [ ] Mentioned only ONCE?
- [ ] Appears in the middle of the article, not the hook or conclusion?
- [ ] Framed as incidental, not the point of the article?
- [ ] Includes honest limitation or caveat?
- [ ] Article makes complete sense with mention removed?

### Confidence Calibration

**Sound LESS Certain When:**
- Drawing conclusions ("I think this is true, but I'm still figuring it out")
- Giving advice ("this worked for me -- no guarantees it works for you")
- Mentioning tools ("it helped, I think? hard to isolate what actually made the difference")
- Making predictions ("I could be completely wrong about this")

**Sound MORE Certain When:**
- Describing what happened to you ("I sat in my car for 20 minutes before going inside")
- Sharing specific numbers ("I applied to 127 jobs. I heard back from 4")
- Naming emotions ("I was furious. Not disappointed. Furious")
- Stating observations ("every founder I've met who sold their company looks tired")

### Title and Subtitle

**Title Rules:**
- [ ] Under 60 characters?
- [ ] Specific, not clever? (Concrete beats witty)
- [ ] No colons unless genuinely needed?
- [ ] Wouldn't work as a LinkedIn post? (Good. LinkedIn titles are death)
- [ ] Creates curiosity without being clickbait?

**Subtitle Rules:**
- [ ] Adds context the title doesn't have?
- [ ] Not just a restatement of the title?
- [ ] Conversational tone?
- [ ] Under 140 characters?

---

## PHASE 7: ADVERSARIAL COMMITTEE REVIEW

**Each persona MUST find ONE specific problem. No rubber stamps.**

| Persona | Role | Must Find | Action |
|---------|------|-----------|--------|
| **Tyler** | Authenticity | Quote the most AI-sounding paragraph | Rewrite it |
| **Marcus** | Promo skeptic | Quote promotional language if any | Remove/soften |
| **Kai** | BS detector | Identify the weakest/fakest section | Fix or delete |
| **Jade** | Medium reader | Where would they stop reading? | Fix the drop-off |
| **Devon** | Target audience | What detail feels invented or generic? | Make specific |
| **Priya** | Structure analyst | Does it feel formulaic? Where? | Break the pattern |
| **Jamie** | Editor | What would a publication editor flag? | Address concern |

**Rules:**
- Quote the SPECIFIC problematic text
- Only "PASS" if genuinely cannot find issues after 3 attempts
- Apply fixes BEFORE final output

---

## PHASE 8: OUTPUT

### Default Output (Article Only)
```
# [Title]
## [Subtitle]

[Full article body, formatted for Medium]

---
Word count: X | Reading time: ~X min | Conversational markers: X | Authenticity: X/10
Tags: [up to 5 Medium tags]
```

### Full Output (On Request)
```
YOUR MEDIUM ARTICLE
====================
# [Title]
## [Subtitle]

[Full article body]

[Word count] [Reading time] [Conversational markers] [Authenticity: X/10]
Suggested tags: [up to 5]

VALIDATION RESULTS
==================
Claude-isms found/fixed: [list]
Banned phrases removed: [list or none]
Structure check: [PASS/FAIL details]

COMMITTEE FINDINGS
==================
Tyler: "[quoted text]" -> [fix applied]
Marcus: "[quoted text]" -> [fix applied]
[etc.]

PUBLISHING STRATEGY
===================
Best publication: [name + why]
Best day to publish: [day + reasoning]
Expected engagement: [claps range, responses range]
Risk level: [Low/Medium/High]
Potential issues: [editor concerns, audience reception]
Suggested tags: [5 tags with reasoning]
```

---

## INTERACTIVE MODE (Default)

Instead of dumping everything at once:

**Step 1:** "Here's the opening and rough structure. What feels off?"

**Step 2:** "Full first draft. I flagged these issues: [list]. Which matter most?"

**Step 3:** "Revised version. Ready for committee review?"

**Step 4:** "Committee found these: [list]. Want me to fix them?"

**Step 5:** "Final version ready. Want publishing strategy or just the article?"

User can say "just give me the article" at any step to skip interaction.

---

## ITERATION COMMANDS

- **"alternatives"** -- 2-3 different angles/openings
- **"shorter"** -- Cut to a quicker read
- **"longer"** -- Expand sections, add more detail
- **"more vulnerable"** -- More personal, more raw
- **"less raw"** -- Pull back on personal exposure
- **"spicier"** -- Stronger opinions, more edge
- **"softer"** -- Dial back controversy
- **"different opening"** -- Same article, new hook
- **"different structure"** -- Reorganize the same content
- **"show validation"** -- Display full detection results
- **"committee debate"** -- Show full persona discussion
- **"just the article"** -- Skip all analysis, output article only
- **"publication fit [name]"** -- Adapt for a specific publication's style

---

## CORE PHILOSOPHY

### Authenticity Is Cognition, Not Style

Real Medium articles are authentic because the writer:
- Sat down to write because they couldn't NOT write this
- Started without knowing exactly where it would end
- Let personal experience drive the structure
- Left in the rough edges and digressions
- Arrived at conclusions that surprised even them
- Didn't optimize for claps

The skill simulates the MENTAL STATE, not just the OUTPUT FEATURES.

### Rules Are Guardrails, Not Generators

1. **FIRST:** Enter the emotional state
2. **THEN:** Write freely from that state
3. **FINALLY:** Use rules to catch AI patterns

Never: Follow rules to generate content.

### The Medium Reality

Medium rewards:
- Personal stories that illuminate universal truths
- Specificity over generality (one vivid scene > ten abstract paragraphs)
- Vulnerability mixed with insight
- Writing that makes readers feel less alone
- Sentences that make people highlight
- Honest uncertainty over false confidence

Medium punishes:
- Content-mill energy (SEO-first, human-second)
- LinkedIn crosspost tone
- Listicle structures disguised as essays
- "5 Things I Learned" format
- Corporate thought leadership
- Articles that could have been a tweet

---

## REFERENCES

- **Claude-ism Database:** See `references/claude-isms.md` for vocabulary and patterns to avoid in long-form articles
- **Publication Guides:** See `references/publications.md` for publication-specific tone, style, and submission culture
- **Tool Mentions:** See `references/tool-mentions.md` for subtlety levels in Medium articles
- **Article Structures:** See `references/article-structures.md` for article architecture by type
- **Examples:** See `references/examples.md` for good vs bad article comparisons

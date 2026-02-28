# Claude-Specific Vocabulary Database (Medium Edition)

Vocabulary, phrases, and patterns statistically overrepresented in Claude outputs. Adapted for detecting AI tells in long-form articles where structural patterns matter as much as word choice.

---

## Why Detection Works Differently on Medium

On X.com, a single word outs you. On Reddit, a pattern across paragraphs does. On Medium, it's **structural uniformity** that kills authenticity. A Medium article can use "however" once and survive. But if every paragraph is 4 sentences, every section follows the same arc, and every transition is smooth -- that's the tell.

Medium detection is about **rhythm and pattern**, not just vocabulary.

---

## CATEGORY 1: Formal Transition Words

Medium tolerates slightly more formality than Reddit/X.com, but Claude still overuses these.

| Claude Says | Article Alternative | Notes |
|-------------|-------------------|-------|
| however | but, still, though | One "however" per article max |
| therefore | so | or just let the logic speak |
| furthermore | also, and, plus | or just continue |
| nevertheless | still, but, even so | |
| consequently | so | |
| additionally | also, and, oh -- and | |
| moreover | also | maybe once per article |
| thus | so | |
| subsequently | then, after, later | |
| nonetheless | still | |
| conversely | but | |
| specifically | like, meaning | or just get specific |
| notably | especially | |
| indeed | (delete or use "really") | |
| certainly | sure, definitely | |

---

## CATEGORY 2: Filler Hedges (Overly Polite)

Medium articles can hedge -- but Claude hedges in a specific robotic way.

| Claude Says | Article Alternative | Notes |
|-------------|-------------------|-------|
| I would say that | [just say it] | |
| It's important to note | [just note it] | |
| It's worth mentioning | [just mention it] | |
| I should mention | look, / honestly, | or just state it |
| I believe that | I think | or just state it directly |
| In my opinion | (just state the opinion) | |
| From my perspective | to me, the way I see it | |
| I must admit | honestly | |
| I have to say | look | |
| Allow me to | [delete] | |
| Let me explain | [just explain] | |

---

## CATEGORY 3: Formal Verb Choices

| Claude Says | Article Alternative | Notes |
|-------------|-------------------|-------|
| utilize | use | always |
| implement | build, try, set up | |
| facilitate | help, enable | |
| leverage | use | always |
| navigate | deal with, work through, figure out | |
| demonstrate | show | |
| possess | have | |
| require | need | |
| obtain | get | |
| commence | start, begin | |
| endeavor | try | |
| comprehend | understand, get | |
| establish | build, start, set up | |
| maintain | keep, sustain | |
| determine | figure out, decide | |
| ensure | make sure | |
| provide | give, offer | |
| modify | change, adjust | |
| eliminate | cut, drop, remove | |
| enhance | improve | |

---

## CATEGORY 4: Claude Power Words

These appear 3-10x more in Claude outputs. In a 1,500-word article, even 2-3 of these create a cumulative AI feel.

| Word | Severity | Article Alternatives |
|------|----------|---------------------|
| genuinely | CRITICAL | actually, really, for real |
| straightforward | CRITICAL | simple, easy, obvious, plain |
| comprehensive | CRITICAL | full, complete, thorough |
| absolutely | HIGH | totally, definitely, yes |
| essential | HIGH | important, key, necessary |
| fundamental | HIGH | basic, core |
| significant | HIGH | big, major, real |
| effectively | HIGH | basically, really, in practice |
| ultimately | HIGH | in the end, eventually |
| particularly | HIGH | especially |
| incredibly | HIGH | really, very, wildly |
| essentially | HIGH | basically, at its core |
| substantial | HIGH | big, real, serious |
| valuable | HIGH | useful, helpful, worth it |
| crucial | HIGH | important, key, critical |
| seamless | MEDIUM | smooth, easy |
| robust | MEDIUM | solid, strong |
| nuanced | MEDIUM | complicated, layered |
| streamlined | MEDIUM | simpler, cleaner |
| intuitive | MEDIUM | easy, natural, obvious |
| pivotal | MEDIUM | key, turning-point |

**Rule:** Maximum 2 words from this list per 1,000 words. Zero is better.

---

## CATEGORY 5: Structural Patterns (Most Important for Medium)

### Paragraph Length Uniformity
**AI Pattern:** Every paragraph is 3-5 sentences
**Human Pattern:** 1 sentence, then 6 sentences, then 2, then 1, then 4

**Test:** No two consecutive paragraphs should have the same sentence count.

### Section Arc Uniformity
**AI Pattern:** Every section follows Setup -> Detail -> Conclusion
**Human Pattern:** Some sections are one paragraph. Some are five. Some end abruptly.

**Test:** At least one section should be surprisingly short or surprisingly long.

### Transition Smoothness
**AI Pattern:** Every paragraph logically follows the previous one
**Human Pattern:** "Anyway." "But I'm getting off track." Topic jumps. Returns to earlier points.

**Test:** At least 2 transitions should feel abrupt or informal.

### Sentence Length Regularity
**AI Pattern:** Consistent 15-25 words per sentence
**Human Pattern:** Wild variance. 3 words. Then 40 words with two parentheticals.

**Test:** Standard deviation of sentence lengths should be > 10 words.

### The Perfect Arc
**AI Pattern:** Clear beginning-middle-end. Problem introduced, explored, resolved.
**Human Pattern:** The ending doesn't quite answer the beginning. Something is left unresolved. The writer is still thinking.

**Test:** The conclusion should introduce at least one new doubt or complication.

---

## CATEGORY 6: Opening Patterns (Instant AI Flags)

| Opening | Why It Fails | Fix |
|---------|--------------|-----|
| "In today's fast-paced world..." | Content mill cliche | Start with a specific moment |
| "We've all been there..." | Presumptuous generalization | Start with YOUR moment |
| "I've been thinking a lot about..." | Vague, no entry point | What SPECIFIC thing triggered it? |
| "Let me tell you about..." | Announces instead of doing | Just tell |
| "There's a common misconception..." | Academic essay voice | Show the misconception in action |
| "Picture this:" | Fiction workshop energy | Just put the reader in the scene |
| "If you're like me..." | Assumes shared experience | Describe YOUR experience |
| "[Topic] is everywhere these days" | Trend-piece filler | Why does it matter to YOU? |

### Better Openings (Medium Style)
- A specific scene with sensory detail ("I was sitting in my car in the parking lot...")
- A direct statement of the thing ("I quit my job on a Tuesday")
- A question you actually don't know the answer to
- A contradiction ("I love my work. I also fantasize about never opening my laptop again")
- Mid-action entry ("By the time I realized the deploy was broken, 400 users had already seen it")

---

## CATEGORY 7: Closing Patterns (Instant AI Flags)

| Closing | Why It Fails | Fix |
|---------|--------------|-----|
| "And that's the lesson" | Too neat | Leave something messy |
| "So what's the takeaway?" | Essay question format | Just end |
| "If there's one thing I've learned..." | Cliche wisdom packaging | Show, don't summarize |
| "The journey continues" | Journey language + cliche | |
| "And maybe, just maybe..." | Inspirational calendar | |
| "Here's to [positive thing]" | Toast format | |
| "What about you? I'd love to hear..." | Formulaic engagement ask | Ask something specific or don't ask |

### Better Closings (Medium Style)
- End on the uncertainty: "I still don't know if I made the right call"
- End on a specific image: "I closed my laptop and went outside for the first time that day"
- End mid-thought: "But that's a different article, I think"
- Circle back with a twist: Return to the opening scene but with changed context
- Just stop when you've said what you needed to say

---

## CATEGORY 8: Medium-Specific Humanizers

### Conversational Markers (Need 4-6 per article)
- honestly
- look
- the thing is
- I mean
- I think
- anyway
- right?
- sure
- fine
- or whatever
- basically

### Medium Writing Patterns
- One-sentence paragraphs for emphasis
- Parenthetical asides (like this one, which probably isn't necessary but here we are)
- Self-interruption: "But wait -- I'm getting ahead of myself"
- Footnote energy: casual additions that break the flow
- The mid-article confession: admitting something you didn't plan to share
- Addressing the reader casually: "you know what I mean"
- Second-guessing yourself mid-paragraph

### Uncertainty Markers
- "I think"
- "maybe"
- "I'm not sure about this, but"
- "or maybe not"
- "I could be wrong"
- "at least that's how it felt"

---

## STATISTICAL TARGETS FOR MEDIUM

| Metric | AI Typical | Human Target |
|--------|------------|--------------|
| Sentence length std dev | 4-6 words | > 10 words |
| Claude power words per 1000 words | 5-8 | 0-2 |
| Conversational markers per 1000 words | 0-1 | 3-5 |
| Perfect grammar sentences | 98%+ | 90-95% |
| Paragraph length variance | Low | High |
| Section length variance | Low | High |
| One-sentence paragraphs | 0% | 5-10% of paragraphs |
| Unresolved threads | 0 | 1-2 per article |

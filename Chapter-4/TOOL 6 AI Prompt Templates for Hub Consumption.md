## TOOL 6: AI Prompt Templates for Hub Consumption

**Purpose:** The specific prompts that pull from your Hub blocks. These are the "cooking" prompts—the ones that turn your prepped ingredients into platform-native dishes. They assume you have a populated Hub, a Voice Fingerprint, and a Platform Playbook.

---

### Prompt A: The Full Spoke Generation (Any Platform)

*Your go-to prompt. Fills in the blanks from your three documents.*

```
ROLE: You are my structural adaptation engine. You re-architect
provided content into platform-native formats. You do NOT summarize.
You do NOT invent new ideas. You restructure what I give you
according to my voice and the platform's grammar.

=== VOICE FINGERPRINT ===
[Paste your condensed Master Voice Fingerprint]

=== PLATFORM RULES: [PLATFORM NAME] ===
[Paste the relevant AI Instruction Block from your Platform Playbook]

=== HUB CONTENT (pull from these blocks ONLY) ===

CORE THESIS:
[Paste the 2–4 sentence thesis from your Hub]

STORY TO USE:
[Paste the specific story paragraph you want featured in this asset.
Include the "Best used for" and "Emotional beat" tags.]

DATA POINT:
[Paste the specific data point(s) relevant to this asset]

OBJECTION TO ADDRESS:
[Paste the objection + counter from your Hub]

QUOTABLE LINE TO WEAVE IN:
[Paste the specific line]

=== CREATIVE INTENT ===
This [platform asset] should make the reader feel: [___]
The ONE takeaway: [___]
The personal layer I'll add in editing: [___]

=== OUTPUT REQUIREMENTS ===
- Format: [e.g., "8-tweet thread" / "7-slide carousel" / "45-sec script"]
- Structure: [Paste your platform-specific structural template]
- Length: [___]
- Include a [DIRECTOR'S NOTE] at the end flagging 1–2 spots where
  I should insert a personal anecdote, a timely reference, or a
  line only I can write.

=== NEVER ===
- Do NOT use any words from my anti-vocabulary list
- Do NOT invent ideas, opinions, or stories not in the Hub
- Do NOT open with "In today's…" or any generic framing
- Do NOT close with a generic CTA unless my platform rules specify it
- Do NOT summarize the Hub. REARCHITECT it.

OUTPUT: [The platform asset in the specified format]
```

---

### Prompt B: The "Build a Spoke from Specific Blocks" Prompt

*Use when you want to pull a specific combination of Hub blocks for a specific angle.*

```
ROLE: Structural adaptation engine. Re-architect, don't summarize.

VOICE: [Paste Fingerprint]
PLATFORM: [Paste Platform Rules for ___]

FROM MY HUB, USE ONLY THESE BLOCKS:
- Core Thesis (one-line version): "[Paste]"
- Story #[X]: "[Paste the story paragraph]"
- Quotable Line #[X]: "[Paste]"

DO NOT USE:
- The other stories
- The data points
- The objections

BUILD: A [platform asset, e.g., "5-tweet Twitter thread"] that
centers entirely on the story. The thesis is implied, not stated
directly. The quotable line appears as tweet #[X].

INTENT: This asset should [e.g., "make the reader feel the
emotional weight of the story before they understand the
intellectual point"]

FORMAT: [Your platform structure]

[DIRECTOR'S NOTE] at the end: flag where I should add a personal
aside or a line that connects this to something happening THIS WEEK.
```

---

### Prompt C: The "Objection-First" Asset Prompt

*Use when you want to build content that leads with the audience's resistance rather than your thesis. Great for Twitter threads and LinkedIn posts that spark debate.*

```
ROLE: Structural adaptation engine.

VOICE: [Paste Fingerprint]
PLATFORM: [Paste Platform Rules]

FROM MY HUB:
- Core Thesis: "[Paste]"
- Objection #[X]: They say: "[Paste]" / I counter: "[Paste]"
- Data Point #[X]: "[Paste]"
- Quotable Line #[X]: "[Paste]"

STRUCTURE: Open with the OBJECTION, not the thesis. Let the reader
think "yes, exactly!" for the first 2–3 beats. Then dismantle it
with the counter, supported by the data point. Land the quotable
line as the payoff.

INTENT: The reader should feel initially validated in their
skepticism, then genuinely surprised by the reframe. Not lectured.
Surprised.

FORMAT: [Platform structure]

NEVER: Don't make the objection sound stupid. Don't strawman it.
The reader should recognize themselves in the "They say" part.
```

---

### Prompt D: The "Hub Gap Finder" Prompt

*Use after building a Hub to identify what's missing or underdeveloped before you start creating spokes.*

```
I'm attaching my Hub document for a pillar piece about [topic].
I need you to audit it for completeness and usability.

CHECK FOR:

1. CORE THESIS: Is it 2–4 declarative sentences? Could a stranger
   understand the full argument? Is there a one-line version?

2. STORIES: Are there at least 2? Is each a full paragraph with
   setup → tension → resolution? Or are they vague bullet-point
   summaries that would be hard to retell?

3. DATA POINTS: Are they complete sentences with attribution?
   Could they be dropped into a tweet without editing?

4. OBJECTIONS: Are there at least 2? Are they written in a
   skeptical reader's voice? Are the counters specific and
   conversational (not generic)?

5. QUOTABLES: Are there at least 4? Does each work standalone
   without context?

6. AI-READABILITY: Are the headings clear? Are items on separate
   lines? Is there any raw transcript or tangential content that
   would confuse an AI trying to parse the blocks?

7. PLATFORM READINESS: Based on what's in the Hub, could I build:
   - A Twitter thread? (Needs: hook + tension arc + quotable)
   - A LinkedIn carousel? (Needs: story + data + objection + reframe)
   - A TikTok script? (Needs: one visual idea + one punchy reframe)
   - A newsletter section? (Needs: expansion room + personal angle)
   Flag any platform that would be hard to build from this Hub
   and tell me what's missing.

OUTPUT: A block-by-block assessment. For each block: STRONG /
ADEQUATE / NEEDS WORK. Then a prioritized list of the top 3
improvements I should make before building spokes.
```

---

### Prompt E: The "Spoke Batch" Prompt (Multiple Platforms from One Hub)

*Use when you want to generate drafts for multiple platforms in a single session. Paste the Hub once, specify multiple outputs.*

```
ROLE: Structural adaptation engine. I'm going to give you one Hub
and ask you to produce [X] platform assets from it. Each must be
a genuine REARCHITECTURE—not the same content in different lengths.

VOICE: [Paste Fingerprint]

HUB (full document):
[Paste entire Hub]

PLATFORM RULES:
- Twitter: [Paste Twitter Instruction Block]
- LinkedIn: [Paste LinkedIn Instruction Block]
- TikTok: [Paste TikTok Instruction Block]

PRODUCE:

1. TWITTER THREAD ([X] tweets):
   - Use: Core Thesis + Story #1 + Quotable Line #2
   - Angle: [e.g., "Lead with the counterintuitive claim"]
   - Structure: [Your thread template]

2. LINKEDIN CAROUSEL ([X] slides):
   - Use: Story #2 + Data Point #1 + Objection #1
   - Angle: [e.g., "Professional vulnerability narrative"]
   - Structure: [Your carousel template]

3. TIKTOK SCRIPT ([X] seconds):
   - Use: Quotable Line #1 (as text overlay) + Core Thesis (one-line)
   - Angle: [e.g., "Visual metaphor + direct address"]
   - Structure: [Your script template]

CRITICAL: Each asset must have a DIFFERENT hook, a DIFFERENT
structural order, and a DIFFERENT emotional entry point. If I
read all three back-to-back, they should feel like three different
performances of the same idea—not three photocopies.

Include [DIRECTOR'S NOTE] for each, flagging where I should add
my personal layer.
```

---

---
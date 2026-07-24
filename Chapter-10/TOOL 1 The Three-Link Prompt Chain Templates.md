## TOOL 1: The Three-Link Prompt Chain Templates

**Purpose:** The sequential prompts that generate progressively deeper long-form content. Link 1 builds the skeleton. Link 2 adds the flesh. Link 3 adds the soul. Each link is a checkpoint where you steer before the next generation.

**Time needed:** 60–90 minutes for the full chain (including your editorial interventions between links).

---

### LINK 1: The Expansion Outline

*Generate the narrative skeleton before the AI writes a single paragraph of prose.*

```
═══════════════════════════════════════════════════════
LINK 1: EXPANSION OUTLINE
Pillar: [Title]
Target format: [Newsletter essay / Long-form LinkedIn post /
Lead magnet / Other: ___]
Target length: [___] words
═══════════════════════════════════════════════════════

ROLE:
You are my editorial architect. You are NOT writing the final
piece yet. You are building the structural blueprint that will
guide the writing. Think like a magazine editor planning a
feature article.

VOICE CONSTRAINTS (for tone reference during outlining):
[Paste your condensed Voice Fingerprint]

HUB CONTENT:
CORE THESIS:
[Paste]

KEY STORIES:
[Paste all stories with their tags]

DATA POINTS:
[Paste]

AUDIENCE OBJECTIONS:
[Paste]

QUOTABLE LINES:
[Paste]

CONTENT TYPE: [Analytical / Personal / Contrarian]
(If Personal: the outline should center the narrative arc.
If Analytical: the outline should center the framework.
If Contrarian: the outline should center the tension.)

TASK:
Generate a detailed narrative outline for a [target length]-word
[target format]. The outline must include:

1. OPENING BEAT (approx. [X] words):
   - What specific scene, moment, or statement opens the piece?
   - Which hook architecture applies? [From Chapter 8]
   - What emotional note does it set?

2. DEEPENING SECTION (approx. [X] words):
   - Which story from the Hub anchors this section?
   - What data point supports the argument?
   - What's the "director's cut" insight—the thing I didn't
     say in the original pillar that I can add here?

3. TENSION / OBJECTION SECTION (approx. [X] words):
   - Which audience objection does this address?
   - How is the counter-argument structured?
   - Is there a personal moment of doubt I can insert here?

4. REFLECTIVE CLOSE (approx. [X] words):
   - What question does the piece leave the reader with?
   - What's the emotional landing? (Hope? Challenge? Invitation?
     Quiet acknowledgment?)
   - Is there a callback to the opening beat?

FORMAT THE OUTLINE AS:
- Section headings with word count targets
- Bullet points for each beat (not full sentences)
- [PERSONAL INSERT] markers where I should add a real story
  or opinion
- [DATA] markers where a specific statistic should go
- [TENSION] markers where the argument should complicate

DO NOT write prose. DO NOT draft paragraphs. Only the skeleton.

OUTPUT: The outline. Then a [STRUCTURAL NOTE] explaining why
you chose this arc and where you think the emotional peak
should land.

═══════════════════════════════════════════════════════
END OF LINK 1
═══════════════════════════════════════════════════════
```

**Your checkpoint after Link 1:**

Read the outline. Before proceeding to Link 2:

☐ Does the arc make sense? (Beginning → deepening → tension → close?)
☐ Is the emotional peak in the right place? (Not too early. Not buried.)
☐ Are the [PERSONAL INSERT] markers in spots where I actually have something to add?
☐ Does the opening beat match my hook architecture?
☐ Does the close match my closing pattern?

**Adjustment before Link 2 (if needed):**

_______________________________________________________________

---

### LINK 2: The Voice-Infused Draft

*Take the outline and generate the full prose, with voice constraints applied.*

```
═══════════════════════════════════════════════════════
LINK 2: VOICE-INFUSED DRAFT
Pillar: [Title]
Target length: [___] words
═══════════════════════════════════════════════════════

ROLE:
You are my voice-infused drafter. You are writing the full piece
based on the outline below. You are NOT inventing new ideas.
You are giving prose to the structure I've approved.

VOICE CONSTRAINTS (follow exactly):
[Paste your full Voice Fingerprint]

PLATFORM / FORMAT RULES:
[Paste relevant format rules—newsletter, long-form LinkedIn, etc.]

THE APPROVED OUTLINE:
[Paste the outline from Link 1, including any adjustments you made]

HUB CONTENT (for reference):
[Paste relevant Hub blocks]

ADDITIONAL INSTRUCTIONS:
- Where the outline says [PERSONAL INSERT], write a plausible
  placeholder story that matches my Voice Fingerprint. Mark it
  clearly: [PLACEHOLDER: Replace with real story about ___].
  I will replace it.
- Where the outline says [DATA], insert the specific data point
  from the Hub. Do NOT invent statistics.
- Where the outline says [TENSION], allow the argument to
  complicate. Do NOT smooth over the contradiction. Let the
  reader sit in the discomfort for a beat.
- Add one unexpected insight or contrarian aside in the
  deepening section—something that surprises even me.
- Maintain the hook architecture from the outline throughout.
  Do NOT drift into generic openings in later paragraphs.

LONG-FORM VOICE REINFORCEMENT:
In outputs longer than 500 words, the AI tends to drift toward
formality. To counteract this:
- Increase contraction frequency by 20% after the 500-word mark.
- Add at least one direct reader address ("you know the feeling,"
  "here's the thing, friend") every 300 words.
- Include at least one sentence fragment for emphasis in every
  section.
- If you catch yourself writing a sentence that could appear in
  a corporate white paper, DELETE it and rewrite in my voice.

OUTPUT: The full draft. Then a [DRAFT NOTE] flagging:
- The 2–3 spots where my personal insertion will have the
  biggest impact
- Any place where you felt the voice constraints were hard to
  maintain (so I can check those spots carefully)
- The one sentence you're most proud of (so I know what to
  protect in editing)

═══════════════════════════════════════════════════════
END OF LINK 2
═══════════════════════════════════════════════════════
```

**Your checkpoint after Link 2:**

Read the draft. Don't edit yet. Just assess:

☐ Does it sound like me? (Voice Accuracy: ___ / 5)
☐ Does it follow the outline? (Structure: ___ / 5)
☐ Are the [PLACEHOLDER] spots clearly marked?
☐ Is there at least one moment that surprised me?
☐ Is the emotional peak where the outline said it would be?

**Proceed to Link 3 only if Voice Accuracy ≥ 3 and Structure ≥ 4.** If lower, adjust the prompt and regenerate Link 2 before deepening.

---

### LINK 3: The Editorial Deepening ("Yes, And")

*This is where you add your soul. The AI integrates your personal interventions into the draft.*

```
═══════════════════════════════════════════════════════
LINK 3: EDITORIAL DEEPENING
═══════════════════════════════════════════════════════

ROLE:
You are my editorial integrator. I'm going to give you paragraphs
from the draft and my personal additions. Your job is to weave
my additions into the prose seamlessly, maintaining voice and
flow. You are NOT rewriting from scratch. You are surgically
integrating.

VOICE CONSTRAINTS:
[Paste Voice Fingerprint]

THE DRAFT (full text):
[Paste the Link 2 draft]

MY INTERVENTIONS:

INTERVENTION 1:
Target paragraph: [Paste the paragraph I want to deepen]
My addition (raw, unpolished, in my own voice):
"[Write 1–3 sentences. A real memory. A contrarian thought.
A vulnerable admission. Something the AI could never generate
because it didn't live it.]"

Instruction: Rewrite the target paragraph to naturally integrate
my addition. If my addition challenges the paragraph's argument,
ADJUST the argument to accommodate the tension. Do NOT smooth
it over. The tension is the point.

INTERVENTION 2:
Target paragraph: [Paste]
My addition:
"[Your second personal intervention]"

Instruction: [Same as above, or specify: "Add this as a new
paragraph after the target" / "Use this to replace the
placeholder story" / "Let this complicate the close"]

INTERVENTION 3 (if applicable):
Target paragraph: [Paste]
My addition:
"[Your third intervention]"

Instruction: [___]

RULES:
- Preserve the voice constraints throughout.
- Do NOT add generic filler to accommodate my additions.
- If my addition is rough or fragmentary, polish it into my
  voice but keep its rawness. Do NOT make it "professional."
- The final piece should read as if I wrote it in a single
  inspired session, not as if two people wrote it.

OUTPUT: The revised draft with my interventions integrated.
Mark the integrated sections with **bold** so I can see what
changed. Then a [FINAL NOTE]: "The piece now feels [X]. The
strongest moment is [Y]. The one spot that still feels slightly
off is [Z]."

═══════════════════════════════════════════════════════
END OF LINK 3
═══════════════════════════════════════════════════════
```

---

### The Full Chain Timing

| Link | What Happens | Your Time | AI Time | Total |
|---|---|---|---|---|
| Link 1: Outline | You set up the prompt. AI generates skeleton. You review and adjust. | 10 min | 2 min | 12 min |
| Link 2: Draft | You paste outline + prompt. AI writes full draft. You assess. | 8 min | 3 min | 11 min |
| Link 3: Deepen | You write 2–3 personal interventions. AI integrates. You final-read. | 20 min | 3 min | 23 min |
| Final Polish | You read the whole piece. Fix typos. Add the last personal line. | 10 min | — | 10 min |
| **TOTAL** | | **~48 min** | **~8 min** | **~56 min** |

> *Under an hour for a 1,000–1,200-word essay that is structurally sound, voice-true, and deeply personal. The old way—staring at a blank page for two hours, writing three paragraphs, deleting them, starting over—took three times as long and produced something you were less proud of. The chain doesn't replace your creativity. It scaffolds it.*

---

---
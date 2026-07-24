## TOOL 2: The Conditional Logic Prompt Block

**Purpose:** The "Content Type Detection" block you add to your prompt templates so the AI adapts its hook, arc, and tone to the emotional register of the content. This is the upgrade from "one-size-fits-all structure" to "context-aware editorial intelligence."

**Time needed:** 15 minutes to add to each prompt. 10 minutes to test.

---

### The Block (Paste Into Every Prompt Template, After the Role Section)

```
═══════════════════════════════════════════════════════
CONTENT TYPE DETECTION & CONDITIONAL LOGIC
═══════════════════════════════════════════════════════

Before writing, read the Core Thesis and Key Stories in the Hub.
Categorize the content into ONE of three types:

TYPE 1 — ANALYTICAL:
The primary focus is teaching a framework, system, or method.
The content is instructional. The reader wants to learn HOW.

TYPE 2 — PERSONAL:
The primary focus is a personal story of struggle, failure,
transformation, or realization. The content is narrative. The
reader wants to feel LESS ALONE.

TYPE 3 — CONTRARIAN:
The primary focus is challenging a widely held belief or
conventional wisdom. The content is argumentative. The reader
wants to have their assumption SHAKEN.

Then apply the corresponding rules:

─── IF ANALYTICAL ───
HOOK: Use [Insight-First Headline / Bold Reframe / Specificity Bomb].
ARC: Problem → Framework → Application → Reflective close.
TONE: Confident, instructive, warm. One personal anecdote as
supporting evidence, NOT the emotional center.
VOICE ADJUSTMENT: Slightly more structured. Numbered steps welcome.
Sentences can be medium-length. Authority register at 80%.
NEVER: Vulnerability as the opening. "I struggled with this" as
the hook. Save the personal for the supporting beat.

─── IF PERSONAL ───
HOOK: Use [Vulnerability Ledger / Mid-Scene Drop / Quiet Confession].
ARC: Struggle → Lowest moment → Insight → Transformation →
Lesson for the reader (offered, not prescribed).
TONE: Warm, self-disclosing, honest. NOT self-indulgent. The
story serves the reader, not the ego.
VOICE ADJUSTMENT: Increase emotional register markers. Allow
longer, more flowing sentences in the story beat. Use fragments
for emotional emphasis. Vulnerability at 60%, authority at 40%.
NEVER: Framework-style numbering. "Here are 5 steps." The word
"optimize." A prescriptive "you should" close. Offer the lesson
as "here's what worked for me," not "here's what you must do."

─── IF CONTRARIAN ───
HOOK: Use [Contrarian Cliffhanger / Bold Reframe / Diagnostic Question].
ARC: State the challenged belief → Present evidence/story that
undermines it → Offer the reframed perspective → Invite debate.
TONE: Provocative but calm. Invite disagreement, not enemies.
VOICE ADJUSTMENT: Shorter, punchier sentences. Fewer qualifiers
("maybe," "perhaps," "I think"). More declarative. Authority at
90%. But the close should soften: "I could be wrong. But I don't
think I am."
NEVER: Aggressive or dismissive tone. "If you still believe X,
you're wrong." Strawmanning the opposing view. The reader who
holds the challenged belief should feel respected, not attacked.

─── CONTENT TYPE FOR THIS HUB ───
[OPTION A: Let the AI detect]
"Detect the content type from the Hub and apply the corresponding rules."

[OPTION B: Override with your judgment]
"This content is TYPE [X]. Apply the [X] rules regardless of
what the Hub might suggest."

═══════════════════════════════════════════════════════
END OF CONDITIONAL LOGIC
═══════════════════════════════════════════════════════
```

---

### Testing the Conditional Logic

Run the SAME prompt against two different Hubs:

| Test | Hub Topic | Expected Type | Hook Used? | Arc Correct? | Tone Matched? |
|---|---|---|---|---|---|
| A | *(e.g., "My burnout story")* | Personal | ☐ Yes ☐ No | ☐ Yes ☐ No | ☐ Yes ☐ No |
| B | *(e.g., "The 4-step decision framework")* | Analytical | ☐ Yes ☐ No | ☐ Yes ☐ No | ☐ Yes ☐ No |

**Are the two outputs meaningfully different?** (Different hook, different arc, different tone?)

☐ Yes, clearly differentiated
☐ Somewhat. The hook changed but the arc/tone didn't shift enough.
☐ No. They feel the same. → Tighten the conditional rules. Add more specific voice adjustments per type.

**Adjustment needed:**

_______________________________________________________________

---

---
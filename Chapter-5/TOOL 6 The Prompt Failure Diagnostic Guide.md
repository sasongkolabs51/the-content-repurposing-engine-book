## TOOL 6: The Prompt Failure Diagnostic Guide

**Purpose:** A quick-reference for the five most common prompt failures. When an output disappoints you, scan this list BEFORE you rewrite manually. Find the missing constraint. Add it. Regenerate.

---

### Failure 1: Generic Opening Creep

**The symptom:** Despite your hook rules, the AI opens with "We've all been there…" or "In today's fast-paced world…" or "Have you ever wondered…?"

**The cause:** Your Voice Constraint Block lacks a strong enough negative example. The AI defaults to the statistical average of all openings it's seen.

**The fix (add to your prompt):**

```
NEVER open with:
- A universal statement ("We've all experienced…")
- A rhetorical question ("Have you ever wondered…?")
- A "In today's world…" framing
- A "Let me tell you about…" preamble

ALWAYS open with:
[Your specific hook pattern. e.g., "A bold, declarative,
counterintuitive statement under 12 words. No setup. No
context. Just the claim."]

BAD EXAMPLE: "We've all felt the weight of too many decisions."
GOOD EXAMPLE: "Decision fatigue doesn't announce itself. It
just quietly makes you worse at everything."
```

**Did the fix work?** ☐ Yes ☐ No → Add a second BAD/GOOD example pair.

---

### Failure 2: Format Bleed

**The symptom:** Your Twitter thread reads like a LinkedIn post. Your newsletter reads like an expanded tweet thread. Your TikTok script reads like a YouTube intro.

**The cause:** Your Structural Rules are too vague, or your Reference Example is from the wrong platform.

**The fix (add to your prompt):**

```
FORMAT DELIMITATION:
This is a [PLATFORM] asset. It is NOT a [OTHER PLATFORM] post.

Specific differences:
- [Platform] uses [specific structural element]. [Other platform]
  does NOT.
- [Platform] has [specific cadence]. [Other platform] has
  [different cadence].
- On [Platform], each [unit] must [specific rule]. On [Other
  platform], [different rule].

If you find yourself writing [other-platform pattern], STOP and
restructure for [this platform].
```

**Example for Twitter:**
"This is a Twitter thread. It is NOT a LinkedIn post. Twitter uses single-sentence tweets with line breaks. LinkedIn uses multi-sentence paragraphs. Twitter builds tension through rapid micro-hooks. LinkedIn builds through narrative arc. Each tweet must stand alone and compel the next. Do NOT write multi-paragraph tweets."

---

### Failure 3: Data Hallucination

**The symptom:** The AI invents a statistic, a study, or a quote that sounds plausible but isn't in your Hub.

**The cause:** Your Constraint block doesn't explicitly prohibit invention.

**The fix (add to your prompt):**

```
DATA INTEGRITY RULE:
Use ONLY the data points, stories, and quotes provided in the
Hub content below. Do NOT invent, extrapolate, estimate, or add
any external research, statistics, or quotes.

If the Hub does not contain a data point you think would
strengthen the argument, do NOT fabricate one. Instead, insert:
[PLACEHOLDER: Add relevant statistic here]

I will fill the placeholder myself or remove it.
```

**Did the fix work?** ☐ Yes ☐ No → Add: "If you are uncertain whether a fact is in the Hub, treat it as NOT in the Hub and use a placeholder."

---

### Failure 4: Voice Drift Mid-Output

**The symptom:** The first 2–3 tweets/sentences sound like you. Then the AI gradually shifts into generic mode. By the end, it's corporate again.

**The cause:** The Voice Constraint Block is at the top of the prompt, and the AI's attention fades over a long output. The constraints need reinforcement.

**The fix (add to your prompt):**

```
VOICE REINFORCEMENT:
Maintain the voice constraints throughout the ENTIRE output.
Do not drift into generic language after the first 3 sentences.

Specifically:
- The final [tweet / slide / paragraph] must sound as distinctive
  as the first.
- If you catch yourself writing a sentence that could appear in
  any corporate blog post, DELETE it and rewrite using my
  vocabulary and rhythm rules.
- Re-read my Voice Constraint Block before writing the final
  [tweet / slide / paragraph].
```

**Did the fix work?** ☐ Yes ☐ No → Add a second Reference Example at the END of the prompt: "For the closing, model the energy of this line from my work: '[paste a strong closing line].'"

---

### Failure 5: Over-Structuring / Robotic Output

**The symptom:** The AI follows every rule so mechanically that the output feels stiff. Every sentence is exactly the specified length. Every transition is formulaic. It's "correct" but lifeless.

**The cause:** Your rules are too rigid. You've specified exact sentence counts or exact word counts per unit, leaving no room for natural variation.

**The fix (add to your prompt):**

```
NATURAL VARIATION RULE:
Follow the structural rules as a FRAMEWORK, not a straitjacket.
Vary sentence length naturally within the specified range.
Not every [tweet / slide / paragraph] must be exactly the same
length. Allow one [tweet / slide] to be slightly longer if the
idea demands it. Allow one to be a single fragment for emphasis.

The output should feel like a human wrote it following these
guidelines—not like a robot executing a script. Prioritize
NATURAL RHYTHM over mechanical compliance.
```

**Did the fix work?** ☐ Yes ☐ No → Loosen one specific rule (e.g., change "exactly 2 sentences per tweet" to "1–2 sentences per tweet, varying naturally").

---

### The Universal Diagnostic Question

When ANY output disappoints you, before you do anything else, ask:

> **"What rule did I fail to give it?"**

Not "Why is the AI stupid?" Not "I guess I'll just write it myself." Just: *What constraint was missing?*

Then add that constraint. Regenerate. Score. Iterate.

**The missing constraint from my last disappointing output was:**

_______________________________________________________________

**The rule I added:**

_______________________________________________________________

**Did the next output improve?** ☐ Yes ☐ Somewhat ☐ No → The problem is deeper (Reference Example or Voice Block). Revisit those.

---

---
## Tool 5: Prompt Output Scoring Rubric & Iteration Log

**Purpose:** To transform testing from a vague feeling (“this doesn’t sound like me”) into a measurable, improvable system. Use this rubric every time you test a prompt, and log your fixes.

### The Scoring Rubric

**Voice Accuracy (1–5)**  
*How closely does the output match your Voice Fingerprint?*

| Score | Meaning | Example Indicators |
|-------|---------|--------------------|
| 5 | Indistinguishable from my manual writing. Could post with zero edits. | Hooks match my pattern exactly; lexical phrases are present; emotional register is spot-on. |
| 4 | One or two phrases feel slightly off, but overall unmistakably me. | Rhythm is right but a sentence slipped into a slightly formal tone; one banned word appeared. |
| 3 | The skeleton is correct but the word choices feel generic. | Argument structure matches but vocabulary is bland; missing my signature phrases. |
| 2 | Recognizable attempt but major drift; would need a heavy rewrite. | Hook is generic; sentence length is uniform; corporate words appear. |
| 1 | Completely generic, sounds like a stock AI output. | “In today’s fast-paced world…”; no trace of my voice. |

**Format Correctness (1–5)**  
*How closely does the output follow the platform’s structural grammar from your Playbook?*

| Score | Meaning | Example Indicators |
|-------|---------|--------------------|
| 5 | Perfect adherence to every structural rule. | Exact tweet count, line breaks, slide structure, closing style. |
| 4 | One minor deviation. | Missing one line break, final tweet is slightly off-pattern. |
| 3 | Mostly follows rules but one major element is missing or wrong. | Thread has 5 tweets instead of 7–9; carousel slides lack visual cues. |
| 2 | Format is recognizable but inconsistent; several rules ignored. | Mix of thread and paragraph style; hook missing entirely. |
| 1 | Ignores platform format completely. | Produced a blog post when asked for a Twitter thread. |

### Testing Protocol

For each prompt template, generate **three separate outputs** (to account for AI variability). Score each output on both dimensions. Calculate the average.

**Prompt being tested:** _______________  
**Hub used:** _______________  
**Date:** _______________

| Output # | Voice Accuracy (1–5) | Format Correctness (1–5) | Notes (what worked, what drifted) |
|----------|----------------------|--------------------------|-----------------------------------|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| **Average** | | | |

**If average Voice Accuracy < 4:** Diagnose the specific drift (hook style? vocabulary? emotional register?) and add a tighter constraint or a “Bad Example” line to your prompt.  
**If average Format Correctness < 4:** Tighten your Structural Rules—add explicit line-break instructions, slide count, or format-delimiting language like “This is a Twitter thread, not a LinkedIn post.”

### Prompt Iteration Log

After adjusting, re-test and log the improvement.

| Iteration # | Change Made to Prompt | New Voice Avg. | New Format Avg. | Date |
|-------------|-----------------------|----------------|-----------------|------|
| 1 (initial) | — | | | |
| 2 | | | | |
| 3 | | | | |

**Stop when both averages are 4 or above.**

---
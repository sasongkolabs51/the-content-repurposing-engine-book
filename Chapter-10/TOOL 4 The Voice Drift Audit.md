## TOOL 4: The Voice Drift Audit

**Purpose:** The QA system for multipiece content. Run it on any batch of 3+ pieces before publishing. Catches the subtle drift that happens when AI generates longer or more varied output.

**Time needed:** 10 minutes for a batch of 3–5 pieces.

---

### VOICE DRIFT AUDIT

**Date:** _______________
**Pieces being audited:** _______________
**Generated in:** ☐ Single sprint ☐ Prompt chain ☐ Five-Day Arc ☐ Other: ___

---

#### Marker 1: Hook Architecture Consistency

Read the opening line of each piece. Do they ALL follow your documented hook patterns?

| Piece | Opening Line | Matches My Hook Architecture? | Pattern Used |
|---|---|---|---|
| 1 | "_______________" | ☐ Yes ☐ No | |
| 2 | "_______________" | ☐ Yes ☐ No | |
| 3 | "_______________" | ☐ Yes ☐ No | |
| 4 | "_______________" | ☐ Yes ☐ No | |
| 5 | "_______________" | ☐ Yes ☐ No | |

**Drift detected?** ☐ No ☐ Yes → Which piece(s): _______________
**What happened:** *(e.g., "Piece 4 opened with a generic question instead of my Bold Reframe pattern.")*
**Fix:** Add to prompt: "Maintain the exact hook architecture from the Reference Example. Do NOT default to generic openers in later pieces."

---

#### Marker 2: Lexical Consistency

Scan all pieces for your signature vocabulary and anti-vocabulary.

| Check | Result |
|---|---|
| Are my top 5 "use" words/phrases present across all pieces? | ☐ Yes ☐ Missing in piece(s): ___ |
| Are any of my top 5 "avoid" words present? | ☐ No ☐ Yes → Which: ___ In piece(s): ___ |
| Are contractions used consistently? | ☐ Yes ☐ No → Piece(s) ___ got more formal |
| Is my direct-address style ("you") consistent? | ☐ Yes ☐ No → Piece(s) ___ shifted to "we" or impersonal |

**Drift detected?** ☐ No ☐ Yes
**Pattern:** *(e.g., "The longer pieces (newsletter, Day 5 reflection) drift toward formality. Contractions disappear. Sentences get longer.")*
**Fix:** Add Long-Form Voice Reinforcement rule: "In outputs over 500 words, increase contractions by 20%. Add one direct reader address every 300 words. Include one fragment per section."

---

#### Marker 3: Emotional Register Consistency

Read the CLOSING line of each piece. Does the emotional register match what you specified?

| Piece | Closing Line | Intended Register | Actual Register | Match? |
|---|---|---|---|---|
| 1 | "_______________" | *(e.g., Tension/curiosity)* | | ☐ Yes ☐ No |
| 2 | "_______________" | *(e.g., Vulnerability)* | | ☐ Yes ☐ No |
| 3 | "_______________" | *(e.g., Confidence/clarity)* | | ☐ Yes ☐ No |
| 4 | "_______________" | *(e.g., Provocative/calm)* | | ☐ Yes ☐ No |
| 5 | "_______________" | *(e.g., Warm/inviting)* | | ☐ Yes ☐ No |

**Drift detected?** ☐ No ☐ Yes
**Pattern:** *(e.g., "Day 5 became preachy instead of inviting. The AI shifted from 'I wonder' to 'you should.'")*
**Fix:** Add to prompt: "The close must be an INVITATION, not a prescription. Use 'I wonder' and 'I'd love to hear' language. NEVER use 'you should' or 'you need to' in the closing."

---

#### Overall Drift Assessment

| Marker | Drift? | Severity | Fix Applied? |
|---|---|---|---|
| Hook Architecture | ☐ No ☐ Yes | ☐ Minor ☐ Major | ☐ Yes ☐ Pending |
| Lexical Consistency | ☐ No ☐ Yes | ☐ Minor ☐ Major | ☐ Yes ☐ Pending |
| Emotional Register | ☐ No ☐ Yes | ☐ Minor ☐ Major | ☐ Yes ☐ Pending |

**Decision:**

☐ All clear. Publish.
☐ Minor drift in 1 piece. Quick fix (regenerate that piece with reinforced constraint).
☐ Major drift across multiple pieces. Add a global reinforcement rule to all prompts. Regenerate affected pieces.

**The reinforcement rule I'm adding to my prompt templates:**

```
GLOBAL VOICE REINFORCEMENT (for all multipiece projects):
[Paste your fix here. e.g., "In any output longer than 500 words
or in any piece that is part 3+ of a series, increase contractions
by 20%, add one direct reader address per 300 words, and maintain
the exact hook architecture from the Reference Example. Do NOT
drift toward formality in later pieces."]
```

---

---
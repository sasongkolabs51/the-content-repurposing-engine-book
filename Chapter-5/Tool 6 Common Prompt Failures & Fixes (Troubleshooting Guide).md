## Tool 6: Common Prompt Failures & Fixes (Troubleshooting Guide)

**Purpose:** A quick-reference to diagnose the most predictable prompt failures and apply the right fix immediately—without frustration.

| Failure Mode | Symptoms | Likely Cause | Fix |
|--------------|----------|--------------|-----|
| **Generic Opening Creep** | Thread or post starts with “We’ve all been there…” or “In today’s world…” | Voice Fingerprint lacks a negative example; hook rule too vague. | Add a “Bad Example” line: “Never open with a universal statement. Instead, open with a specific, counterintuitive claim.” Paste an actual bad opening and your corrected version. |
| **Format Bleed** | Twitter thread reads like a LinkedIn post (multi-paragraph tweets, no tension arc). | Structural Rules too vague or missing platform-delimiting language. | Add: “This is a Twitter thread, not a LinkedIn post. Each tweet is 1–2 sentences max. Use line breaks. End each tweet with a pattern interrupt.” |
| **Data Hallucination** | AI invents a statistic or quote not in your Hub. | Constraint didn’t explicitly forbid invention. | Add: “Use ONLY the data and stories provided in the Hub. Do not invent, extrapolate, or add any external research. If a needed element is missing, insert [placeholder].” |
| **Monotone Rhythm** | All sentences are the same length; no variety. | Sentence rhythm rule is too general. | Be more specific: “Mix short sentences (5–8 words) with occasional longer ones (20–25 words). After every long sentence, follow with a short, punchy one.” |
| **Voice Drift (Too Formal)** | Output uses “we,” “one must,” or passive voice. | Voice Fingerprint doesn’t explicitly ban formal constructions. | Add: “Use ‘I’ statements, not ‘we.’ Use active voice. Write like you’re talking to a friend over coffee, not giving a keynote.” |
| **Closing Mismatch** | Final tweet is a link, or carousel ends with a summary instead of a question. | Structural rules didn’t specify closing style. | Add explicit closing instruction: “Final tweet is a reflective question. Never a link.” “Final slide asks readers to share their own experience.” |

**The Troubleshooting Principle:** Every disappointing output contains a clue about a missing constraint. Before you rewrite manually, ask: “What rule did I fail to give the AI?” Add that rule, regenerate, and watch the output improve.

---
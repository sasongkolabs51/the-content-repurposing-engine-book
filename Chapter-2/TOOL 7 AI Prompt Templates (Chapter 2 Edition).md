## TOOL 7: AI Prompt Templates (Chapter 2 Edition)

**Purpose:** Ready-to-use prompts that embed the Cocreator Pact principles. These are more refined than the Chapter 1 starters because they assume you now have a Voice Fingerprint document and a Hub structure. Fill in the brackets. Use them as-is or modify to fit your workflow.

---

### Prompt A: The Voice Fingerprint Validator

*Use this AFTER you've drafted your Voice Fingerprint (Tool 2). Paste your Fingerprint and 2–3 sample posts, and ask the AI to stress-test your spec sheet.*

```
I'm building a "Voice Fingerprint" document that I'll use to instruct
you (and other AI tools) to write in my voice. I need you to
stress-test it.

HERE IS MY VOICE FINGERPRINT:
[Paste your full Fingerprint from Tool 2, all five dimensions plus
the condensed Master Fingerprint]

HERE ARE 2–3 SAMPLE POSTS THAT REPRESENT MY VOICE:
[Paste them]

YOUR TASK:
1. Read the Fingerprint, then read the samples. Tell me: does the
   Fingerprint accurately capture what's happening in the samples?
   Where is it vague, incomplete, or slightly off?

2. Identify any patterns in the samples that I MISSED in the
   Fingerprint. Be specific. (e.g., "You use em-dashes to create
   mid-sentence interruptions in 3 of 3 samples, but your Fingerprint
   doesn't mention punctuation style.")

3. Rewrite my Fingerprint as a tighter, more precise set of
   instructions that you could follow mechanically. Keep my language
   and categories, but sharpen every rule.

4. Flag any contradictions between my stated rules and what the
   samples actually show. (e.g., "You say you 'always close with a
   question,' but sample #3 closes with a declarative one-liner.")

Be direct. I'd rather hear "this rule is too vague to follow" than
"this is great!" Accuracy matters more than politeness here.
```

---

### Prompt B: The "Write in My Voice" Master Prompt

*This is your go-to prompt for generating any platform asset. It embeds the full Pact structure.*

```
ROLE: You are my structural adaptation engine. You are NOT a
ghostwriter inventing ideas. You are re-architecting provided
material into a platform-native format, following my voice constraints
precisely.

=== MY VOICE FINGERPRINT (follow these rules exactly) ===
[Paste your condensed Master Voice Fingerprint from Tool 2]

=== THE CREATIVE BRIEF (Hub Components) ===
Core thesis: [Paste from Hub]
Story/Example to anchor this piece: [Paste from Hub]
Objection to address: [Paste from Hub]
Quotable line to weave in: [Paste from Hub]
Data/proof (if relevant): [Paste from Hub]

=== PLATFORM FORMAT RULES ===
Platform: [e.g., Twitter/X]
Format: [e.g., 8-tweet thread]
Native structure: [e.g., "Tweet 1 = pattern interrupt hook. Tweets 2-3
= tension. Tweets 4-5 = insight via story. Tweet 6 = objection.
Tweet 7 = quotable line. Tweet 8 = reflective question."]
What to AVOID on this platform: [e.g., "No hashtags. No 'thread 🧵'
announcements. No 'In today's world' openers."]

=== CREATIVE INTENT ===
This piece should make the reader feel: [e.g., "seen in their
specific frustration, then quietly challenged to reframe it"]
The ONE thing the reader should walk away with: [e.g., "the
realization that their 'productivity problem' is actually a
clarity problem"]

=== YOUR OUTPUT ===
Produce the [platform asset]. Follow the Voice Fingerprint rules
mechanically. Follow the platform structure precisely. Do NOT invent
new ideas or opinions beyond what's in the brief. Do NOT use any
words from my anti-vocabulary list.

After the draft, add a [DIRECTOR'S NOTE] section: flag 1–2 spots
where you think I should insert a personal anecdote, a timely
reference, or a line that only I can write. These are my "human
layer" insertion points.
```

---

### Prompt C: The "This Doesn't Sound Like Me" Revision Prompt

*Use this when an AI draft came back slightly off. Instead of scrapping it, diagnose and direct the revision.*

```
I gave you a prompt and you produced a draft. It's structurally
fine, but the VOICE is off. I'm going to tell you specifically
what's wrong. Fix ONLY the voice issues. Do not restructure.

THE DRAFT:
[Paste the AI's output]

WHAT'S OFF (be specific):
- Hook: [e.g., "You opened with a question. I never open with
  questions. I open with a short declarative fragment. Fix it."]
- Rhythm: [e.g., "Sentences 3-5 are all the same length. I alternate
  short-long-short. Vary them."]
- Vocabulary: [e.g., "You used 'utilize' and 'furthermore.' I would
  never. Replace with 'use' and 'plus.'"]
- Register: [e.g., "This reads like a LinkedIn thought-leader post.
  I sound like a friend talking too honestly over coffee. Loosen it."]
- Close: [e.g., "You ended with a CTA. I end with a reflective
  question the reader answers internally. Rewrite the close."]

MY VOICE FINGERPRINT (for reference):
[Paste condensed Fingerprint]

Revise the draft. Change ONLY what I flagged. Keep everything else.
Show me the revised version with the changes in **bold** so I can
see what you adjusted.
```

---

### Prompt D: The Voice Fingerprint Builder (AI-Assisted)

*Use this if you're struggling to articulate your own patterns. Feed the AI your best posts and let it do the forensic linguistics.*

```
I need you to act as a forensic linguist analyzing my writing voice.
I'm going to give you 4–5 of my best-performing posts. Your job is
to extract the mechanical patterns I use unconsciously, so I can
document them as a "Voice Fingerprint."

HERE ARE MY POSTS:
[Paste 4–5 posts, labeled by platform]

ANALYZE THESE FIVE DIMENSIONS:

1. HOOK ARCHITECTURE: How do I open? What's the mechanical pattern?
   (Sentence length, type—question/statement/fragment, what it does
   to the reader's attention.) Give me the rule AND two examples.

2. SENTENCE RHYTHM & LENGTH: What's my cadence? Map the sentence
   lengths across a paragraph. Is there a pattern? (e.g., "short-
   short-long-fragment") What's my average sentence length? Paragraph
   length?

3. LEXICAL FINGERPRINTS: What words/phrases appear repeatedly that
   are distinctive to me? What contractions do I use? What transitional
   phrases? What would NEVER appear in my writing? List at least 8
   "use" words and 5 "never" words.

4. ARGUMENT STRUCTURE: What's the narrative skeleton? How do I build
   from opening to close? How do I handle counterarguments? What's
   my closing move?

5. EMOTIONAL REGISTER: What's the temperature? Vulnerability level?
   Humor type? What emotional moves do I make? What do I avoid?

FORMAT YOUR OUTPUT AS:
For each dimension, give me:
- The PATTERN (one sentence)
- The RULE (stated as an instruction: "Always…" / "Never…")
- TWO EXAMPLES quoted from my posts
- One ANTI-PATTERN (what I would never do)

Then write a CONDENSED MASTER FINGERPRINT (6–8 lines) that I could
paste into any AI prompt as a voice constraint block.

Be specific. Mechanical. No "you have a warm, authentic voice"
fluff. I need rules a machine can follow.
```

---

### Prompt E: The Cocreator Pact Compliance Check

*Run this monthly. Paste your Pact and a recent AI interaction, and ask the AI to audit whether both sides held up their end.*

```
I have a "Cocreator Pact" that governs how I work with AI tools.
I want you to audit our last interaction against it.

HERE IS MY PACT:
[Paste your Cocreator Pact from Tool 3]

HERE IS THE PROMPT I GAVE:
[Paste it]

HERE IS THE OUTPUT I RECEIVED:
[Paste it]

AUDIT QUESTIONS:
1. Did I (the human) fulfill all my Article 1 responsibilities?
   Did I provide the Hub, the Fingerprint, the format rules, the
   intent? What was missing or vague?

2. Did the AI fulfill all its Article 2 responsibilities? Did it
   restructure (not summarize)? Follow the Fingerprint? Stay within
   the brief? Flag uncertainty?

3. Did either party violate Article 3 boundaries? Did the AI invent
   ideas? Did I expect mind-reading?

4. Against the Article 4 quality standard: does the output pass or
   fail? Which specific criteria did it miss?

5. What is the ONE change (to my prompt OR to my Fingerprint) that
   would most improve the next output?

Be direct. This is a working audit, not a compliment session.
```

---

---
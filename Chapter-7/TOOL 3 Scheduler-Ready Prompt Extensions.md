## TOOL 3: Scheduler-Ready Prompt Extensions

**Purpose:** Add an "Output Format" section to each of your prompt templates so the AI produces text that can be pasted directly into your scheduling tool with zero reformatting. This eliminates the format-translation tax permanently.

**Time needed:** 15 minutes to add to your prompts. 10 minutes per platform to test.

---

### How to Use

Add the relevant "Output Format" block to the END of each prompt template (after the OUTPUT instruction, before the "END OF PROMPT" line). Choose the version that matches YOUR scheduling tool.

---

### For Twitter/X Threads

**If you use Buffer:**

```
OUTPUT FORMAT (Buffer-ready):
- Output the thread as plain text.
- Each tweet on its own line.
- Separate tweets with a SINGLE blank line (one empty line between).
- No numbering (no "1/" "2/" etc.).
- No markdown formatting (no bold, no italics, no bullet points).
- No hashtags unless specified in my voice constraints.
- Character count per tweet must not exceed 280.
- If a tweet is close to the limit, note it: [CHAR COUNT: ___]
- This output will be copied directly into Buffer's thread composer.
```

**If you use Later:**

```
OUTPUT FORMAT (Later-ready):
- Output the thread as plain text.
- Each tweet on its own line, separated by a single blank line.
- No numbering. No markdown. No hashtags.
- Max 280 characters per tweet.
- Add a note at the top: "THREAD: [X] tweets. Post as Twitter thread in Later."
- This output will be pasted into Later's caption field for a threaded post.
```

**If you use Hootsuite (CSV bulk upload):**

```
OUTPUT FORMAT (Hootsuite CSV-ready):
- Output as a CSV block with columns: Date, Time, Message
- Leave Date and Time blank (I will fill these in Hootsuite).
- Each tweet is a separate row.
- The Message column contains the tweet text (no numbering, no markdown).
- Wrap the Message text in double quotes if it contains commas.
- Max 280 characters per Message cell.
- Add a header row: Date,Time,Message
- This CSV will be imported directly into Hootsuite's bulk composer.
```

**If you post manually (no scheduler):**

```
OUTPUT FORMAT (Manual posting):
- Output the thread as plain text.
- Number each tweet: "1/" "2/" etc. (for my reference while posting).
- Separate tweets with a blank line.
- No markdown. No hashtags.
- Max 280 characters per tweet.
- Add [COPY] before each tweet so I can quickly select and paste.
```

---

### For LinkedIn Carousels / Text Posts

**If you use Buffer:**

```
OUTPUT FORMAT (Buffer-ready):
- For a TEXT POST: Output the final caption as plain text.
  Use single line breaks between paragraphs. No markdown.
  Max 3,000 characters total. Note the character count at the end.

- For a CAROUSEL: Output as follows:
  [SLIDE 1]
  Headline: [bold headline text]
  Body: [1-2 sentences]

  [SLIDE 2]
  Headline: [text]
  Body: [text]

  [... continue for all slides ...]

  [CAPTION FOR POST]
  [The text that goes in the LinkedIn post caption field,
  separate from the carousel slides. 2-3 sentences max.
  Include the engagement question here.]

- This output will be used to create slides in Canva and
  paste the caption into Buffer's LinkedIn composer.
```

**If you use Later:**

```
OUTPUT FORMAT (Later-ready):
- Output the carousel script slide-by-slide:
  Slide 1: [Headline] | [Body text]
  Slide 2: [Headline] | [Body text]
  [... etc ...]

- Then output the post caption separately:
  CAPTION: [The LinkedIn post caption. 2-3 sentences.
  Include engagement question. Max 3,000 characters.]

- Note: I will create visuals in Canva matching the slide
  order, upload to Later, then paste the caption.
- Keep each slide's text under 150 characters for readability
  on a standard carousel template.
```

---

### For TikTok / Reels Scripts

**For any workflow (scripts aren't "scheduled" the same way):**

```
OUTPUT FORMAT (Filming-ready script):
- Output as a clean script with timestamps.
- Format:
  [0:00] VISUAL: [description]
  [0:00] TEXT OVERLAY: "[text]"
  [0:00] SPOKEN: "[exact words]"
  [0:00] BODY LANGUAGE: [direction]

  [0:05] VISUAL: [description]
  [... etc ...]

- No markdown. Plain text.
- Add a PROPS/SETUP note at the top listing anything I need
  before filming (props, location, outfit, graphics to prep).
- Add a TOTAL DURATION note at the bottom.
- This script will be printed or put on a teleprompter app
  for filming. Keep it clean and scannable.
```

---

### For Newsletter Sections

**If you use Substack:**

```
OUTPUT FORMAT (Substack-ready):
- Output in clean, simple formatting.
- Subject line on the first line: SUBJECT: [text]
- Then the body in plain paragraphs separated by blank lines.
- No markdown headers (no ##). Use plain text.
- Bold key phrases with **asterisks** (Substack renders these).
- Italicize with *single asterisks*.
- Links: [link text](URL) format.
- Max [X] words.
- End with: --- (a horizontal rule before the sign-off).
- This will be pasted directly into Substack's editor.
```

**If you use ConvertKit / Mailchimp:**

```
OUTPUT FORMAT (Email platform-ready):
- Output as clean HTML:
  <p>[paragraph text]</p>
  <p><strong>[bold text]</strong></p>
  <p><em>[italic text]</em></p>
  <p><a href="[URL]">[link text]</a></p>
- Subject line: SUBJECT: [text]
- Preview text: PREVIEW: [text]
- No inline CSS. No complex formatting.
- Paragraphs separated by <p> tags.
- This will be pasted into the HTML editor of [platform name].
```

---

### Testing Protocol (Do This Once Per Platform)

After adding the Output Format block to your prompt:

1. Run the prompt with a test Hub.
2. Copy the output.
3. Paste it into your scheduling tool.
4. Check: Does it render correctly? Are line breaks right? Is anything truncated? Are characters within limits?
5. If something breaks, adjust the Output Format instruction. (e.g., "Use single line breaks, not double." or "Wrap text in quotes for CSV.")
6. Re-run. Re-paste. Re-check.
7. Repeat until the paste is flawless.

**Test results:**

| Platform | Scheduler | First Paste Result | Adjustment Made | Second Paste Result |
|---|---|---|---|---|
| Twitter | | ☐ Perfect ☐ Needed fix | | ☐ Perfect ☐ Still fixing |
| LinkedIn | | ☐ Perfect ☐ Needed fix | | ☐ Perfect ☐ Still fixing |
| TikTok | | ☐ Perfect ☐ Needed fix | | ☐ Perfect ☐ Still fixing |
| Newsletter | | ☐ Perfect ☐ Needed fix | | ☐ Perfect ☐ Still fixing |

---

---
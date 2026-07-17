## Tool 3: Scheduler‑Ready Output Format Builder

**Purpose:** To extend your prompt templates so that the AI outputs assets formatted for direct copy‑paste into your scheduling tools—eliminating post‑sprint reformatting.

**Instructions:** For each platform, fill in the “Output Format” instruction tailored to your scheduling tool. Then test, note any formatting glitches, and refine.

### Step 1: Identify Your Scheduling Tools

- Twitter: ☐ Buffer ☐ Hootsuite ☐ Later ☐ Native app ☐ Other: ________
- LinkedIn: ☐ Buffer ☐ Hootsuite ☐ Later ☐ Native ☐ Other: ________
- TikTok/Reels: ☐ Later ☐ Native ☐ Other: ________
- Newsletter: ☐ Substack ☐ ConvertKit ☐ beehiiv ☐ Other: ________

### Step 2: Write the Output Format Instruction for Each Prompt

**Example for Twitter via Buffer Bulk Upload:**
“Output the thread as plain text. Each tweet on a new line, separated by a single blank line. No numbering, no hashtags, no emojis, no markdown. This output will be copied directly into Buffer’s bulk upload.”

**Example for LinkedIn Carousel via Later:**
“Output the carousel script with each slide’s caption in the following format: [Slide 1] headline text / body text. Separate slides with a blank line. At the end, output the main post caption separately, labeled ‘Caption.’ No extra formatting.”

**Example for Newsletter via Substack:**
“Output the newsletter in clean HTML. Use `<p>` tags for paragraphs, `<h2>` for section headings if needed. No CSS. Include the subject line at the top in plain text, marked as ‘Subject:’. This output will be pasted into Substack’s HTML editor.”

**Your Output Format Instructions:**

**Twitter Prompt:**
_______________

**LinkedIn Prompt:**
_______________

**TikTok/Reels Prompt:**
_______________

**Newsletter Prompt:**
_______________

### Step 3: Test & Refine

For each prompt, generate a test output, copy it into your scheduler, and check:
- [ ] Line breaks render correctly?
- [ ] Character limits respected?
- [ ] No stray markdown or bullet points?
- [ ] Slide/caption separation clear?
- [ ] Newsletter formatting clean in preview?

If something breaks, note it and adjust the output format instruction. Keep a running log of prompt format fixes:

| Platform | Issue Encountered | Prompt Adjustment Made | Resolved? |
|----------|-------------------|------------------------|-----------|
| | | | |

---
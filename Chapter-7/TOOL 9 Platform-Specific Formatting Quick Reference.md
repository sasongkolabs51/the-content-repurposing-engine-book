## TOOL 9: Platform-Specific Formatting Quick Reference

**Purpose:** A one-page cheat sheet for the formatting quirks of common scheduling tools. Tape it near your monitor. Glance at it when a paste doesn't render correctly.

---

### Buffer

| Platform | Formatting Rule | Gotcha |
|---|---|---|
| Twitter/X threads | Use "Add Tweet" button for multi-tweet. Or paste plain text with single line breaks. | Double line breaks create extra spacing. Use single. |
| LinkedIn text posts | Paste plain text. Line breaks render as paragraph breaks. | Max 3,000 chars. Buffer truncates silently. Check count. |
| LinkedIn carousels | Buffer doesn't natively handle carousel uploads well. Use "document post" or upload PDF. | Create slides as a PDF in Canva. Upload as document. Paste caption separately. |
| Instagram | Caption only. No line breaks in caption (use periods or dots for spacing). | Line breaks in the caption field get eaten. Use "..." or "·" for visual spacing. |

### Later

| Platform | Formatting Rule | Gotcha |
|---|---|---|
| Twitter/X | Paste caption in caption field. Thread posting supported. | Later's thread composer requires you to add tweets one by one. Paste each tweet separately. |
| LinkedIn carousels | Upload images/PDF first, then add caption. | Caption is separate from slide content. Keep slide text in the visuals, caption in the text field. |
| Instagram | Upload visual first. Caption in caption field. | Hashtags: Later suggests putting them in first comment. Check your strategy. |
| TikTok | Upload video. Caption in caption field. | Later's TikTok scheduling requires a business account. Verify yours is set up. |

### Hootsuite

| Platform | Formatting Rule | Gotcha |
|---|---|---|
| Bulk upload (CSV) | Columns: Date, Time, Message, Link. One row per post. | Wrap Message in double quotes if it contains commas. Use UTF-8 encoding. |
| Twitter threads | Not natively supported in bulk. Post individually or use thread composer. | For threads, use the manual composer. Bulk upload is for single tweets. |
| LinkedIn | Paste in message field. Supports line breaks. | Carousel posts: upload document separately. Hootsuite's LinkedIn integration can be finicky. Test first. |

### Substack / ConvertKit / Mailchimp (Newsletters)

| Platform | Formatting Rule | Gotcha |
|---|---|---|
| Substack | Paste plain text or markdown. Renders **bold**, *italic*, [links]. | Don't paste HTML. Substack's editor handles markdown natively. |
| ConvertKit | Use the visual editor or paste HTML. | Plain text paste loses formatting. Use HTML or the visual editor's paste function. |
| Mailchimp | Use the HTML editor or the visual builder. | Word paste introduces garbage code. Always paste as plain text first, then format in Mailchimp. |

---

### Universal Rules

- **Always paste as plain text first.** Rich text paste (Ctrl+V from a formatted doc) introduces hidden formatting that breaks schedulers.
- **Check character limits BEFORE scheduling.** Twitter: 280/tweet. LinkedIn: 3,000/post. Instagram: 2,200/caption.
- **Preview before publishing.** Every scheduler has a preview mode. Use it. Always.
- **If a paste breaks formatting, the fix is almost always in the prompt's Output Format block.** Don't fix it manually. Fix the prompt. Regenerate.

---

---
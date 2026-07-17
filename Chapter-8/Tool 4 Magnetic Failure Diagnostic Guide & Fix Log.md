## Tool 4: Magnetic Failure Diagnostic Guide & Fix Log

**Purpose:** To quickly categorize why a magnetically-designed post still underperformed, and apply a precise fix to your prompt rather than abandoning the system.

**Instructions:** When a post flops (despite a good hook and voice), use the table to diagnose and log the fix.

### Diagnostic Table

| Failure Type | Symptoms | Likely Cause | Prompt Fix |
|--------------|----------|--------------|------------|
| **Hook-Context Mismatch** | High clicks but very low likes/comments; people felt baited. | Hook architecture was too aggressive or genre-inappropriate for the content tone. | Tighten conditional logic: ban that hook for that content type. Add “Do not use [pattern] for Personal content” in prompt. |
| **Fatigue Pattern** | Gradual decline in engagement across several posts using the same hook pattern. | Audience has become desensitized; pattern is overused. | Rotate hook architecture: demote fatigued pattern to secondary, promote a different one. Add “Avoid the [pattern] for next 4 posts” to prompt. |
| **Emotional Flatline** | Decent likes, very low shares. Post is useful but not evocative. | Lacks an emotional peak; reads like a well-structured lecture. | Add emotional peak instruction: “In the second tweet/slide, insert a brief moment of personal self-doubt or realization that makes the subsequent insight feel earned.” |
| **Curiosity Gap Too Wide** | Post gets impressions but very low click-through. Hook is too cryptic. | Hook created confusion, not curiosity. | Tighten hook: “Make the hook specific enough that the reader can form a mental question they want answered. Avoid abstraction.” |
| **Voice Inconsistency** | Engagement is fine but comments say “this doesn’t sound like you.” | Conditional tone adjustments drifted too far from core voice. | Add a “Voice Anchor” line: “Regardless of content type, always maintain these core voice markers: [list 3-5 non-negotiables].” |

### Failure Fix Log

| Date | Platform | Post Description | Failure Type | Prompt Adjustment Made | Result (next post) |
|------|----------|------------------|--------------|------------------------|---------------------|
| | | | | | |

---
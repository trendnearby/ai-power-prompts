# Bonus: Prompt Engineering Guide

## How to Write Great Prompts

### The Formula:
[ROLE] + [TASK] + [CONTEXT] + [FORMAT] + [CONSTRAINTS] = Great output

### Examples:

Bad: "Write a blog post"
Good: "Act as a senior tech writer. Write a 1500-word blog post about why Rust is growing in popularity for systems programming. Target audience: junior developers. Include 3 subheadings, use bullet points, end with CTA. Tone: informative but accessible."

### Key Principles:

1. **Give context**: Who is the AI? Who is the audience? What's the situation?
2. **Be specific**: Instead of "write something good," say "write a 1500-word blog post with 3 subheadings"
3. **Show examples**: "Here's the style I want: [example]"
4. **Iterate**: First output is rarely perfect. Refine with follow-ups
5. **Ask for structure**: "Format as: headline, intro, 3 points with examples, conclusion"

### Common Mistakes:
- Too vague → garbage output
- Too long → AI misses key instructions
- No format specified → unstructured text
- No examples → AI guesses what you want

### Advanced Techniques:

**Chain of Thought**: "Think step by step" — improves reasoning tasks

**Few-Shot**: Give examples of what you want before asking

**Role Playing**: "Act as [expert role]" — changes the AI's approach

**Output Formatting**: "Output as JSON/Markdown/table" — structured results

**Temperature Guidance**: "Be creative" vs "Be precise" — adjusts output style

---

© 2026 AI Power Prompts. All rights reserved.

# de-slop

A Claude Code skill that eliminates AI slop writing patterns from any text, making it sound more natural and human-written.

## What is de-slop?

de-slop is an automated writing assistant that detects and removes common patterns found in AI-generated text. These patterns, often called "slop," make writing sound robotic, overly polished, or artificially structured. The skill helps you produce prose that reads like it was written by a human, not a machine.

Whether you're writing emails, blog posts, essays, reports, or any other content, de-slop ensures your text avoids the telltale signs of AI generation while maintaining clarity and professionalism.


## Installation

### Personal Skills 
For skills available across all your projects:

1. Create the skills directory:
   ```bash
   mkdir -p ~/.claude/skills/de-slop
   ```

2. Copy `SKILL.md` to the directory:
   ```bash
   cp SKILL.md ~/.claude/skills/de-slop/
   ```

3. Restart Claude Code or reload your session


## Usage

Trigger the de-slop skill whenever you:

- Write new content
- Edit existing text
- Review drafts
- Want to "de-slop" any text

Simply mention phrases like:
- "Write this email"
- "Rewrite this paragraph"
- "Edit this blog post"
- "This sounds too AI"
- "Make this more human-sounding"

Or invoke it directly with `/de-slop` followed by your text.

The skill will automatically scan your text and provide cleaned-up versions.

## Examples

### Before:
```
The result? Devastating. From innovation to cultural transformation, this isn't just technical — it's a mindset change. Experts argue that the path forward is clear. Think of it like a highway system for data.
```

### After (de-slopped):
```
The result was devastating. This changes both our technology and our thinking. The path forward is straightforward. It's like a network for moving data efficiently.
```

## Common Slop Patterns Detected

The skill identifies and eliminates patterns including:

- **Rhetorical Self-Q&A**: "The result? Devastating."
- **False Ranges**: "From innovation to transformation"
- **Negative Parallelism**: "Not technical - psychological"
- **Anaphora Abuse**: Repeating sentence starters
- **Tricolon Overuse**: Excessive rule of three
- **Grandiose Stakes**: Inflating importance unnecessarily
- **Invented Labels**: "The supervision paradox"
- **Ornate Vocabulary**: Words like "tapestry," "leverage," "harness"
- **Em-dash Overuse**: "The problem - and this - is..."
- And 23+ more patterns

For the complete list, see [SKILL.md](SKILL.md).

## How It Works

de-slop uses a comprehensive pattern recognition system based on linguistic analysis of AI-generated text. When you trigger the skill:

1. Text is scanned for known slop patterns
2. Each pattern match is flagged and rewritten
3. The cleaned version maintains your original meaning
4. Suggestions are provided for natural, human-sounding alternatives


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## References

This skill is informed by research on AI writing patterns from:
- [Wikipedia: Signs of AI Writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)
- [tropes.fyi](https://tropes.fyi)
- ["Semantic Ablation: Why AI Writing Is Boring and Dangerous"](https://www.theregister.com/2026/02/16/semantic_ablation_ai_writing) by Claudio Nastruzzi

---

**Made with ❤️ to combat AI slop and preserve human writing**


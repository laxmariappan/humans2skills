# Humans 2 Skills

**Turn your favorite people into AI skills. Carry their vibes with you.**

You know that colleague who always knows what to say? Or that friend who makes hard things feel doable?

This project lets you capture their vibe and bring it into any AI conversation.

## Live Demo

**[Try it out →](https://laxmariappan.github.io/humans2skills)**

## Example Skills

| Name | Vibe | Good For |
|------|------|----------|
| **Alfredo** | "Debugging with joy" | When you're stuck and need warmth |
| **Cristina** | "Your coach in the corner" | When you're overwhelmed and need direction |
| **Salvatore** | "Finding what matters" | When you need deep understanding |

Check out the full skill files in [`/skills`](./skills).

## How to Use

### Option 1: Use the Generator

1. Go to the [live site](https://laxmariappan.github.io/humans2skills)
2. Think of someone whose vibe you want to capture
3. Describe what makes them great
4. Click to open in Claude, ChatGPT, or Gemini

### Option 2: Copy a Skill

Grab a prompt from the [`/skills`](./skills) folder and paste it into your AI assistant.

Or just say things like:
- "Channel Alfredo and help me debug this"
- "I need Cristina's energy right now"
- "Explain this the way Salvatore would"

## Why This Exists

Sometimes you're stuck and you think: "I wish [person] was here."

Not because AI can replace them. But because their way of thinking helps you think better.

So I started describing people to AI assistants. Turns out it works pretty well.

This is a way to share that trick.

## Project Structure

```
humans2skills/
├── index.html          # The whole thing
├── style.css           # Styling
├── skills/
│   ├── alfredo.md      # Happy developer
│   ├── cristina.md     # Supportive coach
│   └── salvatore.md    # Wise engineer
├── README.md           # You're here
├── CONTRIBUTING.md     # How to add skills
└── LICENSE             # MIT
```

## Run It Locally

No build. No dependencies. Just open `index.html`.

Or:

```bash
python -m http.server 8000
# visit http://localhost:8000
```

## Contributing

Want to share a skill? See [CONTRIBUTING.md](./CONTRIBUTING.md).

## Privacy Note

The skills here are based on how I experience these people at work. I focus on their professional vibes, not personal stuff.

If you create your own, be thoughtful. Capture vibes, not secrets.

## License

MIT. Do what you want with it.

## Credits

Made by [Lax](https://github.com/laxmariappan).

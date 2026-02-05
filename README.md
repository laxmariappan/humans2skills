# Humans 2 Skills

**Turn the people who shaped you into AI skills.**

We all have people who changed how we work. A mentor who made things click. A colleague who made hard days easier. A friend who believed in us first.

This project helps you capture their energy and call on it whenever you need it—through AI.

## What This Is

A simple tool to honor the people who helped you by turning their approach into AI assistant prompts.

It's not about replacing them. It's about remembering what they gave you.

## Live Demo

**[Visit the site →](https://laxmariappan.github.io/humans2skills)**

## The Three Example Skills

These are real people who shaped me. I captured their energy as skills I can call on:

| Name | Tagline | When to Use |
|------|---------|-------------|
| **Alfredo** | "Debugging with joy" | When you're stuck on a bug and need warmth, not just answers |
| **Cristina** | "Your coach in the corner" | When you're overwhelmed and need someone who believes in you |
| **Salvatore** | "Finding what really matters" | When you need deep understanding, explained with patience |

Read their full skill files in the [`/skills`](./skills) folder.

## How to Use

### Option 1: Use the Generator

1. Go to the [generator page](https://laxmariappan.github.io/humans2skills/generator.html)
2. Think of someone who helped you
3. Describe what makes them special
4. Click to open in Claude, ChatGPT, or Gemini

### Option 2: Use Existing Skills

Copy a skill prompt from the [`/skills`](./skills) folder and paste it into your AI assistant.

Or just say things like:
- "Channel Alfredo and help me debug this"
- "I need Cristina's coaching energy"
- "Explain this like Salvatore would"

## Why I Built This

I kept finding myself wishing I could talk to certain people when I was stuck. Not because AI can replace them—it can't. But because their *approach* helped me, and I wanted access to that approach anytime.

So I started describing them to AI assistants. It worked better than expected.

This project is my way of sharing that idea. And honoring the people who helped me along the way.

## Project Structure

```
humans2skills/
├── index.html          # Landing page
├── generator.html      # Create your own skill
├── style.css           # Styling
├── skills/
│   ├── alfredo.md      # Example: Happy developer
│   ├── cristina.md     # Example: Supportive coach
│   └── salvatore.md    # Example: Empathetic engineer
├── README.md           # You're here
├── CONTRIBUTING.md     # How to contribute
└── LICENSE             # MIT
```

## Run Locally

No build process. No dependencies. Just open `index.html` in your browser.

Or use a simple server:

```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

## Contributing

Want to share your own "human skill"? See [CONTRIBUTING.md](./CONTRIBUTING.md).

This project welcomes:
- New example skills (with thoughtful, respectful descriptions)
- Bug fixes and improvements
- Translations
- Better prompts

## A Note on Privacy

The example skills in this project are based on my personal observations of real people. They focus on professional qualities and approaches—not personal details.

If you create your own skills, please be thoughtful. Honor people. Don't expose them.

## License

MIT — do what you want with it. See [LICENSE](./LICENSE).

## Credits

Built by [Lax](https://github.com/laxmariappan) to honor the people who helped me become who I am.

---

*The people who help us deserve to be remembered. This is one small way to do that.*

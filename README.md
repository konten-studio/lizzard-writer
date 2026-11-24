# Twist Kadal 🦎

**Konten yang bikin orang bilang: "Oh... hanya dengan begitu aja ternyata."**

An agent skill by [Konten Studio](https://github.com/konten-studio) for Claude Code, Codex, and any agent that reads `SKILL.md`.

---

## The idea

Before the thinking brain wakes up, the lizard brain asks two questions:

- 🚨 **Danger mode:** "Am I in trouble without knowing it?"
- 😌 **Happy mode:** "Is there an easy way to get what I want?"

Twist Kadal content opens on one of those, then pays off with something **much smaller and simpler than expected**. Big stake, small lever. That gap is the twist, and it's what keeps people watching to the end.

| Mode | Hook | Twist payoff |
|---|---|---|
| Danger | "5 kebiasaan kecil ini diam-diam bikin lutut cepat aus" | Habits you did this morning |
| Happy | "Cukup gerakan 2 menit ini, lutut kerasa lebih enteng" | One simple move, shown on screen |

## What it does

Give it a topic, product, or offer and an audience. It returns:

1. The audience's real fears and desires
2. 10 twist ideas (danger + happy, 8 patterns), each with its "ternyata cuma gitu" payoff
3. Scores, then full scripts for the top 3 (short video by default)
4. A batch test plan: post many, keep the winners, promote only those

With a **truth contract**: the payoff must be real, no invented fear, no miracle cures, ad-policy-safe wording for paid ads.

## Install

**Claude Code (plugin)**

```
/plugin marketplace add konten-studio/twist-kadal
/plugin install twist-kadal@twist-kadal
```

**Any agent (copy the skill folder)**

```bash
git clone https://github.com/konten-studio/twist-kadal
cp -r twist-kadal/skills/twist-kadal ~/.claude/skills/      # Claude Code
cp -r twist-kadal/skills/twist-kadal ~/.codex/skills/       # Codex
```

## Use

```
Pakai twist-kadal: bikin 10 ide konten buat kelas online bahasa Inggris, target karyawan 25-35, format Reels. CTA join kelas trial gratis.
```

## Pairs well with

[`jekardah-writer`](https://github.com/konten-studio/jekardah-writer): `hook-gokil` to sharpen the hook, `no-ai-slop` to clean the script.

## License

MIT © Konten Studio

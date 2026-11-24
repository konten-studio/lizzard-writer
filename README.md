<div align="center">

# 🦎 Lizzard Writer

### Brief in. Reel script out, ready to shoot.

**Konten yang bikin orang berhenti scroll, nonton sampai habis, lalu bilang:**
*"Oh... hanya dengan begitu aja ternyata."*

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
![Claude Code](https://img.shields.io/badge/Claude%20Code-plugin-D97757)
![Codex](https://img.shields.io/badge/Codex-skill-000000)
![Bahasa](https://img.shields.io/badge/bahasa-ID%20%2B%20EN-blue)

An agent skill by [Konten Studio](https://github.com/konten-studio)

</div>

---

## 🦎 Why "Lizzard"?

Picture a lizard on a warm rock.

A shadow passes overhead. It's gone before it has "decided" anything. 🚨
A fly lands nearby. It turns, still, locked on. 😌

That's the whole operating system: **is this going to hurt me, or is this something I want?** No reading, no weighing pros and cons. Just a reaction in a fraction of a second.

Copywriters call that fast, gut-level check the **lizard brain** (*otak kadal*). It's a shorthand from the old "three brains" model, not a precise neuroscience claim, but it describes something every creator has seen: in the first second of a reel, your viewer isn't thinking yet. Their thumb is the lizard on the rock. It only stops for **danger** or **desire**.

So a Lizzard Writer script does two things, in order:

1. **Talk to the lizard first.** Open on a real risk ("5 kebiasaan kecil ini ternyata bisa bikin sendi lebih cepat aus") or a real want ("cukup 2 menit ini aja..."). The thumb stops.
2. **Then hand it to the thinking brain with a twist.** The cause, or the fix, turns out to be something small and everyday. The viewer relaxes, the thinking brain catches up, and they say:

> *"Oh... hanya dengan begitu aja ternyata."*

The scare (or the promise) earns the stop. The small, true twist is what keeps them watching to the end. A lizard that gets scared and never gets relief just scrolls away, which is why every danger script here ends in relief.

---

## 🧠 The idea

Before the thinking brain wakes up, the lizard brain asks two questions:

| | Mode | The gut question | The twist |
|---|---|---|---|
| 🚨 | **Danger** | "Am I in trouble without knowing it?" | The cause is something you did this morning |
| 😌 | **Happy** | "Is there an easy way to get what I want?" | The fix is one small thing you can do today |

Open on one of those. Pay off with something **much smaller and simpler than expected**.
Big stake, small lever. That gap is the twist, and it's what keeps people watching to the last second.


---

## 🎬 What you get

Give it a **brief**: a source, an idea, a topic, a product. It hands back a reel you can shoot today.

```
HOOK (danger / happy)  →  OPEN LOOP  →  SMALL LEVERS  →  TWIST  →  RELIEF + CTA
```

| You give | You get |
|---|---|
| Topic, product or source | 5 scored angles (danger + happy) |
| Audience | A timed beat table: seconds · visual · on-screen text · voice-over |
| Platform + length (optional) | A clean voice-over block for the teleprompter |
| CTA (optional) | Caption, cover text, 3 alt hooks to A/B test |

---

## 🔁 Before / after

Same brief: an online English class for office workers who freeze when they have to present in English.

**Before** (a normal promo reel)
> "Mau jago presentasi pakai bahasa Inggris? Yuk join kelas kami! Materi lengkap, mentor berpengalaman, jadwal fleksibel."

**After** (Lizzard Writer, happy mode)
> "Presentasi pakai English nggak harus nunggu grammar lo sempurna. Ada satu kalimat pembuka yang bikin lo langsung kedengeran siap. Gue kasih tahu di akhir."

The first one asks for attention. The second one earns it: a want in the first second, a promise of one small thing, and a payoff the reel actually delivers.

---

## 🧾 Sample output

Shortened. A real run also gives 5 scored angles first and the voice-over as one clean block.

```
ANGLE: HAPPY · one small line
AUDIENCE: karyawan 25-35, takut presentasi pakai English
LENGTH: ~35s · 9:16

| Detik | Visual / B-roll              | Teks di layar              | Voice over                                                         |
|-------|------------------------------|----------------------------|--------------------------------------------------------------------|
| 0-3   | Laptop, slide pertama kebuka | Takut presentasi English?  | Presentasi pakai English nggak harus nunggu grammar lo sempurna.   |
| 3-7   | Ikon gembok di pojok layar   | 1 kalimat. Di akhir. 🔒    | Ada satu kalimat pembuka yang bikin lo kedengeran siap.            |
| 7-25  | Tiga kartu catatan           | 1. Pelan 2. Jeda 3. Senyum | Pertama, ngomong lebih pelan dari biasanya...                      |
| 25-31 | Gembok kebuka                | "Let me walk you through…" | Kalimat yang tadi: "Let me walk you through this."                 |
| 31-35 | Muka lega, tutup laptop      | Coba besok pagi            | Simpan video ini, coba di meeting lo berikutnya.                   |

CAPTION: Satu kalimat ini bikin presentasi English kerasa lebih ringan. Simpan buat meeting berikutnya.
COVER TEXT: 1 kalimat pembuka presentasi
ALT HOOKS: 3 more first lines to test
```

---

## 🛡️ Truth contract

Lizard-brain content is easy to abuse. This skill won't.

- ✅ The twist is **true** and the reel **shows** it
- ✅ Danger always ends in **relief**
- ❌ No invented fear, no unsourced stats
- ❌ No miracle cures ("membantu", never "menyembuhkan")
- ❌ No "kamu" + personal condition in paid ads

---

## ⚡ Install

**Claude Code**

```
/plugin marketplace add konten-studio/lizzard-writer
/plugin install lizzard-writer@lizzard-writer
```

**Codex, or any agent that reads `SKILL.md`**

```bash
git clone https://github.com/konten-studio/lizzard-writer
cp -r lizzard-writer/skills/lizzard-writer ~/.claude/skills/   # Claude Code
cp -r lizzard-writer/skills/lizzard-writer ~/.codex/skills/    # Codex
```

---

## ✍️ Use

```
Pakai lizzard-writer. Brief: kelas online bahasa Inggris buat karyawan 25-35
yang takut presentasi pakai English. Reels 35 detik. CTA: join kelas trial gratis.
```

```
Pakai lizzard-writer. Sumber: [paste artikel / transkrip / catatan].
Target ibu-ibu 40+. Bikin 3 script, 1 danger 2 happy.
```

---

## 📚 Inside

| File | What's in it |
|---|---|
| [`SKILL.md`](skills/lizzard-writer/SKILL.md) | The engine, truth contract, workflow, output format |
| [`references/formula.md`](skills/lizzard-writer/references/formula.md) | Stake/lever grid, 8 twist patterns, scoring, batch testing |
| [`references/reel-craft.md`](skills/lizzard-writer/references/reel-craft.md) | How the voice-over is written: beats, rhythm, on-screen text, checklist |
| [`references/examples.md`](skills/lizzard-writer/references/examples.md) | Full reel scripts + unsafe → safe repairs |

---

## 🧪 Test like a media buyer

1. Write 10-20 variants. Same stake, danger vs happy.
2. Post organic first. Read 3-second hold, watch %, saves, shares.
3. Keep the top 20%. Put ad budget only behind those.
4. Make 3-5 new hooks for each winner.

---

## 🤝 Pairs well with

[`jekardah-writer`](https://github.com/konten-studio/jekardah-writer): `hook-gokil` to sharpen the hook, `no-ai-slop` to clean the voice-over.

<div align="center">

MIT © [Konten Studio](https://github.com/konten-studio) · formerly `twist-kadal`<br>
Method by [Bahni](https://github.com/bahni-m) · reel craft studied from Indonesian explainer reels (patterns only, no one's words copied)

</div>

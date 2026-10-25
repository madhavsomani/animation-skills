# Madhav's animation skills

These are the skills we built together during Madhav Somani's ([@madhav_somani](https://www.instagram.com/madhav_somani/)) content-creation journey, and we're giving them to the public.

There are **16 skills** here: one **format/pipeline** skill (news-qa-reel) and 15 visual styles. Each one is a complete, tested recipe for one video style: how to plan it,
how it looks, how it moves, how the audio is built and how to check the result before you ship it.
Most of them come with working code from the first video we made in that style. They're written for
AI coding agents (Claude Code or Codex), but a person can read them too.

Below you'll find the storyboards and the animation styles each one can make.

## The skills

| Skill | What it makes | Style | Storyboard | Use it when you want... |
|---|---|---|---|---|
| [board-explainer](skills/board-explainer/SKILL.md) | **Madhav's favourite.** A hand-drawn iPad blackboard (pure black, coloured marker strokes drawn on at the speed of speech with a visible pencil tip, red stamp arrows, hand lettering) mixed with the presenter's real talking-head take for their own lines (matted cut-out, their own jokes) and their cloned voice for the facts they didn't cover. Voice-only sound. Built for our PHP2Shell security reel (Instagram 9:16, under 3:00). | <img src="docs/board-explainer/style.jpg" width="240"> | <img src="docs/board-explainer/storyboard.jpg" width="240"> | "like Code with Caleb", a blackboard / iPad drawing explainer with your face, tech news and security explainers from your own recording |
| [vector-world-explainer](skills/vector-world-explainer/SKILL.md) | A rich, colourful flat-vector world (an indigo night study with one glowing gold hero object) that teaches a CS/tech/science idea, with the presenter floating over the animation as a real-face cut-out from their own on-camera takes and their own voice as the spine. Built for our quantum-computer explainer. | <img src="docs/vector-world-explainer/style.jpg" width="240"> | <img src="docs/vector-world-explainer/storyboard.jpg" width="160"> | "make it like the quantum one", a flat-vector concept explainer, "teach X with animation" with your face floating over it |
| [case-file-explainer](skills/case-file-explainer/SKILL.md) | An investigative "evidence room" documentary: charcoal ground, one glowing red accent, photo cards with torn name tags, dark system maps with a red route, white clay 3D dioramas, sourced quote cards, date stamps and a calm narrator over a never-silent score. Built for a story about the xz backdoor. | <img src="docs/case-file-explainer/style.jpg" width="240"> | <img src="docs/case-file-explainer/storyboard.jpg" width="240"> | "case file", "investigation", "how X was discovered / hacked / leaked", breach, outage or history stories |
| [decode-explainer](skills/decode-explainer/SKILL.md) | A tech idea made easy for non-experts: a concept ladder, toy model first, a legend that stays on screen, one idea per screen, one colour = one meaning, worked examples, in a neon-on-purple look, with an avatar popping in and out, in English and Hinglish versions. | <img src="docs/decode-explainer/style.jpg" width="240"> | <img src="docs/decode-explainer/storyboard.jpg" width="240"> | "decode X", "make it easy to understand", security/tech explainers, English + Hinglish versions |
| [paper-lab-reel](skills/paper-lab-reel/SKILL.md) | (Now also a `template-train/` variant from our CS-degree reel: a paper train set, an AI robot arm and the "bullet train on the Himalayas" gag.) A hybrid Reel: the presenter's real talking-head footage composited into a hand-made paper-collage world (torn typewriter scraps, tape, pins, stamps, polaroids, red marker, a gold origami hero object, stop-motion on twos), every animation timed to the exact spoken word. Our favourite so far. | <img src="docs/paper-lab-reel/style.jpg" width="240"> | <img src="docs/paper-lab-reel/storyboard.jpg" width="240"> | "Paper Lab", a paper/collage explainer over your own footage, a presenter + animation hybrid |
| [luminous-cosmos-3d](skills/luminous-cosmos-3d/SKILL.md) | A real-3D glowing world (three.js through @react-three/fiber and @remotion/three): additive glowing points, halos, glass cards, a recurring hero object and keyed fly-through cameras, composited over a presenter or full frame. | <img src="docs/luminous-cosmos-3d/style.jpg" width="240"> | <img src="docs/luminous-cosmos-3d/storyboard.jpg" width="240"> | "real 3D", "make it 3D", a glowing three.js world inside a Remotion video |
| [canvas-explainer](skills/canvas-explainer/SKILL.md) | (Now also a Remotion variant in `template-remotion/` from our drug-discovery reel, with the presenter's real cut-out.) An "infinite canvas" Reel: marker strokes drawn live on a black canvas, a camera that glides between regions and zooms into sketched frames holding the presenter, real artifacts annotated in red, a zoom-out map ending and a spoken comment CTA. | <img src="docs/canvas-explainer/style.jpg" width="240"> | <img src="docs/canvas-explainer/storyboard.jpg" width="240"> | "canvas style", whiteboard/marker explainers, tech and career tips over a voice track |
| [madhav-split-reels](skills/madhav-split-reels/SKILL.md) | A white-grey split teaching Reel: an animated lesson panel on top (sequential reveals, drawn checks), bold unboxed captions in the middle, a large moving presenter below. | <img src="docs/madhav-split-reels/style.jpg" width="240"> | <img src="docs/madhav-split-reels/storyboard.jpg" width="240"> | "teach on top, me below", checklists and three-step lessons with a big presenter |
| [large-presenter-teaching-reels](skills/large-presenter-teaching-reels/SKILL.md) | A teaching Reel with a near-full-width moving presenter in the lower half and one concrete, changing teaching visual above (code and output, an array updating, a highlighted document). | <img src="docs/large-presenter-teaching-reels/style.jpg" width="240"> | <img src="docs/large-presenter-teaching-reels/storyboard.jpg" width="240"> | enlarging a tiny presenter inset, algorithm or coding lessons with your face big on screen |
| [ai-demo-reel](skills/ai-demo-reel/SKILL.md) | A result-first AI/software tutorial: open on the finished result, then a real cursor-led walkthrough of the actual app, a large grounded presenter in the corner, and a complete CTA. Includes a React layer kit and QA scripts. | <img src="docs/ai-demo-reel/style.jpg" width="240"> | <img src="docs/ai-demo-reel/storyboard.jpg" width="240"> | "show the result, then how I made it", AI tool demos, app walkthroughs |
| [news-qa-reel](skills/news-qa-reel/SKILL.md) | **The format + pipeline** behind our news batch ("Microsoft engineer answers your IG questions"): the presenter records one news-reaction take (a 3-second hook, then reads follower-style questions and answers from talking points); the pipeline transcribes, fact-checks and cuts untrue claims, builds a tight ~1.10x spine (ums and pauses cut, voice + footage sped together), denoises the voice (DeepFilterNet3), cuts the presenter out, stages them big bottom-left with graphics top + right, shows every question as an anonymous Instagram DM card, then mixes, renders 1440x2560 and runs delivery QA. Style-agnostic: any world below plugs in. | <img src="docs/news-qa-reel/style.jpg" width="240"> | <img src="docs/news-qa-reel/storyboard.jpg" width="240"> | "someone asks, I answer", news reactions, opinion Reels from your own recording |
| [declassified-dossier](skills/declassified-dossier/SKILL.md) | A manila case-file / evidence look on a dark desk: typewriter memos typed on the word, rubber stamps, redaction bars, a dated news card, pinned maps, OR→AND take cards, a "WHAT IF?" analogy panel and non-graphic strategy tables. Built for our DeepSeek-ban reel. | <img src="docs/declassified-dossier/style.jpg" width="240"> | <img src="docs/declassified-dossier/storyboard.jpg" width="240"> | policy, bans, geopolitics, security, "is it X or Y" takes |
| [glass-bubble-3d](skills/glass-bubble-3d/SKILL.md) | A real three.js iridescent glass bubble with a tiny AI city inside, coins pouring in, 3D icons on light threads, a desk + live code editor, orchestration nodes and a pipeline grid stamped "AI". Built for "is AI a bubble?" (honest note: Madhav rated this one "okayish"; its SKILL.md lists what to improve). | <img src="docs/glass-bubble-3d/style.jpg" width="240"> | <img src="docs/glass-bubble-3d/storyboard.jpg" width="240"> | AI economy / hype / "how my job changed" topics in 3D |
| [iso-diorama-3d](skills/iso-diorama-3d/SKILL.md) | A low-poly clay toy city on a floating isometric island (three.js orthographic): job tiles, people that swap to robots with a puff on the word, a two-pan scale, a chai corner, a day/night switch, labels as rounded pills projected from 3D. Built for "robots will take these jobs first". | <img src="docs/iso-diorama-3d/style.jpg" width="240"> | <img src="docs/iso-diorama-3d/storyboard.jpg" width="240"> | jobs, economy, "which X will Y" topics with a playful 3D world |
| [retro-space-poster](skills/retro-space-poster/SKILL.md) | A 1960s/70s screen-printed travel poster brought to life: flat SVG, halftone, ink mis-registration, a striped sun over parallax hills, a rocket stack and launch tower, a globe with dotted routes, boarding passes and fact chips. Built for our SpaceX reel. | <img src="docs/retro-space-poster/style.jpg" width="240"> | <img src="docs/retro-space-poster/storyboard.jpg" width="240"> | space, rockets, aviation, travel and transport news |
| [pixel-arcade](skills/pixel-arcade/SKILL.md) | Everything as 8-bit pixel art on a 9 px grid with a hand-made bitmap font, CRT scanlines and bloom, the presenter as "PLAYER 1", game screens (patch notes, VS / FIGHT!, territory map, GAME OVER → CONTINUE). Built for our Xbox reel. | <img src="docs/pixel-arcade/style.jpg" width="240"> | <img src="docs/pixel-arcade/storyboard.jpg" width="240"> | gaming, rivalries (X vs Y), console and tech-company news |

Click any image to see it full size. All images are real frames from videos we made with these
skills; the storyboards are key-frame boards in story order.

## What's inside each skill

```
skills/<skill>/
  SKILL.md        the recipe: when to use it, stages, approval stops, look, motion, audio, QA
  reference/      deeper notes (art direction, camera rig, audio, pitfalls, commands)
  template/       starting code from the first film (Remotion / HyperFrames)
  scripts/        helper scripts (QA, TTS timing, etc.) where the skill has them
  examples/       small text examples (fact-check notes, take choices, captions)
```

No media ships with the skills: no footage, voice, music or fonts. Every template expects you to
bring your own recording, your own voice and your own assets.

## How to install

### Claude Code

Copy (or symlink) the skill folders into your skills directory:

```bash
git clone https://github.com/madhavsomani/animation-skills.git
cp -r animation-skills/skills/* ~/.claude/skills/
# or, to keep them updated with git pull:
for s in animation-skills/skills/*; do ln -s "$(pwd)/$s" ~/.claude/skills/; done
```

On Windows (PowerShell), copy them to `%USERPROFILE%\.claude\skills\`, or create directory junctions
with `mklink /J`. For a single project, put them in `<project>/.claude/skills/` instead.

Then ask for the style by name ("make a Paper Lab reel about ...", "do this as a case file").

### Codex

Copy the same folders into `~/.codex/skills/` (the `agents/openai.yaml` files in some skills are
Codex display metadata). Invoke them with `$skill-name`, for example `$ai-demo-reel`.

## Dependencies

- **News Q&A Reels:** start with `news-qa-reel` (format, pipeline, shell), then pick one world skill (declassified-dossier,
  glass-bubble-3d, iso-diorama-3d, retro-space-poster, pixel-arcade, or the Remotion variants of paper-lab-reel / canvas-explainer).
  Each world only supplies `src/world`; the shell owns the presenter, captions, IG DM cards, audio and render.
- Most of the animated skills (vector-world, case-file, decode, paper-lab, luminous-cosmos and the news-batch worlds) run
  **inside the open-source cstack `animated-video` skill**: <https://github.com/goodnight000/cstack>.
  It owns the stages and approval stops; these skills add the style, kit and pipeline. Install it first.
- **[Remotion](https://www.remotion.dev/)** (React video) for the animated skills, plus
  **three.js / @react-three/fiber** for the 3D ones.
- **[HyperFrames](https://github.com/heygen-com/hyperframes)** (HTML + GSAP compositions) for
  canvas-explainer and madhav-split-reels; ai-demo-reel and large-presenter-teaching-reels work
  with either engine.
- **[FFmpeg](https://ffmpeg.org/)** for preparing media, encoding, loudness and QA.
- **Python 3.10+** with numpy/scipy/Pillow, and **faster-whisper** for word timings.
- **DeepFilterNet3** (in its own Python 3.10 venv) for voice denoising in news-qa-reel, and **HyperFrames `remove-background`** (u2net) for CPU cut-outs.
- Optional, depending on the skill: a CUDA GPU with PyTorch for RobustVideoMatting cut-outs,
  OpenCV YuNet for gaze checks, edge-tts for stand-in narration, and your own ElevenLabs voice clone
  or HeyGen avatar (API keys come from environment variables; never commit them).

## Ground rules baked into the skills

- **Your real face and voice stay real.** Cut-outs are mattes of your own pixels; nothing is
  regenerated or lip-synced unless you ask for exactly that.
- **Every claim gets checked.** Facts go into a `NOTES.md` with sources before they reach the screen;
  honest qualifiers are drawn into the art, not read as disclaimers.
- **Approval stops are real stops**: concept, style frame, key-frame board, final review.
- **Ship the full-quality master** (Instagram max: 1440x2560, H.264, up to ~24 Mbps, under 300 MB).
  Never shrink a video to fit an uploader.
- **Nothing is uploaded, scheduled or paid for without an explicit yes.**

## License

[MIT](LICENSE), Copyright 2026 Madhav Somani. Some template files come from cstack's MIT-licensed
`animated-video` template; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

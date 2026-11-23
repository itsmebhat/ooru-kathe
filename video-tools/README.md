# Video tools (reference only)

Not loaded automatically. Opened only when Praveen asks to use one.

- `hyperframes/`: HyperFrames skills (hyperframes, hyperframes-cli, hyperframes-registry, media-use), copied unchanged from https://github.com/heygen-com/hyperframes (commit c451aca). Apache License 2.0, see `hyperframes/LICENSE`. Renders HTML to video: animated titles, captions, kinetic text. Runs the `hyperframes` npm CLI; it asks before sending a usage note to HeyGen, and some media features need a HeyGen account.
- `motion-graphics-skill/`: link (git submodule) to https://github.com/mattypark/Motion-graphics-skill. The repo has no licence, so it is linked, not copied. Main file: `skills/motion-video-director/SKILL.md`. Plans and makes reels with motion graphics; optional API keys go in a local `.env` (never committed).

To get the linked one after cloning: `git submodule update --init`.

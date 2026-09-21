# Learning Companion Marketplace

Personal Codex marketplace containing the `learning-companion` plugin.

The plugin bundles three AI and mathematics learning workflows:

- `learn-lecture` for bilingual, chat-first lecture study; it creates detailed Markdown notes only after the learner finishes questions and explicitly requests them.
- `learn-lab` for bilingual, step-by-step lab work in chat; it creates the detailed lab record only after completion and an explicit request.
- `learn-project` for turning theory into a small validated project.

## Install

Add this GitHub repository as a Codex marketplace, then select **Hanxi Learning** in the Plugin Directory and install **Learning Companion**.

```powershell
codex plugin marketplace add OWNER/REPOSITORY --ref main --sparse .agents/plugins
```

Replace `OWNER/REPOSITORY` with this repository's GitHub name.

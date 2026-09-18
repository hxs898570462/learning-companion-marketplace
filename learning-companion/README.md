# Learning Companion Marketplace

Personal Codex marketplace containing the `learning-companion` plugin.

The plugin bundles three AI and mathematics learning workflows:

- `learn-lecture` for guided lecture study and Markdown notes.
- `learn-lab` for completing course labs step by step.
- `learn-project` for turning theory into a small validated project.

## Install

Add this GitHub repository as a Codex marketplace, then select **Hanxi Learning** in the Plugin Directory and install **Learning Companion**.

```powershell
codex plugin marketplace add OWNER/REPOSITORY --ref main --sparse .agents/plugins
```

Replace `OWNER/REPOSITORY` with this repository's GitHub name.

# Scoop bucket

Manifests for my tools. Today it holds [ctxray](https://github.com/MairwunNx/ctxray), which shows what Claude Code, Codex, Cursor, Gemini CLI, and OpenCode load into a model's context, and tests it in CI.

```powershell
scoop bucket add mairwunnx https://github.com/MairwunNx/scoop-bucket
scoop install mairwunnx/ctxray
```

ctxray's release workflow writes `bucket/ctxray.json` from each release's checksums, so changes go to [MairwunNx/ctxray](https://github.com/MairwunNx/ctxray).

# Project Principles Kit

两条原则，一个来源。

## 注入新项目

macOS / Linux：

```sh
for file in AGENTS.md CLAUDE.md GEMINI.md; do curl -fsSLO "https://raw.githubusercontent.com/Kayce001/Project-Principles-Kit/main/$file"; done
```

Windows PowerShell：

```powershell
'AGENTS.md','CLAUDE.md','GEMINI.md' | % { iwr "https://raw.githubusercontent.com/Kayce001/Project-Principles-Kit/main/$_" -OutFile $_ }
```

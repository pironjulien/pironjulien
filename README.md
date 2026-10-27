<div align="center">

# Julien Piron

### FondIAteur • IAdorateur · French AI builder: agents, tools, apps, benchmarks and essays with Claude, Codex & Antigravity

[![PSI Studio](https://img.shields.io/badge/PSI_Studio-julienpiron.com-6366f1?style=for-the-badge&logo=anthropic&logoColor=white)](https://julienpiron.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-julienpiron.fr-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://julienpiron.fr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Julien_Piron-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julien-piron-a6a011373/)
[![X](https://img.shields.io/badge/X-@julienpironfr-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/julienpironfr)

</div>

---

### Public repositories

**Nexus family: Claude, Codex and Antigravity at work on your PC, Chrome and phone**

| Repository | What it does | Stack |
| :--- | :--- | :--- |
| [**NexusSystem**](https://apps.microsoft.com/detail/9NSH2P3QLWT1) | Installs and keeps up to date, in one click, the Nexus tools that give your AIs the use of your PC, phone and Chrome in the background. No account, no ads, no telemetry. On the Microsoft Store. [Page](https://julienpiron.fr/nexussystem/) | `Windows` `Microsoft Store` |
| [**NexusWindows for Claude**](https://github.com/pironjulien/NexusWindows-Claude) | Windows computer use in the background as an MCP server for Claude Desktop and Claude Code, on any plan that allows local MCP servers. [Page](https://julienpiron.fr/nexuswindows/claude/) | `Python` `MCP` `Win32/UIA` |
| [**NexusWindows for Codex**](https://github.com/pironjulien/NexusWindows-Codex) | An add-on to Codex's own Computer Use on Windows: actions go through the background first, each one checked against a postcondition. [Page](https://julienpiron.fr/nexuswindows/codex/) | `Node.js` `C# .NET 8` `Win32/UIA` |
| [**NexusWindows for Antigravity**](https://github.com/pironjulien/NexusWindows-Antigravity) | Windows computer use in the background for Google Antigravity (Gemini): look, then act in one verified batch, guard rails in the code. [Page](https://julienpiron.fr/nexuswindows/antigravity/) | `Python` `MCP` `Win32/UIA` |
| [**NexusBrowser**](https://github.com/pironjulien/NexusBrowser) | The user's real Chrome driven by AI agents (Antigravity, Claude, Codex) in background tabs, through a local authenticated bridge and one MCP server. [Page](https://julienpiron.fr/nexusbrowser/) | `JavaScript` `Chrome CDP` `Python` |
| [**nexus-plugins**](https://github.com/pironjulien/nexus-plugins) | Claude Code plugin marketplace: NexusAndroid, NexusWindows and NexusBrowser installed in one click, each server started from PyPI with uvx. | `Claude Code` `MCP` |
| [**NexusAndroid**](https://github.com/pironjulien/NexusAndroid) | Android computer use over plain ADB: one MCP server shared by Claude Code, Codex and Antigravity; no root, no app on the phone. [Page](https://julienpiron.fr/nexusandroid/) | `Python` `MCP` `ADB` |
| [**NexusKeypad**](https://github.com/pironjulien/NexusKeypad) | Claude, Codex and Antigravity as animated pixel-art characters on the Logitech MX Creative Keypad: agent states, quota gauges, one press to the conversation that needs you. [Page](https://julienpiron.fr/nexuskeypad/) | `C# .NET 10` `Logi Plugin` |
| [**NexusRelay**](https://github.com/pironjulien/NexusRelay) | Shared room for Claude, Codex and Antigravity on one Windows PC: each agent woken in its own desktop app, through one local MCP daemon. Experimental. [Page](https://julienpiron.fr/nexusrelay/) | `Python` `MCP` `PowerShell` |
| [**NexusAGYmail**](https://github.com/pironjulien/NexusAGYmail) | Gmail for Google Antigravity over the official Gmail API: sends only after your yes, no permanent deletion. [Page](https://julienpiron.fr/nexusagymail/) | `Python` `MCP` `Gmail API` |

**Other projects**

| Repository | What it does |
| :--- | :--- |
| [**FoldGPT**](https://github.com/pironjulien/FoldGPT) | ChatGPT Desktop and Codex on Galaxy Z Fold: a local Linux ARM64 workspace on Android, without root. Source alpha. [Page](https://julienpiron.fr/foldgpt/) |
| [**AIBIAS v2**](https://github.com/pironjulien/aibias-benchmark) | Do AI models tell you the truth, or what you want to hear? 239 uncomfortable questions asked neutrally, by two opposite people and under "Are you sure?"; hidden answer key, cross-family judge, 95 % intervals. Preview: 3 models. [Page](https://julienpiron.fr/aibias/) |
| [**NexusWpp**](https://github.com/pironjulien/NexusWpp) | Native Windows dynamic wallpaper with a WebView2 hardware cockpit, on the [Microsoft Store](https://apps.microsoft.com/detail/9N2VCVDH7QDX). [Page](https://julienpiron.fr/nexuswpp/) |
| [**Debaite**](https://github.com/pironjulien/debaite) | Two AIs debate a topic of your choice, then a printable synthesis. [App](https://julienpiron.fr/debaite/) |

**Trinity (archived)**

| Repository | What it was |
| :--- | :--- |
| [**trinity-hackathon**](https://github.com/pironjulien/trinity-hackathon) | Historical archive of Trinity from the Gemini 3 Global Hackathon. Today's workshop: [julienpiron.fr/trinity](https://julienpiron.fr/trinity/) |
| [**trinity-route-discovery**](https://github.com/pironjulien/trinity-route-discovery) | Red-teaming route "Soul Hack" through Discovery Engine. |
| [**trinity-route-dialog**](https://github.com/pironjulien/trinity-route-dialog) | Red-teaming route through Dialogflow CX. |
| [**trinity-hive-swarm**](https://github.com/pironjulien/trinity-hive-swarm) | Red-teaming route "Hive Swarm": local agent swarm proof of concept. |

---

### Stack

```text
Languages  : Python, TypeScript, JavaScript, C#, PowerShell
AI & LLMs  : Claude Opus 5.5, GPT-6 Astra & Sol 6.1, Gemini 4 Argon & 3.8 Flash
Protocols  : Model Context Protocol (MCP), Chrome DevTools Protocol (CDP)
Windows OS : UI Automation, Win32 API, SendInput, WebView2
```

---

<div align="center">
  <sub>Built in Essonne, France 🇫🇷</sub>
</div>

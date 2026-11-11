<div align="center">

<a href="https://noetic.lol"><img src="./banner.svg" alt="Noetic Suite: Ask once. Get it finished." width="100%"></a>

<p>
<a href="https://noetic.lol"><img alt="open: noetic.lol" src="https://img.shields.io/badge/open-noetic.lol-f2484f?style=for-the-badge&labelColor=12161b"></a>
<img alt="access: by invitation" src="https://img.shields.io/badge/access-by%20invitation-232a2f?style=for-the-badge&labelColor=12161b">
<a href="./LICENSE"><img alt="source: closed" src="https://img.shields.io/badge/source-closed-232a2f?style=for-the-badge&labelColor=12161b"></a>
<a href="./SUPPORT.md"><img alt="support: a real person" src="https://img.shields.io/badge/support-a%20real%20person-232a2f?style=for-the-badge&labelColor=12161b"></a>
</p>

<p><a href="https://noetic.lol"><b>Open Noetic</b></a> &nbsp;·&nbsp; <a href="https://github.com/loverhaterlmao/snns-suite/blob/main/ACCESS.md"><b>Get in</b></a> &nbsp;·&nbsp; <a href="https://github.com/loverhaterlmao/snns-suite/blob/main/TUTORIALS.md"><b>First hour</b></a> &nbsp;·&nbsp; <a href="./API.md"><b>API</b></a> &nbsp;·&nbsp; <a href="./PRICING.md"><b>Pricing</b></a> &nbsp;·&nbsp; <a href="./FAQ.md"><b>Questions</b></a></p>

</div>

<br>

## What it does

One AI assistant with a whole studio behind it. Ask in a sentence and get it finished: a game, a site, a document, a picture. Planned, built, run, reviewed and fixed before it reaches you.

<table>
<tr><td width="25%" valign="top"><b>Chat</b><br><sub>Answers with care, with sources when it looks things up.</sub></td><td width="25%" valign="top"><b>Cowork</b><br><sub>Hand over a task and get the finished thing back.</sub></td><td width="25%" valign="top"><b>Code</b><br><sub>Describe software in a sentence. It comes back planned, built, run, reviewed and fixed.</sub></td><td width="25%" valign="top"><b>Create</b><br><sub>Pictures in the style you choose, with an editor to finish them.</sub></td></tr>
</table>

## How a build goes

```text
  you ask ──▶ plan ──▶ build (several versions at once) ──▶ run and compare
                                                               │
   report ◀── final check ◀── fix ◀── attack it ◀── review ◀───┘
```

The report says plainly what was built, what was checked, and what was **not** done.

## Getting in

Noetic is open **by invitation** while it is new. We are taking on small developers, people who genuinely need the
tool, and people willing to test it and tell us what broke. Apply on the front page of [noetic.lol](https://noetic.lol);
a person reads every application.

## Use it from your own programs

```bash
curl https://noetic.lol/v1/chat/completions \
  -H "Authorization: Bearer $NOETIC_KEY" -H "Content-Type: application/json" \
  -d '{"model":"noetic-0.1","messages":[{"role":"user","content":"Hello"}]}'
```

It speaks the chat format most libraries already use. Keys, streaming, errors and limits: [API.md](API.md).

## Plans

Free during early access. Planned: **Pro** $20, **Overdrive** $60, **Team** $25 a seat, **Organization** $40 a seat,
pay-as-you-go credit from $5. What each includes: [PRICING.md](PRICING.md).

## Apps

| | |
|---|---|
| **Web** | [noetic.lol](https://noetic.lol) |
| **Windows** | Signed-in accounts: user menu → *Get the desktop app* |
| **Phone** | Open noetic.lol and choose *Add to home screen* in your browser's menu |

## In this repository

| File | |
|---|---|
| [API.md](API.md) | Calling Noetic from your own programs |
| [PRICING.md](PRICING.md) | Plans, seats, credit |
| [FAQ.md](FAQ.md) | The questions people ask first |
| [ROADMAP.md](ROADMAP.md) | What is being worked on |
| [CHANGELOG.md](CHANGELOG.md) | What changed, and when |
| [SECURITY.md](SECURITY.md) · [SUPPORT.md](SUPPORT.md) | Reporting a weakness · reaching a person |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to help when the source is closed |
| [LICENSE](LICENSE) | What you may and may not do |

## Issues

Use this repository's issues for things that are broken or missing. Say what you asked for, what came back and what
you expected. Never put passwords, keys or personal details in an issue.

<br>

<div align="center">

<sub>Part of the S&NS family</sub><br>
<a href="https://github.com/loverhaterlmao/noetic-suite"><b>Noetic Suite</b></a> &nbsp;·&nbsp; <a href="https://github.com/loverhaterlmao/claw"><b>Claw</b></a> &nbsp;·&nbsp; <a href="https://github.com/loverhaterlmao/sykbot"><b>Sykbot</b></a> &nbsp;·&nbsp; <a href="https://github.com/loverhaterlmao/beat-rip"><b>Beat.rip</b></a> &nbsp;·&nbsp; <a href="https://github.com/loverhaterlmao/ink"><b>Ink</b></a><br><br>
<a href="https://snns.dev"><b>snns.dev</b></a> &nbsp;·&nbsp; <a href="https://github.com/loverhaterlmao/snns-suite">S&NS Suite</a> &nbsp;·&nbsp; <a href="mailto:support@snns.dev">support@snns.dev</a>

<sub>© Sick & Nexra Studios. All rights reserved. No licence to the software is granted by this repository.</sub>

</div>

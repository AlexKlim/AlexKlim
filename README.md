## Aliaksandr Klimiankou

I publish here as **Alex Klimenkov**.

Engineering Manager at Jitera, based in Gdansk, Poland. Sixteen years in
software, the last ten of them leading engineering teams.

### What I work on

AI systems that run inside an organisation's own infrastructure.

A lot of organisations hold material they are not allowed to send to an
outside service: regulated records, customer data, and the internal
discussions that are never written down anywhere. My work is about making
that material usable by AI systems without it leaving the organisation that
owns it.

At Jitera I led the work that made our AI agent platform installable and
operable inside a customer's own environment. Before that I spent seven and
a half years at Craft.co, a United States supply chain intelligence company,
where I joined as the second engineer and built the data platform the
product runs on.

### A note on what is not here

The code I write and review at work is in private repositories, so none of
it appears on this page as source. Since February 2024 I have reviewed more
than a thousand pull requests in Jitera's repositories, and I wrote the
company's code review standard and its development workflow.

### Things I build on my own

**[Jiterka](https://github.com/AlexKlim/Jiterka)** - a prototype desktop
application that records a meeting, transcribes it, separates the speakers,
cleans up the transcript and produces a summary. Speaker diarization runs as
a local service rather than through an external provider, which is the same
constraint the rest of my work is aimed at. Built over six days in November
2025.

**[Wave Terminal fork](https://github.com/AlexKlim/waveterm)** - I built an
Excalidraw diagram editor into Wave Terminal, an open source terminal, as a
native block with its own `wsh` command, and replaced its hardcoded keyboard
shortcuts with a configurable keybinding system defined in
`keybindings.json`. Around 2400 lines across Go and TypeScript, with tests.

**[memorizable](https://github.com/AlexKlim/memorizable)** - a command line
tool, published on npm, that captures AI-assisted coding sessions and keeps
a running summary of what was decided and why. The same idea as Jiterka
applied to a different kind of conversation: knowledge that is produced in
passing and then lost.

**[allcollate](https://github.com/AlexKlim/allcollate)** - a hotel price comparison service I built with a friend from 2020. Ruby on Rails, React, PostgreSQL, Elasticsearch, on AWS. It imported hotel listings and kept their price history, so you could tell whether today's price was actually a good one. I no longer host it, but it still runs from the repository.

### Writing

I write about engineering management and AI-assisted development on
[Medium](https://axklmn.medium.com/).

### Elsewhere

[LinkedIn](https://linkedin.com/in/alex-klimenkov)

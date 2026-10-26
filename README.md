<a href="https://jorgeress.github.io">
  <img src="assets/header.svg" width="100%" alt="Jorge García: malware, Linux and cybersecurity.">
</a>

<p align="center">
  <a href="https://jorgeress.github.io"><img src="https://img.shields.io/badge/web-jorgeress.github.io-c792ea?style=flat-square&labelColor=0b0d12" alt="Website"></a>
  <a href="mailto:jgarciamartinezdev@proton.me"><img src="https://img.shields.io/badge/email-proton.me-3ddc97?style=flat-square&labelColor=0b0d12" alt="Email"></a>
  <a href="https://www.linkedin.com/in/jorgegarciamartinezdev"><img src="https://img.shields.io/badge/LinkedIn-Jorge_García-0a66c2?style=flat-square&labelColor=0b0d12" alt="LinkedIn"></a>
</p>

Cybersecurity, Linux and ML. [Versión en español](README.es.md)


### What I work with

<p align="left">
  <img src="https://skillicons.dev/icons?i=arch,linux,bash,c,cpp,docker,python,nodejs,java,postgres,mongodb,js,ts,react,nextjs,pytorch,aws,git&perline=11" alt="Arch, Linux, Bash, C, C++, Docker, Python, Node.js, Java, PostgreSQL, MongoDB, JavaScript, TypeScript, React, Next.js, PyTorch, AWS, Git">
</p>


### Projects

<p align="center">
  <a href="https://github.com/jorgeress/crisol"><img src="assets/proyectos/crisol.webp" width="48%" alt="Crisol"></a>
  <a href="https://github.com/jorgeress/cromatoforo"><img src="assets/proyectos/cromatoforo.webp" width="48%" alt="Cromatóforo"></a>
  <a href="https://github.com/jorgeress/cibo"><img src="assets/proyectos/cibo.webp" width="48%" alt="CIBO"></a>
  <a href="https://github.com/jorgeress/pinchadiscos"><img src="assets/proyectos/pinchadiscos.webp" width="48%" alt="Pinchadiscos"></a>
  <a href="https://github.com/jorgeress/garabato"><img src="assets/proyectos/garabato.webp" width="48%" alt="Garabato"></a>
  <a href="https://github.com/jorgeress/vitrina"><img src="assets/proyectos/vitrina.webp" width="48%" alt="Vitrina"></a>
</p>

<details>
<summary><b>Crisol</b>: static malware triage engine and test bench for YARA rules</summary>
<br>

Anyone can run `yara rules.yar sample.exe`. What sets an analyst apart is knowing how good that rule is: how many false positives it throws against legitimate software and what it actually detects. Here that is a reproducible number. The harness measured a 12.18% false positive rate on 52 signed, legitimate binaries, and drove the redesign rule by rule down to 0% with no loss of detection. Every change is backed by data, not gut feeling.
</details>

<details>
<summary><b>Cromatóforo</b>: an Arch desktop where every color comes from the wallpaper</summary>
<br>

Change the wallpaper and the bar, launcher, terminal, prompt, notifications, editor, browser, Steam, Spotify and the GTK and Qt apps all pick up the palette in the same pass. Nineteen consumers hanging off a single source of truth, each with its own template: to change how a color is mapped you edit the template, never the program's final config.

The interesting part isn't that it looks nice, it's what doesn't fit the model. `qt6ct` watches its own config file and not the color scheme that file points to, so regenerating the palette repaints nothing until you `touch` it. Steam only reads its CSS at startup, and the script deliberately doesn't restart it: it would kill your game mid-match. All of that is documented, pitfalls included.
</details>

<details>
<summary><b>CIBO</b>: an AI assistant that runs fully local on Ollama</summary>
<br>

It knows when to reach for a real calculator instead of making up numbers, runs Python code in an isolated subprocess and has a layer that keeps sensitive data from leaving the machine. I started it to understand how an LLM works on the inside instead of just using one.
</details>

<details>
<summary><b>Pinchadiscos</b>: Spotify playlist generator in Next.js</summary>
<br>

Filter by artist, genre, decade and popularity, review the result in the browser and save it to your real account. OAuth 2.0 with automatic token refresh, and the token exchange goes through server routes so the client secret never reaches the browser.
</details>

<details>
<summary><b>Garabato</b>: from a plain-text script to an edited video</summary>
<br>

Voice, images, subtitles and final assembly. I built it because recording the narration and finding an image for every sentence is what turns an eight-minute video into a full day of work. Scripts follow a fixed set of rules, and the pipeline makes the rest of the video without me touching anything. Every step is idempotent: you can stop halfway and pick up where you left off.
</details>

<details>
<summary><b>Vitrina</b>: my collection of games, films, books and albums, from Obsidian to the web</summary>
<br>

Each work is a Markdown note in Obsidian, published as a static site at [jorgeress.github.io/vitrina](https://jorgeress.github.io/vitrina/). It works as a template to build your own, in English or Spanish.
</details>

Also **[PokeGAN](https://github.com/jorgeress/pokegan)**, a DCGAN trained from scratch for 10,000 epochs to generate Pokémon sprites.

Right now I'm building an app that's still under wraps.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jorgeress/jorgeress/output/serpiente-oscura.svg">
  <img src="https://raw.githubusercontent.com/jorgeress/jorgeress/output/serpiente.svg" width="100%" alt="A snake eating its way through my contribution graph">
</picture>

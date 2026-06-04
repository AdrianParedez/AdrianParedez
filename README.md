<div align="center">

# Adrian Paredez

<p>
  <strong>First-principles systems · hardened runtimes · open-source engineering</strong>
</p>

<p>
  <a href="https://paredez.dev">paredez.dev</a> ·
  <a href="https://github.com/AdrianParedez/milner">milner</a>
</p>

<p>
  <img alt="Rust" src="https://img.shields.io/badge/rust-systems-f74c00">
  <img alt="Windows" src="https://img.shields.io/badge/windows-first-0078D4">
  <img alt="Dependencies" src="https://img.shields.io/badge/dependencies-minimal-fbdecc">
  <img alt="Public work" src="https://img.shields.io/badge/public%20focus-milner-6f42c1">
</p>

</div>

I build software from first principles: small surfaces, explicit contracts,
minimal dependencies, and behaviour that can be inspected under pressure. My
current public focus is Milner, a Windows-first command runtime being shaped
into production-grade infrastructure with safety, performance, and long-term
open-source maintenance treated as design requirements from the start.

## Public Focus

<table>
  <tr>
    <td width="160"><strong>Milner</strong></td>
    <td>
      A Windows-first Rust command runtime built around explicit process launch,
      typed parsing, narrow execution policy, and hardened operating-system
      boundaries.
      <br><br>
      <a href="https://github.com/AdrianParedez/milner">Repository</a> ·
      <a href="https://github.com/AdrianParedez/milner/releases/latest">Latest release</a>
    </td>
  </tr>
</table>

Install Milner on Windows:

```powershell
irm https://paredez.dev/install.ps1 | iex
```

## Current Lane

```text
native execution      typed command surfaces      first-principles systems
hardened runtimes     safety by construction      open-source engineering
```

<details>
<summary><strong>Working principles</strong></summary>

- Design from first principles before importing complexity.
- Keep dependencies intentional, minimal, and justified.
- Prefer explicit contracts over ambient behaviour.
- Reject ambiguous input instead of guessing.
- Make verification part of the operating surface.
- Optimise from evidence, not instinct.
- Publish only what can be maintained with discipline.

</details>

<details>
<summary><strong>Recurring stack</strong></summary>

- Rust for command runtimes and native execution boundaries
- TypeScript for web-facing control surfaces
- Tauri for planned desktop applications
- Python for research automation and local AI experiments
- Cloudflare for lightweight public infrastructure

</details>

<sub>Built with assistance from Sole.</sub>

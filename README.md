<h1 align="center">Nethum Weerasinghe</h1>
<p align="center">Computer Science @ Texas A&M · builds multi-agent AI tooling · contributes to the NVIDIA open-source stack</p>

<p align="center">
  <a href="https://github.com/nethum529?tab=repositories">Repositories</a> ·
  <a href="#selected-open-source-contributions">Contributions</a> ·
  <a href="#things-ive-built">Projects</a>
</p>

---

I'm a CS major at Texas A&M, currently interning at Global Shop Solutions. Outside of that I spend most of my time doing two things: building my own multi-agent orchestration tooling for coding with LLMs, and sending patches into the GPU/data-science and AI-agent open-source projects I actually use.

### Selected open-source contributions

| Repo | Contribution | Status |
|---|---|---|
| [rapidsai/cudf](https://github.com/rapidsai/cudf) | [Support host buffers (`BytesIO`) in `cudf.read_text`](https://github.com/rapidsai/cudf/pull/23032) | ✅ merged |
| [rapidsai/cudf](https://github.com/rapidsai/cudf) | [Accept inf/-inf as valid FLOAT32 scalar values (pylibcudf)](https://github.com/rapidsai/cudf/pull/23099) | 🔄 in review |
| [rapidsai/cuml](https://github.com/rapidsai/cuml) | [Support object dtype in `ColumnTransformer` + `SimpleImputer` on cuDF](https://github.com/rapidsai/cuml/pull/8317) | 🔄 in review |
| [NVIDIA/cccl](https://github.com/NVIDIA/cccl) | [Cache `cuda.compute` builds for closures over Python scalars](https://github.com/NVIDIA/cccl/pull/9680) | ✅ merged |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [Migrate `langdetect` to `langid.py` with lazy loading](https://github.com/NVIDIA/garak/pull/1899) | 🔄 in review |
| [NVIDIA/boro](https://github.com/NVIDIA/boro) | [Order-independent subject sanitizing and case-insensitive trailer](https://github.com/NVIDIA/boro/pull/12) | ✅ merged |
| [omnigent-ai/omnigent](https://github.com/omnigent-ai/omnigent) | [Isolate per-tool schema build in `get_tool_schemas`](https://github.com/omnigent-ai/omnigent/pull/1335) | ✅ merged |

A few more merged fixes to `boro` (patch-apply conflict handling) and open PRs to `cudf`/`cuml`/`cccl` live on my [pull requests page](https://github.com/pulls?q=is%3Apr+author%3Anethum529).

### Things I've built

- **[ShaiBot](https://github.com/nethum529/ShaiBot)** — an agentic LLM trading system with a deterministic safety layer: a paper-trading testbed for letting an unreliable model take real actions without letting it hurt you.
- **[Seer](https://github.com/nethum529/Seer)** — a native, keyboard-first launcher for Linux/Wayland in the spirit of Raycast. No Electron, no web runtime — a resident Rust agent + native GUI panel.
- **[perci](https://github.com/nethum529/perci)** — a course-companion app: syllabus parsing, per-course assignment tracking, and dashboards for students.
- **[tool-ring](https://github.com/nethum529/tool-ring)** — a radial ring of launcher badges around the cursor for Hyprland/wlroots compositors, drawn as a transparent GTK4 layer-shell overlay.
- **[obsidian-axi](https://github.com/nethum529/obsidian-axi)** — the first AXI (Agent eXperience Interface) for Obsidian: read, search, and edit a vault from the shell, built for agents to drive directly instead of through an MCP.

### Stack

`Python` · `Rust` · `TypeScript` · `C++` · `CUDA` · Linux/Wayland · multi-agent orchestration (Claude Code, Codex)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nethum529&show_icons=true&hide_title=true&hide_border=true&count_private=true" alt="nethum529's GitHub stats" height="165"/>
</div>

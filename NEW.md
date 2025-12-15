
<div align="center">

<img src="logo.png" width="96">

<h1><samp><b>Project Title</b></samp></h1>

<table>
<tr><td>
Short, focused description of what the project does.
</td></tr>
</table>

</div>

---

## Overview

Brief explanation of the project goals, scope, and audience.

---

> [!TIP]
> ## 🎬 Demo
>
> <details>
> <summary><b>View demo</b></summary>
>
> Short explanation of what is shown.
>
> <img src="demo.gif" width="680">
> </details>

---

> [!IMPORTANT]
> ## Setup
>
> Clone the repository:
> ```sh
> git clone <repo>
> cd project
> ```
>
> Build and install:
> ```sh
> make
> sudo make install
> ```

---

> [!NOTE]
> ## ℹ️ Information
>
> - Purpose: experimental / educational
> - Stability: usable
> - Scope: terminal application
>
> <details>
> <summary><b>Compatibility</b></summary>
>
> | Platform | Status |
> |---|---|
> | Linux | ✅ |
> | macOS | ⚠️ |
> | Windows | ❌ |
>
> </details>

---

> [!TIP]
> ## Usage
>
> ```sh
> project [-f fps] [-s speed] [--info]
> ```
>
> ### Runtime Controls
> | Action | Key |
> |---|---|
> | Toggle UI | `i` |
> | Speed ± | `←` / `→` |

---

> [!IMPORTANT]
> ## Build
>
> Using Makefile:
> ```sh
> make
> make run
> sudo make install
> make clean
> ```
>
> Manual compilation:
> ```sh
> gcc -O2 main.c -o project
> ```

---

> [!NOTE]
> ## 🧱 Architecture
>
> - Core logic
> - Rendering layer
> - CLI interface
>
> <details>
> <summary><b>Flow</b></summary>
>
> Input → Parser → Core → Renderer → Output
>
> </details>

---

> [!TIP]
> ## ⚙️ Configuration
>
> ```ini
> fps=60
> speed=1.0
> theme=dark
> ```

---

> [!WARNING]
> ## Assets
>
> <details>
> <summary><b>Logos & banners</b></summary>
>
> <img src="banner-dark.svg" width="280">
>
> <img src="logo-light.svg" width="80">
>
> </details>

---

> [!WARNING]
> ## 🔐 Security
>
> - No sandboxing
> - No privilege separation
> - Do not run as root unless required

---

> [!CAUTION]
> ## Requirements
>
> - Linux / macOS
> - GCC or Clang
> - UTF-8 terminal

---

> [!IMPORTANT]
> ## 🛠 Troubleshooting
>
> **Blank output**
> - Check terminal UTF-8 support
>
> **Build fails**
> - Verify dependencies
> - Run `make clean`

---

> [!NOTE]
> ## 🎯 Philosophy
>
> This project prioritizes:
> - Learning
> - Simplicity
> - Visual experimentation

---

> [!NOTE]
> ## 🤝 Contributing
>
> Contributions are welcome:
> - Bug reports
> - Packaging
> - Documentation

---

> [!TIP]
> ## 🗺 Roadmap
>
> - [ ] Config file support
> - [ ] Better Unicode fallback
> - [ ] Cross-platform builds

--- 

# INDEXED

# COMPONENT_INDEX.md
Reusable, tagged Markdown documentation components.
Each block is self-contained and copy‑paste friendly.

---

## [COMPONENT:HEADER:CENTERED]

```md
<div align="center">

<img src="logo.png" width="96">

<h1><samp><b>Project Title</b></samp></h1>

<table>
<tr><td>
One‑line project description.
</td></tr>
</table>

</div>
```

---

## [COMPONENT:SECTION:OVERVIEW]

```md
## Overview

Short explanation of goals, scope, and audience.
```

---

## [COMPONENT:CALLOUT:DEMO:TIP]

```md
> [!TIP]
> ## 🎬 Demo
>
> <details>
> <summary><b>View demo</b></summary>
>
> Short explanation of what is shown.
>
> <img src="demo.gif" width="680">
> </details>
```

---

## [COMPONENT:CALLOUT:SETUP:IMPORTANT]

```md
> [!IMPORTANT]
> ## Setup
>
> ```sh
> git clone <repo>
> cd project
> make install
> ```
```

---

## [COMPONENT:CALLOUT:INFO:NOTE]

```md
> [!NOTE]
> ## ℹ️ Information
>
> - Purpose: experimental / educational
> - Stability: usable
> - Scope: terminal application
```

---

## [COMPONENT:TABLE:COMPATIBILITY]

```md
| Platform | Status |
|---|---|
| Linux | ✅ |
| macOS | ⚠️ |
| Windows | ❌ |
```

---

## [COMPONENT:CALLOUT:USAGE:TIP]

```md
> [!TIP]
> ## Usage
>
> ```sh
> project [options]
> ```
```

---

## [COMPONENT:TABLE:HOTKEYS]

```md
| Action | Key |
|---|---|
| Toggle UI | `i` |
| Speed ± | `←` / `→` |
```

---

## [COMPONENT:CALLOUT:BUILD:IMPORTANT]

```md
> [!IMPORTANT]
> ## Build
>
> ```sh
> make
> sudo make install
> ```
```

---

## [COMPONENT:CALLOUT:ARCHITECTURE:NOTE]

```md
> [!NOTE]
> ## 🧱 Architecture
>
> Input → Core → Renderer → Output
```

---

## [COMPONENT:CALLOUT:CONFIG:TIP]

```md
> [!TIP]
> ## ⚙️ Configuration
>
> ```ini
> key=value
> ```
```

---

## [COMPONENT:CALLOUT:ASSETS:WARNING]

```md
> [!WARNING]
> ## Assets
>
> <details>
> <summary><b>Logos & banners</b></summary>
>
> <img src="logo.svg" width="80">
> </details>
```

---

## [COMPONENT:CALLOUT:SECURITY:WARNING]

```md
> [!WARNING]
> ## 🔐 Security
>
> - No sandboxing
> - No privilege separation
```

---

## [COMPONENT:CALLOUT:REQUIREMENTS:CAUTION]

```md
> [!CAUTION]
> ## Requirements
>
> - Linux / macOS
> - UTF‑8 terminal
```

---

## [COMPONENT:CALLOUT:TROUBLESHOOTING:IMPORTANT]

```md
> [!IMPORTANT]
> ## 🛠 Troubleshooting
>
> **Build fails**
> - Check dependencies
```

---

## [COMPONENT:CALLOUT:PHILOSOPHY:NOTE]

```md
> [!NOTE]
> ## 🎯 Philosophy
>
> Learning‑first, minimal, experimental.
```

---

## [COMPONENT:CALLOUT:CONTRIBUTING:NOTE]

```md
> [!NOTE]
> ## 🤝 Contributing
>
> Issues, docs, and packaging welcome.
```

---

## [COMPONENT:CALLOUT:ROADMAP:TIP]

```md
> [!TIP]
> ## 🗺 Roadmap
>
> - [ ] Feature A
> - [ ] Feature B
```

---

## [COMPONENT:FOOTER:LICENSE]

```md
## License
MIT © Author
```

---

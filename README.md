# Awesome-Terminal-Emulator-Utility

## Top Terminal Emulator Utility Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Shell Enhancement, CLI Productivity & Terminal Workflow Tools*  

**Last updated: October 2026**



This repository tracks notable **commercial terminal utilities** and **open-source projects** that enhance the terminal experience — from shell prompts and command history to file managers, fuzzy finders, and session managers that make command-line work faster and more ergonomic.



**Examples** include Windows Terminal Preview, iTerm2, Alacritty, Kitty, Hyper, ConEmu, PuTTY, Warp, MobaXterm, and WezTerm (the category leaders).



**Open-source emphasis**: Terminal utilities are one of the strongest open-source domains. **Starship**, **fzf**, **zoxide**, **bat**, **eza**, and **ripgrep** collectively modernize the command line with zero licensing costs. **tmux** and **Zellij** provide session persistence, while **Atuin** and **McFly** reinvent shell history. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Warp](https://www.warp.dev/)**  

  AI-powered terminal with command suggestions, blocks-based output, and collaborative features. **Free tier available**; paid for teams. **The most AI-forward commercial terminal** — closed source. Includes Warp Drive for sharing workflows and Agent Mode for multi-step task automation.



- **[MobaXterm](https://mobaxterm.mobatek.net/)**  

  Windows terminal with built-in X server, SSH client, SFTP browser, and remote desktop tools. **Free tier available** with limited sessions; Professional edition for unlimited use. **The Swiss Army knife of Windows remote access** — proprietary but widely deployed in enterprise.



- **[Windows Terminal Preview](https://github.com/microsoft/terminal)**  

  Preview channel of Microsoft's terminal with early access to upcoming features. **Open-source** (MIT) — the preview channel is the testing ground for stable releases .



## Open-Source GitHub Projects



### Shell Prompts & Enhancement



- **[Starship](https://github.com/starship/starship)**  

  **The minimal, blazing-fast, and infinitely customizable prompt for any shell**, ISC licensed with 45,000+ GitHub stars . **Written in Rust** — works with Bash, Zsh, Fish, PowerShell, Ion, Elvish, Xonsh, and more . Shows context-aware information: Git status, language versions, execution time, battery, and cloud context . **The de facto cross-shell prompt** — replace your shell's prompt with one binary .



- **[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)**  

  **The most popular Zsh configuration framework**, MIT licensed with 175,000+ GitHub stars . **300+ plugins and 150+ themes** for Git, Docker, Kubernetes, and more . **The standard Zsh setup** — makes Zsh usable without manual configuration .



- **[Powerlevel10k](https://github.com/romkatv/powerlevel10k)**  

  **The fastest Zsh theme**, MIT licensed with 45,000+ GitHub stars . **Instant prompt** with no perceptible delay . **The most responsive prompt** — optimized for speed while remaining highly configurable .



- **[Oh My Posh](https://github.com/JanDeDobbeleer/oh-my-posh)**  

  **Cross-shell prompt customization engine**, MIT licensed with 20,000+ GitHub stars . **Works on Windows, Linux, macOS, and WSL** with any shell . **The best prompt for Windows PowerShell users** — brings Starship-like features to PowerShell .



- **[Nushell](https://github.com/nushell/nushell)**  

  **Modern shell with structured data pipelines**, MIT licensed with 35,000+ GitHub stars . **Treats data as structured tables** rather than text streams . **The most innovative shell** — commands like `ls | where size > 10mb | sort-by modified` work natively .



### Command History & Navigation



- **[Atuin](https://github.com/atuinsh/atuin)**  

  **Magical shell history with a SQLite database**, MIT licensed with 20,000+ GitHub stars . **Syncs history across machines** with end-to-end encryption . **Full-text search, stats, and context** — know where, when, and how long each command ran . **The best shell history replacement** — supports Bash, Zsh, Fish, and Nushell .



- **[McFly](https://github.com/cantino/mcfly)**  

  **Neural network-powered shell history search**, MIT licensed . **Learns from your choices** to prioritize relevant commands . **The smartest history search** — works with Bash and Zsh .



- **[fzf](https://github.com/junegunn/fzf)**  

  **The general-purpose command-line fuzzy finder**, MIT licensed with 65,000+ GitHub stars . **Fuzzy search for files, history, processes, and anything piped to it** . **The most important CLI utility in the last decade** — integrates with Vim, Neovim, and every shell .



- **[zoxide](https://github.com/ajeetdsouza/zoxide)**  

  **Smarter cd command that learns your habits**, MIT licensed with 25,000+ GitHub stars . **Jump to frequently used directories with `z foo`** . **The best directory navigation tool** — works with all major shells .



- **[z (rupa)](https://github.com/rupa/z)**  

  **The original directory jumper** — predecessor to zoxide . **Simple and effective** — tracks visited directories and allows jumping by partial match .



- **[autojump](https://github.com/wting/autojump)**  

  **Fast directory navigation using a weighted database**, GPL-3.0 licensed . **The classic `j` command** — learns from `cd` usage .



### File & Text Utilities



- **[bat](https://github.com/sharkdp/bat)**  

  **A cat clone with syntax highlighting and Git integration**, MIT licensed with 50,000+ GitHub stars . **Replaces cat with automatic paging, line numbers, and syntax highlighting** . **The best cat replacement** — supports 200+ languages and themes .



- **[eza](https://github.com/eza-community/eza)**  

  **Modern replacement for ls**, MIT licensed with 15,000+ GitHub stars . **Icons, Git status, colors, and tree view** by default . **The best ls replacement** — fork of the now-unmaintained exa .



- **[lsd](https://github.com/lsd-rs/lsd)**  

  **The next-gen ls command**, Apache-2.0 licensed with 14,000+ GitHub stars . **Icons, colors, and tree view** with a different aesthetic from eza .



- **[ripgrep](https://github.com/BurntSushi/ripgrep)**  

  **Recursively searches directories for a regex pattern**, MIT licensed with 50,000+ GitHub stars . **Faster than grep, ag, and ack** — respects .gitignore by default . **The standard code search tool** — used internally by VS Code .



- **[fd](https://github.com/sharkdp/fd)**  

  **Simple, fast, user-friendly alternative to find**, MIT licensed with 35,000+ GitHub stars . **Intuitive syntax, smart case, and .gitignore respect** . **The best find replacement** — `fd pattern` instead of `find . -name "*pattern*"` .



- **[delta](https://github.com/dandavison/delta)**  

  **A viewer for git and diff output**, MIT licensed with 25,000+ GitHub stars . **Syntax highlighting, side-by-side view, and line numbers** for diffs . **The best git diff viewer** — integrates with git, delta, and diff-so-fancy .



- **[jq](https://github.com/stedolan/jq)**  

  **Command-line JSON processor**, MIT licensed with 30,000+ GitHub stars . **Slice, filter, map, and transform JSON** with a simple query language . **The standard JSON tool** — essential for API work .



- **[yq](https://github.com/mikefarah/yq)**  

  **Command-line YAML/XML/JSON processor**, MIT licensed with 12,000+ GitHub stars . **jq for YAML** — essential for Kubernetes and CI/CD .



- **[fx](https://github.com/antonmedv/fx)**  

  **Terminal JSON viewer and processor**, MIT licensed with 19,000+ GitHub stars . **Interactive JSON exploration** — better than jq for viewing .



### Terminal Multiplexers & Session Management



- **[tmux](https://github.com/tmux/tmux)**  

  **The standard terminal multiplexer**, ISC licensed with 35,000+ GitHub stars . **Sessions, windows, and panes with detach/reattach** . **Essential for remote work and long-running processes** .



- **[Zellij](https://github.com/zellij-org/zellij)**  

  **Modern terminal workspace and multiplexer**, MIT licensed with 20,000+ GitHub stars . **Built-in layouts, plugins, and discoverable keybindings** . **The user-friendly tmux alternative** .



- **[abduco](https://github.com/martanne/abduco)**  

  **Session management with minimal dependencies**, ISC licensed . **The simplest detach/reattach tool** — pairs with dvtm for panes .



### Process & System Monitoring



- **[btop](https://github.com/aristocratos/btop)**  

  **Resource monitor with a beautiful TUI**, Apache-2.0 licensed with 20,000+ GitHub stars . **CPU, memory, disks, network, and processes** with graphs and themes . **The best top replacement** — visually stunning and informative .



- **[htop](https://github.com/htop-dev/htop)**  

  **Interactive process viewer**, GPL-2.0 licensed with 6,000+ GitHub stars . **The classic top replacement** — color, scrolling, and mouse support .



- **[bottom](https://github.com/ClementTsang/bottom)**  

  **Cross-platform graphical process/system monitor**, MIT licensed with 9,000+ GitHub stars . **Customizable widgets and layouts** — written in Rust .



- **[glances](https://github.com/nicolargo/glances)**  

  **Cross-platform system monitoring tool**, LGPL-3.0 licensed with 25,000+ GitHub stars . **Web UI, API, and export formats** — monitors CPU, memory, disks, network, and sensors .



### Network & Remote Access



- **[lazygit](https://github.com/jesseduffield/lazygit)**  

  **Simple terminal UI for Git commands**, MIT licensed with 50,000+ GitHub stars . **Stage, commit, branch, rebase, and resolve conflicts** with keyboard shortcuts . **The best Git TUI** — makes complex Git operations accessible .



- **[lazydocker](https://github.com/jesseduffield/lazydocker)**  

  **Terminal UI for Docker and Docker Compose**, MIT licensed with 35,000+ GitHub stars . **Manage containers, images, volumes, and logs** with keyboard navigation . **The best Docker TUI** .



- **[k9s](https://github.com/derailed/k9s)**  

  **Kubernetes CLI to manage your clusters in style**, Apache-2.0 licensed with 25,000+ GitHub stars . **Real-time cluster monitoring, pod logs, and resource editing** . **The best Kubernetes TUI** .



- **[termshark](https://github.com/gcla/termshark)**  

  **Terminal UI for tshark**, MIT licensed with 9,000+ GitHub stars . **Wireshark-like packet analysis in the terminal** .



- **[ncdu](https://github.com/rofl0r/ncdu)**  

  **NCurses disk usage analyzer**, MIT licensed with 3,000+ GitHub stars . **Interactive disk usage exploration** — find what's consuming space .



### Additional Strong Open-Source Options



- **exa** — Predecessor to eza, now unmaintained but still used .

- **prettyping** — Prettier ping output with graphs and colors .

- **dog** — DNS lookup tool with colorful output .

- **httpie** — User-friendly HTTP client for the terminal .

- **curlie** — Modern curl with httpie-like syntax .

- **xh** — Fast HTTP client in Rust .

- **gron** — Make JSON greppable .

- **hyperfine** — Command-line benchmarking tool .

- **tokei** — Count lines of code by language .

- **procs** — Modern ps replacement in Rust .

- **dust** — More intuitive du in Rust .

- **duf** — Disk usage/free utility with table output .

- **bandwhich** — Terminal bandwidth utilization tool .

- **grex** — Generate regular expressions from examples .



**Frameworks for building custom terminal utility stacks**: Combine **Starship** for a cross-shell prompt with **fzf** for fuzzy finding and **zoxide** for directory jumping . Replace core utilities with **bat** (cat), **eza** (ls), **fd** (find), **ripgrep** (grep), and **delta** (diff) . Add **tmux** or **Zellij** for session management and **lazygit**/**lazydocker**/**k9s** for Git/Docker/Kubernetes workflows . Use **Atuin** for encrypted shell history sync and **btop** for system monitoring . Note that true commercial terminal utilities like Warp's AI features and MobaXterm's integrated X server remain primarily proprietary, but open-source alternatives match or exceed their core functionality .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Terminal utilities often handle sensitive data including command history, credentials, and file contents. **Review privacy settings** — Atuin syncs history to a server (encrypted), Warp transmits command data for AI features .

- **Replacing core utilities (cat, ls, find) requires shell aliases** — ensure your configuration is portable across machines and doesn't break scripts that expect standard output .

- **Some utilities require Rust/Cargo or Go for installation** — pre-built binaries are available for most, but check compatibility with your system .

- The open-source ecosystem provides strong prompt, navigation, and monitoring foundations, but **AI-powered command generation and integrated remote access** remain primarily commercial offerings.



---



**Made for developers, system administrators, and command-line enthusiasts.**

Let's make terminal utilities more open, transparent, and productive.

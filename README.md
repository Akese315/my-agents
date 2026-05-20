# my-agents

# Setup #

## 1ère étape : ##

Placer le dossier agents dans :

Pour Linux :
```sh
~/.config/opencode/
```
Pour MacOS :
```sh
~/Library/Application Support/opencode/
```
Pour Windows :
```sh
C:\Users\<USER>\.config\opencode\
```

Et remplacer le fichier opencode.jsonc du dossier précédent avec celui du repo

## 2nd étape ## 

Par défaut, OpenCode possède 2 agents : 
- Build
- Plan

L'agent que j'ai créé s'appelle Orchestrator. Veuillez le sélectionner.

# Liste des agents #

| Agent Name | Primary Capability | Triggers / Keywords |
| :--- | :--- | :--- |
| `c-architecture-reviewer` | C architecture, modularity, APIs | "review architecture", "coupling", "design" |
| `c-build-reasoning` | Makefiles, toolchains, CI/CD | "build fails", "makefile", "linking error" |
| `c-performance-reviewer` | C cache efficiency, concurrency | "slow", "optimize", "bottleneck", "profiling" |
| `c-security-reviewer` | C memory safety, UB, exploits | "security check", "memory leak", "segfault" |
| `rust-reviewer` | Rust code quality, lifetimes, FFI | "rust review", "borrow checker", "unsafe" |
| `web-searcher` | Web research, factual verification | "search the web", "look up documentation" |
| `codebase-explorer` | Local file search, structure | "find file", "where is", "grep", "explore" |
| `C&Rust-coder-implementer` | C and Rust Code implementation & editing | "fix bug", "write feature", "refactor" |
| `test-engineer` | Writing and running tests | "write tests", "run suite", "coverage" |
| `python-coder-implementer` | Python code implementation & refactoring | "fix python bug", "python feature", "python refactor" |
| `python-reviewer` | Python code review (style, correctness, idioms) | "python review", "python style", "idiomatic python" |
| `python-performance-reviewer` | Python performance analysis | "python slow", "python optimize", "python bottleneck" |
| `python-security-reviewer` | Python security audit | "python security", "python vuln", "injection" |
| `python-test-engineer` | Python test writing & execution | "python tests", "pytest", "python coverage" |
| `git-manager` | Git operations & commits | "git commit", "stage files", "version control" |

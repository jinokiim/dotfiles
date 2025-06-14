# ⚙️ Dotfiles for me

반복적인 개발 환경 세팅을 자동화하고, 일관된 코딩 스타일을 유지하며 협업 시 환경 차이를 줄이기 위한 **dotfiles 저장소**입니다.

> 구성: Zsh, Git, ESLint, Prettier, VSCode, pnpm, nvm, stow 자동 세팅 스크립트 등

---

## 📁 구조 개요

```text
.
├── zsh/                  # Zsh 설정 (.zshrc)
├── git/                  # Git 설정 (.gitconfig, .gitignore_global)
├── npm/                  # pnpm 설정 (.npmrc)
├── editor/               # Editor 설정 (Prettier, ESLint, VSCode 등)
│   └── vscode/           # VSCode 사용자 설정 및 확장 목록
├── scripts/              # 초기 세팅 자동화 스크립트
└── README.md

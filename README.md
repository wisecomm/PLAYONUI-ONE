# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

1. vite 프로젝트 생성 (svelet 프로젝트, sveletkit 사용)
npm create vite@latest 

2. flyonui 설치 (참조 tailwind 설치)
- npm i flyonui 
- Tailwind CSS 설치:
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

tailwind.config.js : 수정

# 에러 처리
- Unknown at rule @tailwind vscode 코드 워닝
Go to the Extensions view in VS Code (Ctrl+Shift+X or Cmd+Shift+X on Mac).
Search for "Tailwind CSS IntelliSense" and install it.


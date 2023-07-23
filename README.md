"# howToSvelte" 

create a new repository on the command line:
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MYHan531/howToSvelte.git
git push -u origin main

To push an existing repository from the command line:
git remote add origin https://github.com/MYHan531/howToSvelte.git
git branch -M main
git push -u origin main

How to Create a new Svelte app in steps below:
1. npm create svelte@latest my-app
2. cd my-app
3. npm install
4. npm run dev

The first command will scaffold a new project in the "my-app" directory asking you if you'd like to set up some basic tooling such as TypeScript. 
The subsequent commands will then install its dependencies and start a server on localhost:5173.


Type-checked JavaScript
  https://www.typescriptlang.org/tsconfig#checkJs

✔ ESLint
  https://github.com/sveltejs/eslint-plugin-svelte

✔ Prettier
  https://prettier.io/docs/en/options.html
  https://github.com/sveltejs/prettier-plugin-svelte#options

✔ Playwright
  https://playwright.dev

✔ Vitest
  https://vitest.dev

Install community-maintained integrations:
  https://github.com/svelte-add/svelte-add

Next steps:
1. cd my-app
2. npm install (or pnpm install, etc)
3. git init && git add -A && git commit -m "Initial commit" (optional)
4. npm run dev -- --open
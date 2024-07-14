# svelte-bug

## Creation
The repository's initial commit was constructed like so.

```
~
❯ cd desktop
~/desktop
❯ npm create svelte@latest svelte-bug

> npx
> create-svelte svelte-bug


create-svelte version 6.3.3

┌  Welcome to SvelteKit!
│
◇  Which Svelte app template?
│  Skeleton project
│
◇  Add type checking with TypeScript?
│  No
│
◇  Select additional options (use arrow keys/space bar)
│  Try the Svelte 5 preview (unstable!)
│
└  Your project is ready!

Install more integrations with:
  npx svelte-add

Next steps:
  1: cd svelte-bug
  2: npm install
  3: git init && git add -A && git commit -m "Initial commit" (optional)
  4: npm run dev -- --open

To close the dev server, hit Ctrl-C

Stuck? Visit us at https://svelte.dev/chat
~/desktop
❯ cd svelte-bug
~/desktop/svelte-bug
❯ npm install
npm warn ERESOLVE overriding peer dependency

added 52 packages, and audited 53 packages in 5s

4 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
~/desktop/svelte-bug
❯ git init && git add -A && git commit -m "skeleton project"
Initialized empty Git repository in /Users/brian/Desktop/svelte-bug/.git/
[main (root-commit) 6630421] skeleton project
 11 files changed, 1453 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 .npmrc
 create mode 100644 README.md
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 src/app.html
 create mode 100644 src/lib/index.js
 create mode 100644 src/routes/+page.svelte
 create mode 100644 static/favicon.png
 create mode 100644 svelte.config.js
 create mode 100644 vite.config.js
 ```

## Running
THe project is run via ```npm run build && npm run preview```.

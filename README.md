

### General Prerequisites:

- NodeJS/npm
- Vue CLI (`yarn global add @vue/cli` / `npm i -g @vue/cli`)
- [Rust/Cargo](https://www.rust-lang.org/)
- Tauri CLI (`cargo install tauri-bundler`)
- [Yarn](https://yarnpkg.com/lang/en/) (optional but recommended over npm)

### Steps:

1. Create a Vue CLI project (or cd into an existing one)

```bash
vue create my-tauri-app
cd my-tauri-app
```

2. Install Vue CLI Plugin Tauri

```bash
vue add tauri
```

3. Run commands

With Yarn:

```bash
# Start dev server with HMR
yarn tauri:serve
# Build executable
yarn tauri:build
```

With npm:

```bash
# Start dev server with HMR
npm run tauri:serve
# Build executable
npm run tauri:build
```
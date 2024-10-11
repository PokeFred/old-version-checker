# Requirements

- NodeJS
    - every pnpm command can be used with npm too
    - `pnpm abc` -> `npm run abc`
- Rust ([More here](https://tauri.app/start/prerequisites/))

# Setup

## Pre-Steps for every Environment

```bash
$ git clone https://github.com/PokeFred/version-checker.git
$ cd version-checker
$ pnpm install
```

## Post-Steps for an Development Environment

```bash
$ pnpm dev
```

## Post-Steps for an Production Environment

```bash
// Windows
$ pnpm build
$ ./src-tauri/target/release/app.exe

// Linux
$ pnpm build
$ chmod +x ./src-tauri/target/release/app
$ ./src-tauri/target/release/app

// MacOS
// Comming soon...
```

# Setup

## Base Setup

```bash
$ git clone https://github.com/PokeFred/version-checker.git
$ cd version-checker
$ pnpm install
```

## Post Steps for an Development Environment

```bash
$ pnpm dev
```

## Post Steps for an Production Environment

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
# Snake Game

Snake game using plain TypeScript and Rust, which is being compiled to WASM

## Run Locally

Clone the project

```bash
  git clone git@github.com:37flwr/snake-game-rs.git
```

Go to the project directory

```bash
  cd snake-game-rs
```

Compile Rust code into WASM

```bash
  wasm-pack build --target web
```

Start the server

```bash
  cd www
  npm run dev
```

## Tech Stack

**Client:** Plain TS, CSS

**Server:** Rust, WASM

## Roadmap

- [ ] Add more UI (Vue)
- [ ] Refactor Rust code

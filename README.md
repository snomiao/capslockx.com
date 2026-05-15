# capslockx.com

Landing page for [CapsLockX 2.0](https://github.com/snolab/CapsLockX) — a cross-platform keyboard productivity layer in Rust with voice dictation and an LLM agent.

Live at <https://capslockx.com>.

## Stack

Plain static HTML + CSS (no build step). Theme toggle and smooth scroll in inline JS.

## Local preview

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy

```bash
bunx vercel --prod
```

(Auto-deploys from `main` via the connected hosting provider.)

## License

MIT — see [LICENSE](./LICENSE).

## Bug Reproduction

- pnpm install
- pnpm dev
  - App works
- pnpm build
- pnpm start
  - Crash. Cannot read length of undefined.
- Remove lazy import in createServerData$
- pnpm build
- pnpm start
  - Works.

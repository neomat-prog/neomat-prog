
```ts
const kacper = {
  role: "fullstack engineer",
  years: 3,

  editors: ["neovim", "vscode"],

  languages: ["typescript", "golang"],

  frameworks: {
    backend: ["node", "express", "effect-ts", "bun"],
    frontend: ["react", "next.js", "zustand"],
    mobile: ["react-native", "expo"],
  },

  infrastructure: {
    cloud: ["gcp"],
    containers: ["docker"],
    orchestration: ["kubernetes"],
    tooling: ["kubectl"],
  },
} as const;


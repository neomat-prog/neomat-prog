
```ts
const kacper = {
  role: "software engineer",
  years: 3,

  editors: ["neovim", "vscode"],

  stack: {
    languages: ["typescript", "go"],
    backend: ["node", "express", "gin"],
    frontend: ["react", "zustand", "tanstack query"],
    infra: ["gcp", "docker", "kubernetes", "kafka"],
  },
} as const;


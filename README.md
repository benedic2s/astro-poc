 bunx create-astro .
 bun add @astrojs/renderer-react
 bunx astro add react

// bunfig.toml
 [install.scopes]
# registry as string
"@gjensidige" = { token = "", url = "https://npm.pkg.github.com" }

brew tap oven-sh/bun
brew install bun

https://bun.sh/docs/installation

integrations: [
    react({
      experimentalReactChildren: true,
    }),
  ],

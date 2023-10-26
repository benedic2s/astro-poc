 bunx create-astro .
 bun add @astrojs/renderer-react
 bunx astro add react
 bun add @gjensidige/builders-fonts
 bun add @gjensidige/builders-components

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

  https://github.com/benedic2s/astro-poc.git
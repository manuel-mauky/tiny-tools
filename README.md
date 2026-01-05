# Tiny tools

This repo contains some tiny tools and scripts that I use all the time.
All of them are targeted for MacOS / Linux shells.


## `create-monorepo`

Creates a _yarn_ monorepo project
- create yarn project with workspaces setting
- add biome settings (see "biomeinit")


## `biomeinit`
Adds [biome](https://biomejs.dev/) to an existing _yarn_ project.

## Deprecated

### `prettierinit`

Adds prettier to an existing _yarn_ project.

- install prettier
- create a `.prettierrc.json` with my preferred settings
- configure git hooks to run prettier automatically

### `create-react-app`

Creates a basic react app with my preferred settings and tools. Not to be confused with
the [create-react-app](https://create-react-app.dev/)
tool that was once the official tool to setup react apps.

- create a yarn project with vite.js and react-ts template
- add prettier (see "prettierinit")
- setup gitignore

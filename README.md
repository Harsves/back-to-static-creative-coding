# Creative coding

<img width="359" alt="Schermafbeelding 2023-12-08 om 11 45 19" src="https://github.com/Harsves/back-to-static-creative-coding/assets/112931845/ed298aa4-c303-439e-ae76-3d109538ac95">

## Beschrijving
Week 1: Crazy 90s space psychedelia card

## Kenmerken

#### TOOLS :

* VSCode
* Miro
* Figma

#### GEBRUIKTE TECHNIEKEN :

* Svelte
* Sveltekit
* Hygragh
* JS
* CSS
  
COMMUNICATIE MIDDELEN :

* Team Canvas
* Microsoft Teams
* Calls


## Creating a project

If you're seeing this, you've probably already done this step. Congrats!
```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```


## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

Everything inside `src/lib` is part of your library, everything inside `src/routes` can be used as a showcase or preview app.

## Building

To build your library:

```bash
npm run package
```

To create a production version of your showcase app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## Publishing

Go into the `package.json` and give your package the desired name through the `"name"` option. Also consider adding a `"license"` field and point it to a `LICENSE` file which you can create from a template (one popular option is the [MIT license](https://opensource.org/license/mit/)).

To publish your library to [npm](https://www.npmjs.com):

```bash
npm publish
```

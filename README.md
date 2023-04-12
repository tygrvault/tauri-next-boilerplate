> **Note**  
> Tauri have their own [guide](https://tauri.app/v1/guides/getting-started/setup/next-js) on using NextJS as your frontend providor now. Please use that instead.

# ☁ Tauri & Next
![](https://i.imgur.com/asEHkSk.png)

# Setting up
```bash
$ git clone https://github.com/tygerxqt/tauri-next-boilerplate
$ cd tauri-next-boilerplate
$ yarn && yarn dev
=== OR ===
$ yarn && yarn dev:app
```

# Scripts
`yarn dev` - Starts Next development server.  
`yarn build` - Builds the Next app to `./out`.  
`yarn dev:app` - Builds and exports the Next app and launches the Tauri dev app.  
`yarn build:app` - Builds and exports the Next app, then builds the Tauri app and installer.

# Project tree
```
tauri-next-boilerplate/
├─ src/
│  ├─ pages/
│  ├─ public/
│  ├─ styles/
├─ src-tauri/
│  ├─ icons/
│  ├─ src/
│  ├─ build.rs
│  ├─ tauri.conf.json
│  ├─ Cargo.toml
...
```
`/src` - NextJS Project.  
`/src-tauri` - Tauri Project.  

**Note:** You might wanna edit the `/src-tauri/tauri.conf.json` file and replace the application icons at `/src-tauri/icons/*`

# Docs
[NextJS](https://nextjs.org/docs/getting-started) - Frontend framework docs.  
[Tauri](https://tauri.app/) - Tauri docs.

# Help
If more help is needed, you can contact me by [e-mail](mailto:hello@tygr.dev) or [tweet](https://twitter.com/intent/tweet?text=%40tygerxqt) to me.

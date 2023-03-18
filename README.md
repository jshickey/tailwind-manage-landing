# Tutorial Notes: Tailwind Crash Course | Project From Scratch

[YouTube Tutorial](https://www.youtube.com/watch?v=dFgzHOX84xQ&t=138s)
[Tutorial Repo](https://github.com/bradtraversy/tailwind-landing-page)

[Tailwind CSS Home Page](https://tailwindcss.com/docs/installation)

## Setup Sublime
[Add a Terminal](https://www.geeksforgeeks.org/how-to-use-terminal-in-sublime-text-editor/)
[Enable Auto-Save](https://lucybain.com/resources/setting-up-sublime-autosave/)
[Markdown Support](https://github.com/SublimeText-Markdown/MarkdownEditing)
[Markdown Preview](https://winmundo.com/plugins-how-to-preview-github-flavored-markdown-offline-in-sublime-text-3/)

[Sublime Essential Plugins](https://www.hongkiat.com/blog/sublime-text-plugins/)
[Format HTML, JS, CSS on Save](https://codecontinue.com/article/sublime-text-prettier-auto-format-on-save)

Emmet 

[BrowserSync](https://ainfographie.com/blog/tutoriels-wordpress/live-reload-sublime-how-to-install-live-reload-live-reload-extension-sublime-best-package/)

### Sublime Hot-Keys
* `alt + 1` to open a terminal
* `ctrl-shift-v` markdown preview in a browser


## Tutorial
```bash
npm init -y
npm i -D tailwindcss
npx tailwindcss init
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch 
```
 ### Update package.json
 ```json
   "scripts": {
    "build": "tailwindcss -i ./input.css -o ./css/main.css",
    "watch": "tailwindcss -i ./input.css -o ./css/main.css --watch"
  },
  ```
 ```bash
 npm run build
 npm run watch
 ```

 ```bash
 browser-sync start --server -f -w
 ```

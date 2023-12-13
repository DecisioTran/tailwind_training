# 1.1 Setting up Tailwind and PostCSS

To get started, `cd` into this subfolder and run `npm install` to install the dependencies.

Use `npm run build` to generate the compiled CSS, and a tool like [live-server](https://www.npmjs.com/package/live-server) to preview the site in the browser.

# Notes during setup and installations for TailwindCSS
(npm init -y -> npm i tailwindcss postcs-cli autoprefixer)
PostCSS will be responsible for importing our plugins for working with TailwindCSS and other configurations

tailwind.config.js (generated with npx tailwind init): contains all the configurations for tailwindcss in filename

npm run build (with the path containing compiled CSS for generating these compiles CSS files)

(Add file index.html with cdn(link enqueue in head tag) and usage of live server of previewing):
npm install -g live-server 
live-sever public
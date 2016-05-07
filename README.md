# Gulp Static Site Template

Simple application template that helps you out to kickstart a static application that includes Gulp tasks to compile assets (SASS, Jade, JS, Images) and deploy to Github Pages.

This application includes the following gulp tasks in order to automate

- **js**: Concats and minifies JS files to `app/dist/app.js`.
- **css**: Uses SCSS to process `app/src/style/app.scss` to `app/dist/style/app.css`.
- **clean_images**: Cleans `app/dist/images` folder.
- **images**: Copies images from `app/src/images/*/**` to `app/dist/images`.
- **jade**: Uses Jade to process `app/src/*.jade` to `app/dist`.
- **deploy**: Uses `gulp-gh-pages` npm library to deploy `dist` content to Github pages (it builds first!)
- **watch**: Runs corresponding task for supported action.
- **run**: Uses `serve` npm library to start a server with static content.

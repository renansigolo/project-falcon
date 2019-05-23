# Project Falcon

**The fastest task builder around the block**

Project Falcon is a template designed to simplify the folder structure used on a website development with a gulp workflow that delivers the fastest performance to your code.

## Getting Started

**Download and Install**

- [Node.js](https://nodejs.org/en/)

**Download and Unzip**

- [Project Falcon](https://github.com/renansigolo/project-falcon)

**Install Project Falcon Dependencies**

- Open terminal and run

  ```
  cd /Users/your-username-here/Downloads/project-falcon-master/

  npm i
  ```

#### ** That's it ! Your're ready to go ;) **

## How it works !?

**Watch**

- The watch command will compile SASS, JS and JS Libraries in real time

**Distribution Workflow**

Gulp optimize you code to the production environment. The workflow does the following:

- Clean the dist folder

- SASS

  Create sourcemaps,

  Use autroprefixer to ensure compatibility with the 2 last versions of all web browsers,

  Minify the code with cssnano,

  Rename `*.sass` to `styles.min.css`

  Paste in `/src/assets/css/`

- JS

  Create sourcemap,

  Minifiy the code with uglify,

  Concat all files in `/src/assets/_pre/js/`

  Paste scripts.min.js in `/src/assets/js/`

- Concat JS libraries

- Minify HTML files

- Optimize Images (GIF, SVG, ICO, JPG, JPEG, PNG)

- Copy remaining files

## Commands

- To serve your files and reload the browser after compile use: `npm start`

- To compile only js and sass files use: `npm run build`

- To compile everything in order to deploy to production use: `gulp` or `npm run build:prod`

- To auto-format your code and make it look pretty use: `npm run prettier`

## Acknowledgments

- This template uses [Bootstrap 4](https://getbootstrap.com/) framework

- This template uses [Google Material Icons](https://material.io/icons/)

- JPG's and JPEG's are compressed with [Guetzli](https://github.com/google/guetzli) from [Google](https://github.com/google)

- PNG's are compressed with [Pngquant](https://pngquant.org/) from [Kornel Lesiński](https://kornel.ski/about)

- Last but not least a huge thumbs up to everyone at [Mastertech](https://mastertech.tech/)

## Documentation

All documentation can be found [here](https://github.com/renansigolo/project-falcon).

## License

The code is open source and available under the [MIT License](LICENSE.md).

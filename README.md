# Sample HTML static project with GULP

### How to start

1. Be sure that you have installed Node.js and Gulp CLI global.
   Open the terminal and type next commands:

   ```
   node -v
   ```
   and

   ```
   gulp -v
   ```
2. Please install the Example project by execute next command:

   ```
   npm install
   ```
   or

   ```
   npm i
   ```
3. For running project for local development, please execute next command:

   ```
   npm start
   ```
   or

   ```
   gulp dev
   ```

### Scripts list

`npm start` - starting local server for development by address http://localhost:3000/, watch changes

`npm build` - building project to the "docs" folder

`npm deploy` - deploying current project to the GitHub pages branch. Deploy is available ONLY after building the project.

### Gulp Tasks

`gulp serve` - start local server

`gulp buildStyles` - compile SCSS files into CSS

`gulp buildHTML` - build HTML file

`gulp buildScripts` - concatenate, uglify JS files

`gulp buildPageScripts` - uglify separated JS files for pages

`gulp modernImages` - convert JPG, PNG to AVIF and WEBP and compress images

`gulp convertFonts` - conver font filest from TTF, OTF to WOFF and WOFF2 formats

`gulp cleandocs` - remove all files from the "docs" folder

`gulp move` - move favicon, fonts, plugins to the "docs" folder

`gulp build` - build project files into the "docs" folder

`gulp deploy` - deploy project to the GitHub pages

`gulp dev` - build ans run local server for development
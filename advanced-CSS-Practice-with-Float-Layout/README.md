# advanced-CSS-Practice-with-Float-Layout

Practicing Advanced CSS and HTML concepts.<br>
This is responsive one page project based on the online course:
https://www.udemy.com/course/advanced-css-and-sass/

##Available Scripts

In the project directory, you can run:

### `npm run watch:sass`

Runs SASS compiler with watching property

### `npm run devserver`

Runs live-server (live-server should be installed locally or globally)

### `npm run start`

Runs Two processes mentioned above parallely (requires npm-run-all package)

### `npm run compile:sass`

Compiles main.scss file to style.css file

### `npm run concat:css`

Concatinates css/style.concat.css file with css/icon-font.cssfile and saves into css/style.comp.css

### `npm run prefix:css`

Runs Autoprefixer (npm package) with latest 10 versionsof browser option and output file is css/style.prefix.css

### `npm run compress:css`

Compresses css/style.prefix.css file and saves output into css/style.css

### `npm run build:css`

Runs combined command consisting of commands: compile:sass concat:css prefix:css compress:css to build final css file

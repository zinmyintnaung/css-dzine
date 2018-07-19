Inside package.json,
scripts section to define compiling to sass
"compile:sass": "node-sass sass/main.scss css/style.css -w"
-w is to watch and auto compile when changes made to main.scss file

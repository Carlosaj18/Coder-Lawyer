A. Intalaccion de SASS 

1. Installar  live server 
2. Installar Live Saass Compiler
3. Ir a file>preference>settings>extensions>live sass compiler > live sass compile - settings - formats > eddit in settings.json

"liveSassCompile.settings.formats": [

    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "./css",
      "savePathReplacementPairs": null
    }
  ]

B. Instalacion de SASS con node 

1. $ npm init
2. $ npm install -D node-sass nodemon o install -g sass
3. En la sección de scripts añade un comando scss debajo del comando test, como se muestra abajo:

 "build-css": "node-sass --include-path scss scss/style.scss css/style.css",
 "watch-css": "nodemon -e scss -x \"npm run build-css\""

4. npm run watch-css

5. Resorces using
https://nodejs.org/en/about/
https://devcode.la/blog/que-es-npm/
https://www.w3schools.com/nodejs/nodejs_npm.asp
https://www.sitepoint.com/beginners-guide-node-package-manager/ 
 

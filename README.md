# curso-webpack
curso para aprender a manejar web pack.

-Instalación de Webpack
si no quieres escribir ese comando también puedes usar este
la i de install

npm i webpack webpack-cli -D

Al hacer esto webpack creo una carpeta llamada dist, esto lo hace por defecto webpack sin preguntarnos.
Modo de desarrollo
Por defecto webpack al compilar nuestro proyecto setea el modo “production” implícitamente pero podemos definirle el modo explícitamente corriendo:

npx webpack --mode production
npx webpack --mode development

La diferencia radica que el modo development deja el código mas legible para los desarrolladores pero con comentarios, el modo production deja el código comprimido y mas limpio para usarse.
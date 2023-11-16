#instalar angular
npm install -g @angular/cli
#revisar versión
ng v
#crear una aplicación
ng new "nombre"
#ejecutar la app
ng serve
#crear un componente
ng g c "nombre"
# Para utilizar el comando ng en la terminal de vscode
En la consola de windows o en visual studio code, como administrador, lista las politicas con: get-ExecutionPolicy -list Después le asignas al usuario actual la politica: Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
#dudas
-En esta versión 17 no está el fichero app.module.ts. En este fichero se declaran otros componentes, servicios, etc
-Los ficheros environment tampoco están, ni el de dev, ni el de prod. En estos ficheros podemos crear variables, poner urls de api que vayamos a utilizar tanto en desarrollo, como en producción.
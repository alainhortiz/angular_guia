# instalar angular
npm install -g @angular/cli

# revisar versión
ng v

# crear una aplicación
ng new "nombre"

# ejecutar la app
ng serve | npm start

# crear un componente
ng g component "path/nombre" | "nombre"

# detener el servidor 
# instalar 
npm install --global kill-port
kill-port --port 4200

# Para utilizar el comando ng en la terminal de vscode
En la consola de windows o en visual studio code, como administrador, lista las politicas con: get-ExecutionPolicy -list Después le asignas al usuario actual la politica: Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

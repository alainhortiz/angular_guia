# Instalar angular
npm install -g @angular/cli

# Revisar versión
ng v

# Crear una aplicación
ng new "nombre"

# Ejecutar la app
ng serve | npm start
ng s --port 4300
ng s -o

# Detener el servidor 
# Instalar 
npm install --global kill-port
kill-port --port 4200

# Crear un componente
ng g component "path/nombre" | "nombre"

# Crear una interface
ng g interface "path/nombre" | "nombre"

# Declarar variable de varios tipos
let hp: string|number = 95;

# Para utilizar el comando ng en la terminal de vscode
En la consola de windows o en visual studio code, como administrador, lista las politicas con: get-ExecutionPolicy -list Después le asignas al usuario actual la politica: Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

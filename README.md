# jab-dh-oct-2021
Practicas Octubre
desde terminal // te recomiendo usar GIT BASH
npm init -y //la bandera -y crea con los valores por defecto

Se crea el package.jason 

Aqui se debera actualizar el main con "app.js" 
en lugar del valor "index.js" que se tiene por defecto
// esto desde Viosula studio Code

//En la terminal de VS se instala express 
npm install express --save

// Tambien se pude instalar nodemon
npm install --save-dev nodemon
El script se modifica dentro del package.Json

Valores por defecto
---------------------------
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
--------------------------

Valores a cambiar
--------------------------
  "scripts": {
    "start": "nodemon app.js"
  },
--------------------------

Por lo tanto el programa se ejecutaria con:
npm run start

Y se detiende de igial manera con Control + C


//Se sigue con app.js para la configuracion de express y el puerto que se este usando

Para acceder al servidor que se creo desde una ventana del servidor con el nombre del puerto.

http://localhost:3000/ o el servidor que hayas seleccionado



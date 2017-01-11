# Ejercicio Next Cloud
# paymentDemo

a [Sails](http://sailsjs.org) application

# Autor: Juan Carlos Camarena Pérez
# Backend, Nodejs, Sails

# Puede consultar el ejercicio funcionando en

http://camlab.mx/next/app


# Para utilizar en localhost

npm install sails -g

sails lift

# Para utilizar con MongoDB en localhost

npm install sails-mongo

# Descomentar las lineas en config/connections.js

// someMongodbServer: {
//   adapter: 'sails-mongo',
//   host: 'localhost',
//   port: 27017,
//   user: 'username', //optional
//   password: 'password', //optional
//   database: 'your_mongo_db_name_here' //optional
// },


# cambiar en config/models.js

connection: 'localDiskDb',

# por

connection: 'someMongodbServer',

  # PROYECTO FINAL - BACKEND
  Este proyecto es una aplicación en Node.js que gestiona productos y carritos de compras, con funcionalidades avanzadas de gestión de usuarios y productos. Utiliza Handlebars para renderizar vistas, MongoDB para la persistencia de datos y cuenta con un sistema de autenticación y autorización para diferentes roles de usuario.

 
 Se incluye en el schema del user las propiedades de "documents" donde se almacenara los archivos cargados por los usuarios, y "last-connection" que almacena en la base de datos la fecha de la ultima vez que el usuario haga login o logout.

Tambien se incluye una opcion de validacion para que los usuarios normales de tipo "user" puedan subir su rango a usuario de tipo "premium" que les permita cargar productos al sistema. Este sistema de validacion requiere que el usuario cargue tres documentos: identificacion, comprobante de domicilio y comprobante de estado de cuenta. Una vez cargados estos archivos, el usuario puede actualizar su rol y cambiar a premium.

Packages utilizados
"bcrypt": "^5.1.1", "cookie-parser": "^1.4.6", "cron": "^3.1.6", "dotenv": "^16.3.1", "express": "^4.18.2", "express-compression": "^1.0.2", "express-handlebars": "^7.1.2", "jsonwebtoken": "^9.0.2", "mongoose": "^7.6.1", "nanoid": "^5.0.3", "nodemailer": "^6.9.7", "nodemon": "^3.0.1", "passport": "^0.6.0", "passport-jwt": "^4.0.1", "passport-local": "^1.0.0", "socket.io": "^4.7.2", "swagger-jsdoc": "^6.2.8", "swagger-ui-express": "^5.0.0", "sweetalert2": "^11.10.1", "winston": "^3.11.0" "chai": "^5.0.0", "mocha": "^10.2.0", "supertest": "^6.3.3"

Accesos al sistema :
Al momento de ejecutar aplicación se puede registrar un nuevo usuario

Rol : Admin, email :  pati@pati, password: 123456

Rol : user, email : andres@andres, password: 123456

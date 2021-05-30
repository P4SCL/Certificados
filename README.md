# GENERADOR DE CERTIFICADOS 

Aplicación web encargada de generar **certificados digitales**. Podemos observar que esta funcionalidad está presente en plataformas reconocidas como **Udemy**, **Platzi**, etc.

### Tecnologías empleadas:
#### Front-end
- Angular 10.
- Angular Material.
- Sweet Alert 2.
- Pdfmake-wrapper.
- Bootstrap.
- UUID. ( Versión 4 )

#### Back-end
- Firebase Cloud Firestore.
- Firebase Storage.
- Firebase Authentication.

------------
### Análisis
1. El flujo de la aplicación es sencilla, el mayor parte del front-end está hecha con Angular, mediante los **servicios** realizamos operaciones CRUD ( CREATE - READ - UPDATE - DELETE ) a Google Cloud Firestore.

2. Para acceder necesitas autenticarte con las credenciales, debido a que sólo el rol **ADMIN** puede realizar las operaciones CRUD.

3. Para generar los certificados y poder descargarlos utilicé la librería **Pdfmake-wrapper** que mediante los servicios obtiene la información necesaria para generar el certificado digital en formato PDF.

------------

#### LINK
Acceda a la aplicación:  https://certificadoapp-3bb25.web.app/

#### Credenciales

`username: prueba@gmail.com`

`password: 123456`

Image:

![](https://firebasestorage.googleapis.com/v0/b/certificadoapp-3bb25.appspot.com/o/imagenes%2Fprueba.jpg?alt=media&token=7d0b0712-c8fd-4c8f-ad36-83f5bf96a65d)

![](https://firebasestorage.googleapis.com/v0/b/certificadoapp-3bb25.appspot.com/o/imagenes%2Fprueba%202.jpg?alt=media&token=14035745-2340-460e-bd85-3affc8749b23)

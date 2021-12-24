Proyecto Nivelación MisionTic 

Usar el template para crear un repositorio propio, completar el proyecto y verificar que las pruebas de widget e integración funcione

Para la prueba de integración se asume que hay un usuario creado a@a.com con clave 123456

Recordar que la prueba de integración se corre con:   

flutter drive --driver test_driver/integration_test.dart --target integration_test/app_test.dart

Este proyecto trabaja las funcionalidades de Firestore y autenticación de Firebase, hay que agregar el google-services.json y habilitar esos servicios en el firebase console. Ver: https://drive.google.com/file/d/1qPSQkVIiUy6Iv9OfwAC_dTRLvEDPz4pp/view?usp=sharing   

Pista: Revisar los comentarios TODO   


<img src="firebase.gif" width="300" />

luis guillermo salinas peniche y César Andres Santana Gereda 

Video de Prueba de Aplicacion
https://drive.google.com/file/d/1yr80Q2P0bQJtyW596AdBKFxeGIyt9891/view?usp=sharing

Video prueba de Widget e Integracion
https://drive.google.com/file/d/1D_G9hzZjbMBIXu3k2aW6Gq-hhnbU1Jfm/view?usp=sharing

GitHub Proyecto final para Demo de Aplicacion
https://github.com/lpeniche7/nivelacion-mintic

GitHub Proyecto final para pruebas de widget por la web
https://github.com/lpeniche7/test-nivelacion


Nota: este fue el comando para realizar el test de widget e integracion ya que con el que se menciona en las instrucciones arrojaba errores 

flutter drive --driver=test_driver/integration_test.dart --target=integration_test/app_test.dart -d web-server -d chrome --web-port=4444 --browser-name=chrome --no-headless

Agracedemos todo el apoyo prestado durante estos meses

Cordialmente
LUIS GUILLERMO SALINAS Y  CESAR ANDRES SANTANA GEREDA 

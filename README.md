# TuringTool
RAG para la detección de posible uso de IA en textos cortos.\
Este Proyecto usa Groq para procesar y análizar los textos.

## ¿Comó usarlo?
### Paso 1 - API KEY:
Ingresa a [Groq](https://console.groq.com) registrate y obten tu propia API Key de manera gratuita para tu free tier.\
La Key debe verse algo así: gsk_xxxxxxxxxxxxx.

### Paso 2 - Variables de Session:
Con tu API Key, ingresa a tu página desplegada en navegador y añade la variable de sesión "yek" poniendo como value tu nueva Key.\
Para esto solo debes abrir las devs tools en tu navegador (usualmente F12), ir a la opción de "Application", hacer click en "Session Storage", busca el dominio de tu página y añade la nueva variable.

### Paso 3 - Recarga:
Para que la SPA tome los nuevos cambios, se aconseja recargar la página.

### NOTA: 
Para probar una "demo" se puede activar la variable de sesion (como en el Paso 2) "emulate" con valor 1, lo que cargará un mock de respuesta de la API. 

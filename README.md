# Aplicaci-n-M-vil
Esta es una APP que vincula a Profesionales de limpieza con Usuarios que requieren sus servicios por horas
Aplicación móvil que permite vincular a profesionales de limpieza con clientes que requieran sus servicios por horas de forma esporádica.

Descripción
Esta aplicación móvil permite a los usuarios registrarse y buscar profesionales de limpieza cercanos a su domicilio. Los profesionales pueden ofrecer sus servicios, y los usuarios pueden calificarlos y agendar citas. La aplicación está desarrollada en React Native y utiliza SQLite para la gestión de la base de datos local.

Características
Registro de Usuarios y Profesionales: Los usuarios pueden registrarse y crear perfiles de manera independiente.
Geolocalización: La aplicación utiliza geolocalización para vincular usuarios con profesionales cercanos.
Gestión de Anuncios: Los usuarios pueden publicar Anuncios y asignarlas a profesionales quienes a su vez pueden tomar o rechazar el requerimiento.
Calificaciones y Reseñas: Los usuarios pueden calificar y dejar comentarios sobre los profesionales.
Agendamiento de Citas: Los usuarios pueden agendar citas con los profesionales directamente desde la app.

Instrucciones para Desarrolladores

Prerrequisitos:

Node.js y npm instalados.
React Native CLI instalado.
Android Studio (para emular en Android) o Xcode (para emular en iOS).
Google Maps API Key para la funcionalidad de mapas.

Instalación

1. Clona el repositorio:

git clone https://github.com/tu-usuario/nombre-del-repositorio.git

cd nombre-del-repositorio

2. Instala las dependencias:

npm install

3. Configura las variables de entorno:

Crea un archivo .env en la raíz del proyecto y agrega tu clave de API de Google Maps:

REACT_NATIVE_GOOGLE_MAPS_API_KEY=tu-api-key

4. Instala las dependencias específicas para iOS (si estás desarrollando en iOS):

cd ios
pod install
cd ..

Ejecución

Para Android:

npx react-native run-Android

Para iOS:


npx react-native run-ios

Estructura del Proyecto


src/: Contiene todo el código fuente de la aplicación.
components/: Componentes reutilizables de la interfaz de usuario.
screens/: Pantallas principales de la aplicación.
navigation/: Configuración de la navegación entre pantallas.
database/: Gestión de la base de dtaos SQLite.
services/: Lógica de negocio, incluyendo la integración con la API de Google Maps.

Base de Datos

La aplicación utiliza SQLite para la gestión local de datos. 
Aquí está el esquema básico de las tablas:

users: Información sobre los usuarios.
professionals: Información sobre los profesionales.
tasks: Tareas disponibles.
ads: Anuncios publicados pro los usuarios.
ad_tasks: Relación entre anuncios y tareas.
ratings: Calificaciones de los usuarios a los profesionales.
appointments: Citas agendadas entre usuarios y profesionales.

Instalación
Descarga la aplicación desde el código QR que se pondrá a disposición cuando la APP esté disponible para su uso.


Registro: Al abrir la aplicación por primera vez, puedes registrarte como usuario o profesional.

Uso de la Aplicación:

Buscar Profesionales: Ingresa tu ubicación y selecciona la tarea que deseas realizar. La aplicación mostrará profesionales cercanos.

Contratar Profesionales: Selecciona un profesional y agenda una cita para el servicio.

Calificar Servicio: Después de que el profesional complete el servicio, puedes dejar una calificación y un comentario.

Soporte
Si tienes algún problema o pregunta, puedes escribir directamente a mi correo electróncio v.frenaraneda@uandresbello.edu


# TodoApp

TodoApp es una aplicación de gestión de tareas que incluye funcionalidades como CRUD de tareas, priorización de tareas, vistas de Pomodoro y un dashboard con informes usando Recharts. La aplicación utiliza Firebase para la autenticación y almacenamiento.

## Características

- Crear, leer, actualizar y eliminar tareas
- Priorizar tareas
- Temporizador Pomodoro
- Dashboard con informes usando Recharts
- Autenticación y almacenamiento usando Firebase

## Requisitos previos

- Node.js (>= 14.x)
- npm (>= 6.x) o yarn (>= 1.22.x)
- Cuenta de Firebase

## Instalación

Sigue estos pasos para instalar y configurar TodoApp:

### Clonar el repositorio

bash
git clone https://github.com/usuario/todoapp.git
cd todoapp


### Instalar dependencias

Usa npm o yarn para instalar las dependencias:


npm install
o
bash
yarn install

### Configuración de Firebase

1. Ve a [Firebase Console](https://console.firebase.google.com/).
2. Crea un nuevo proyecto de Firebase.
3. En la configuración del proyecto, agrega una nueva aplicación web.
4. Copia la configuración de Firebase y pégala en un archivo `.env` en la raíz del proyecto:

REACT_APP_FIREBASE_API_KEY=your-api-key
REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
REACT_APP_FIREBASE_PROJECT_ID=your-project-id
REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
REACT_APP_FIREBASE_APP_ID=your-app-id


5. Habilita la autenticación de correo y contraseña en la sección de autenticación de Firebase.

### Ejecutar la aplicación

Después de configurar Firebase y Recharts, puedes iniciar la aplicación:


npm start
o
yarn start


Esto iniciará la aplicación en `http://localhost:3000`.

## Scripts Disponibles

En el directorio del proyecto, puedes ejecutar:

- `npm start` o `yarn start`: Inicia la aplicación en modo de desarrollo.
- `npm run build` o `yarn build`: Construye la aplicación para producción.
- `npm test` o `yarn test`: Ejecuta las pruebas.

## Estructura del Proyecto


src/
├── components/    # Componentes reutilizables
├── views/         # Vistas principales (Dashboard, Pomodoro, etc.)
├── services/      # Servicios (Firebase)
├── hooks/         # Custom hooks
├── App.js         # Componente principal de la aplicación
├── index.js       # Punto de entrada de la aplicación
└── ...            # Otros archivos y configuraciones


## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio importante antes de enviarlo C:

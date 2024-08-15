# Full Stack Uber Clone

Clon de Uber es una aplicación móvil moderna desarrollada utilizando React Native, Expo, PostgreSQL y Stripe. Este proyecto simula las funcionalidades de una app de transporte, enfocándose en la usabilidad y el rendimiento.

## Tecnologías Utilizadas

- React Native
- Expo
- Stripe
- PostgreSQL
- Google Maps
- Zustand
- Clerk
- Tailwind CSS

## Vista previa

| ![Vista previa 1](https://raw.githubusercontent.com/miltonAlan/react-native-uber-clone/master/capture1.png "Vista previa 1") | ![Vista previa 2](https://raw.githubusercontent.com/miltonAlan/react-native-uber-clone/master/capture2.png "Vista previa 2") |
|:--------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------:|
| ![Vista previa 3](https://raw.githubusercontent.com/miltonAlan/react-native-uber-clone/master/capture3.png "Vista previa 3") | ![Vista previa 4](https://raw.githubusercontent.com/miltonAlan/react-native-uber-clone/master/capture4.png "Vista previa 4") |
| ![Vista previa 5](https://raw.githubusercontent.com/miltonAlan/react-native-uber-clone/master/capture5.png "Vista previa 5") |



## Características del Proyecto

- **Onboarding Flow**: Proceso fluido de registro y configuración de usuarios.
- **Autenticación con Verificación de Email**: Inicio de sesión seguro con verificación por correo electrónico.
- **OAuth con Google**: Inicio de sesión fácil usando credenciales de Google.
- **Autorización**: Control seguro de acceso para distintos roles de usuario.
- **Pantalla de inicio con ubicación en vivo y Google Map**: Seguimiento en tiempo real de la ubicación con marcadores en un mapa.
- **Viajes Recientes**: Visualiza una lista de los viajes recientes.
- **Google Places Autocomplete**: Busca cualquier lugar del mundo con sugerencias automáticas.
- **Buscar Viajes**: Busca viajes ingresando las ubicaciones de 'Origen' y 'Destino'.
- **Seleccionar Viajes desde el Mapa**: Elige autos disponibles cerca de tu ubicación desde el mapa.
- **Confirmación de Viaje con Información Detallada**: Visualiza detalles completos del viaje, como el tiempo y el precio de la tarifa.
- **Pago con Stripe**: Realiza pagos usando múltiples métodos como tarjetas y más.
- **Crear Viajes tras el Pago Exitoso**: Reserva un viaje después de confirmar el pago.
- **Perfil**: Administra los detalles de tu cuenta en la pantalla de perfil.
- **Historial**: Revisa todos los viajes reservados hasta el momento.
- **Responsive**: Optimizado tanto para dispositivos Android como iOS.

... y muchas más, incluyendo arquitectura de código y reusabilidad.

## Requisitos Previos

Asegúrate de tener instalados en tu máquina:

- Git
- Node.js
- npm (Node Package Manager)

## Instrucciones de Instalación

Sigue estos pasos para configurar el proyecto localmente en tu máquina:

1. **Clonar el Repositorio**:

    ```bash
    git clone https://github.com/JavaScript-Mastery-Pro/uber.git
    cd uber
    ```

2. **Instalar Dependencias**:

    ```bash
    npm install
    ```

3. **Configurar Variables de Entorno**:

    Crea un archivo `.env` en la raíz del proyecto con el siguiente contenido:

    ```bash
    EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=
    EXPO_PUBLIC_PLACES_API_KEY=
    EXPO_PUBLIC_DIRECTIONS_API_KEY=
    DATABASE_URL=
    EXPO_PUBLIC_SERVER_URL=https://uber.dev/
    EXPO_PUBLIC_GEOAPIFY_API_KEY=
    EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=
    STRIPE_SECRET_KEY=
    ```

    Reemplaza los valores de las variables por tus credenciales reales obtenidas de Clerk, Stripe, NeonDB, Google Maps y Geoapify.

4. **Ejecutar el Proyecto**:

    ```bash
    npx expo start
    ```

Descarga la aplicación Expo Go y escanea el código QR en tu dispositivo para ver el proyecto en ejecución.

## Ayuda

Si necesitas asistencia o tienes preguntas sobre el proyecto, no dudes en contactarme a través de mi correo electrónico: **miltonpaucar99@gmail.com**.

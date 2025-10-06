# yougrow-biblico
# YouGrow Bíblico - Paquete privado

Este paquete contiene un repositorio inicial para tu app privada **YouGrow Bíblico** (Android + iOS).
Incluye:
- Código base Flutter (mobile/)
- Backend Node.js (server/)
- .env.example
- Mockups (assets/mockups) con un ejemplo de diseño

## Instrucciones rápidas

### Mobile (Flutter)
1. Instala Flutter (https://flutter.dev).
2. En `mobile/` ejecuta:
   - `flutter pub get`
   - `flutter run` (en dispositivo o emulador)
   - Para release Android: `flutter build apk --release`
   - Para release iOS: `flutter build ios --release` y abre en Xcode para firmar.

### Backend (Node.js)
1. En `server/` ejecuta:
   - `npm install`
   - Crea archivo `.env` basado en `.env.example` con tus claves.
   - `npm start`
2. Asegúrate de configurar `FRONTEND_ORIGIN` con la URL de tu app o `http://localhost:xxxx`

### APIs a configurar
- YouTube Data API v3 (Google Cloud Console)
- OpenAI API (clave)
- OAuth 2.0 Google (para acceso al canal privado)

## Notas de seguridad
- Mantén las claves en variables de entorno. No subir a repos públicos.
- Si deseas, puedo ayudarte a desplegar el backend y configurar TestFlight / APK.

## Contenido del paquete


## Archivos añadidos (actualización)
- server/Procfile
- server/Dockerfile
- .github/workflows/deploy-server.yml
- mobile/lib/screens/ideas_screen.dart
- mobile/lib/screens/thumbnail_editor.dart

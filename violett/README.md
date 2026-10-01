# Violett

Aplicación móvil iOS/Android con Expo + React Native.

## Ejecutar

1. Instala Node.js LTS.
2. `npm install`
3. `npx expo start`
4. Abre con Expo Go o usa `npm run ios` / `npm run android`.

## Catálogo real

La app está preparada para consumir feeds autorizados. Awin ofrece feeds de producto para publishers con deep links, nombre, precio, imágenes y atributos de producto. Para producción se deben configurar las credenciales/IDs autorizados en un backend seguro; nunca se deben poner tokens en la app móvil.

Variables previstas para el backend:
- AWIN_PUBLISHER_ID
- AWIN_FEED_API_KEY
- AWIN_ADVERTISER_IDS

Los productos de ejemplo que aparecen en esta primera compilación son únicamente placeholders visuales para comprobar la interfaz; deben sustituirse por el índice de productos del backend antes de publicar.

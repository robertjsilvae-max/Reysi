# Reisy (reysi) — Aserradero Cojedes

App de una sola página (index.html). Accesos y datos en Supabase (plan gratuito).

## Subir a GitHub (gratis)
1. Crea el repositorio `reysi` (público: Pages gratis lo exige; la página ya NO lleva datos de ventas, solo imágenes y código).
2. Sube `index.html`, `README.md` y `.gitignore`. NO subas `datos_iniciales_reisy.json`.
3. Settings → Pages → Deploy from a branch → main / root. La URL será https://TU-USUARIO.github.io/reysi/

## Configurar Supabase (Authentication → URL Configuration)
- Site URL y Redirect URLs: la URL de Pages de arriba (necesario para confirmar correo y recuperar clave).
- Providers → Email activado con "Confirm email". Google es opcional (requiere crear credenciales en Google Cloud).
- El correo gratis de Supabase tiene límite de envíos por hora; para uso real configura un SMTP propio.

## Primer uso
1. Regístrate TÚ primero con tu Gmail (el primer usuario queda como administrador).
2. Entra y sube `datos_iniciales_reisy.json` desde la pantalla de datos vacíos.
3. Los demás se registran y quedan pendientes; los habilitas en la tuerca → permisos.

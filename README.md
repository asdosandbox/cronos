# 🕐 TIME.IS Clone

Reloj mundial en tiempo real — archivo HTML único, sin dependencias, desplegable en GitHub Pages.

## Funciones

- **Reloj principal** con detección automática de ciudad y zona horaria (GPS)
- **Temperatura en tiempo real** vía [Open-Meteo](https://open-meteo.com/) (sin API key)
- **Modo pantalla completa** con segundo reloj opcional para comparar zonas horarias
- **Chips de ciudades** con hora local y temperatura — más de 165 ciudades disponibles
- **Cuentas regresivas** con soporte para fechas pasadas y futuras (años · meses · días · horas · min · seg)
- **Diferencias horarias** desplegables desde el menú
- **Modo oscuro / claro** con persistencia
- **Sincronización** de tiempo cada 6h vía WorldTimeAPI y temperatura cada 30 min
- **Wake Lock** en móvil para mantener pantalla encendida en fullscreen

## Tecnología

- HTML + CSS + JS vanilla — archivo único `index.html`
- APIs externas (gratuitas, sin clave):
  - [Open-Meteo](https://api.open-meteo.com) — temperatura
  - [BigDataCloud](https://api.bigdatacloud.net) — geocodificación inversa
  - [WorldTimeAPI](https://worldtimeapi.org) — sincronización de tiempo
- Fuente: [Oswald](https://fonts.google.com/specimen/Oswald) vía Google Fonts

## Despliegue en GitHub Pages

1. Sube `index.html` y `README.md` a un repositorio
2. Ve a **Settings → Pages**
3. Source: `Deploy from a branch` → `main` → `/ (root)`
4. Listo — disponible en `https://tuusuario.github.io/nombre-repo`

## Uso local

Abre `index.html` directamente en el navegador. No requiere servidor.

# Kcal

App web (PWA) para iPhone: calorías consumidas vs objetivo diario, por comida (desayuno, comida, cena, snacks), con vistas Hoy / Semana / Mes.

Diseño inspirado en [OpenNutriTracker](https://github.com/simonoppowa/OpenNutriTracker): anillo de kcal restantes, comidas por momento del día y botón + central con lo reciente a un toque.

- Sin servidor ni cuentas: los datos se guardan en el propio iPhone (localStorage).
- Funciona offline (service worker). Al cambiar archivos, sube `VERSION` en `sw.js`.
- Copia de seguridad: Ajustes (botón Objetivo) → Exportar / Importar JSON.

## Instalar en el iPhone
1. Abrir la URL en **Safari**.
2. Compartir → **Añadir a pantalla de inicio**.

# Registro de recorridos

App web (un solo archivo `index.html`) para registrar viajes por localidad con tarifas de **técnico**, **móvil** y **fallido**.

- Totales por semana (lunes a domingo), por técnico y por móvil
- Viaje fallido: se usa la tarifa "Fallido" repartida mitad técnico y mitad móvil
- Datos guardados en el dispositivo (localStorage)
- Exportar a Excel (CSV) de la semana o de todo

## Publicar en GitHub Pages
1. Crea un repositorio nuevo y sube estos archivos.
2. Ve a Settings, luego Pages.
3. En Source elige "Deploy from a branch", rama `main` y carpeta `/ (root)`.
4. Guarda. En un par de minutos la app queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Cambiar tarifas
Edita el arreglo `T` dentro de `index.html`. Cada fila es: localidad, km, técnico, móvil, total, fallido.

Nota: los datos se guardan por navegador y por dispositivo; no se comparten entre celulares.

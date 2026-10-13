# OFSC FRONT V22.31 — resolución compacta + ventana -7/+30

Cambios sobre V22.30:

- Mantiene el diseño compacto para notebooks de 14/15 pulgadas.
- Mantiene cabecera de tabla y filtros de columnas fijos durante el scroll.
- Mantiene el mapa como popup activado desde el icono.
- Ventana operativa fija ampliada a **Hoy -7 días → Hoy +30 días**.
- Para no penalizar la carga inicial, primero carga **-2/+2 días** y completa en segundo plano:
  - -7/-3 días (operativo reciente)
  - +3/+10 días (futuro cercano)
  - +11/+30 días (programación futura)
- Al finalizar, la tabla contiene la ventana completa -7/+30.

Archivos modificados respecto de V22.30:
- `app.js`
- `index.html`

`styles.css` conserva las correcciones de resolución/cabecera de V22.30.

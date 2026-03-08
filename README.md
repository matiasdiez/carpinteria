# Mesa de Trabajo para Artista — Sistema Dos Islas

Documentación técnica interactiva para la fabricación de una mesa de trabajo de artista con sistema de dos islas rodantes (Flat File Cabinet + Isla de Herramientas).

## Estructura del proyecto

```
carpinteria/
├── index.html              ← Selector de modelos (página de inicio)
├── modelo_a/               ← Modelo A (Rev. B)
│   ├── index.html              Planos técnicos con vistas y especificaciones
│   ├── plan-de-cortes-presupuesto.html   Lista de piezas y presupuesto
│   ├── plan-de-cortes-CNC.html           Planos de corte para CNC
│   └── detalles-constructivos.html       Detalles y secuencia de armado
└── modelo_b/               ← Modelo B (Rev. D)
    ├── index.html              Planos técnicos (full-overlay + perfil Fox MF18)
    ├── presupuesto-RevD.html   Lista de piezas y presupuesto
    ├── plan-de-cortes-CNC-RevD.html      Planos de corte para CNC
    └── detalles-constructivos-RevD.html  Detalles y secuencia de armado
```

## Descripción del mueble

El sistema consiste en dos islas móviles diseñadas para uso en taller o estudio de artista:

- **Isla A — Flat File Cabinet (FFC):** Cajonera para almacenar planos A0 (1240 × 900 mm), con 6 cajones de apertura total.
- **Isla B — Isla de Herramientas:** Módulo complementario (600 × 900 mm) para herramientas, materiales y accesorios.
- **Tablero corrido:** Superficie de trabajo compartida que descansa sobre ambas islas (2640 × 1000 × 50 mm).
- **Ruedas con freno:** Ambas islas son rodantes (⌀75 mm) para máxima flexibilidad.

### Diferencias entre modelos

| | Modelo A (Rev. B) | Modelo B (Rev. D) |
|---|---|---|
| Tiradores | Convencionales | Perfil aluminio Fox MF18 (finger pull) |
| Frentes cajones | Parciales | Full-overlay (cubren laterales de carcasa) |
| Isla B | Cajones estándar | Doble zona: cajones 600 mm + estantes abiertos 300 mm |

## Tecnologías

HTML puro con SVG para los planos técnicos. Sin dependencias ni frameworks — se abre directamente en el navegador.

**Fuentes:** Share Tech Mono · Bebas Neue · IBM Plex Sans · Crimson Pro (Google Fonts)

## Ver el proyecto

[**→ Abrir página de inicio**](https://matiasdiez.github.io/carpinteria/)

---

Buenos Aires, 2026 · Sistema Dos Islas

# 🧳 Rediseño App Reservas Imserso

Prototipo funcional de alta fidelidad para la búsqueda y reserva de viajes del programa Imserso (TSO), diseñado desde cero con foco en **accesibilidad y usabilidad para personas mayores**.

---

## 📋 Descripción

La web oficial de reservas Imserso presenta una experiencia de usuario muy deficiente para su público objetivo: personas mayores con experiencia limitada en navegación web. Este proyecto replantea todo el flujo de reserva, desde la búsqueda de disponibilidad hasta la confirmación final, priorizando la claridad, la simplicidad y la guía al usuario en cada paso.

El resultado es un **prototipo HTML/CSS/JS de una sola página** (single-file), completamente funcional e interactivo, listo para realizar tests de usuario.

---

## 🎯 Problema que resuelve

| Problema original | Solución propuesta |
|---|---|
| Búsqueda por destino único con filtros obligatorios confusos | Exploración de destinos disponibles con filtros opcionales |
| Calendario gigante antes de ver precios | Listado de opciones con precio visible desde el principio |
| Formularios largos sin guía | Flujo por pasos (stepper) con validación progresiva |
| Sin feedback de estado | Tags dinámicos que se actualizan con las selecciones del usuario |
| UX genérica no adaptada a mayores | Tipografía grande, botones amplios, lenguaje claro |

---

## 🗺️ Flujo de la aplicación

El prototipo cubre **7 pasos** completos:

1. **Inicio** — Selección del número de pasajeros
2. **Búsqueda** — Exploración de destinos y fechas disponibles con tags dinámicos
3. **Habitaciones** — Selección de tipo de habitación y asignación de compañero de habitación
4. **Datos de pasajeros** — Formulario con opción de copiar datos al resto de pasajeros
5. **Resumen** — Revisión completa de la reserva antes de confirmar
6. **Pago** — Selección del método de pago
7. **Confirmación** — Pantalla final con resumen de la reserva confirmada

---

## ✨ Funcionalidades destacadas

- **Tags dinámicos** en el buscador que se actualizan en tiempo real con las selecciones del usuario
- **Bottom sheet de servicios** que se despliega automáticamente al seleccionar "Sí" en la opción de servicios adicionales
- **Auto-asignación de compañero de habitación** basada en el tipo de habitación seleccionado; se desasigna automáticamente al cambiar a individual
- **Checkbox "Usar estos datos para todos los pasajeros"** que copia teléfono y email al resto de viajeros en tiempo real
- **Información de transporte dinámica** (bus a las 17:30) reflejada en el resumen y la confirmación
- **Soporte multi-pasajero** con nombre completo del titular (José María Patricio Rodríguez) propagado por todo el flujo

---

## 🛠️ Tecnología

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura del prototipo |
| CSS3 | Estilos, animaciones y bottom sheets |
| JavaScript (Vanilla) | Lógica de flujo, validaciones y estado de la app |

> El prototipo es un **archivo único** (`index.html`) sin dependencias externas ni frameworks, lo que facilita su distribución y uso en tests de usuario.

---

## 🎨 Diseño

El diseño sigue las especificaciones del archivo Figma del proyecto, respetando:

- Paleta de colores de Turismo Social (verde `#03594C`, amarillo `#F1EDB1`)
- Tipografía y tamaños adaptados a personas mayores
- Componentes mobile-first con áreas táctiles amplias
- Patrón de bottom sheet para selecciones secundarias

---

## 🚀 Cómo probarlo

https://mariacoronil.github.io/turismo-social/

---

## 📁 Estructura del proyecto

```
/
├── index.html                                 # Prototipo completo (HTML + CSS + JS)
└── README.md                                  # Este archivo
└── sesion_diseno_ia_turismosocial.pdf         # Resumen de cómo se creó este prototipo paso a paso
```

---

## 📌 Estado del proyecto

> ✅ Prototipo funcional completo — listo para tests de usuario

---

## 👤 Autoría

Proyecto desarrollado como rediseño UX/UI de la plataforma de reservas de viajes del programa Imserso (TSO), con el objetivo de mejorar la experiencia de personas mayores en entornos digitales.

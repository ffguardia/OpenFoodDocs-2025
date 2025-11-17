# 🍽️ OpenFoodDocs 2025

**OpenFoodDocs** es un proyecto colaborativo creado para construir una base de conocimiento abierta sobre cocina, nutrición, gastronomía y alimentos.  
Este repositorio sirve como entorno real para aprender y aplicar **Git y GitHub avanzado** mediante trabajo colaborativo.

---

## 🎯 Objetivos del proyecto

- Trabajar con GitHub Flow (issue → branch → commit → PR → review → merge)
- Usar forks y contribuciones externas
- Gestionar Issues y Pull Requests con revisiones
- Resolver conflictos reales en colaboración
- Usar automatizaciones mediante GitHub Actions
- Gestionar versiones mediante tags y releases
- Crear documentación estructurada usando Markdown

---

## 📂 Estructura del repositorio

```
OpenFoodDocs-2025
│
├── README.md
├── LICENSE
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── CONTRIBUTORS.md
├── CHANGELOG.md
│
└── docs/
    ├── recetas/
    ├── nutricion/
    └── utensilios/
```

---

## 🧩 Cómo contribuir

1. Haz un **fork** del repositorio.
2. Clona tu fork:

```
git clone <URL_DE_TU_FORK>
```

3. Configura el repositorio original como `upstream`:

```
git remote add upstream https://github.com/ffguardia/OpenFoodDocs-2025

git fetch upstream
```

4. Reclama una issue escribiendo:

```
Me asigno esta tarea. @miUsuario
```

5. Crea una rama para tu contribución:

```
feature/tuUsuario-nombreTarea
```

6. Haz commits claros y descriptivos.
7. Envía un Pull Request enlazando la issue:

```
Closes #NUMERO
```

> 🔒 No se permiten commits directos a `main`.

---

## 🧪 Integración Continua

Este repositorio incluye validación automática.  
Los Pull Requests deben:

✔ Pasar el CI  
✔ Seguir la guía `CONTRIBUTING.md`  
✔ Ser revisados antes del merge  

---

## 🏷️ Versionado

| Versión | Estado |
|--------|--------|
| `v0.1-alpha` | 🏗 Configuración inicial |
| `v0.5-beta` | 📚 Contenido en desarrollo |
| `v1.0` | 🚀 Primera versión estable |

Historial completo: `CHANGELOG.md`.

---

## 📜 Licencia

Este proyecto usa licencia **MIT**.

---

## 👥 Créditos

Mantenido por **Francisco Fernandez Guardia (@ffguardia)**.

Participantes: `CONTRIBUTORS.md`.

---

## 🚀 Bienvenido

Tu primera contribución empieza reclamando una issue.  
¡Gracias por participar! 🙌


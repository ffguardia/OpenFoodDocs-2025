# Guía de contribución

Gracias por participar en **OpenFoodDocs 2025**.  
Lee estas normas antes de contribuir.

---

## 1. Flujo de trabajo

1. Haz un fork del repositorio.
2. Clona tu fork:

```
git clone <URL_DE_TU_FORK>
```

3. Añade el remoto original:

```
git remote add upstream https://github.com/ffguardia/OpenFoodDocs-2025
git fetch upstream
```

4. Antes de trabajar, sincroniza tu fork:

```
git checkout main
git pull --rebase upstream main
git push origin main
```

5. Crea una rama para cada issue:

```
feature/usuario-nombreTarea
```

---

## 2. Issues

Antes de empezar, reclama la issue así:

```
Me asigno esta tarea. @miUsuario
```

---

## 3. Reglas de contenido

- Usa formato Markdown (`.md`)
- Sigue la estructura establecida en `docs/`
- Mantén títulos legibles y contenido claro
- Usa listas, pasos numerados y secciones si corresponde

---

## 4. Mensajes de commit

Ejemplos correctos:

- `Añadida receta de hummus`
- `Corrige ortografía en README`
- `Reorganización de docs/recetas`

Evita:

❌ `update`  
❌ `arreglo`  
❌ `cosas`

---

## 5. Pull Requests

Los PR deben:

- Seguir la plantilla
- Indicar la issue: `Closes #NUMERO`
- Pasar la validación automatizada
- Ser revisados y aprobados

---

## 6. Conflictos

Si aparece un conflicto:

```
git fetch upstream
git checkout feature/tuRama
git merge upstream/main
```

Soluciona, commit, push.

---

## 7. Primera contribución

Si es tu primera participación:

✔ añade tu nombre a `CONTRIBUTORS.md`.

@OsquerM
---

¡Gracias por colaborar! 🍽️✨


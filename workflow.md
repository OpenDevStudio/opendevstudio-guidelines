# Flujo de Trabajo – OpenDevStudio

Este documento explica **cómo trabajamos en OpenDevStudio**.
Está diseñado para ser **simple, ordenado y realista**, especialmente para estudiantes y desarrolladores junior.

No buscamos velocidad, buscamos **aprender a trabajar bien**.

---

## 🎯 Objetivo del workflow

Nuestro flujo de trabajo busca:

- Mantener el código organizado
- Facilitar la colaboración
- Simular un entorno de trabajo real
- Evitar el caos y la confusión

Todo el proceso gira alrededor de **Issues, ramas, Pull Requests y un tablero Kanban**.

---

## 🧩 Metodología que usamos

Usamos una mezcla sencilla de:

- **Kanban** → para visualizar el trabajo
- **Scrum ligero** → para planificar objetivos

Sin reuniones obligatorias ni procesos pesados.

---

## 📌 Issues: el punto de partida

Todo empieza con un **Issue**.

Un issue puede ser:
- Una nueva funcionalidad
- Un bug
- Una mejora
- Documentación

### Estados típicos de un issue

- `Por hacer`
- `En progreso`
- `En revisión`
- `Completado`

Nadie trabaja sin issue asignado.

---

## 🗂️ Tablero Kanban (GitHub Projects)

Cada proyecto tiene un **GitHub Project** con columnas:

- 📝 Por hacer
- 🔧 En progreso
- 🔍 En revisión
- ✅ Completado

Cuando tomes un issue:
1. Asígnate el issue
2. Muévelo a **En progreso**

---

## 🌿 Ramas (Branches)

Nunca se trabaja directamente sobre `main`.

### Convención de nombres

- `feature/nombre-corto`
- `fix/descripcion-corta`
- `docs/archivo-o-tema`

Ejemplos:
- `feature/formulario-login`
- `fix/error-calculo-total`
- `docs/actualizar-readme`

---

## 💾 Commits

Buenas prácticas:

- Commits pequeños
- Mensajes claros y simples

Ejemplos:
- `Agrega validación al formulario`
- `Corrige estilos del botón`

No hace falta usar inglés obligatorio.

---

## 🔁 Pull Requests (PR)

Cuando termines tu tarea:

1. Sube tu rama a tu fork
2. Abre un **Pull Request** al repositorio original

### El PR debe incluir:

- Qué se hizo
- Qué issue soluciona (`Closes #12`)
- Cualquier duda o comentario

---

## 🔍 Revisión de código

- Al menos un mantenedor revisará el PR
- Puede haber comentarios o solicitudes de cambios
- Esto es normal y parte del aprendizaje

Cuando esté aprobado, se hará el merge a `main`.

---

## 🏁 Finalización

Cuando el PR se fusiona:

- El issue se mueve a **Completado**
- El contributor queda registrado

Celebramos las contribuciones 🎉

---

## 🤝 Filosofía OpenDevStudio

- Mejor claro que perfecto
- Mejor preguntar que asumir
- Mejor aprender que correr

Aquí todos estamos creciendo.

Bienvenido/a a OpenDevStudio 💙

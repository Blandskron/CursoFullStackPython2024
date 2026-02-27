# Repositorio Educativo Full-Stack

Colección de material formativo para aprender **Frontend**, **Python**, **Bases de Datos** y **Django** mediante ejercicios diarios, mini-proyectos y laboratorios prácticos.

> Este repositorio está estructurado por módulos y semanas, con un enfoque incremental: de fundamentos a aplicaciones prácticas.

## Tabla de contenido

- [Visión general](#visión-general)
- [Estructura académica](#estructura-académica)
- [Tecnologías cubiertas](#tecnologías-cubiertas)
- [Cómo usar este repositorio](#cómo-usar-este-repositorio)
- [Rutas de aprendizaje sugeridas](#rutas-de-aprendizaje-sugeridas)
- [Buenas prácticas para estudiantes](#buenas-prácticas-para-estudiantes)
- [Documentación adicional](#documentación-adicional)

## Visión general

El repositorio organiza contenidos por áreas:

- `02Frontend`: HTML, CSS, JavaScript, jQuery, Bootstrap y ejercicios de UI.
- `03Python`: fundamentos de Python, estructuras de control, funciones y casos de uso.
- `04Python2`: Python intermedio/avanzado, algoritmos, ejercicios tipo reto y notebooks.
- `05Basededatos`: SQL y PostgreSQL (básico y avanzado), scripts y prácticas de consultas.
- `06DjangoV1`: introducción a Django, creación de proyectos y páginas dinámicas.

Esta distribución facilita el seguimiento pedagógico por bloques de estudio y permite reutilizar el repositorio como base para clases, talleres o autoaprendizaje.

## Estructura académica

```text
Sustantiva/
├── 02Frontend/
├── 03Python/
├── 04Python2/
├── 05Basededatos/
├── 06DjangoV1/
└── docs/
```

Cada módulo contiene subcarpetas por `Semana` y `Día`, lo que permite:

1. Navegar cronológicamente el avance.
2. Trabajar por sesiones de clase.
3. Identificar rápidamente actividades de práctica y apoyo visual.

## Tecnologías cubiertas

- **Frontend:** HTML5, CSS3, JavaScript, jQuery, Bootstrap.
- **Backend/Fundamentos de programación:** Python.
- **Datos:** SQL y PostgreSQL.
- **Framework web:** Django.
- **Material didáctico:** notebooks (`.ipynb`), guías y scripts de ejemplo.

## Cómo usar este repositorio

### 1) Clonar el proyecto

```bash
git clone <url-del-repositorio>
cd Sustantiva
```

### 2) Ejecutar ejercicios Frontend

Abre cualquier archivo `.html` directamente en tu navegador.

### 3) Ejecutar scripts de Python

```bash
python3 ruta/al/script.py
```

> Recomendación: usar entorno virtual cuando trabajes con dependencias externas.

### 4) Practicar SQL/PostgreSQL

Usa los archivos `.sql` con tu cliente preferido (por ejemplo, `psql` o DBeaver) sobre una base de datos de práctica.

### 5) Explorar contenido Django

Entra a las carpetas de `06DjangoV1` y sigue el flujo por lecciones (`L1`, `L2`, `L3`).

## Rutas de aprendizaje sugeridas

### Ruta A · Principiante absoluto

1. `02Frontend/Semana1`
2. `03Python/Semana1`
3. `05Basededatos/Semana1`

### Ruta B · Desarrollo web completo (base)

1. `02Frontend` completo
2. `03Python` + `04Python2`
3. `05Basededatos`
4. `06DjangoV1`

### Ruta C · Refuerzo algorítmico en Python

1. `03Python`
2. `04Python2/Semana3/Python`
3. `04Python2/Semana3/BonusPythonV3`

## Buenas prácticas para estudiantes

- Trabaja por **semana y día** para mantener continuidad.
- Crea una rama por actividad si harás cambios propios.
- Añade comentarios en tus scripts explicando decisiones.
- Conserva una bitácora de aprendizaje (`log.md`) con errores y hallazgos.
- Convierte ejercicios clave en mini-proyectos integradores.

## Documentación adicional

Consulta la guía de arquitectura y contenidos en:

- [`docs/GUIA_DEL_REPOSITORIO.md`](docs/GUIA_DEL_REPOSITORIO.md)

---

Si usas este repositorio para formación académica, se recomienda acompañarlo con sesiones de revisión de código, ejercicios de refactorización y evaluación por proyectos.

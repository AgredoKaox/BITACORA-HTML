# Bitácora ADSO: vistas de Información, Trazabilidad y Auditoría

Sitio web estático (solo HTML, sin estilos ni frameworks) que presenta en tres vistas independientes la bitácora técnica del día **03/09/2026** de la ficha **3381732**, Tecnología en Análisis y Desarrollo de Software (SENA), y la auditoría de pares aplicada a esa bitácora. Cada vista reproduce fielmente uno de los libros de Excel validados.

**Sitio publicado (GitHub Pages):** <>
**Repositorio:** <https://github.com/AgredoKaox/BITACORA-HTML.git>

## ¿De qué trata el trabajo?

La bitácora registra, ID por ID, qué se hizo en la jornada, con qué resultado, qué impedimentos hubo y cuál fue el plan de acción. Este proyecto convierte esos libros de Excel en páginas web navegables y accesibles, y lo desarrolla un equipo de tres aprendices usando Git Flow y Conventional Commits.

## Estructura del proyecto

| Archivo | Vista | Contenido | Responsable |
|---|---|---|---|
| `index.html` | Información | Programa de formación, competencia, aprendiz autor, ficha y periodo | Kevin Santiago Triana Tarazaona |
| `trazabilidad.html` | Trazabilidad | Tabla con ID, timestamp, autoría, actividad, evidencia, impedimentos y plan de acción | Juan Sebastián Agredo García |
| `auditoria.html` | Auditoría | Datos de la inspección y matriz de criterios (cumple, hallazgo, acción correctiva) | Julio Cesar Barajas Poveda |
| `acuerdo_trabajo.md` | Documentación | Acuerdo, reglas y planeación del equipo | Equipo |

Las tres vistas son archivos HTML independientes y se conectan con un menú de navegación (`<nav>` con enlaces `<a>`), de modo que se puede pasar de una a otra sin usar el botón de retroceso del navegador.

## Prácticas semánticas aplicadas

- Estructura base en cada archivo: `<!DOCTYPE html>`, `<html lang="es">`, `<head>` con `<meta charset="UTF-8">`, `<meta name="viewport">` y un `<title>` distinto por página, y `<body>`.
- Etiquetas semánticas: `<header>`, `<nav>`, `<main>`, `<section>`, `<table>` y `<footer>`.
- Un solo `<h1>` por página, con encabezados `<h2>` ordenados.
- Tablas con `<caption>`, `<thead>`, `<tbody>` y celdas de encabezado `<th>`.

## Accesibilidad (a11y)

- Idioma declarado con `lang="es"`.
- Enlace "Saltar al contenido" al inicio de cada página.
- `<nav aria-label="Navegación principal">` y `aria-current="page"` en la vista activa.
- Encabezados de tabla asociados con `scope="col"` y `scope="row"`.
- Secciones relacionadas con su título mediante `aria-labelledby`.
- Toda imagen incluye el atributo `alt`.

## Cómo verlo en local

1. Clonar el repositorio: `git clone <URL_REPOSITORIO>`.
2. Abrir `index.html` en el navegador (o usar la extensión Live Server de VS Code).

## Flujo de trabajo del equipo

- Ramas: `main`, `develop` y una rama `feature/<vista>` por integrante.
- Commits en formato Conventional Commits (`feat`, `docs`, `chore`, `fix`), un commit por cada ID de la bitácora.
- Integración: `feature/*` → `develop` → `main`.
- Detalle en [`acuerdo_trabajo.md`](acuerdo_trabajo.md).

## Equipo

- Juan Sebastián Agredo García
- Kevin Santiago Triana Tarazaona
- Julio Cesar Barajas Poveda
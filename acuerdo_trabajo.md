# Acuerdo de Trabajo del Equipo (Team Agreement)

Este documento establece las reglas de convivencia, comunicación y estándares de calidad de nuestra célula ágil. Al participar en este repositorio, todos los miembros del equipo aceptamos y nos comprometemos a cumplir estos acuerdos.

**Programa:** Tecnología en Análisis y Desarrollo de Software · **Ficha:** 3381732
**Fecha del acuerdo:** <24/10/2026>

## 1. Miembros del Equipo y Roles

| Nombre | Rol | Usuario de GitHub |

| :--- | :--- | :--- |
| Juan Sebastián Agredo García | <COMPLETAR: Líder (Arquitecto) | `@<COMPLETAR>` |
| Kevin Santiago Triana Tarazcona | <COMPLETAR: Desarrollador | `@<COMPLETAR>` |
| Julio Cesar Barajas | <COMPLETAR: Desarrollador | `@<COMPLETAR>` |

## 2. Canales de Comunicación

Para mantener el orden y separar lo profesional de lo personal, usaremos los siguientes canales:

* **Comunicación Oficial y Archivos:** < Whatsapp, Discord > (Aquí se comparten avances, dudas técnicas y archivos de trabajo).
* **Urgencias o bloqueos rápidos:** < grupo de WhatsApp >
* **Gestión de Tareas y Código:** Estrictamente a través de los *Issues* y *Pull Requests* de GitHub. (Si se revisa código por WhatsApp).

## 3. Horarios y Sincronización

* **Reuniones de Sincronización (Daily Stand-up):** Nos reuniremos los días correspondientes a las horas que sean necesarias de forma virtual por medio de la plataforma discord.

* **Tiempo máximo de respuesta:** Nos comprometemos a responder mensajes del equipo en un máximo de
<2 horas> durante el horario hábil.

## 4. Reglas de Desarrollo

* **Prohibido el "Push" a Main:** Nadie, bajo ninguna circunstancia, subirá código directamente a `main` o `develop` sin pasar por un Pull Request y sin ser el lider.
* **Flujo de ramas (Git Flow):** `main` (estable) y `develop` (integración). Cada semana de trabajo se hace en una rama `feature/<mes>-semanaN` creada desde `develop`.
* **Antes de empezar:** se hace `git pull origin develop`. Al terminar se sube la rama con un único `git push`.
* **Commits propios y trazables:** cada integrante configura su `user.name` y `user.email` (los de su cuenta de GitHub) y sus commits salen a su nombre. Se hace un commit, con mensaje en formato *Conventional Commits* (`feat`, `docs`, `fix`, `chore`).
* **Alcance propio:** cada integrante modifica solo sus propios archivos. Si necesita cambiar algo de otro integrante, lo avisa antes.
* **Sin reescribir historia compartida:** no se usa `git push --force` sobre ramas compartidas. Los conflictos se resuelven antes de subir (`git pull` y `git status`).
* **Integración:** las ramas `feature` entran a `develop` mediante Pull Request revisado por < JUAN SEBASTIAN AGREDO GARCIA O KEVIN SANTIAGO TRIANA TARAZONA>; `main` se actualiza al final, con todo verificado.
* **Regla del Bloqueo (Timeboxing):** Si un desarrollador lleva más de < 2 horas > atascado en el mismo error, **debe** levantar la mano y pedir ayuda al equipo. No se permite perder días enteros en silencio.
* **Calidad antes que velocidad:** Ningún código se envía a revisión si tiene errores en la terminal, si deja instrucciones de depuración (como `console.log`) o si rompe el diseño en dispositivos móviles.
* **Fidelidad de la bitácora:** los registros se transcriben tal como fueron diligenciados; las correcciones a jornadas pasadas se registran como entradas nuevas que referencien el ID original.

## 5. Resolución de Conflictos y Ausencias

Somos profesionales en formación. Si surgen problemas, actuaremos así:
1.**Ausencias:** Si alguien no puede trabajar por fuerza mayor, debe avisar por el canal oficial con al
menos con 3 días de anticipación para reasignar sus tareas.
2. **Incumplimiento:** Si un miembro del equipo no entrega sus tareas en la fecha del *Milestone* sin justificación, el Líder reportará la situación formalmente al instructor.
3. **Decisiones Técnicas:** En caso de desacuerdo sobre cómo programar algo, se debatirá con argumentos técnicos y la decisión final será tomada por el **Líder (Arquitecto)**.

## 6. Planeación Colaborativa

| Actividad | Responsable | Fecha límite |
| :--- | :--- | :--- |

| Preparar repositorio (`main` y `develop`) | Juan Sebastian Agredo Garcia | 28/10/2026 |
| Subir la bitácora de cada integrante | Cada integrante | 28/10/2026 |
| Verificar commits y autoría | Cada Integrante | 28/10/2026 |
| Integrar `feature` → `develop` → `main` | Juan Sebastian Agredo Garcia | 28/10/2026 |

---
> **Firma Digital:** La creación de este archivo y los commits asociados a él representan la firma electrónica de aceptación de todos los integrantes de este equipo.

# Memorias de Primavera · Taller de novela visual con Unity y Naninovel

**Material didáctico para aprender a personalizar una novela visual interactiva.** Este repositorio acompaña el tutorial ilustrado del taller y conserva el guion de ejemplo escrito para *Memorias de Primavera*.

> **Importante:** este repositorio **no incluye Naninovel**, sus bibliotecas, código, paquetes ni una copia ejecutable del proyecto original. Naninovel es un producto comercial y debe obtenerse e instalarse mediante un canal autorizado. El material disponible aquí **no es un proyecto Unity listo para abrir**: es un kit de documentación y guion para incorporar a un proyecto propio con Naninovel instalado legítimamente.

## ¿Qué aprenderás?

- Organizar fondos, personajes y música en un proyecto Unity.
- Registrar los recursos en Naninovel.
- Crear personajes con distintas expresiones.
- Escribir diálogos y controlar escenarios y audio con un archivo `.nani`.
- Crear elecciones, rutas y finales alternativos.
- Personalizar la portada y comprobar las rutas.

## Material disponible

| Archivo | Contenido |
| --- | --- |
| [Guion de ejemplo](examples/textScript.nani) | Diálogos de Ana y Luis, tres rutas iniciales y seis finales. |
| [Tutorial ilustrado en PDF](docs/tutorial-nani-novel-mejorado.pdf) | Guía de diez pasos para personalizar el ejemplo, con capturas de Unity. |
| [Guía de preparación](docs/PREPARACION.md) | Cómo crear tu propio proyecto y qué necesitas antes de seguir el PDF. |

## Requisitos

- Unity Hub y Unity Editor. El proyecto histórico del taller utilizó **Unity 2023.2.20f1**.
- **Una instalación legítima y compatible de Naninovel**, obtenida por separado. El proyecto histórico usó Naninovel 1.18.1; comprueba compatibilidad en la documentación oficial del producto.
- Fondos, imágenes de personajes PNG con transparencia y audio **propios o con licencia que permita su uso**.
- Un editor de texto para modificar el guion.

## Cómo utilizar el material

1. Prepara un proyecto Unity propio e instala Naninovel legalmente siguiendo la documentación de tu versión.
2. Crea o importa fondos, personajes y música autorizados.
3. Registra esos recursos en Naninovel con los identificadores que usa el guion, o adapta el guion a tus nombres.
4. Incorpora [`examples/textScript.nani`](examples/textScript.nani) a la ubicación de scripts narrativos de tu proyecto y configúralo para ejecutarse.
5. Sigue el [tutorial ilustrado en PDF](docs/tutorial-nani-novel-mejorado.pdf), personaliza la portada y prueba las opciones.
6. Recorre **todas las rutas**, no solamente la primera.

El guion hace referencia a cuatro escenarios (`Aula`, `Patio`, `Pasillo`, `Canchas`), dos personajes (`Ana`, `Luis`) y cuatro expresiones por personaje (`Normal`, `Happy`, `Sad`, `Angry`). También hace referencia a `SchoolMemories` y `ABrightNewChapter`: **los archivos de música no están incluidos**. Puedes registrar pistas propias con esos nombres o modificar el guion.

## Contexto docente

Este material procede de un taller práctico impartido por el autor. Su propósito es mostrar cómo una historia sencilla se convierte en una experiencia interactiva mediante escenas, personajes, música y decisiones.

## Licencias y limitaciones

Naninovel y sus componentes pertenecen a sus respectivos titulares y **no se redistribuyen** aquí. Los recursos multimedia del proyecto histórico tampoco se incluyen porque sus permisos de redistribución no se han verificado. El contenido propio de este repositorio no tiene aún una licencia de reutilización explícita; conserva los avisos de autoría y solicita permiso antes de redistribuirlo.

**Estado:** documentación inicial. No se ha validado todavía el montaje desde cero del ejemplo con una instalación limpia de Unity y Naninovel.

---

[Portafolio profesional](https://github.com/isaiassolis) · [Otros talleres Unity 2D](https://github.com/isaiassolis/unity-2d-chrome-dino-workshop)

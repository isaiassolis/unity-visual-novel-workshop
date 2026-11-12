# Preparación del entorno

Esta guía acompaña el tutorial **Memorias de Primavera**. No proporciona ni sustituye una licencia de Naninovel.

## 1. Software

1. Instala Unity Hub.
2. Para reproducir el entorno histórico del taller, usa Unity **2023.2.20f1**. Si eliges otra versión, verifica su compatibilidad.
3. Obtén Naninovel por una vía autorizada y sigue **sus instrucciones oficiales** de instalación. El ejemplo original utilizó Naninovel **1.18.1**.
4. Comprueba que las opciones de configuración de Naninovel aparecen en Unity.

## 2. Prepara tus recursos

El tutorial ilustra la siguiente estructura didáctica:

```text
Assets/
  Recursos/
    Backgrounds/
    Characters/
      Ana/
      Luis/
    Music/
  Scripts/
```

Los archivos de imagen y sonido **no se incluyen en este repositorio**. Crea o utiliza recursos con los permisos necesarios. Para que el guion de ejemplo funcione sin cambios, registra estos identificadores:

- Fondos: `Aula`, `Patio`, `Pasillo`, `Canchas`.
- Personajes: `Ana` y `Luis`.
- Expresiones: `Normal`, `Happy`, `Sad`, `Angry` para cada personaje.
- Música: `SchoolMemories` y `ABrightNewChapter` (o sustituye los nombres en el guion).

## 3. Incorpora el guion

Copia [`examples/textScript.nani`](../examples/textScript.nani) a la ubicación de guiones de tu proyecto y configúralo según la documentación de Naninovel instalada. El guion tiene opciones que llevan a distintas rutas; recórrelas todas.

## 4. Sigue el tutorial ilustrado

El PDF mejorado explica en diez pasos cómo preparar y registrar recursos, personalizar la portada y comprender comandos como `@back`, `@bgm`, `@char` y `@choice`.

**Disponible:** [Abrir tutorial ilustrado (PDF)](tutorial-nani-novel-mejorado.pdf).

## 5. Si algo no aparece

- **Fondo o personaje invisible:** verifica que esté registrado y que el identificador coincida exactamente con el guion.
- **Pose incorrecta:** comprueba el nombre de la expresión y el archivo PNG asignado.
- **Sin música:** verifica el registro, la pista y el volumen.
- **Elección sin destino:** comprueba la etiqueta usada en `goto:`.
- **Menús diferentes a las capturas:** revisa la versión instalada y la documentación oficial.

> Esta guía describe el ejemplo histórico; aún no se ha comprobado una reconstrucción completa en un entorno limpio.

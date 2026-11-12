# Auditoría de código y recursos del proyecto histórico

**Origen revisado:** `darksite79/visual-novel-unity-2026` (árbol público de GitHub).  
**Objetivo:** seleccionar únicamente materiales propios y redistribuibles para el repositorio educativo.

## Hallazgos

- El árbol original contiene **2,149 elementos**. Una gran cantidad corresponde a `Assets/Naninovel/`, que contiene código y otros componentes del producto comercial: **excluido**.
- El guion propio `Assets/Scripts/textScript.nani` contiene la historia de Ana y Luis, tres elecciones iniciales y seis desenlaces: **incluido sin modificaciones narrativas** como [`examples/textScript.nani`](../examples/textScript.nani).
- No se identificaron scripts C# personalizados fuera de los componentes comerciales en el inventario revisado. **No se atribuye código del framework al autor del taller.**
- `Assets/Scenes/SampleScene.unity` contiene una escena genérica con cámara y luz 2D. No constituye por sí sola una demo funcional de la novela visual: **no se trasladó**.
- `Packages/manifest.json` y `ProjectSettings/` describen el entorno Unity, pero trasladarlos sin validar el conjunto de dependencias podría dar una falsa impresión de proyecto reproducible: **no se trasladaron**.
- `Assets/NaninovelData/` contiene configuración serializada y referencias al producto comercial; requiere una reconstrucción y validación en un entorno limpio: **no se trasladó**.
- `Assets/Recursos/Backgrounds/`, `Assets/Recursos/Characters/` y `Assets/Recursos/Music/` contienen imágenes y pistas cuyo origen y licencia no se han acreditado: **no se trasladaron**.
- El tutorial ilustrado, publicado por el autor, está disponible en [PDF](tutorial-nani-novel-mejorado.pdf).

## Alcance real de este repositorio

Se ofrece un **kit didáctico de guion y documentación**, no un proyecto Unity que se pueda ejecutar inmediatamente. Para reproducir la experiencia se requiere instalar Naninovel legalmente, preparar recursos propios o licenciados y registrarlos siguiendo el tutorial.

## Para convertirlo en proyecto base ejecutable

1. Confirmar permisos de redistribución de los recursos gráficos y musicales, o sustituirlos por recursos originales/autorizados.
2. Crear un proyecto Unity nuevo e instalar Naninovel desde una fuente legítima.
3. Incorporar el guion original, registrar recursos y reconstruir las configuraciones necesarias.
4. Verificar cada una de las seis rutas y los elementos de interfaz en Unity.
5. Publicar **solo** archivos propios o redistribuibles, sin el framework comercial ni su historial.

**Verificación pendiente:** no se ha ejecutado Unity ni Naninovel durante esta auditoría. La revisión es estática, basada en los archivos del repositorio.

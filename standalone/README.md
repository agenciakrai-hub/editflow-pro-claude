# EditFlow Pro · copia independiente

Esta aplicación web estática no se conecta a Base44 ni necesita sus credenciales. Funciona en el navegador y guarda proyectos y archivos localmente en IndexedDB del mismo dispositivo y perfil de navegador.

## Funciones disponibles

- Crear proyectos de fotografía y gestionar la selección local de imágenes.
- Importar JPEG, PNG y RAW habituales (CR2/CR3, NEF, ARW, DNG, RAF, ORF, RW2, PEF, entre otros). En RAW se muestra la vista previa JPEG embebida y se conserva el original.
- Revelar JPEG o la vista previa embebida de RAW con controles básicos, sin sobrescribir el original.
- Preparar páginas sencillas de álbum, aplicar presets y exportar JPEG/XMP y copias JSON del proyecto.
- Usar una selección heurística local; no llama a modelos ni servicios de IA.

## Límites de esta versión

Los RAW se archivan y se muestran mediante su preview embebida; no se revela el mosaico del sensor. No hay cuentas, copia en la nube, sincronización entre dispositivos, pagos, integración de Lightroom ni modelos remotos. Los datos no salen del navegador: al borrar los datos del sitio o cambiar de dispositivo, hay que importar el respaldo JSON y las fotos originales de nuevo.

## Publicación

El workflow de GitHub Pages sirve únicamente esta carpeta. El repositorio puede seguir privado, pero GitHub Pages publica la web en una URL pública. No se incluyen claves ni datos de usuario en el sitio.

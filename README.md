# GEO-ECUADOR

## Catálogo abierto de servicios web geoespaciales de Ecuador para TerriaJS

¡Bienvenido al proyecto GEO ECUADOR! Este es un catálogo abierto de servicios web geoespaciales para Ecuador, diseñado específicamente para utilizar en el visualizador [TerriaJS](https://terria.io/).

Para colaborar utilizar el catálogo en tu instancia de [TerriaJS](https://terria.io/):

1. Edita tu "archivos de inicialización" (o archivos de inicio). En una instalación predeterminada de TerriaMap, el archivo de inicio principal se encuentra en wwwroot/init/simple.json, y pega el siguiente objetco JSON:

    ```
    {
      "type": "terria-reference",
      "url": "https://raw.githubusercontent.com/ubica-ecuador/geo-ecuador/main/catalogo.json",
      "isGroup": true,
      "name": "Catálogo de Datos Geoespaciales de Ecuador - GeoEcuador",
      "id": "ubica-ec-geoportal-ecuador",
      "isOpen": true
    }
    ```

Animamos a la comunidad relacionada a los datos espaciales ecuatoriana a contribuir y mantener el catálogo, te invitamos a añadir servicios web geoespaciales como WMS, WFS, ESRI, GEOJSON, KML y más, Puedes seguir estos pasos:

1. Abre el archivo `catalog.json` en el repositorio clonado.
2. Busca la sección correspondiente a los servicios web existentes.
3. Añade una nueva entrada para el servicio que deseas agregar, siguiendo el formato adecuado para el tipo de servicio (WMS, WFS, ESRI, GEOJSON, KML, etc.).
4. Asegúrate de proporcionar la URL correcta y cualquier otra información relevante, como el nombre y la descripción del servicio.
5. Realiza un commit y un push de tus cambios al repositorio.

¡Tu contribución ayudará a enriquecer el catálogo y brindar más opciones a los usuarios!

Recuerda consultar la [documentación de TerriaJS](https://docs.terria.io/guide/) para obtener más detalles sobre cómo agregar servicios web geoespaciales al catálogo.

¡Gracias por tu colaboración y feliz mapeo!


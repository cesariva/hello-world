Investigar si se puede descargar la información de esta página
https://www.tenable.com/plugins/nessus/23847 
en la cual cambiando el numero cambia informacion de una vulnerabilidad analizada por Tenable.


# Evaluacion Inicial
## Robots .txt
La página tenable.com efectivamente tiene un archivo robots.txt con la siguiente informacion relevante:
```User-agent: *
Sitemap: http://www.tenable.com/sitemap.xml
Disallow: /watch/
Disallow: /read/
Disallow: /includes/
Disallow: /misc/
Disallow: /modules/
Disallow: /profiles/
Disallow: /scripts/
Disallow: /themes/
Disallow: /private/
```

Se puede observar que no esta prohibido el directorio `plugins` del cual queremos descargar la información.
Igualmente se puede ver que la politica es para todo tipo de robot con cualquier User-Agent.

## Sitemap.xml
En este archivo se muestran 2 links a 2 paginas de urls del sitio, en total 5274 en estos no se encuentra el link https://www.tenable.com/plugins/nessus/






### PEC2 Plataformas de publicación y distribución

## Tarea 1.1
Elige un clip de vídeo de máximo 20 segundos (puedes crearlo con tu dispositivo móvil, que tenga objetos en detalle y en movimiento) y codifícalo con Avidemux eligiendo el formato y resolución que creas adecuadas para su publicación en web. Teniendo en cuenta que no todos los navegadores aceptan todos los códecs, codifica el vídeo en los formatos necesarios para que sea compatible con el máximo de navegadores posible. Explica las decisiones tomadas en la codificación y el porqué de cada una. Confirma con la herramienta MediaInfo que lo ha codificado a la velocidad que querías.


Respuesta: WebM o AAC MPEG H.264 para trabajar con HTML los dos formatos más populares son. Existen muchos más como se observa en la tabla de esta wikipedia. 
EL formato MP4 utiliza el códec de vídeo H.264 conn códec de audio AAC o MP3. Es compatible con IE, Safari y Chrome pero no con Opera. Y ademas con Firefox desde una version bastante tardia. Ademas este formato no tiene una licencia libre. Por otro lado el formato WebM utiliza el códec de vídeo VP8/9 y el códec Vorbis de Vídeo y es soportado por Firefox, Chrome, Opera y mediante un add-on en IE y Safari. Su uso es gratuito y libre.

Intente dar como primer formato el VP9 , puesto que lo veia mejor para uso con HTML5, tiene una calidad semejante a H.264 y es software libre pero por alguna razon, usando Windows y Avidemux me ha dado el error siguiente varias veces, aun probando diferente configuraciones. Y por ultimo, dandole como salida MKV muxer.

Para generar el clip de video con estos códecs se ha utilizado el software xMediaRecorder debido a los problemas que estamos encontrando para trabajar con Avidemux. El video se encuentra adjuntado a la práctica con el nombre videoTarea1.








---------------

You can use the [editor on GitHub](https://github.com/Daleman2/UOC_PEC2_Publi/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Daleman2/UOC_PEC2_Publi/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

# NLP en Español con Hugging Face

"NLP en Español 🤗" es la comunidad de hispanohablantes de la iniciativa "Languages at Hugging Face".

Nuestra misión es crear y compartir recursos que posibiliten y aceleren el avance del NLP en Español. Es un objetivo muy amplio que se puede traducir en:
- Crear bases de datos o añadir las ya existentes a la librería Datasets de Hugging Face
- Entrenar modelos utilizando dichas bases de datos y añadirlos al Model Hub de Hugging Face
- Crear tutoriales explicando cómo hacer uso de estos recursos o traducir los tutoriales ya existentes
- Compartir eventos, artículos y proyectos interesantes para la comunidad ([Slack](https://join.slack.com/t/nlpenespaol/shared_invite/zt-n0cpcd87-hdAR_qiHtDcCAlCyZtwDKQ))

<p align="center">
  <img src="logo.png" alt="logo" width="400"/>
</p>

## Datasets
Ahora mismo hay [7 datasets monolingües en español](https://huggingface.co/datasets?filter=languages:es,multilinguality:monolingual).

Cómo contribuir a la librería 🤗 Datasets:
- Completar la documentación de las bases de datos ya existentes
- Añadir una base de datos a la librería
- Crear una nueva base de datos

### Completar la documentación de las bases de datos ya existentes
El README de cada base de datos se llama Dataset Card y contiene información referente al uso, la estructura, la creación, la licencia y la citación de dicha base de datos.

Todas las Dataset Cards siguen una misma [plantilla](https://github.com/huggingface/datasets/blob/master/templates/README_guide.md) y cuanto más completas estén, mejor
(e.g. [Dataset Card for ELI5](https://github.com/huggingface/datasets/tree/master/datasets/eli5#dataset-card-for-eli5)). 
Si encuentras información que todavía no está incluida en la Dataset Card de cualquier base de datos, crea una Merge Request con tu aportación.

### Añadir una base de datos a la librería
Si quieres añadir una base de datos a la librería de HF, solo tienes que:
1. Añadir una nueva fila a la hoja de cálculo* con la información de dicha base de datos y poner tu nombre en la columna "Contribuyente"
2. Seguir las instrucciones detalladas en [este documento](https://github.com/huggingface/datasets/blob/master/ADD_NEW_DATASET.md)

Si quieres sugerir la adición de una base de datos a la librería añade una nueva fila en la hoja de cálculo* y 
deja la columna "Contribuyente" en blanco para que otra persona pueda trabajar en ello.

*El enlace a la hoja de cálculo está en la descripción del canal #datasets del grupo de Slack.

### Crear una nueva base de datos
Si tienes una idea para crear una nueva base de datos de NLP en español estás en el sitio adecuado:
1. Comparte tu idea en el canal #tutoriales de la comunidad de [Slack](https://join.slack.com/t/nlpenespaol/shared_invite/zt-n0cpcd87-hdAR_qiHtDcCAlCyZtwDKQ)
2. Reúne un equipo para hacerla realidad
3. Añádela a la librería de Hugging Face

## Modelos
Ahora mismo hay [259 modelos en español](https://huggingface.co/models?filter=es).

Cómo añadir tu modelo al 🤗 Model Hub:
1. Entrena/fine-tune tu modelo (echa un vistazo a los [datasets en español](https://huggingface.co/datasets?filter=languages:es,multilinguality:monolingual))
2. Sigue las instrucciones de [esta página](https://huggingface.co/transformers/model_sharing.html) para compartir tu modelo y subirlo al Hub

Recuerda detallar bien la Model Card, puedes utilizar [esta plantilla](https://github.com/huggingface/model_card).

Si tienes más dudas echa un vistazo a [Model Hub docs](https://huggingface.co/docs).


## Tutoriales
Tanto si quieres crear un tutorial desde cero como si quieres traducir uno:
1. Comparte tu idea en el canal #tutoriales de la comunidad de [Slack](https://join.slack.com/t/nlpenespaol/shared_invite/zt-n0cpcd87-hdAR_qiHtDcCAlCyZtwDKQ)
2. Reúne un equipo para hacerla realidad
3. Crea una subcarpeta nlp-es-hugging-face/tutoriales/<nombre_del_nuevo_tutorial> en una nueva rama y ¡a trabajar!

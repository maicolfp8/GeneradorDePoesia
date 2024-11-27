# 🌟 Generador de Poesías con Narración y Música 🌟

Este proyecto permite generar poesías personalizadas a partir de un tema dado, que son narradas en voz alta y acompañadas de música de fondo. 
El sistema utiliza la API de OpenAI para generar las poesías, `gTTS` (Google Text-to-Speech) para la narración, y `pydub` para combinar la música con la narración.

## Descripción
El generador de poesías permite a los usuarios ingresar un tema (como una palabra o frase) y obtener una poesía breve y única relacionada con ese tema.
Luego, la poesía generada es narrada usando tecnología de texto a voz (gTTS) y la narración se combina con música de fondo, todo esto en un solo archivo de audio.

El proyecto está diseñado para ejecutarse en **Google Colab**, pero también puede adaptarse a otros entornos con los ajustes adecuados.

## Características
- **Generación automática de poesías**: Utiliza la API de OpenAI (GPT-4) para generar poesías únicas y creativas basadas en un tema proporcionado.
- **Narración de la poesía**: La poesía generada se narra automáticamente con `gTTS` en español.
- **Música de fondo**: Puedes agregar música de fondo a la narración utilizando archivos `.mp3` personalizados.
- **Interfaz gráfica**: Interfaz simple y atractiva creada con `Gradio` para que el usuario ingrese un tema y reciba una poesía narrada.

Archivos de Música
Este proyecto requiere que subas un archivo de música de fondo a Google Colab. 
Los archivos no están incluidos en el repositorio, por lo que deberás subirlos manualmente.

Archivo de música de fondo: 
El archivo debe llamarse musica_fondo.mp3 y debe cargarse en el entorno de Colab. 
Si usas un nombre diferente o tienes varios archivos de música, asegúrate de cambiar la ruta del archivo en el código según corresponda.

Interacción con la interfaz
Caja de texto: Ingresa un tema para la poesía (por ejemplo, "la luna", "amor", "amistad").
Botón: Haz clic en el botón "Crear Poesía Narrada" para generar la poesía con música de fondo y narración.
Salida: Después de un momento, la poesía generada aparecerá en la caja de texto y podrás escuchar la narración acompañada de música.

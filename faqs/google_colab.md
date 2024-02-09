# FAQs de Google Colab

## No se puede conectar con el backend de GPU

La versión gratuita de Google Colab pone limitaciones para que la gente no abuse del servicio. Podéis consultar las limitaciones en este link: [research.google.com/usage-limits](https://research.google.com/colaboratory/faq.html#usage-limits). Las limitaciones son bastante ambiguas tanto para saber cuales son los límites como para saber cuándo se reestablece el servicio. 

## ¿Cómo evitar llegar al límite?

El límite llega cuando usas mucha potencia de la GPU y/o lo usas durante mucho tiempo. Al final hay mucha gente conectandose y si Google ve que estás ocupando todo el rato un ordenador es cuando bloquea temporalmente su uso.

### Recomendaciones para no llegar al límite

1. Intenta usar el cuaderno exclusivamente para lo que necesites. 
2. Cuando no uses el cuaderno acuerdate de apagarlo para no estar ocupando todo el rato el ordenador.
3. Si vas a tener que usarlo durante mucho tiempo intenta dividir el tiempo de uso en varias tandas y entre medias ponte con otra cosa o descansa.
4. Si tienes que hacer muchas pruebas intenta consumir lo menos posible. Por ejemplo, si estás usando el cuaderno de Fooocus intenta usar el cuaderno en modo `SPEED` y no subir la cantidad de generación de imágenes por encima de 2.
5. Otro factor que provoca llegar al límite es el uso de `gradio.live`, la interfaz que usa Fooocus, porque prioriza los cuadernos "normales" como el que vimos el primer día en clase. Si ese cuaderno te sirve intenta usarlo antes que el gradio.live.

## He llegado al límite

Los más recomendable es esperar a que te den acceso de nuevo y ponerse con otra cosa. Google no especifica cuanto tiempo hay que esperar pero no suele ser más de un día (ya, es un rollo, pero es lo que tiene usarlo grátis🙃)

Puedes intentar crear otra cuenta de Google y probar de nuevo. Suele funcionar pero Google no es tonto y sabe que eres la misma persona. Puedes intentarlo desde otro ordenador a ver si funciona pero vuelve a ser lo mismo. Al final lo mejor siempre es esperar e intentar economizar los recursos cuando estés usandolo

## He llegado al límite y necesito usarlo!

Por suerte, existen otras herramientas online que puedes usar para salir al paso mientras no funcione el colab. También, no te olvides que no es obligatorio usar IA todo el rato y herramientas que ya conocéis como photoshop tmabién son una alternativa.

Aun así, todos los códigos de colab pueden ejecutarse también en tu ordenador AUNQUE dependiendo de cada herramienta y sobretodo de tu ordenador será más o menos fácil. Podrás usarlo sin límites pero la velocidad cambiará según las capacidades de tu ordenador.

> ### Generación de imágenes.
>
> Prueba el cuaderno "normal" de generación de imágenes. [Generación de imágenes (SDXL)](https://colab.research.google.com/drive/1viT3anI3z6lv_y2FoMmmA6W1ECEaiR_W?usp=sharing)
>
> Puedes generar imágenes usando Copilot (gratuito) - [bing.com/search](https://www.bing.com/search?q=Bing+AI&showconv=1)
>
> Puedes usar estas demos de Hugging Face [Image to Image SDXL](https://huggingface.co/spaces/tonyassi/image-to-image-SDXL), [Text to Image SDXL](https://huggingface.co/spaces/tonyassi/text-to-image-SDXL) y [sdxl-stable-diffusion-xl](https://huggingface.co/spaces/prodia/sdxl-stable-diffusion-xl). Van lentas pero funcionan.
>
> Si no te sirve ninguna opción también puedes en este link descargar y usar el fooocus en tu ordenador [Fooocus/download](https://github.com/lllyasviel/Fooocus?tab=readme-ov-file#download).
> 
> En windows tienes que descargarlo desde este link [fooocus/descarga_windows](https://github.com/lllyasviel/Fooocus/releases/download/release/Fooocus_win64_2-1-831.7z) y hacer doble click en `run.bat`. Si todo sale bien debería abrirse una ventana del navegador con el fooocus y podrás generar imágenes.
>
> Si tienes problemas al instalarlo pregunta por Github :)


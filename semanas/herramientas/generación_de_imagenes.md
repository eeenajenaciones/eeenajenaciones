[← Volver al índice](/semanas/README.md)

*Semana 2*

# 🖼️ Generación de imágenes - Modelos de difusión

![cat](https://github.com/eeenajenaciones/backend/assets/157328061/e8c0fd73-b0d6-455c-9fcc-9a316318bfdd)

## 🐍 Python básico

Colab: [Python básico](https://colab.research.google.com/drive/1fpSmaQexwrUBF1QYspa8qoFiOL84Mx-o?usp=sharing)

🎁 ➔ [Grids de imágenes](https://colab.research.google.com/drive/1PXcGqst1YSY-Hjz9lYFugJEJQpKFW5YJ?usp=sharing)

## 🖼️ Generación de imágenes 

Colab: [Generación de imágenes (SDXL)](https://colab.research.google.com/drive/1viT3anI3z6lv_y2FoMmmA6W1ECEaiR_W?usp=sharing)

# 🎯 Fooocus (SDXL)

## Modelos de difusión
- **Stable Diffusion:** (recomendado)
  - Interfaces:
    - [Fooocus](https://github.com/lllyasviel/Fooocus) (recomendada)
    - [Automatic111](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
    - [ComfyUI](https://github.com/comfyanonymous/ComfyUI)

- **Bing chat** (gratuito) - [bing.com/search](https://www.bing.com/search?q=Bing+AI&showconv=1)
- **Dall-E:** (de pago) - [openai.com/dall-e-3](https://openai.com/dall-e-3)
- **Midjourney:** (de pago) - [midjourney.com](https://www.midjourney.com/home)
- **Firefly:** (de pago) - [adobe.com/es/products/firefly](https://www.adobe.com/es/products/firefly.html)

## 1. Encender Fooocus en Colab ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

EL primer paso es darle al play para encender instalar y ejecutar Fooocus

![play](/archivos/play.png)

Esperar hasta que aparezca el link HTTPS://................GRADIO.LIVE

![gradio](/archivos/gradio.png)

## 2. Ajustes previos a generar una imagen

En la pestaña `ADVANCED` puedes ajustar los parametros de la imagen. Se recomienda trabajar primero en el modo `SPEED` para hacer pruebas rápidamente y cuándo se quieran mejores resultados usar las otras opciones. Además es recomendable dejar el número de imágenes en 2 ya que si se sube demasiado el colab podría dar ERROR

![gradio](/archivos/ajustes.png)

Recuerda por último apagar los estilos que vienen por defecto

![gradio](/archivos/apagar_estilos.png)

## 3. Generación texto ➔ imagen

Introduce un texto en la celda inferior con la descripción de la imagen. En la descripción puedes incluir tanta información como quieras describiendo el estilo, el tipo de imagen su contenido, etc...

![gradio](/archivos/text2image.png)

## 4. Transformación imagen ➔ imagen

Para transformar una imagen en otra se usa el apartado `UPSCALE OR VARIATION`. Sube una imagen y selecciona `Vary (Subtle)` o `Vary (Strong)` para modificar la imagen siguiendo el texto de la celda.

![gradio](/archivos/image2image.png)

`Vary (Subtle)` o `Vary (Strong)` son dos valores muy ambiguos y no dan mucho control sobre el resultado. Para controlar mejor la variación puedes ir a `ADVANCED` >> `ADVANCED` >> `DEVELOPER DEBUG MODE` >> `Forced Overwrite of Denoising Strength of "Vary"`. Ese slider controla la variación de la imagen desde `0` no varía nada a `1` que la imagen desaparece. Se recomienda usar valores entre `0.5` y `0.8`

![gradio](/archivos/advanced_settings.png)
![gradio](/archivos/advanced_settings2.png)

## 4. Generación texto + imagen ➔ imagen

También se pueden usar imágenes de referencia en la pestaña `IMAGE PROMPT` para controlar mejor el ouput. 



### ⚠️ERROR⚠️

Seguramente el cuaderno de error cuando cambies de herramienta porque has cargado demasiada memoria. La manera de arreglarlo es volver al colab y volver a darle al play para que se cargue de nuevo el cuaderno hasta que aparezca de nuevo el link. Ten cuidado porque los ajustes que hagas previos se perderán.

![gradio](/archivos/error.png)
![gradio](/archivos/error2.png)

## **Enunciado semana 2** ➔ [Bourriadas ciclotímicas](/semanas/enunciados/bourriadas_ciclotimicas.md)

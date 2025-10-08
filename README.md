# Generador de Código de Barras

Aplicación web sencilla para convertir un nombre en un código de barras **Code 128** y generar un PDF de 48 mm x 30 mm listo para imprimir.

## Requisitos

No necesitas instalar dependencias adicionales. Solo un navegador moderno (Chrome, Edge, Firefox, etc.).

## Cómo probar la aplicación

### Opción 1: Abrir el archivo directamente
1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` con tu navegador (doble clic o arrastrándolo al navegador).
3. Escribe el nombre en el cuadro de texto.
4. Haz clic en **Vista previa PDF** para ver el documento sin descargarlo.
5. Presiona **Imprimir** si deseas abrir el PDF listo para impresión.

### Opción 2: Servirlo localmente (recomendado)
1. Sitúate en la carpeta del proyecto (`/workspace/imprimir`).
2. Ejecuta un servidor estático sencillo, por ejemplo con Python:
   ```bash
   python3 -m http.server 8080
   ```
3. Abre en tu navegador `http://localhost:8080/index.html`.
4. Ingresa el nombre y usa **Vista previa PDF** para revisar la etiqueta.
5. Haz clic en **Imprimir** cuando quieras enviarla a la impresora.

> **Nota:** La vista previa del código de barras se actualiza automáticamente mientras escribes para que puedas verificar el resultado antes de generar el PDF.

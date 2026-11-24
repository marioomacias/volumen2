# Volumen 2 — proyecto PWA

Primera versión de tu aplicación personal. Está hecha con HTML, CSS y JavaScript sin frameworks ni dependencias.

## Ejecutarla en Windows

1. Instala Visual Studio Code.
2. Descomprime este proyecto en una carpeta.
3. Abre la carpeta desde VS Code.
4. Instala la extensión **Live Server**.
5. Haz clic derecho en `index.html` y elige **Open with Live Server**.

La vista local sirve para probar la interfaz. Para instalarla en un iPhone como PWA, la aplicación debe estar publicada en una dirección HTTPS.

## Publicarla gratis para instalarla en iPhone

Una opción sencilla es GitHub Pages:

1. Crea una cuenta en GitHub.
2. Crea un repositorio nuevo llamado `volumen2`.
3. Sube todos los archivos y carpetas de este proyecto (no subas el ZIP).
4. En el repositorio entra en **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**.
6. Selecciona `main` y `/ (root)`, y guarda.
7. Espera a que GitHub Pages publique la web. La dirección será similar a `https://TU-USUARIO.github.io/volumen2/`.

## Instalar en iPhone

1. Abre esa dirección HTTPS en Safari en el iPhone.
2. Pulsa el botón Compartir.
3. Elige **Añadir a pantalla de inicio**.
4. Confirma con **Añadir**.

## Qué contiene

- Resumen y semana.
- Registro manual de gastos, ingresos y ahorro.
- Objetivos personales.
- Biblioteca de libros.
- Seguimiento de asignaturas SMIR.
- Manifest y service worker para instalación y uso offline básico.

## Importante sobre los datos

Esta versión guarda los datos en `localStorage` del navegador de ese dispositivo. No hay sincronización entre iPhone y ordenador ni copia de seguridad en la nube. Si borras los datos del navegador, puedes perder los registros. No introduzcas datos bancarios sensibles.

## Siguiente etapa de aprendizaje

1. Personalizar diseño y componentes.
2. Añadir entrenamientos y seguimiento de carrera.
3. Añadir exportación/importación de datos.
4. Añadir persistencia más robusta y, si interesa, sincronización.

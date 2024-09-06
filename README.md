# Proyecto de Aplicación Móvil

Este proyecto consiste en la creación de una aplicación móvil con dos pantallas, utilizando Java para las validaciones en la primera pantalla. A continuación se detallan los requisitos y características del proyecto.

## Requisitos del Proyecto

1. **Pantalla de Login:**
   - La primera pantalla debe contener un diseño de login similar al proporcionado en las imágenes.
   - **Validaciones en Java:**
     - **Validación de Campos Vacíos:** Ambos campos (usuario y contraseña) deben ser llenados. Si alguno de los campos está vacío, se debe mostrar el mensaje "Por favor llenar los campos".
     - **Validación de Usuario y Contraseña:** El usuario debe ingresar el nombre de usuario "uac123" y la contraseña "12345678" para acceder a la segunda pantalla. Si las credenciales son incorrectas, se debe mostrar el mensaje "Usuario o contraseña incorrectos".

2. **Segunda Pantalla:**
   - La segunda pantalla debe mostrar el nombre "Ustedes" y la respuesta a la parte teórica, tal como se muestra en la imagen proporcionada.

## Estructura del Proyecto

- `MainActivity.java`: Archivo principal de la aplicación donde se encuentra la lógica para la pantalla de login.
- `SecondActivity.java`: Archivo que define la segunda pantalla que se muestra después de una autenticación exitosa.
- `res/layout/activity_main.xml`: Archivo de diseño XML para la pantalla de login.
- `res/layout/activity_second.xml`: Archivo de diseño XML para la segunda pantalla.

## Instrucciones para Ejecutar el Proyecto

1. **Clonar el Repositorio:**
   ```bash
   git clone [URL del repositorio]
   ```

2. **Abrir el Proyecto en Android Studio:**
   - Importa el proyecto a Android Studio.

3. **Ejecutar la Aplicación:**
   - Conecta un dispositivo o usa un emulador de Android.
   - Haz clic en el botón "Run" en Android Studio.

4. **Validaciones y Pruebas:**
   - Asegúrate de que ambas validaciones en la pantalla de login funcionen correctamente.
   - Verifica que el diseño de ambas pantallas coincida con las imágenes proporcionadas.

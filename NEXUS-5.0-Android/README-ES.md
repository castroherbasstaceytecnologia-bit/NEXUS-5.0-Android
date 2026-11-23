# NEXUS 5.0 para Android

Este proyecto crea una aplicación Android sencilla que abre la versión publicada de NEXUS 5.0 dentro de una ventana WebView.

**Dirección web utilizada:**
https://castroherbasstaceytecnologia-bit.github.io/NEXUS-5.0/

## Generar el APK con Android Studio

1. Instala Android Studio en una computadora.
2. Abre Android Studio y selecciona **Open**.
3. Selecciona la carpeta `NEXUS-5.0-Android`.
4. Espera a que termine la sincronización de Gradle.
5. Si Android Studio solicita instalar Android SDK 35, acepta.
6. En el menú, selecciona **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
7. El APK de prueba aparecerá en `app/build/outputs/apk/debug/app-debug.apk`.

## Generar el APK automáticamente con GitHub Actions

1. Crea un repositorio nuevo en GitHub.
2. Sube el contenido de esta carpeta a la rama `main`.
3. Abre la pestaña **Actions** del repositorio.
4. Ejecuta **Build NEXUS 5.0 APK** con **Run workflow** (o espera a que termine la ejecución automática).
5. Cuando finalice correctamente, abre la ejecución y descarga el artefacto **NEXUS-5.0-APK**.
6. GitHub descargará un ZIP que contiene `app-debug.apk`.

## Importante

- Esta versión necesita conexión a Internet porque abre la aplicación publicada en GitHub Pages.
- Los archivos y cambios que publiques en GitHub Pages se mostrarán también en la aplicación Android.
- El APK `debug` sirve para instalar y probar. No es una versión firmada de publicación.

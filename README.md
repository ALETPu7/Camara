# Camera Recording App

Aplicación Android simple para grabar videos con la cámara del dispositivo.

## Características

✅ Interfaz simple e intuitiva
✅ Grabación de video en tiempo real
✅ Permisos de cámara y micrófono configurados
✅ Almacenamiento de videos en la galería
✅ Control de grabación (iniciar/detener)

## Requisitos

- Android 5.0 (API 21) o superior
- Permisos: Cámara, Micrófono, Almacenamiento

## Instalación

1. Clona el repositorio
2. Abre el proyecto en Android Studio
3. Conecta tu dispositivo Android o usa un emulador
4. Presiona "Run" o Shift + F10

## Estructura del Proyecto

```
Camara/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/example/camerarecorder/
│   │   │   │       ├── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── values/
│   │   │   │   │   ├── strings.xml
│   │   │   │   │   └── colors.xml
│   │   │   └── AndroidManifest.xml
│   ├── build.gradle.kts
├── build.gradle.kts
├── settings.gradle.kts
└── gradle.properties
```

## Permisos

La app solicita los siguientes permisos:
- `android.permission.CAMERA` - Para usar la cámara
- `android.permission.RECORD_AUDIO` - Para grabar audio
- `android.permission.WRITE_EXTERNAL_STORAGE` - Para guardar videos
- `android.permission.READ_EXTERNAL_STORAGE` - Para acceder a los videos grabados

## Uso

1. Abre la app
2. Presiona "Iniciar Grabación" para comenzar a grabar
3. Presiona "Detener Grabación" para terminar
4. El video se guardará automáticamente en la memoria del dispositivo

## Licencia

MIT License

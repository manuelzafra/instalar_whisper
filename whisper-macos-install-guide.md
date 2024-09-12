# Guía de instalación de Whisper para macOS

## Paso 1: Instalar Homebrew

1. Abre Terminal (puedes encontrarlo en Aplicaciones > Utilidades)
2. Pega el siguiente comando y presiona Enter:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

3. Sigue las instrucciones en pantalla

## Paso 2: Instalar Python

1. En Terminal, ejecuta:

```
brew install python
```

## Paso 3: Instalar FFmpeg

1. En Terminal, ejecuta:

```
brew install ffmpeg
```

## Paso 4: Instalar Whisper

1. En Terminal, ejecuta:

```
pip3 install openai-whisper
```

## Paso 5: Verificar la instalación

1. En Terminal, ejecuta:

```
whisper --version
```

Si ves un número de versión, la instalación fue exitosa.

## Paso 6: Uso básico

Para transcribir un archivo de audio, en Terminal ejecuta:

```
whisper ruta/al/archivo/audio.mp3
```

Reemplaza `ruta/al/archivo/audio.mp3` con la ruta real de tu archivo de audio.

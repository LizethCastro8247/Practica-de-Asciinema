# Practica 0
# Grabar la sesión con Asciinema

Este documento explica cómo grabar y documentar una práctica en la terminal de Linux usando **Asciinema**.

---
## 1. Instalación de Asciinema

Dentro de la terminal de Ubunto se ejecutan los siguientes códigos:

```bash
sudo apt update
sudo apt upgrade -y
```
Después, se instala "Asciinema" y figlet con los siguientes comandos:
```bash
sudo apt install asciinema
sudo apt install figlet
```
se verifica si la instalación de asciinema fue exitosa
```bash
asciinema --version
```

## 2. Grabación con Asscinema
Posteriormente, se ejecuta el siguiente comando para dar inicio a la grabación de la termina
```bash
asciinema rec
```
A partir de este momento, cada código ingresado a la terminal se grabara.

## 3. Vídeo de Asciinema
Ahora, se anexa el vídeo de la terminal donde se ejecuto cada uno de los comandos realizados:

[![asciicast](https://asciinema.org/a/7382TxQrN9CUMalbKAkGQWOR7.svg)](https://asciinema.org/a/7382TxQrN9CUMalbKAkGQWOR7)

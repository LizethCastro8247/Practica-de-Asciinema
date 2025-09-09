# Practica 0
# Grabar la sesión con Asciinema

Este documento explica cómo grabar y documentar una práctica en la terminal de Linux usando **Asciinema**.

---
## 1 Instancia de AWS

En el apartado de instancias de AWS, nos conectamos a la instancia que se creo anteriormente. Le damos clic al botón de "Conectar".

<img width="1920" height="1080" alt="imagen" src="https://github.com/user-attachments/assets/d48c90db-60e3-404c-ba89-fcb2ab58c552" />


## 2. Instalación de Asciinema

Se abrirá otra pestaña donde nos aparecerá este recuadro negro, indicando que estamos dentro de la terminal de Ubuntu.

<img width="1920" height="1080" alt="imagen" src="https://github.com/user-attachments/assets/30cdd2b8-0e75-4745-9cab-e7d0c0ca05af" />

Ahora, se ejecutan los siguientes códigos:

```bash
sudo apt update
sudo apt upgrade
```

Después, se instala "Asciinema" y figlet con los siguientes comandos:

```bash
sudo apt install asciinema
```
<img width="720" height="131" alt="imagen" src="https://github.com/user-attachments/assets/817cd0a3-f4dd-4652-a75d-b74ae737f327" />

```bash
sudo apt install figlet
```
<img width="715" height="134" alt="imagen" src="https://github.com/user-attachments/assets/7c6beccf-a661-448f-9239-a0cc02b2cf5b" />

## 3. Grabación con Asscinema
Posteriormente, se ejecuta el siguiente comando para dar inicio a la grabación de la termina
```bash
asciinema rec
```
A partir de este momento, cada código ingresado a la terminal se grabara.

## 4. Vídeo de Asciinema
Ahora, se anexa el vídeo de la terminal donde se ejecuto cada uno de los comandos realizados:

[![asciicast](https://asciinema.org/a/7382TxQrN9CUMalbKAkGQWOR7.svg)](https://asciinema.org/a/7382TxQrN9CUMalbKAkGQWOR7)

---
layout: single
title: SolarLab - HackTheBox
excerpt: "Maquina Season 5 SolarLab"
date: 2024-05-16
classes: wide
header:
  teaser: /assets/images/htb-writeup-solarlab
  teaser_home_page: true
  icon: ./assets/images/hackthebox.webp
categories:
  - hackthebox
tags:  
  - enumeracion
  - ftp
  - ssh
  - http
  - https

---

# Enumeración con Nmap

![](/assets/images/htb-writeup-solarlab/image.png)



# Enumeración del servicio FTP

El Protocolo de Transferencia de Archivos (FTP, por sus siglas en inglés) utiliza dos puertos diferentes para su funcionamiento. Estos puertos son estándar y se utilizan para la transferencia de archivos y comandos entre el cliente FTP y el servidor FTP. Aquí tienes una enumeración de los puertos FTP estándar.

## Puerto de Control (FTP Control Port):

Número de Puerto: 21/TCP (Transmisión de Control)
Descripción: El puerto 21 es el puerto de control utilizado para establecer la conexión inicial entre el cliente FTP y el servidor FTP. Todas las comunicaciones de control, como comandos y respuestas del servidor, se realizan a través de este puerto.

## Puerto de Datos (FTP Data Port):

Número de Puerto: 20/TCP (Transmisión de Datos)
Descripción: El puerto 20 es utilizado para la transferencia de datos cuando se realizan descargas desde el servidor al cliente en modo activo. En este modo, el servidor se conecta al puerto de datos del cliente.
Además de estos dos puertos estándar, es importante mencionar que el FTP puede funcionar en dos modos diferentes:

    - Modo Activo (Active Mode): En este modo, el cliente FTP abre un puerto de datos efímero (un puerto de -  alta numeración) y envía su dirección IP y número de puerto al servidor a través del puerto de control (puerto 21). El servidor luego se conecta al puerto de datos del cliente para la transferencia de archivos.
  
    - Modo Pasivo (Passive Mode): En este modo, el servidor FTP abre un puerto de datos efímero y envía su      dirección IP y número de puerto al cliente a través del puerto de control. El cliente se conecta al puerto de datos del servidor para la transferencia de archivos. El modo pasivo se utiliza a menudo en situaciones en las que los cortafuegos u otros dispositivos de seguridad pueden bloquear las conexiones entrantes al cliente.
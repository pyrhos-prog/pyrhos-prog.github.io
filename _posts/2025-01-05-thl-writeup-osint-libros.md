---
layout: single
title: Cámara - The Hackers Labs
excerpt: "Este reto OSINT de The Hacker Labs consiste en usar las camaras cctv públicas para conseguir la información del dueño de la empresa a traves de una foto."
date: 2025-01-05
classes: wide
header:
  teaser: /assets/images/thl-writeup-osint-camara/avatar.jpg
  teaser_home_page: true
  icon: /assets/images/osint.webp
categories:
  - thehackerlabs
  - OSINT
tags:  
  - osint
  - Google Maps
---

![](/assets/images/thl-writeup-osint-camara/avatar.jpg)


# Descripción del desafio


Estimados miembros de las FFCCSE,

Me dirijo a ustedes con un asunto de extrema gravedad que requiere su atención inmediata. He sido objeto de extorsión, donde se me ha exigido transferir 300 ETH a una dirección desconocida. El extorsionador amenaza con hacer pública mi interés por aprender hacking en The Hackers Labs, lo que podría tener serias repercusiones para mi reputación y seguridad.

A continuación, detallo los pasos que considero cruciales para abordar esta situación:

Identificación de la Transacción: Rastrear la transacción involucrada y recopilar información clave, incluyendo el valor transferido y las direcciones de envío y recepción.
Análisis de la Billetera Destinataria: Examinar la actividad de la billetera que ha recibido los fondos, buscando detectar posibles pagos o transacciones sospechosas que puedan estar relacionadas con el extorsionador.
Informe de Resultados: Elaborar un informe detallado sobre los hallazgos de la investigación, con el objetivo de identificar y exponer al extorsionador. Este informe será fundamental para realizar la denuncia correspondiente.
En la captura de pantalla adjunta se encuentra la dirección de la billetera involucrada. Recomiendo que se copie esta información en un formato de texto, ya que es una captura de pantalla. Utilizar esta dirección será clave para resolver gran parte del problema. Agradezco de antemano su atención y apoyo en esta delicada situación. 

# Primer paso (Analizar la imagen)

En la imagen qeu nos viene en el desafio podemos ver un correo electrónico de un intento de extorsión en el que hay una direccion de una wallet

![](/assets/images/thl-writeup-osint-camara/camara-cctv.png)



![](/assets/images/thl-writeup-osint-camara/busqueda-google.png)

Despues de explorar un poco en los resultado nos encontramos con una cámara en Nashville que cuadra con la de la imagen, al meternos en ella comprobamos que si que es la misma.

![](/assets/images/thl-writeup-osint-camara/camara-cctv-actual.png)

Después de buscar en el historial de la cámara nos encontramos que la imagen es del 10 de julio de 2024.

![](/assets/images/thl-writeup-osint-camara/cctv-historial.png)

## Segundo paso (Busqueda de el dueño de la cámara cctv)

En la página de la cámara podemos ver que la cámara esta en Nashville TN y es de The Acme Feed & Seed asi que ahora vamos a buscar en google maps el edificio.

![](/assets/images/thl-writeup-osint-camara/acme-cctv.png)

# Solución:

**Enlace a la cámara CCTV:** [enlace CCTV](https://www.earthcam.com/usa/tennessee/nashville/?cam=nashville)

**Fecha de Captura de la imagen:** 10 de julio de 2024

**Ciudad y ubicación exacta:** Nashville, 101 US-70, Nashville, Tennessee

**Propietario del edificio:** Acme Farm Supply
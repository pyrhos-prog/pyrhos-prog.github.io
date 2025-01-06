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
  - cctv
---

![](/assets/images/thl-writeup-osint-camara/avatar.jpg)


# Descripción del desafio


> El FBI está solicitando su colaboración inmediata para obtener información crucial relacionada con la imagen que se presenta a continuación. Esta información es vital para resolver un caso de “robo de miradas intensas” que requiere nuestra atención urgente. Cualquier detalle que pueda proporcionar podría marcar la diferencia para llevar a los responsables ante la justicia.

### ¿Qué necesitamos de usted?
 
**Enlace a la Cámara CCTV:** Si reconoce la ubicación de la cámara de seguridad que capturó esta imagen o si tiene acceso al sistema de CCTV correspondiente, por favor proporcione el enlace o la forma de acceso. Su aporte podría ser fundamental para rastrear los movimientos y actividades relacionadas con este caso.

**Fecha de la Captura de la Imagen:** Saber la fecha exacta en la que esta imagen fue tomada es de suma importancia para alinear los hechos y avanzar en la investigación. Si tiene información precisa sobre cuándo fue capturada, le pedimos que se comunique con nosotros lo antes posible.

**Ciudad y Ubicación Exacta:** Si puede identificar la ciudad, el barrio, o el edificio donde está situada la cámara de seguridad, su información será de un valor incalculable para nuestra investigación.

**Propietario del Edificio:** Es especialmente importante que sepamos quién es el propietario del edificio donde se encuentra la cámara. Esta información es esencial para establecer contacto y obtener acceso a cualquier dato adicional que pueda ser relevante para la investigación.


# Primer paso ( busqueda de localización y fecha )

![](/assets/images/thl-writeup-osint-camara/camara-cctv.png)

Metiendo el nombre de la tienda "Hot Chicken and BBQ" que hay en la imagen en [esta pagina](https://cipher387.github.io/webcamcse/) nos sale las cámaras publicas que hay donde sale esa misma tienda.

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
# RTK GPS

## Descripción del Proyecto

El proyecto **RTK GPS** tiene como objetivo explorar y probar la tecnología RTK (Real-Time Kinematic) para mejorar la precisión de la geolocalización. Esta tecnología se basa en el uso de una estación base y un rover, donde la base transmite correcciones diferenciales al rover para mejorar la precisión del posicionamiento GPS.

## ¿Qué es RTK GPS?

RTK (Real-Time Kinematic) es un método de corrección diferencial utilizado en sistemas de navegación por satélite (GNSS). A diferencia de los sistemas GPS convencionales, que pueden tener errores de varios metros, RTK permite alcanzar precisiones centimétricas en tiempo real.

El funcionamiento de RTK GPS se basa en dos componentes principales:

### 1. Base
La base es una estación fija que recibe señales de satélites GNSS y calcula las correcciones necesarias. Luego, estas correcciones son enviadas al rover para mejorar su precisión.

### 2. Rover
El rover es un receptor móvil que también recibe señales de satélites GNSS, pero además incorpora las correcciones proporcionadas por la base para determinar su posición con mayor precisión.

---

## Equipamiento Utilizado para la Prueba

### Test 1:

**Base:**
- Módulo LC29H(BS) HAT 
    - https://www.aliexpress.com/item/1005007938172350.html

- Raspberry Pi 4B / ESP 32

**Rover:**
- Módulo LC29H(DA) HAT
    -   https://www.aliexpress.com/item/1005007513127879.html
- Raspberry Pi 4B / ESP 32



[Ficha Tecnica LC29H](./docs/Quectel_LC29H_GNSS_Specification_V11-1.pdf)

[Ficha Tecnica mas prod QUetel](./docs/Quectel_Product_Brochure_V8.2.pdf)

## Configuración y Pruebas

En las siguientes etapas del proyecto, se documentará el proceso de configuración y pruebas de la tecnología RTK, incluyendo:
- Configuración de la base y el rover.
- Conexión y comunicación entre los dispositivos.
- Evaluación de la precisión del sistema.

Este documento se actualizará conforme avancemos en las pruebas y se realicen ajustes al sistema.


# Links


https://www.waveshare.com/lc29h-gps-hat.htm?sku=25280

https://www.waveshare.com/wiki/LC29H(XX)_GPS/RTK_HAT


Antenas GNSS Networks (europa)
https://epncb.oma.be/_networkdata/stationmaps.php




# Quectel LC29H Dual-Band Multi-Constellation GNSS Modules

![Diagram](./docs/images/Block%20Diagram.webp)

Quectel LC29H Dual-Band Multi-Constellation GNSS Modules are based on the MTK platform and can concurrently track GPS, BeiDou, Galileo, and QZSS satellite signals. The modules use L1/L5 bands, and GLONASS satellite signals on the L1 band. Compared with GNSS modules that can track only L1 signals, LC29H can track more visible satellites, thereby significantly mitigating the multipath effect in urban canyons, reducing signal acquisition time, and improving positioning accuracy. The modules support plenty of tracking channels, which leads to superior navigation performance.

## Features
- Multi-GNSS engine for GPS, GLONASS, BeiDou, Galileo, and QZSS
- Reception of L1 and L5 GNSS band signals concurrently
- Optional integrated DR function
- Optional RTK providing sub-meter accuracy with fast convergence time and outstanding performance
- Integrated LNAs for high-sensitivity
- Integrated SAW filters for noise cancellation
- Support UART, USB, SPI, and I2C interfaces
- Integrated AGNSS function
- B13 band suppression design that reduces interferences from this band by 20dB
- Support EPO™, EASY™, LOCUS™
- Integrated AIC and jamming function
- Ultra-low-power consumption
- Ultra-compact size, 12.2mm × 16.0mm × 2.5mm
    -165dBm tracking sensitivity
    -40°C to +85°C operating temperature range
RoHS-compliant


## Applications
Real-time tracking
Sharing economy-related services
Power-sensitive systems
Battery-powered systems


# Desarrollo Software (docs)

    - [NMEAD0183 Protocol Documentation](./docs/NMEA0183.md)

    

Como funciona RTK

[![Texto alternativo](https://img.youtube.com/vi/ieearzWTCZw/0.jpg)](https://www.youtube.com/watch?v=ieearzWTCZw)
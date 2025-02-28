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
- Raspberry Pi 4B

**Rover:**
- Módulo LC29H(DA) HAT
- Raspberry Pi 4B


## Configuración y Pruebas

En las siguientes etapas del proyecto, se documentará el proceso de configuración y pruebas de la tecnología RTK, incluyendo:
- Configuración de la base y el rover.
- Conexión y comunicación entre los dispositivos.
- Evaluación de la precisión del sistema.

Este documento se actualizará conforme avancemos en las pruebas y se realicen ajustes al sistema.





https://www.waveshare.com/lc29h-gps-hat.htm?sku=25280

https://www.waveshare.com/wiki/LC29H(XX)_GPS/RTK_HAT


Antenas GNSS Networks (europa)
https://epncb.oma.be/_networkdata/stationmaps.php
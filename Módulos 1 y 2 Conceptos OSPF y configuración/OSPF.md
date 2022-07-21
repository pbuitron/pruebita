# **1.1 Características y funciones de OSPF**
---

## **1.1.1 Introducción a OSPF**
---
* Este tema es una breve 
descripción del Camino más Corto Primero (OSPF), que incluye un área única y una multiárea. OSPFv2 se utiliza para redes IPv4. OSPFv3 se utiliza para redes IPv6. El enfoque principal de todo este módulo es OSPFv2 de área única.

* El protocolo OSPF es un protocolo de enrutamiento de estado de enlace que se desarrolló como una alternativa al Protocolo de Información de Enrutamiento del Vector de Distancia (RIP). RIP fue un protocolo de enrutamiento aceptable en los primeros días de las redes e Internet. Sin embargo, el hecho de que RIP dependiera del conteo de saltos como única métrica para determinar la mejor ruta, rápidamente, se volvió problemático. El uso del conteo de saltos no escala bien en redes más grandes con varias rutas de distintas velocidades. El OSPF tiene ventajas significativas sobre el RIP en el sentido que ofrece una convergencia más rápida y se escala a implementaciones de redes mucho más grandes.

* OSPF es un protocolo de enrutamiento de estado de enlace que utiliza el concepto de áreas. Un administrador de red puede dividir el dominio de enrutamiento en áreas distintas que ayudan a controlar el tráfico de actualización de enrutamiento. Un enlace es una interfaz en un router. Un vínculo es también un segmento de red que conecta dos routers, o una red auxiliar, como una LAN Ethernet que está conectada a un único router. La información sobre el estado de un enlace se conoce como estado de enlace. Toda la información del estado del enlace incluye el prefijo de red, la longitud del prefijo y el costo.

* Este módulo cubre implementaciones y configuraciones básicas de OSPF de área única.

---
## 1.1.2. Componentes de OSPF 
--- 
* Todos los protocolos de enrutamiento comparten componentes similares. Todos usan mensajes de protocolo de enrutamiento para intercambiar información de la ruta. Los mensajes contribuyen a armar estructuras de datos, que luego se procesan con un algoritmo de enrutamiento.

|MENSAJES  DE PROTOCOLO DE ENRUTAMIENTO|
|--------------------------------------|
1. Los routers que ejecutan OSPF intercambian mensajes para transmitir información de enrutamiento por medio de cinco tipos de paquetes. Estos paquetes, que pueden verse en la figura, son los siguientes:  

* Paquete Hello  
* Paquete de descripción de la base de datos  
* Paquete de solicitud de estado de enlace  
* Paquete de actualización de estado de enlace  
* Paquete de acuse de recibo de estado de enlace  
Estos paquetes se usan para descubrir routers vecinos y también para intercambiar información de enrutamiento, a fin de mantener información precisa acerca de la red.|


```
html
```

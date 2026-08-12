# Extractor de Humos DIY 💨

Un extractor de humos casero, funcional y muy económico diseñado para proteger tu salud al soldar componentes electrónicos. Este proyecto demuestra que, con creatividad y conocimientos de electrónica básica, es posible crear herramientas esenciales de laboratorio sin depender de una impresora 3D.

El proyecto está documentado en detalle en el archivo [`Extractor de Humos DIY.pdf`](./Extractor%20de%20Humos%20DIY.pdf) adjunto en este repositorio.

## 🛠️ Características Principales
* **Carcasa reciclada:** Construida a partir de un set antihumedad económico.
* **Control de velocidad PWM:** Permite ajustar la velocidad del ventilador sin perder fuerza de succión gracias a un circuito basado en el temporizador NE555.
* **Sistema antivibración:** Anclaje por tensión suspendida que actúa como método de amortiguación, mitigando fricción y vibraciones del rotor.
* **Filtro intercambiable:** Sistema optimizado con clips abatibles para una extracción y reemplazo rápido del filtro de carbón activado.

## 📦 Materiales Necesarios

### Mecánica y Carcasa
* 1x Set antihumedad (modelo de Mercadona, aprox. 3,15€).
* 1x Filtro de carbón activado.
* Adhesivo (pistola de pegamento caliente y super-glue).
* Pintura en spray negra.

### Electrónica
* 1x Circuito Integrado NE555 (Módulo de control lógico).
* 1x Transistor MOSFET N-Channel (IRFZ44N) para la etapa de potencia.
* 1x Ventilador de PC estándar de 12V DC (90mm).
* 1x Módulo DC-DC Buck-Boost (MT3608) para elevar la tensión a 12V.
* 1x Potenciómetro de 100kΩ.
* 2x Diodos 1N4002 (o 1N4148) para direccionar la carga/descarga.
* 1x Diodo Flyback (1N4001G/1N4002) para proteger el motor.
* 2x Condensadores cerámicos 104 (100nF).
* 1x Resistencia de 1kΩ.
* 1x Conector Jack DC hembra (para fuente de alimentación de 9V 2A).
* 1x Botón de encendido.
* Placa perforada (perthboard) y cableado 24 AWG negro.

## 📖 Documentación Completa
Para ver las imágenes paso a paso, los diagramas esquemáticos del circuito PWM, las explicaciones detalladas del funcionamiento interno del flip-flop del NE555 y el proceso de ensamblaje ilustrado, por favor consulta el archivo **Extractor de Humos DIY.pdf** incluido en este repositorio.

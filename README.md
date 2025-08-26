# Informe IEEE: Adquisición y Control de Velocidad Angular de un Motor DC con ESP32

Este proyecto documenta el diseño e implementación de un sistema basado en el microcontrolador ESP32 para la adquisición y control de la velocidad angular de un motor de corriente continua (DC). Incluye medición mediante encoder, acondicionamiento de señal con convertidor frecuencia a voltaje (LM331), visualización en tiempo real de RPM y control de velocidad por interfaz de usuario (teclado y display).

## Autores
- Belfo Junio Puello Carmona
- Daniel Garcia Araque
- Angel David Velasco

## Características principales
- Adquisición de velocidad angular con ESP32 y encoder
- Conversión de frecuencia a voltaje usando LM331
- Visualización de RPM en display
- Control de velocidad por DAC y circuito de potencia
- Interfaz de usuario con teclado
- Comparación de lecturas con tacómetro externo
- Identificación de límites operativos del motor

## Archivos incluidos
- `Untitled-1.sty`: Documento principal en formato LaTeX IEEE
- Código fuente ESP32 (en sección de anexos)
- Esquemático del circuito

## Bibliografía
Referencias sobre ESP32, LM331, motores DC, CAD, electrónica de potencia, encoders, displays y teclados.

## Cómo compilar
1. Instale una distribución LaTeX (TeX Live, MiKTeX, etc.)
2. Compile el archivo `.sty` con su editor LaTeX favorito
3. Asegúrese de tener las imágenes y esquemáticos referenciados en el documento

## Licencia
Este proyecto es educativo y de libre uso para fines académicos.

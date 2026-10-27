# OBC del CubeSat UD34 — Práctica 4

**Integrantes:** José Manuel Arias Toro y Felipe Jiménez Ramírez  
**Universidad:** Universidad de Antioquia  
**Curso:** Laboratorio de Diseño de Productos Electrónicos  
**Herramienta:** Altium Designer 26

## Descripción

En esta práctica desarrollamos el esquema eléctrico de la tarjeta OBC (On-Board Computer) del CubeSat UD34. La tarjeta utiliza el STM32N657X0H3Q para coordinar el procesamiento, el almacenamiento de datos, el manejo de la cámara, los buses de comunicación y el monitoreo de alimentación.

Separamos el circuito en una hoja principal y varias hojas por función: alimentación, núcleo del MCU, SDRAM, almacenamiento, interfaz de cámara, buses de sistema, supervisión y conector de apilamiento. Las interfaces CAN-FD e I²C utilizan hojas reutilizables con instancias independientes.

## Archivos de soporte

- `01_Restricciones_y_Calculos`: matriz eléctrica, criterios de fabricación de referencia y cálculos de dimensionamiento de pistas y señales.
- `02_BOM_y_Costos`: BOM exportada desde Altium y cotizaciones públicas documentadas de 20 referencias para los lotes de 10, 100 y 1000 tarjetas.
- `03_Referencias_Tecnicas`: fichas de referencia de la cámara utilizada en la propuesta.

## Proyecto de Altium

El proyecto nativo se abre con `p4_v07_Arias_Jimenez.PrjPcb` desde Altium Designer 26. La hoja raíz es `00_OBC_Top.SchDoc`. Las ocho hojas funcionales y las dos subhojas repetidas forman parte del mismo proyecto. La verificación se ejecuta con `Project > Validate PCB Project`.




## 💡 Indice
- [📄 Documentos ](Archivos)


# Librerías para adjuntar

Tu lista contiene **19 nombres/entradas**, no 19 bibliotecas únicas necesariamente: hay versiones duplicadas de los cristales ECS. En este paquete sólo están identificados sus nombres. **No tengo el contenido real** de esas bibliotecas.

## Qué copiar
- Todos los `.SchLib` (símbolos) y `.PcbLib` (huellas) que realmente use el proyecto. Los dos de `CYRS17B01G` son especialmente importantes por haberse preparado para el proyecto.
- Los `.IntLib` completos, cuando el proyecto los use.
- De las carpetas descargadas `ul_...`/`LIB_...`, incluir el archivo correspondiente (por ejemplo, `.SchLib`, `.PcbLib`, `.IntLib`), no sólo el nombre de la carpeta.
- ZIP originales de descarga como soporte **opcional**, evitando repeticiones si ya agregas las bibliotecas editables.

## Control antes de entregar
En Altium abre los componentes para verificar: 1) nombre y número de pin; 2) correspondencia símbolo-pad; 3) encapsulado, orientación/polaridad, pad térmico; 4) huella asociada; 5) fabricante y número de parte exactos. Tener el modelo descargado no equivale a haberlo verificado.

**Advertencias del proyecto:** U701 se ha mantenido como TPS3851G18EDRBR provisional; la existencia de una carpeta `LIB_TPS3851H33EDRBR` no demuestra que el cambio esté realizado. D1 también se indicó para corrección; la biblioteca `SMBJ100A` no prueba que la pieza final sea la adecuada.

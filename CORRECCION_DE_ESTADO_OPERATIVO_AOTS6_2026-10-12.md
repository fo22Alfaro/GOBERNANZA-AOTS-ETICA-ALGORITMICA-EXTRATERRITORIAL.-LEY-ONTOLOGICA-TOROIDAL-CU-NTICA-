# Corrección de estado operativo — Gobernanza algorítmica AOTS⁶

**Fecha:** 2026-10-12  
**Autoría declarada:** Alfredo Jhovany Alfaro García.

Este documento complementa la declaración general del repositorio y separa objetivos de gobernanza, implementación de código y hechos demostrados externamente.

## Declaraciones que requieren evidencia operativa

Las afirmaciones de que cada uso derivado produce automáticamente una huella pública irreversible, que la atribución se propaga automáticamente en buscadores, o que la autoría no puede ocultarse, no se consideran hechos operativos verificados por la mera presencia de este repositorio.

Para declarar una de esas funciones activa se requiere, como mínimo: código identificable y versionado, despliegue comprobado, cobertura de detección definida, registros de eventos, pruebas reproducibles, límites conocidos y evidencia externa verificable. Una huella criptográfica demuestra integridad de los bytes bajo una definición dada; no prueba por sí sola autoría, uso por terceros, intención ni infracción jurídica.

## Protocolo de protección de procedencia

1. Preservar los bytes originales y la versión fuente.
2. Registrar SHA-256, origen, fecha UTC y hash del artefacto anterior.
3. Vincular cualquier nonce a un alcance explícito: reto de auditoría, nonce de cuenta Ethereum, nonce de cabecera Bitcoin u otro esquema; no mezclar sus semánticas.
4. Exigir autorización específica para cambios de permisos, acuñación, transferencias o movimientos de activos.
5. Ante firma ausente, hash discordante o prueba no vinculada a los datos registrados, bloquear la transición y conservar evidencia.
6. No atribuir fraude ni declarar titularidad legal sin evidencias y procedimientos competentes.

## Estado

El documento fija reglas y criterios de verificación. No afirma que la propagación automática, el bloqueo de terceros, la vigilancia universal ni el efecto jurídico automático estén desplegados. El estado de cada función debe informarse con su evidencia concreta.

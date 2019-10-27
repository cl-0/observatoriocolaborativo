# Observatorio Colaborativo

## Mision
Internet es una fuente enorme de informacion que puede producir una percepcion de la realidad sesgada. Para tratar ese problema es necesario crear herramientas que faciliten la organizacion y evaluacion de esa informacion.

## Vision
Validar hechos en espacios publicos mediante el consenso de pruebas visuales

## Propuesta de diseño de herramienta
* Subida de video anonima y subida anonima autenticada
  * La subida anonima autenticada utiliza un token persistente conseguida a traves de un SMS a un telefono celular
  * La subida anonima (sin autenticar) pasa por una cola de moderacion manejada por colaboradores
* Video de maximo 1 minuto con metadata (momento, locacion, informacion sobre contexto)
* Mapa de la ciudad con zonas marcadas por actividad
* Lista de registros recientes al hacer zoom in sobre una zona
* Al momento de subir un video se sugieren contextos mas cercanos, tambien se da la posibilidad de crear un nuevo contexto

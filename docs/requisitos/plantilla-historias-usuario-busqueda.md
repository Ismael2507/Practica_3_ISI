# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [dd/mm/aaaa] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como [rol], quiero [capacidad amplia], para [beneficio].

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** Buscar por ingredientes incluidos

Como usuario registrado, quiero poder buscar recetas en a partir de sus ingredientes, para poder seleccionar aquellas recetas que cuenten con los ingredientes de mi preferencia.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que existe una receta que tenga todos los ingredientes seleccionados, cuando la persona usuaria introduce una serie de ingredientes, entonces el sistema muestra todas aquellas recetas que contengan todos los ingredientes indicados.
- **CA-02.** Dado que existe una receta que tiene la mayor parte de los ingredientes seleccionados, cuando [acción], entonces entonces.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-02

**Título:** Buscar por in

Como , quiero, para.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** 
- **CA-02.** 
- **CA-03.** 

## US-03

**Título:** Buscar mediante una palabra o frase.

Como usuario registrado, quiero poder buscar una receta mediante una palabra o frase, para poder visualizar recetas según mis preferencias.

**Fuentes:** UR-08; UC-21; FR-102; acta, 2.

### Criterios de aceptación

- **CA-01.** Dado que existe una receta validada con el título "Tarta de Limón", cuando la persona usuaria introduce "tarta de limon" en el buscador, entonces el sistema muestra la vista previa de esa receta en los resultados, ignorando el uso de minúsculas y la ausencia de tildes.
- **CA-02.** Dado que una receta validada incluye en su descripción breve el texto "estilo tradicional casero", cuando la persona usuaria busca esa frase exacta, entonces el sistema la incluye en los resultados al identificar las palabras seguidas y en el mismo orden.
- **CA-03.** Dado que ninguna receta del sistema contiene la palabra "zahanoria", cuando la persona usuaria ejecuta la búsqueda con ese término, entonces el sistema indica que no hay resultados, conserva el texto buscado en el campo y propone la corrección ortográfica "zanahoria" sin ejecutar una nueva búsqueda automáticamente.

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]

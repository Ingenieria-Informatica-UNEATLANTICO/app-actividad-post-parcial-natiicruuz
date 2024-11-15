Carpeta para incluir el codigo fuente
# Iteración del Examen Parcial

<details open>
<summary>Sistema de transporte publico Iteracion Examen</summary>
<br>

## Diagrama de Clases
| Diagrama | Código Fuente |
|----------|---------------|
| ![Diagrama de Clases](/images/DiagramaClases.svg) | [Ver código](/modelosUML/DiagramaDeClases.puml) |


## Diagrama de Objetos
| Diagrama | Código Fuente |
|----------|---------------|
| ![Diagrama de Objetos](/images/DiagramaDeObjetos.svg) | [Ver código](/modelosUML/DiagramaDeObjetos.puml) |


## Diagrama de Estados
| Diagrama | Código Fuente |
|----------|---------------|
| ![Diagrama de estados de una Ruta](/images/DiagramaDeEstados_Ruta.svg) | [Ver código](/modelosUML/DiagramaDeEstados_Ruta.puml) |
| ![Diagrama de estados de un Pasajero](/images/DiagramaDeEstados_Pasajero.svg) | [Ver código](/modelosUML/DiagramaDeEstados_Pasajero.puml) |

</br>
</details>




# Iteración despues de ayuda de modelo de lenguaje

<details open>
<summary>Sistema de transporte publico CHATGPT</summary>
<br>

## Diagrama de Clases
| Recomendaciones ChatGPT | Diagrama | Código Fuente |
|----------|----------|---------------|
| Conectar `Ciudad` directamente con actores clave como `Pasajero` y `Conductor`, Cambiar `Servicios -r-> Rutas` a composición (`*--`) para reflejar que los servicios incluyen rutas. Fortalecer la relación entre `Rutas` y `Vehículos` usando composición (`*--`).  Vincular directamente `Servicios` con `Tarifas` y mantener la relación con `Abono`.Relacionar `Incidencias` con `Vehículos` y `Rutas` para cubrir ambos contextos posibles. Establecer una relación directa entre `Pasajero` y `SistemaPago` para reflejar su interacción. |![Diagrama de Clases](/images/DiagramaClasesLLM.svg) | [Ver código](/modelosUML/DiagramaClasesLLM.puml) |


## Diagrama de Objetos
| Recomendaciones ChatGPT | Diagrama | Código Fuente |
|--------------------------|----------|---------------|
| Se aplicaron mejoras en las relaciones entre clases, reflejando composiciones y asociaciones relevantes. | ![Diagrama de Objetos](/images/DiagramaDeObjetosLLM.svg) | [Ver código](/modelosUML/DiagramaDeObjDiagramaDeObjetosLLMetos.puml) |



## Diagrama de Estados
| Recomendaciones ChatGPT| Diagrama | Código Fuente |
|----------|----------|---------------|
| Se añadieron precondiciones y acciones en las transiciones, así como descripciones para los estados clave. | ![Diagrama de estados de una Ruta](/images/DiagramaDeEstados_RutaLLM.svg) | [Ver código](/modelosUML/DiagramaDeEstados_RutaLLM.puml) |
| Se añadieron estados intermedios como `SubiendoAlBus`, y se detallaron condiciones y acciones para cada transición, incluyendo el estado inicial y final. | ![Diagrama de estados de un Pasajero](/images/DiagramaDeEstados_PasajeroLLM.svg) | [Ver código](/modelosUML/DiagramaDeEstados_PasajeroLLM.puml) |


### Otros diagramas de estados que hicieron falta recomendados por el ChatGPT :
1. Diagrama de estados para el estado de un vehículo:

Este diagrama podría modelar los diferentes estados en los que se encuentra un vehículo durante su operación, como mantenimiento, en ruta, fuera de servicio, etc.

**Ejemplo de estados:**

- EnMantenimiento: El vehículo está siendo revisado.

- DisponibleParaServicio: El vehículo está listo para ser asignado.

- EnRuta: El vehículo está realizando un servicio.

- FueraDeServicio: El vehículo está detenido por averías u otras razones.

2. Diagrama de estados para la planificación de rutas

Para modelar cómo se gestiona una ruta desde su planificación hasta su ejecución.

**Ejemplo de estados:**

- *PlanificaciónInicial*: Los horarios y paradas son definidos.

- *Publicada*: La ruta está disponible para pasajeros.

- *Modificada*: Cambios en el itinerario o frecuencias.

- *Cancelada*: La ruta ya no está operativa.

3. Diagrama de estados para el sistema de pago

Este diagrama podría modelar cómo un pasajero realiza el pago para acceder al sistema.

**Ejemplo de estados:**

- *EsperandoPago*: El sistema está esperando que el pasajero realice un pago.

- *PagoProcesado*: El sistema ha recibido y validado el pago.

- *PagoFallido*: El pago no se completó, por ejemplo, por saldo insuficiente.

4. Diagrama de estados para la gestión de incidencias

Modelo para cómo una incidencia es registrada y gestionada hasta su resolución.

**Ejemplo de estados:**

- *Registrada*: Una incidencia ha sido reportada.

- *EnRevisión*: La incidencia está siendo evaluada.

- *EnResolución*: Se está trabajando activamente en resolverla.

- *Resuelta*: La incidencia fue solucionada.

- *Cerrada*: Se cerró el caso de la incidencia.

</br>
</details>

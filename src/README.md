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
</detail>


# Iteración despues de ayuda de modelo de lenguaje

<details open>
<summary>Sistema de transporte publico Iteracion Examen</summary>
<br>

## Diagrama de Clases
| Recomendaciones ChatGPT | Diagrama | Código Fuente |
|----------|----------|---------------|
| Conectar `Ciudad` directamente con actores clave como `Pasajero` y `Conductor`, Cambiar `Servicios -r-> Rutas` a composición (`*--`) para reflejar que los servicios incluyen rutas. Fortalecer la relación entre `Rutas` y `Vehículos` usando composición (`*--`).  Vincular directamente `Servicios` con `Tarifas` y mantener la relación con `Abono`.Relacionar `Incidencias` con `Vehículos` y `Rutas` para cubrir ambos contextos posibles. Establecer una relación directa entre `Pasajero` y `SistemaPago` para reflejar su interacción. |![Diagrama de Clases](/images/DiagramaClasesLLM.svg) | [Ver código](/modelosUML/DiagramaClasesLLM.puml) |


## Diagrama de Objetos
| Diagrama | Código Fuente |
|----------|---------------|
| ![Diagrama de Objetos](/images/DiagramaDeObjetosLLM.svg) | [Ver código](/modelosUML/DiagramaDeObjDiagramaDeObjetosLLMetos.puml) |


## Diagrama de Estados
| Diagrama | Código Fuente |
|----------|---------------|
| ![Diagrama de estados de una Ruta](/images/DiagramaDeEstados_RutaLLM.svg) | [Ver código](/modelosUML/DiagramaDeEstados_RutaLLM.puml) |
| ![Diagrama de estados de un Pasajero](/images/DiagramaDeEstados_PasajeroLLM.svg) | [Ver código](/modelosUML/DiagramaDeEstados_PasajeroLLM.puml) |

</br>
</detail>

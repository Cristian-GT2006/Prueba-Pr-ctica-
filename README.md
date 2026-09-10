# Prueba-Pr-ctica-
Evidencia Prueba Práctica 
| Nombre | Rol |  Usuario GitHub | Tarea |
|--------|-----|-----------------|-------|
| Kevin Garcés | Analista | @Javi2145 |  Análisis del problema |
| Cristian Gómez | Programador | @Cristian-GT2006 | Diseño del algoritmo |
| Erick Cordònez | Desarrollador | @Erick-100  | Codificación |



Cristian Gómez

Erick Cordónez

Kevin Garcés
Identificar el problema: leer el enunciado y extraer claramente cuál es la necesidad o situación a resolver.
Determinar los datos de entrada: qué información se recibe (tipo de dato, formato, restricciones).
Determinar los datos de salida: qué resultado se espera obtener.
Establecer las reglas y restricciones: condiciones, fórmulas, casos especiales, validaciones necesarias.
Documentar los requerimientos: dejar por escrito el alcance del problema para que el resto del equipo lo entienda igual.
## Metodologías:

```mermaid
flowchart LR
    subgraph Tradicional["Metodologías Tradicionales"]
        direction LR
        A1[1 Planteamiento] --> A2[2 Análisis] --> A3[3 Diseño] --> A4[4 Programación] --> A5[5 Pruebas] --> A6((Puesta en marcha))
    end

    subgraph Agil["Metodologías Ágiles"]
        direction LR
        B1[1 Planteamiento] --> B2[2 Requerimientos priorizados] --> B3{{Iteración}}
        B3 -.-> B3
        B3 --> B4((Puesta en marcha))
    end

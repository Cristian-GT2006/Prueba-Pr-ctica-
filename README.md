# Prueba-Pr-ctica-
Evidencia Prueba Práctica 
| Nombre | Rol |  Usuario GitHub | Tarea |
|--------|-----|-----------------|-------|
| Kevin Garcés | Analista | @Javi2145 |  Análisis del problema |
| Cristian Gómez | Programador | @Cristian-GT2006 | Diseño del algoritmo |
| Erick Cordònez | Desarrollador | @Erick-100  | Codificación |

| Kevin Garcés | Tester |  Prueba de escritorio |

Cristian Gómez

Erick Cordónez

Kevin Garcés
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

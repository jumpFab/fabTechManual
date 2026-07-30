# Additive Manufacturing

## What is Additive Manufacturing?

Additive Manufacturing is the process of joining materials to make objects from 3D model data, usually layer upon layer. In fabrication, this means using machines like 3D printers to create complex geometries that would be difficult or impossible to achieve through traditional subtractive methods.

Additive manufacturing, originally known as "Rapid Prototyping," has revolutionized the lab by allowing users to go from a digital design to a physical part with minimal material waste and no specialized tooling.

!!! example "In Practice"
    A designer creates a 3D model of a custom gear, which the machine builds by melting plastic filament and extruding it through a nozzle to draw the shape layer by layer.

---

## Key Concepts

| Term | Definition |
|------|------------|
| **Slicing** | The process of converting a 3D model into thin horizontal layers and generating G-code. |
| **Extrusion** | The act of pushing heated material through a small nozzle to deposit it on the build plate. |
| **Support Material** | Temporary structures printed to hold up overhanging parts of a model during the build. |
| **Infill** | The internal structure of a printed part, typically a repetitive pattern used to save material and time. |

[Link to full glossary](../../glossary.md#additive)

---

!!! danger "Category-Wide Hazards"
    All Additive Manufacturing machines share these risks:

    - **High Temperatures:** Nozzles and build plates can reach temperatures exceeding 200\( ^\circ \)C, causing severe burns.
    - **Ultraviolet Radiation:** SLA/DLP printers use high-intensity UV light that can damage eyes if viewed directly.
    - **Chemical Exposure:** Resins and solvents used in resin printing are toxic and require gloves and masks.

---

## How It Works

Additive manufacturing works by translating a digital CAD file into paths for a tool head. The machine deposits material (thermoplastics, resins, or powders) only where the part exists, gradually building height along the Z-axis.

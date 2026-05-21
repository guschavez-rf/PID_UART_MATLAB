# FPGA-Gowin-Plantilla
Plantilla para proyectos FPGA Gowin

Descripción breve de lo que hace tu circuito o tu módulo aquí.

---

## 📂 Estructura del Proyecto

Para mantener el orden entre las herramientas de simulación (Verilator) y el IDE de hardware (Gowin EDA), el proyecto está distribuido de la siguiente manera:

* **`src/`** (Generado por Gowin): Contiene el código fuente en SystemVerilog, Verilog o VHDL (`.sv`, `.v`, `.vhd`) y la asignación física de pines de la FPGA (`.cst`).
* **`sim/`** (Creado en Plantilla): Contiene los archivos de simulación.
* **`doc/`** (Creado en Plantilla): Documentación técnica, diagramas de bloques, capturas de ondas y otros que sean necesarios.
* **`[Nombre].gprj`**: Archivo oficial para abrir el proyecto en Gowin EDA.

---

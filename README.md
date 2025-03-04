# Altium PCB Project Templates

- **`LayerStackups/`**: Contains a set of different layer stackups for designing boards in **Altium Designer** to be manufactured by **JLCPCB**.  Each stackup contains differeential impedance profiles for 90Ω (USB) and 120Ω (CAN).  All values for material thickness and dielectric coefficient were found on https://jlcpcb.com/impedance
  - **`4Layer.stackup`**: Simple 4 layer stackup based on **JLCPCB** 4 layer - no requirement stackup
  - **`6Layer.stackup`**: Simple 6 layer stackup based on **JLCPCB** 6 layer - no requirement stackup
  - **`8Layer.stackup`**: Simple 8 layer stackup based on **JLCPCB** 8 layer - no requirement stackup
- **`LayerStackups/`**: Contains templates for defining PCB layer stackups, specifying material properties, thicknesses, and layer configurations.
- **`OutputTemplates/`**: Stores pre-configured output job files to automate the generation of manufacturing files (Gerbers, BOM, NC drill files, etc.).
- **`Rules/`**: Provides design rule templates that enforce constraints for trace width, clearance, via sizes, and other PCB layout parameters.
- **`SchematicTemplates/`**: Includes schematic templates to ensure consistency in circuit design across multiple projects.

These folders help streamline the PCB design workflow by providing standardized templates for key aspects of the design process.

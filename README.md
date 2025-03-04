# Altium PCB Project Templates

- **`LayerStackups/`**: Contains a set of different layer stackups for designing boards in **Altium Designer** to be manufactured by **JLCPCB**.  Each stackup contains differeential impedance profiles for 90Ω (USB) and 120Ω (CAN).  All values for material thickness and dielectric coefficient were found on https://jlcpcb.com/impedance
  - **`4Layer.stackup`**: Simple 4 layer stackup based on **JLCPCB** 4 layer - no requirement stackup
  - **`6Layer.stackup`**: Simple 6 layer stackup based on **JLCPCB** 6 layer - no requirement stackup
  - **`8Layer.stackup`**: Simple 8 layer stackup based on **JLCPCB** 8 layer - no requirement stackup
 
- **`Rules/`**: Provides design rule templates that enforce constraints for trace width, clearance, via sizes, and other PCB layout parameters.
  - **`JLCPCB.RUL`**: A rules file found on **JLCPCB** help posts at https://jlcpcb.com/help/article/How-to-export-Altium-PCB-to-gerber-files.
  - **`CPRBaja.RUL`**: A rules file created from the manufacturing capabilities provided by **JLCPCB** at https://jlcpcb.com/capabilities/pcb-capabilities.  This ruleset is for multi-layer projects.
 
- **`OutputTemplates/`**: Stores pre-configured output job files to automate the generation of manufacturing files (Gerbers, BOM, NC drill files, etc.).
    - **`CPRBaja.OutJob`**: An output job file for generating documents for review, manufacturing, and validation.  This job file is setup to generate prints of schematics, 3D images of both the front and back of the board file, the pick-n-place file, the GerberX2 files, the layer stackup, the BOM, DRC and ERC reports, and a step file of the PCB.

- **`SchematicTemplates/`**: Includes schematic templates to ensure consistency in circuit design across multiple projects.
    - **`CPRBaja.SchDoc`**: A schematic template file for CPR Baja schematics.  This template uses size B paper if it is printed.  All values will be automatically populated by adding project paramaters for Engineer, Reviewer, Organization, Revision, and Project.

These templates help to maintain consistency amongst projects and reduce manufacturing issues.

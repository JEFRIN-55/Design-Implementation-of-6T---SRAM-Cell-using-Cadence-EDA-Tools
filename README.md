# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-03-24 122239](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)



## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

![WhatsApp Image 2025-10-04 at 13 45 41_e7f4bf3b](https://github.com/user-attachments/assets/2ce6002e-9254-48b6-b55c-63c86ce471ac)


   ![image](https://github.com/user-attachments/assets/c28aea2b-9e73-48e6-abdb-11c430321b86)


## Output
#### 1. Transient Analysis Output:

![WhatsApp Image 2025-10-04 at 13 45 41_339959d6](https://github.com/user-attachments/assets/fb28b86d-89a6-417c-a96f-c6eea26a4da5)

![WhatsApp Image 2025-10-04 at 13 45 41_b7c74666](https://github.com/user-attachments/assets/18a2f9be-320a-4024-95b4-fc0f258aed2d)

![WhatsApp Image 2025-10-04 at 13 45 41_73eddfbc](https://github.com/user-attachments/assets/3f8e1063-0e80-4104-b4f0-7817f90a55c7)


## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.



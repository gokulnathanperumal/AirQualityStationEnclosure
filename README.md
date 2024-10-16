# <img src="https://github.com/user-attachments/assets/b2fddddf-a73c-4617-a5bf-3a34f40eaf00" width="5%" align="left"> Air Quality Station Enclosure


A Fused Deposition Modeling (FDM) project for a 3D-printable enclosure designed for the [Air Quality Station](https://github.com/gokulnathanperumal/AirQualityStation). The enclosure houses the **Sensirion SEN55** sensor and the **Xiao ESP32C3** microcontroller, providing protection and ease of use. The design focuses on durability, accessibility, and compatibility with standard 3D printing setups.

<img src="https://github.com/user-attachments/assets/45e50dbf-6d24-4a51-ac4e-8f27af87081c" width="18%">
<img src="https://github.com/user-attachments/assets/dfeb1623-2116-4014-959b-a8c05733dc99" width="18%">
<img src="https://github.com/user-attachments/assets/78170e47-b91a-4f1f-aee3-6911361f000b" width="18%">
<img src="https://github.com/user-attachments/assets/a31fd2d4-ce87-424d-b51e-5906bd83dc73" width="18%">
<img src="https://github.com/user-attachments/assets/c5af5a89-84d8-421e-b9e6-5b30256c480e" width="18%">

## Features

- **Designed for Sensirion SEN55 and Xiao ESP32C3**: Ensures a secure fit for these specific components.
- **Modular Design**: Easy to assemble and maintain.
- **Ventilation Slots**: Allows proper airflow for accurate air quality measurement.
- **Durable Construction**: Printed using PLA+ filament for strength and longevity.
  
## 3D Modeling and Printing Process

- **Modeling Software**: Autodesk Fusion 360 was used to create the 3D model.
- **Slicer Software**: Ultimaker Cura was used to slice the model for 3D printing.
- **3D Printer**: Creality Ender 3 V3 SE.
- **Filament**: PLA+ filament was chosen for its enhanced strength compared to regular PLA.

### Autodesk Fusion 360
<img src="https://github.com/user-attachments/assets/96253af5-178d-491c-ad94-8bc6f6db5e8c" width="45%">
<img src="https://github.com/user-attachments/assets/08bea432-fdcf-4037-91fc-f6b89c6195f9" width="45%">

### UltiMaker Cura
<img src="https://github.com/user-attachments/assets/6f296e51-aac3-47fb-92d6-edbba650357f" width="45%">
<img src="https://github.com/user-attachments/assets/46505eea-4fe9-4e7d-809a-e430b92ab966" width="45%">

## Printing Instructions

1. **Printer Settings**: 
    - Printer: Creality Ender 3 V3 SE
    - Filament: PLA+
    - Nozzle size: 0.4mm
    - Layer height: 0.2mm
    - Infill: 20% (recommended for balance between strength and material use)
    - Print speed: 50 mm/s
    - Printing Temperature: 210°C
    - Build Plate Temperature: 60°C

2. **Assembly**:
    - Print the two enclosure parts: the top and the bottom.
    - After printing, align the top and bottom parts that snap together to secure the enclosure.
    - Insert the Sensirion SEN55 and Xiao ESP32C3 into their designated slots before closing the enclosure.

## BOM (Bill of Materials)

- 1x Sensirion SEN55 sensor
- 1x Xiao ESP32C3 microcontroller
- 3D-printed enclosure components (STL files included in this repository)

## Files Included

- `.step`: Original Fusion 360 design files for design customization.
- `.stl`, `.3mf`: Standard file format for 3D models suitable for slicing.
- `.gcode` folder: Final instruction files for 3D printing (Creality Ender 3 V3 SE).

Once printed and assembled, the enclosure provides protection and structure for the **Air Quality Station** components, allowing them to function effectively while keeping the design compact and user-friendly.

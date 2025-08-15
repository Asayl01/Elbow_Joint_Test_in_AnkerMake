# Elbow Joint Test in AnkerMake

This task is about converting the robot arm joint design to STL format, slicing it in AnkerMake Studio, selecting the best printing material, and documenting the process.



## Steps

### 1. Download and Install Software
Downloaded **[eufyMake Studio](https://www.eufymake.com/eufymake-studio?srsltid=AfmBOoriMVKhK--Y9ZWkDDQKiMGYHfV-nNkhsOkenRmGKbc6JUl27bW4)** from the official website and installed it.

### 2. Printer Selection
Selected **AnkerMake M5 All Metal Hotend** with a **0.4 mm nozzle**.  
Reason: Allows higher printing temperatures for stronger materials like PETG or ABS, while the 0.4 mm nozzle provides a good balance between precision and strength.

![Printer](Printer.png)

### 3. Model Preparation and Print Settings
After completing the Elbow Joint design in SolidWorks with customized fillets, chamfers, base cut-outs for weight reduction, and a custom logo, the model was exported to **STL** format.  
The STL file was then opened in **eufyMake Studio**, and the print settings were adjusted for maximum strength based on the part’s dimensions (65 × 68 × 8 mm, wall thickness 6 mm):

- **Layer Height:** 0.1 mm – finer layer resolution for better detail.  
- **Strength – Wall Loops:** 6 – increases wall thickness for higher part strength.  
- **Top Shell Layers:** 7 – creates a more solid and durable top surface.  
- **Bottom Surface Pattern:** Concentric – improves bed adhesion and gives a cleaner bottom finish.  
- **Fill – Sparse Infill Density:** 15% – balances weight, material usage, and internal strength.  
- **Material:** AnkerMake PLA+ Metallic (Metallic Blue) – chosen for good print quality, durability, and ease of printing.



## Printer and Filament Setup & Model Orientation
The elbow joint model was oriented vertically to minimize overhangs and avoid printing large sections in mid-air, improving print strength and reducing the need for excessive support material.

![Printer_and_Filament_Setup](Printer_and_Filament_Setup.png)



## Support Material Settings
Support material configured to ensure stable printing for overhanging parts of the elbow joint.

![Support_Settings](Support_Settings.png)


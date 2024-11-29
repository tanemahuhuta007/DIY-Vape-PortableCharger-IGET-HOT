# DIY Portable Charger from a IGET Hot Vape

![Image](https://github.com/user-attachments/assets/22a7cbf8-9873-411f-a0e1-aa59daa8f72e)  
*A creative and sustainable way to upcycle a vape into a portable charger!*

---


## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Parts and Tools](#parts-and-tools)
4. [Step-by-Step Guide](#step-by-step-guide)
5. [Safety Considerations](#safety-considerations)
6. [Future Improvements](#future-improvements)
7. [License](#license)

---


## Introduction

I have access to hundereds of "Disposable" Vapes, I thought that I might as well use the parts for something.

Modeled using Autodesk Inventor 2024. (.ipt Files Included)

Printed with BambuLabs A1-Mini, Esun PLA Black

This project showcases how to upcycle an old or broken vape device into a functional portable charger. It’s a great way to reuse e-waste and learn some basic electronics in the process.  


---

## Features

- **High Capacity:** 4200mAh Capacity (3X 1400mAh cells)
- **Sustainable Design:** Reuses the vapes housing for less waste.
- **Reused Battery:** Reuses the vapes batteries for less waste. 

  
---

## Parts and Tools

### Parts
- [IGET Hot vape](https://iget.com.au/product-category/iget-hot-5500/) (preferably 3 or more)  
- [USB-C Charger](https://www.aliexpress.com/item/1005006514259622.html?spm=a2g0o.order_list.order_list_main.16.6bb01802Uw7v2R#nav-store) module ([Micro-USB](https://www.aliexpress.com/item/1005007468198510.html?spm=a2g0o.productlist.main.1.28e6bmyvbmyvti&algo_pvid=df3a72e6-e21d-4b3c-b01e-a01b60d23e72&algo_exp_id=df3a72e6-e21d-4b3c-b01e-a01b60d23e72-0&pdp_npi=4%40dis%21AUD%210.72%210.49%21%21%210.46%210.31%21%402103011017328888826127879ef68d%2112000042598500189%21sea%21AU%212213527190%21X&curPageLogUid=w6s7ve753neu&utparam-url=scene%3Asearch%7Cquery_from%3A) Available) 
- Wires (22 AWG recommended)
- 3D printed case
- JST Connectors (optional)

### Tools
- Soldering iron (and solder of course)  
- 3D Printer 
- Wire cutters/strippers  
- Multimeter  

---

## Step-by-Step Guide

### 1. Disassemble the Vapes
- Carefully open the vapes and remove the 3.7v batteries.
- Make sure not the short the wires as it WILL burn your hand (or so ive heard)
- Remove all parts from metal case and wipe clean
  
![Image](https://github.com/user-attachments/assets/4b125f3d-9973-45a0-98ef-4e091224b6e9)


### 2. Prepare the Batteries
- Using a Multimetre, test the batteries to ensure it’s functional.
- Using a Multimetre, check batteries are discharged, if not, use TP4056 to discharge all cells to the same voltage.
- Test it for capacity and safety.

### 3. 3D Print the Case
- Print the Portside.STL & Blank.STL case in any filament you want
- Add a layer pause when the module securing bridge starts (137 for me)

![Screenshot_20241130_003223](https://github.com/user-attachments/assets/9e59a2bb-8ba2-4f0b-86db-c49fad6b871b)

### 4. Install the Charging Module
- Slide the module into the paused print.  
- There should be a 0.25mm gap between the top of the board & the next layer.
- Resume the print

### 5. Wire the Batteries
- Follow the diagram to wire the project.  
- Optionally, add an on/off switch for better control.

![Screenshot_20241130_005403](https://github.com/user-attachments/assets/2e0d9f49-b94f-4fd4-9d16-06e6c2d446ad)


### 6. Test the connections
- After Wiring everything up, Test the functionality before assembling.  
- Test the charging functionality with a small device.


### 7. Assemble
- Slide the Metal case into your printed parts
- Be sure to route cables through the slots to advoid damage

---

## Safety Considerations

- Ensure the battery is not damaged or swollen.  
- Avoid short circuits while soldering.  
- Use proper insulation to prevent accidental contact between components.
- No BMS used, use use at your own discretion, may result in damage to cells and yourself. 

---

## Future Improvements

- Add LED indicators for battery status.  
- Integrate a higher-capacity battery for extended use.  
- Upgrade to a faster charging module like QC 3.0.  

---

## License

This project is open-source. Feel free to contribute or adapt this project for your needs.  

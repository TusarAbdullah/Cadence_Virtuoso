# CMOS Inverter Design (Cadence Virtuoso)

## 1. Library Setup
- Open the **Library Manager**
- Create a **new library** and attach it to an existing technology 
  library (e.g. a standard CMOS process technology file)

## 2. Create New Cell View
- In the new library, create a new cell
- Design name: `inverter`
- Open with the **Schematic (Composer)** editor

## 3. Place Devices
- From the **Library Browser**, select and place instances of 
  **NMOS** and **PMOS** transistors
- Set device parameters: **Length (L)** and **Width (W)** for both 
  NMOS and PMOS

## 4. Wire the Circuit
- Connect the gates of NMOS and PMOS together → this becomes the 
  **input**
- Connect the drains of NMOS and PMOS together → this becomes the 
  **output**
- Connect PMOS source to **VDD**
- Connect NMOS source to **GND**

## 5. Add Pins
- Add an **input pin** (connected to the gate node)
- Add an **output pin** (connected to the drain node)
- Add **VDD** and **GND** pins

## 6. Check and Save
- Run **Check and Save** to validate the schematic for errors

## 7. Create Symbol View
- Generate a **Symbol view** from the schematic
- Arrange pins: input (left), output (right), VDD (top), GND (bottom)


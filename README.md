# Ku Mukeka: Children's Story Narrator - 3D Device Prototype
![KU Mukeka 3D prototype](/ "Optional title text")
## Project Overview
This repository contains a 3D interactive prototype of the "Ku Mukeka" children's story narrator device. Designed for African children under 10, this device is simple, durable, and uses a small solar panel with a backup battery. It features basic functions for navigating stories (back, forward, repeat).

This prototype allows for a visual exploration of the device's external design and internal hardware components in a 3D environment directly within a web browser.

## Features
**Interactive 3D Model**: View the device from any angle by clicking and dragging your mouse.

**Zoom Functionality**: Use your mouse scroll wheel to zoom in and out of the device for a closer look.

**Hover Descriptions**: Hover your mouse over any external or internal component to see a brief description of its function.

**Internal View (Exploded View)**: Double-click the device to open its casing and reveal the internal hardware components. Double-click again to close it.

**Simplified Component Representation**: Internal components are represented by distinct 3D shapes and colors for easy identification.

## Technologies Used
**HTML5**: For the basic page structure.

**CSS3**: For styling the page and the tooltip.

**JavaScript**: For all interactive logic.

**Three.js (r128)**: A powerful JavaScript 3D library used for rendering the 3D model and handling camera controls.

## How to Run the Prototype
Clone the Repository:

git clone https://github.com/YOUR_USERNAME/ku-mukeka-narrator-prototype.git

(Replace YOUR_USERNAME with your GitHub username and ku-mukeka-narrator-prototype with your repository name).

Navigate to the Project Directory:

cd ku-mukeka-narrator-prototype

Open index.html:
Simply open the index.html file in your web browser (e.g., by double-clicking it in your file explorer). No web server is required as it's a self-contained HTML file.

## Interaction Guide
Rotate Device: Click and drag your mouse on the 3D model.

Zoom In/Out: Use your mouse scroll wheel.

Open/Close Device: Double-click anywhere on the device.

View Component Descriptions: Hover your mouse over any part of the device (external or internal). The description will appear in the top-right corner.

## Essential Hardware Components (Detailed)
For a functional "Ku Mukeka" device, the following hardware components are crucial:

- Microcontroller (MCU) / Processor: The central processing unit that executes the device's firmware, manages story playback, processes button inputs, and controls other peripherals.

- Flash Memory / Storage: Non-volatile memory (e.g., SPI Flash) to permanently store the 10 embedded audio stories.

- Audio Codec / Digital-to-Analog Converter (DAC): Converts the digital audio data from storage into an analog electrical signal.

- Audio Amplifier: Boosts the analog audio signal to a sufficient power level to drive the speaker.

- Speaker: Converts the electrical audio signal into audible sound waves.

- Solar Panel: A photovoltaic cell that converts sunlight into electrical energy for charging the battery and/or powering the device directly.

- Rechargeable Battery: Provides continuous power when solar energy is unavailable. A Lithium-Ion or Lithium-Polymer battery would be suitable for its energy density and recharge cycles.

- Power Management Unit (PMU) / Charging Circuitry: Manages power distribution, battery charging (from solar), and voltage regulation to ensure stable operation and battery longevity.

- User Interface Buttons (Tactile Switches): Physical buttons for "Next Story," "Previous Story," and "Repeat Story" functionality. Designed for durability and child-friendly tactile feedback.

- Printed Circuit Board (PCB): The physical board that provides electrical connections and mechanical support for all the electronic components.

- Casing / Enclosure: The protective outer shell of the device, designed to be durable, child-safe, and ergonomically shaped.

- Internal Wiring / Connections: Electrical pathways (traces on PCB, wires) connecting all components.

- LED Indicator (Optional but Recommended): A small light to indicate power status, charging, or low battery.

## Development History (Major Changes)
This prototype was developed iteratively, with key features added in stages:

- Initial prototype setup: Basic 3D device model with rotation.

- Feature: Added hover descriptions for device components.

- Improvement: Repositioned hover tooltip to be non-obstructive (top-right).

- Feature: Implemented zoom functionality using mouse scroll wheel.

- Feature: Added double-click to open/close device and view internals.

- Feature: Included basic internal hardware components (circuit board, battery, memory, speaker driver).

- Improvement: Made internal wiring clearly visible as 3D elements.

- Feature: Added essential hardware components (PMU, Microcontroller, Audio Codec/DAC).

- Improvement: Increased internal component sizes, adjusted positions, and used vibrant colors for better visibility.

- Documentation: Added comprehensive README.md file.
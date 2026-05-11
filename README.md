# Automated Syringe Pump System - 3D Design

This repository contains the mechanical design files for an Automated Syringe Pump System. The project focuses on creating a cost-effective, reliable, and programmable solution for precise fluid delivery in low-resource environments.

## Project Overview

Syringe pumps are precision instruments designed to deliver fluids at controlled flow rates. They facilitate accurate medication dosing and support the continuous infusion of fluids. This design demonstrates the potential for low-cost medical and laboratory devices by utilizing standard mechanical components and 3D-modeled parts.

### Working Principle
1. The user initiates the operation.
2. A microcontroller transmits signals to a motor driver.
3. The stepper motor rotates the lead screw.
4. The lead screw subsequently moves the syringe plunger to deliver fluid at a controlled rate.

## Repository Structure

The project is organized into the following directories:

* **Animations**: Contains motion studies and rendered animations showing the device in operation.
* **Assembly**: Contains the top-level assembly files for the entire system.
* **parts**: Includes all individual component files, such as the syringe holder, motor mounts, and lead screw interfaces.
* **project images**: Contains high-resolution renders and technical images of the design.

## Usage and Interaction

To fully interact with the project and explore the component relationships:

1. Locate the **Assembly** folder in the file navigation above.
2. Open the **assembly file** inside that folder using your CAD software to view the full system integration.

## Core Components

The design incorporates the following core mechanical and electronic components:
* **Arduino Uno**: Serves as the programmable microcontroller.
* **Stepper Motor**: Provides precise rotational control.
* **A4988 Motor Driver**: Interfaces the motor with the control logic.
* **Lead Screw**: Translates rotation into linear plunger movement.
* **Mechanical Syringe Holder**: Secures the syringe during operation.

## Applications

* **Medical**: Drug infusion and IV fluid delivery.
* **Laboratory**: Chemical dosing and microfluidic experiments.
* **Industrial**: Precision liquid dispensing.

## Future Improvements

* Implementation of higher precision control.
* Development of multi-syringe systems.
* Improved User Interface for

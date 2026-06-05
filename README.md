# Repulsive Maglev – KiCad Setup

This repository contains the KiCad hardware design for the Repulsive Maglev project.

To use the project correctly, install the required KiCad plugins and external libraries first.

## 1. Required KiCad Plugins

Install the following plugins via:

KiCad → Plugin and Content Manager

### Interactive HTML BOM

Install the **Interactive HTML BOM** plugin.

It is used to generate an interactive HTML bill of materials for easier manual PCB assembly and component placement.

### PCBWay Plugin for KiCad

Install the **PCBWay Plugin for KiCad**.

It is used to export PCB manufacturing files and prepare the order for PCBWay directly from KiCad.

### Espressif KiCad Library

Install the **Espressif KiCad Library** via the Plugin and Content Manager.

It provides the required ESP32 symbols, footprints and models.

## 2. Required Würth Elektronik Library

This project uses components from the Würth Elektronik KiCad library.

Clone the official Würth Elektronik KiCad library:

    git clone https://github.com/WurthElektronik/KiCad-Library.git

Then add the libraries globally in KiCad.

### Add Symbol Libraries

Open:

KiCad → Preferences → Manage Symbol Libraries

Go to:

Global Libraries

Add the required Würth `.kicad_sym` symbol libraries from the cloned repository.

### Add Footprint Libraries

Open:

KiCad → Preferences → Manage Footprint Libraries

Go to:

Global Libraries

Add the required Würth `.pretty` footprint libraries from the cloned repository.
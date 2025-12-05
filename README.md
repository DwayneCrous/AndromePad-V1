# AndromePad V1

A custom mechanical macropad PCB project by DwayneR Engineering, designed in KiCad. This is the first revision of the macropad.

## Features

*   Powered by a Seeeduino XIAO series microcontroller.
*   Includes a rotary encoder with a switch, which can be used for volume control, scrolling, or other functions.
*   Uses a TCA9555RTWR 16-bit I/O expander to manage the key matrix.
*   Includes a potentiometer.
*   Designed with components from the Seeed Studio OPL KiCad library.

## Key Components

*   Seeeduino XIAO microcontroller
*   TCA9555RTWR 16-bit I/O expander
*   Rotary Encoder with switch
*   Potentiometer
*   Mechanical keyswitches
*   Diodes, Resistors, and Capacitors

## Software

This project is designed using [KiCad](https://www.kicad.org/), an open-source EDA software. You will need to have KiCad installed to view and edit the project files.

## How to Use

1.  Clone or download this repository.
2.  Open KiCad.
3.  Go to `File > Open Project...`
4.  Navigate to the `AndromePad V1` directory and open the `AndromePad V1.kicad_pro` file.

## Libraries

This project includes the [OPL_Kicad_Library](https://github.com/Seeed-Studio/OPL_Kicad_Library) from Seeed Studio. The library is included in the `OPL_Kicad_Library-master` directory.

## Bill of Materials (BOM)

To generate the Bill of Materials (BOM):

1.  Open the `AndromePad V1.kicad_sch` file in KiCad's Eeschema.
2.  Go to `Tools > Generate Bill of Materials...`.
3.  You can use the default `bom_csv_grouped_by_value` script or a custom one.

## PCB Layout

<!-- TODO: Replace with an actual image of the PCB layout -->
*(Image of the PCB layout will be here)*
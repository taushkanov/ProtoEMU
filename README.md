# ProtoEMU

ProtoEMU Emulator is a specialized application for emulating devices operating via the Modbus-RTU and Modbus-TCP protocols.

The emulator allows replacing real devices used in automation, dispatching, or other systems with their virtual software counterparts. This enhances the convenience and speed of developing information and control systems that interact with equipment, and eliminates the need for system debugging on-site using operational installations.

## 1 Emulator Capabilities

### 1.1 Core Features
*   Emulation of physical input and output signals.
*   Emulation of internal variables accessible via the register map.
*   Manual control of the device state using various widgets.
*   Automatic control of the device state using built-in programs and subroutines.

### 1.2 Supported Protocols
ProtoEMU supports the following communication protocols (transports) for interaction with real devices:
*   Modbus-RTU in both master and slave modes.
*   Modbus-TCP in both master and slave modes.

### 1.3 Visualization
*   Ability to create multiple screens (forms) for visualizing the state of the emulated device.
*   Various widgets for displaying values and controlling the state of the emulated device:
    *   Analog indicator.
    *   Digital indicator.
    *   Button.
    *   Graph/Chart.

### 1.4 Debugging
*   Validation of virtual device configuration correctness.
*   Monitoring of parameter values during emulation.
*   Logging of events occurring during emulator operation, including a communication log with devices containing full traffic trace. Ability to filter log events in real-time.

### 1.5 Additional Features
*   Support for automatic parameter identification for registers based on identifier files.
*   Recording of parameter values to an archive during an emulation session for subsequent analysis and printing.

A complete description of the emulator is available in the **ProtoEMU User Guide** document.


Change log
=================

 * [Version 1.0 change log (EN)](Changelog-EN.md)
 * [Version 1.0 change log (RU)](Changelog-RU.md)

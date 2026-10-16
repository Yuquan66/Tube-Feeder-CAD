# Tube Feeder CAD

SolidWorks CAD for the tube-sorting system, bowl feeder, Chengyi tube holder and robot integration.

## Download and open

1. [Download the complete CAD package (ZIP)](https://github.com/Yuquan66/Tube-Feeder-CAD/archive/refs/heads/main.zip).
2. Extract the entire ZIP before opening any assembly.
3. Open [`CAD/Main Assembly.SLDASM`](CAD/Main%20Assembly.SLDASM) in **SOLIDWORKS 2025 or a compatible later version**.

All referenced external CAD files are collected in the `CAD` directory using SolidWorks Pack and Go. Keep them together; downloading the main assembly alone is not sufficient. Virtual components remain embedded in their parent assembly.

Useful subassemblies:

- [`Bowl Feeder.SLDASM`](CAD/Bowl%20Feeder.SLDASM)
- [`Chengyi Tube Holder.SLDASM`](CAD/Chengyi%20Tube%20Holder.SLDASM)
- [`UR5.SLDASM`](CAD/UR5.SLDASM)

## Current design

- One bowl-feeder installation connected to the existing sorting assembly.
- Chengyi's tube holder integrated downstream of the linear feeder.
- Complete 360-degree guide tube; the 180-degree cutaway is removed. The inherited filename `pipe - half.SLDPRT` is retained to keep existing references consistent.
- Robot base positioned beside the platform at floor level, rather than on the tabletop.
- Original small conveyor remains suppressed in the main assembly, with its referenced files included.

## Preview

![System overview](previews/system-overview.png)

![Feeder, holder and robot](previews/feeder-holder-robot.png)

## Credits

Tube-holder and gripper components: Chengyi and the project collaboration, [Soft-Gripper-](https://github.com/a2597182460-lgtm/Soft-Gripper-).

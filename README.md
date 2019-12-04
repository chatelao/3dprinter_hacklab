# 3dprinter_hacklab
Our 3D printer in the Hacklab Bern, based on the [CL-260 open-source model](https://www.thingiverse.com/minicooper/collections/cl-260).

## Bestandteile

| Teil |     |
| ---- | --- |
| Mikrocontroller            | https://www.3dware.ch/Iduino-MEGA2560-De.htm    |
| Leistungselektronik Shield | https://reprap.org/wiki/RAMPS_1.4    |
| Verstärker Schrittmotoren  | https://www.allegromicro.com/~/media/Files/Datasheets/A4988-Datasheet.ashx |

| Display Platine     | https://reprap.org/wiki/RAMPS_1.4    |
| Heat Bed            | https://reprap.org/wiki/RAMPS_1.4    |
| Hot End             | https://reprap.org/wiki/RAMPS_1.4    |
| Schrittmotoren      | https://reprap.org/wiki/RAMPS_1.4    |

(Mutmassliche) Hardware für Schrittmotoren: A4988



## Firmware

- https://github.com/MarlinFirmware/Marlin
- https://www.repetier.com/download-software/

### Calibration patterns

Zur Prüfung der Ausrichtung des Heizbetts eignen sich die speziellen Quadratmuster zur Prüfung
der Durckhöhe und aus

- Video: https://youtu.be/RZRY6kunAvs
- Quelle: https://www.thingiverse.com/thing:2789086
- STL: [calibration_patterns](calibration_patterns)

![Calibration Patterns](calibration_patterns/a11e319e6441382d85e158443514f1c2_preview_featured.jpg)

### Better Z-Axis endstop

![Z-Axis Endstop](z_axis_sensor_print/5cc3017be026a4b2a4c0659578d3ea0d_preview_featured.jpg)

Quelle:
- https://www.thingiverse.com/thing:2851658
- STL: [z_axis_sensor_print](z_axis_sensor_print)

### Bed level sensor




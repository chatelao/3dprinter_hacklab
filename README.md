# Unser 3D Drucker im Hacklab Bern

Der 3D Drucker im **Hacklab Bern**, basiert auf dem [CL-260 open-source model](https://www.thingiverse.com/minicooper/collections/cl-260). Er wird abwechslungsweise von Mitgliedern genutzt und verbessert, die dies wünschen.

## Bestandteile

| Funktionalität | Verwendete Lösung | Alternativen |
| ---- | --- | --- |
| Firmware | [Marlin](https://github.com/MarlinFirmware/Marlin) | [Repetier](https://www.repetier.com/download-software) |
| Mikrocontroller            | [Arduino Mega 2560](https://www.3dware.ch/Iduino-MEGA2560-De.htm) |
| Leistungselektronik Shield | [RepRap Arduino Mega Pololu Shield (RAMPS) 1.4](https://reprap.org/wiki/RAMPS_1.4) |
| Verstärker Schrittmotoren  | [A4988 Datasheet](https://www.allegromicro.com/~/media/Files/Datasheets/A4988-Datasheet.ashx) |
| Display Platine     | ?   |
| Heat Bed            | https://reprap.org/wiki/RAMPS_1.4    |
| Hot End             | Hotend: e3d v6 |
| Schrittmotoren      |     |

### Calibration patterns

Zur Prüfung der Ausrichtung des Heizbetts eignen sich die speziellen Quadratmuster zur Prüfung
der Durckhöhe und aus

- Video: https://youtu.be/RZRY6kunAvs
- Quelle: https://www.thingiverse.com/thing:2789086
- STL: [calibration_patterns](calibration_patterns)

![Calibration Patterns](calibration_patterns/a11e319e6441382d85e158443514f1c2_preview_featured.jpg)

### Bessere Z-Axis End-Stops

![Z-Axis Endstop](z_axis_sensor_print/5cc3017be026a4b2a4c0659578d3ea0d_preview_featured.jpg)

Quelle:
- https://www.thingiverse.com/thing:2851658
- STL: [z_axis_sensor_print](z_axis_sensor_print)

### Auto bed level sensoren

Bed Auto Leveling
- https://youtu.be/G-TwWfUzXpc
- Sensor: https://de.aliexpress.com/item/32568347298.html 

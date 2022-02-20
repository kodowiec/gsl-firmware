kiano/intelectx3hdp
---

| Item                      | Description |
|---------------------------|-------------|
| Manufacturer              | KIANO |
| Device                    | Intelect X3 HD+ 4/32 |
| Website                   | https://kiano.pl/produkty/urzadzenia-2w1/intelect-x3-hd-2/ |
| Vendor driver (Windows)   | https://kiano.pl/drivers/Kiano_Intelect_X3_HD+.zip |
| Driver file               | [SileadTouch.sys](SileadTouch.sys)
| Extracted firmware        | [firmware_00.fw](firmware_00.fw) |
| Firmware for gslx680-acpi | [silead_ts.fw](silead_ts.fw) |
| Display resolution        | 1280x800 |
| Touch panel resolution    | 1150x1735 |
| Touch controller          | GSL1860/GSL3860 not verified |
| Multitouch support        | Yes, 10 |
| Finger tracking           | Yes |
| Mirrored horizontally     | No |
| Mirrored vertically       | Yes |
| Axes swapped              | Yes |
| Comments                  | fwtool -c firmware_00.fw -m 1680 -w 1150 -h 1735 -t 10 -f swap,yflip silead_ts.fw |

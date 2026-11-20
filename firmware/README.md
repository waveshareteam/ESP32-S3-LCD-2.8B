# ESP32-S3-Touch-LCD-2.8 and ESP32-S3-LCD-2.8 factory firmware

Select the firmware for your board model.

| File | Board model | Version date | Flash offset |
| --- | --- | --- | --- |
| [ESP32-S3-Touch-LCD-2.8_FactoryOnly_20260523.bin](ESP32-S3-Touch-LCD-2.8_FactoryOnly_20260523.bin) | ESP32-S3-Touch-LCD-2.8 (touch) | 2026-05-23 | `0x0` |
| [ESP32-S3-LCD-2.8_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8_FactoryOnly_20250124.bin) | ESP32-S3-LCD-2.8 (non-touch) | 2025-01-24 | `0x0` |

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-Touch-LCD-2.8_FactoryOnly_20260523.bin
```

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8_FactoryOnly_20250124.bin
```

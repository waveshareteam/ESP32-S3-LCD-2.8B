# ESP32-S3-LCD-2.8B and ESP32-S3-Touch-LCD-2.8B firmware

| File | Description | Flash offset |
| --- | --- | --- |
| [ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin](ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin) | Factory firmware for ESP32-S3-Touch-LCD-2.8B (2024-10-25) | `0x0` |
| [ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin) | Factory firmware for ESP32-S3-LCD-2.8B (2025-01-24) | `0x0` |

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin
```

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin
```

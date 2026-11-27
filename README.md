# Trang Nạp Firmware ESP32 — Hydra ESP v1.1.4

Trang Web Flasher nạp trực tiếp firmware **Hydra ESP v1.1.4** cho mạch **ESP32** qua trình duyệt Chrome / Microsoft Edge bằng **ESP Web Tools** (Web Serial / WebUSB).

## Link trang nạp (GitHub Pages)
- https://thongdithahaha-web.github.io/lekimlamiot/

## Cấu trúc thư mục
- `docs/index.html`: Giao diện trang nạp firmware ESP32.
- `docs/firmware/manifest.json`: Cấu hình nạp cho `esp-web-tools`.
- `docs/firmware/bootloader.bin` (`0x1000`)
- `docs/firmware/partition-table.bin` (`0x8000`)
- `docs/firmware/projecthydra-32.bin` (`0x10000`)
- `docs/firmware/storage.bin` (`0x190000`)

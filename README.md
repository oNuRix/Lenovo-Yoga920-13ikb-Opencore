# Opencore for Lenovo Yoga920-13ikb

![Image PNG](https://user-images.githubusercontent.com/40405226/200408879-726c250f-5640-4e91-ab48-53487d285a4e.png)


## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Lenovo Yoga 920-13ikb       |
| Processor           | Intel Core i7-8550u   |
| Memory              | 16GB 2400MMHz soldered |
| NVME                | M.2 Nvme SAMSUNG MZVLW512HMJP-000L2 |
| Integrated Graphics | Intel HD Graphics 620                     |
| Monitor             |4k 3840x2160 touchscreen (14 inch) |
| Sound Card          | Realtek ALC298           |
| Wireless Card       | Intel AC9260 |


## Current Status

- **Fingerprint sensor is not working (never will work)**
- Everything else works well except Airdrop, right mouse click
- TouchScreen not work!
- Ensure to edit the **config.plist** and add valid  **PlatformInfo Generic** and **SMBIOS** values

## Misc after install:
- [Enable HiDPI](https://github.com/xzhih/one-key-hidpi) :
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"
```

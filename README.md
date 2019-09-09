# Honor-Magicbook
Honor-Magicbook i5-8250u 14'' Hackintosh

[English](README.md) | [中文](README_CN.md)

## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Huawei Honor Magicbook      |
| Processor           | Intel Core i5-8250U Processor     |
| Memory              | 8 GB 2133 MHz DDR3              |
| Hard Disk           | SanDisk SD9SN8W256G1027 SATA    |
| Integrated Graphics | Intel UHD Graphics 620 2048 MB                     |
| Sound Card          | Realtek ALC256           |
| Camera          | hm1091_techfront          |
| Wireless Card       | BCM94352Z                        |
| Touchpad | ELAN2203 |


## What's Working

- Integrated Graphics 
    - Brightness control shortcut (Clover Patchs rename _Q01 &_Q02 and add [SSDT-BrightKey-Magicbook.aml](EFI/CLOVER/ACPI/patched) ) 
- Wireless Card
    - Need to replace the wireless network card
- Touchpad
- Camera
- Realtek ALC256
    - The microphone and headphones are normal, the speaker sound has been fixed using the self-compiled `AppleALC`, but the speaker sound becomes smaller after using the built-in microphone
, you need to connect the headphones and then pull out to make a sound, the reason is unknown
- Monitor
    - Need to re-open after hibernation to light up the monitor
  

## What's not Working

- Fingerprint sensor
- MX150 graphic car
    - Have used [SSDT-Disable_DGPU](EFI/CLOVER/ACPI/patched) to disable it in order to save power

## Donate

> If you find this project useful, you can buy author a glass of juice 🍹

<details>
  <summary>Alipay & Wechat</summary>
    
  <img src="https://cdn.lhjmmc.cn/alipay.jpg" width="300px"  />
  <img src="https://cdn.lhjmmc.cn/wx.jpg" width="350px" />
</details>

# Device tree for Xiaomi 12T (plato) - MT6895
--------------------------------------------
### Files from: `22071212AG` - SP1A.210812.016 - V13.0.7.0.SLQIDXM - `plato` - MediaTek Dimensity 8100 Ultra

## Specs: [Xiaomi 12T](https://www.devicespecifications.com/en/model/9dcb5abd)

## Status
   - [dimap2000](https://4pda.to/forum/index.php?showuser=10698781) user 4pda Testing
   - Starting - enc_dec; touch; vibrator working
   - [TWRP Pictures from dimap2000](https://4pda.to/forum/index.php?act=findpost&pid=121017757&anchor=Spoil-121017757-1)

<details><summary>TWRP Pictures - Click to open</summary>
<p>

![TWRP Menu](https://github.com/lopestom/twrp_device_xiaomi_plato/releases/download/TWP3.7.0_12/IMG20230221195841.jpg)

![TWRP decrypting](https://github.com/lopestom/twrp_device_xiaomi_plato/releases/download/TWP3.7.0_12/IMG20230221200057.jpg)

![TWRP Install Zip](https://github.com/lopestom/twrp_device_xiaomi_plato/releases/download/TWP3.7.0_12/IMG20230221200121.jpg)
</p>
</details>

### Building
```
source build/envsetup.sh
lunch twrp_plato-eng
mka vendorbootimage
```

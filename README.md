# Device tree for Xiaomi 12T (plato) - MT6895
--------------------------------------------
### Files from: `22071212AG` - SP1A.210812.016 - V14.0.1.0.TLQIDXM - `plato` - MediaTek Dimensity 8100 Ultra

** Indonesian Version **

## Specs: [Xiaomi 12T](https://www.devicespecifications.com/en/model/9dcb5abd)

## Status
   - [Samatulli](https://4pda.to/forum/index.php?showuser=4996511) user 4pda Testing
   - Starting - enc_dec; touch; vibrator working
   - [TWRP Pictures from dimap2000](https://)


#### These DT have some different informations and need compile new TWRP for MIUI14.




<details><summary>TWRP Pictures - Click to open</summary>
<p>

![TWRP Menu](https://github.com/lopestom/)

![TWRP decrypting](https://github.com/lopestom/)

![TWRP Install Zip](https://github.com/lopestom/)
</p>
</details>

### Building
```
source build/envsetup.sh
lunch twrp_plato-eng
mka vendorbootimage
```

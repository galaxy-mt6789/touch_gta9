# Modules
/vendor/lib/modules/jdchipset.ko
/vendor/lib/modules/touch_common.ko

# Firmware
/vendor/firmware/jd9366tc_xx_hkc_firmware.bin
/vendor/firmware/jd9366tc_xx_hkc_ito.txt

# Insmod
insmod /vendor/lib/modules/touch_common.ko
insmod /vendor/lib/modules/jdchipset.ko

# vendor_boot Modules
/vendor_boot/lib/modules/lcd_default_mipi_fhd_video.ko
/vendor_boot/lib/modules/lcd_jd9366tc_xx_hkc_video.ko
/vendor_boot/lib/modules/mtk_panel_ext.ko
/vendor_boot/lib/modules/panel-bias.ko
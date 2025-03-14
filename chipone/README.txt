# Modules
/vendor/lib/modules/chipone.ko
/vendor/lib/modules/touch_common.ko

# Firmware
/vendor/firmware/nl9951_gx_boe.bin

# Insmod
insmod /vendor/lib/modules/touch_common.ko
insmod /vendor/lib/modules/chipone.ko
insmod /lib/modules/mtk_panel_ext.ko
insmod /lib/modules/panel-bias.ko
insmod /lib/modules/lcd_default_mipi_fhd_video.ko
insmod /lib/modules/lcd_nl9951_gx_boe_video.ko

# vendor_boot Modules
/vendor_boot/lib/modules/lcd_default_mipi_fhd_video.ko
/vendor_boot/lib/modules/lcd_nl9951_gx_boe_video.ko
/vendor_boot/lib/modules/mtk_panel_ext.ko
/vendor_boot/lib/modules/panel-bias.ko
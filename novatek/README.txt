# Modules
/vendor/lib/modules/novatek.ko
/vendor/lib/modules/touch_common.ko

# Firmware
/vendor/hardware/nt36523d_lc_hsd_firmware.bin
/vendor/firmware/nt36523d_lc_hsd_mpfw.bin

# Insmod
insmod /vendor/lib/modules/touch_common.ko
insmod /vendor/lib/modules/novatek.ko
insmod /lib/modules/mtk_panel_ext.ko
insmod /lib/modules/panel-bias.ko
insmod /lib/modules/lcd_default_mipi_fhd_video.ko
insmod /lib/modules/lcd_nt36523d_lc_hsd_video.ko

# vendor_boot Modules
/vendor_boot/lib/modules/lcd_default_mipi_fhd_video.ko
/vendor_boot/lib/modules/lcd_nt36523d_lc_hsd_video.ko
/vendor_boot/lib/modules/mtk_panel_ext.ko
/vendor_boot/lib/modules/panel-bias.ko
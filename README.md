# Rpi4_OpenWrt_Config
My config for OpenWRT on RaspberryPi 4

Packages to be installed
opkg install kmod-usb-net-rtl8152 kmod-mt76x2u r8152-firmware kmod-usb-net-rndis kmod-usb-net-cdc-ncm kmod-usb-net-huawei-cdc-ncm kmod-usb-net-cdc-eem kmod-usb-net-cdc-ether kmod-usb-net-cdc-subset kmod-nls-base kmod-usb-core kmod-usb-net kmod-usb-net-cdc-ether kmod-usb2 kmod-usb-net-ipheth usbmuxd libimobiledevice usbutils

For configuration folow the official documentation.
The config is as follows:
LAN IP: **10.0.0.1**
Integrated Wireless card: WWAN
Integrated lan Port: WAN
Upper 2.0 USB port: USB
Lower 2.0 USB port: USB NIC (LAN)
Upper 3.0 USB port: Wifi hotspot
Lower 3.0 USB port: USB Tetering (Smartphone)

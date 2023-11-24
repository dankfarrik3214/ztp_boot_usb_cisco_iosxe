# Ztp boot usb cisco iosxe

Bootable USB stick for device with Cisco IOS-XE for ZTP.

Can be used with: 
- [IOS XE ZTP](https://github.com/dankfarrik3214/ios_xe_ztp) - This script can be used with the ZTP process of Cisco IOS-XE.

## Requirements

- **Cisco IOS-XE device**
- **DHCP server**
- **ZTP Server**
- **ZTP python file**

## Example

If you have a Cisco IOS-XE device that needs to receive it's DHCP options via another VLAN then 1. And it's not connected to a Cisco device which can propogate a different vlan. Then you can use this USB script to:

- **Get DHCP different VLAN**
- **Fetch ZTP script**
- **Run Guest shell**
- **Run ztp python file**
- **Destory Guest shell**

## Usage

Save the ciscortr.cfg on a usb fat32 drive and put it in a Cisco IOS-XE device. Make sure there is not a configuration present on the device itself and reboot it with the stick inserted.
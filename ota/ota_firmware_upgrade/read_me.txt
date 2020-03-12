-------------------------------------------------------------------------------------------------------------
Bluetooth Over the Air (OTA) Firmware Upgrade Application
--------------------------------------------------------------------------------------------------------------

 This is a snip application that demonstrates how to link with the
 OTA FW Upgrade library.  The application responsibility is to
 publish OTA FW upgrade service in the GATT database and to pass
 stack callbacks to the library.
 See ota_fw_upgrade.c file for the  description of the OTA protocol.
 (typically in /wiced_btsdk/libraries/wiced-lib-ota/btsdk-ota/COMPONENT_fw_upgrade_lib)
 This version of the OTA firmware upgrade relies on the Bluetooth
 standard security.  The application also can use ECC cryptography
 to validate the image. It is expected that full implementation
 will use application level verification that downloaded firmware is
 for this Product ID and that the image has not been tampered with.

 Features demonstrated
  - OTA Firmware Upgrade

 To use OTA, get the OTA peer applications from "Utils OTA Peer Apps" app if using IDE,
 or git clone repo named "btsdk-peer-apps-ota" if using command line and see
 <app-repo>\ota_firmware_upgrade\readme.txt

 Project Settings
 ----------------
 Application specific project settings are as below -
 OTA_SEC_FW_UPGRADE
    This option enables secure OTA
----------------------------------------------------------------------------------------------------------------------------

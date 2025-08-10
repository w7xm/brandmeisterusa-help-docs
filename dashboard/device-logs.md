# Device Logs

Displays the logs from devices (hotspots, repeaters) connecting to any of the BrandMeister Servers within the last 24 hours. The logs shown are for any activities related to authentication, verification, wrong configuration and verified statues. The logs will show the last 24 hours. No logs indicate no connection attempts, issues and or is beyond the 24 hours.&#x20;

### Access Device Logs

The Device Logs is located on the left menu under the My Devices as a seperate linked labled "Device Logs"

![](<../.gitbook/assets/image (111).png>)

The logs will display for any devices you may have including Hotspots and Repeaters where you are either the trustee and or Sysop of a repeater which has Read Status uneabled for the user of the repeater.&#x20;

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

### Frequently Asked Questions

<details>

<summary>Why am I not seeing any logs?</summary>

If no logs appear this could be due to one of the following reasons:

* The master server is seeing no connection attempts. Check your device configuration.
* It has been more than 24 hours since the device connected. Logs are only displayed for activity within the last 24 hours.
* Or simply means no issues are reported.

</details>

<details>

<summary>What does it mean when it says Verification Failed?</summary>

This error means your Radio ID and Your Call Sign (Radio Alias) which was set on your device is not matching with what you have registered with Radio ID. Check your Radio ID and Call sign.

</details>

<details>

<summary>What does it mean when it says authentication failed (incorrect password)?</summary>

This means the device password has a wrong password. Check your device and or add/change your device password on selfcare and then enter that same password in your device.

</details>

<details>

<summary>What does it mean when it says Configuration Failed?</summary>

This indicates some configuration issues with your device.

* Check your Lat and Long have proper values
* Check your Frequenices are correct. If using a simplex hotspot these should be set to the same frequencies.
* If using a duplex hotspot the frequencies should be different (TX/RX)
* Your Device is not an RF Based Device if connecting via MMDVM Protocol

</details>

<details>

<summary>I made the change/fix but still not seeing it in the logs?</summary>

Allow between 10 to 30 seconds for the logs to refresh for the activity to show on the Device Logs page/table.

</details>

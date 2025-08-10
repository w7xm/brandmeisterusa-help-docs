# MMDVM

{% tabs %}
{% tab title="Quick Version" %}
### Setup your Pi-Star Configuration - Quick Version.

1.) Access the Pi-Star Dashboard - [http://pi-star.local](http://pi-star.local) or IP

2.) Click on Configuration Tab (top right)

3.) Enter Password (Default is all lowercase:   username: pi-star | password: raspberry)

4.) Under Control Software Section:

* Controller Software:   select MMDVMHost
* Controller Mode:         select Duplex Repeater.&#x20;
* Click **Apply Changes**. (The modem will reset after you click Apply Changes each time and this is normal).

5.) Under MMDVMHost Configuration:

* DMR Mode:                  enable "DMR Mode" by click the toggle button.&#x20;
* Click **Apply Changes.**&#x20;

6.) Under General Configuration:

* Node Callsign:               enter Repeater Call Sign&#x20;
* CCS7/DMRI ID:              enter your Repeater DMR ID - 6 Digit ID
* Radio Frequency RX:    Enter Repeater Receive Frequency
* Radio Frequency TX:     Enter Repeater Transmit Frequency
* Radio/Modem Type:     Choose your modem
* Node Type:                     Select Public, unless you want to keep it as a private node/repeater.
* System Time Zone:       Select System Time Zone for your location.&#x20;
* Click **Apply Changes.**&#x20;

7.) Under DMR Configuration:

* DMR Master:                 Select Preferred Master Server (3102, 3103, 3104, etc).
* Hotspot Security:         Enter the Device Password. See Setting Repeater/Device Password.
* DMR ESSID:                   ESSID is not supported for Repeaters using 6-digit Radio IDs.
* DMR Color Code:          Select Color Code
* Click **Apply Changes.**

8.) Click on Dashboard on the top menu. This will take you to the main dashboard and notice on the left side under Network Status, DMR Net should be lit green if all went well.&#x20;
{% endtab %}

{% tab title="Step by Step" %}
Coming Soon.
{% endtab %}
{% endtabs %}

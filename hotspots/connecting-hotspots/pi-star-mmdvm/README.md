---
description: >-
  General instructions on how to setup a RF Based MMDVM Hotspot using Pi-Star
  using MMDVMHost Mode to a BrandMeister Server. This is assuming a new hotspot
  being configured.
---

# Pi-Star (MMDVM)

{% hint style="info" %}
Please make sure you have updated and are on the latest version of Pi-Star software. By doing so will make it easier to provide support by both of the support teams (Pi-Star and Brandmeister).&#x20;
{% endhint %}

{% tabs %}
{% tab title="Detailed Step by Step Version" %}
### Setup your Pi-Star Configuration

**1.)** Start by opening your preferred web browser and enter [http://pi-star.local](http://pi-star.local) or http://pi-star or the IP address of the hotspot if you know it. You will be then presented with the following page (Dashboard). It is assumed you have already setup your Wi-Fi configurations and will not be discussed in this setup step by step you can refer to a helpful website for detailed setup - [Amateur Radio Notes: Pi-Star.](https://amateurradionotes.com/pi-star.htm)

![Pi-Star Dashboard](<../../../.gitbook/assets/image (117).png>)

{% hint style="danger" %}
Notice we indicate after each section/step to click on the "**Apply Changes"**. This is important to do as this will setup the Pi-Star software to allow for the next steps to be performed. Some will not display until a previous step/action is applied to the Pi-Star Software.&#x20;
{% endhint %}

**2.)** Next click on ["Configuration"](http://pi-star.local/admin/configure.php) link at the top right of the dashboard. This will take you to the configuration options for the Pi-Star Software/Hotspot.

![Top Right navigation section where you can find the Configuration Link.](<../../../.gitbook/assets/image (10).png>)

**3.)** In the Control Software section is where you can set the type of Controller Mode the hotspot will operate as, either simplex or duplex. Select the best choice related to the type of MMDVM board you are using and then click save if needing to change to Duplex as Simplex is the default setting or can skip clicking apply since it is defaulted to Simplex and move to the next step.



![Control Software section in the Configuration Page.](<../../../.gitbook/assets/image (112).png>)

**4.)** Next we will need to enable the DMR Mode under the MMDVMHost Configuration section by click on the toggle switch next to DMR Mode. Click **"Apply Changes"** and wait for the Pi-Star software to restart and enable the option. Don't worry about the other options here. You are more than welcome to explore the other modes to enable but for this setup we will only focus on DMR and connecting to a BrandMeister Server.&#x20;



![MMDVMHost Configuration Section, Enabling DMR Mode.](<../../../.gitbook/assets/image (84).png>)

**5.)** Next scroll down to the General Configuration section and enter in the following information below. The ones mentioned are those for recommended to ensure there is a value set.



![General Configuration Screen under Configuration Page.](<../../../.gitbook/assets/image (122).png>)

* **Node Callsign:** - This is your Amateur Radio Call Sign. Only enter your call sign here.
* **CSS7/DMR ID:** - This is your 7-digit ID which was issued to you from RadioID.net. If you need to get one [click here on getting a 7-digit ID](http://radioid.net) from RadioID.net.
* **Radio Frequency:** Enter the simplex frequency here. If you have a duplex an additional box will be present to provide RX and TX frequencies (this is only shown if in duplex mode).
* **Latitude:** - You can leave this as is or enter your Latitude.
* **Longitude:** - You can leave this as is or enter your Longitude.&#x20;
* **Town:** Enter your City/Town.&#x20;
* **Country:** Enter Your Country
* **Radio/Modem Type:** Choose the modem you are using. Refer to the vendor/manufacture you obtained your device from.&#x20;
* **Node Type:** Choose private if you are only using this hotspot yourself and not sharing with any other users. Your 7-digit ID you entered in the CSS7/DMR ID must match to the radio. If you have more than one 7-digit ID and want to allow access then choose Public.
* **DMR Access List:** If you selected Public in the Node Type then enter in the 7-digit Radio IDs you wish to be able to use  your hotspot using a comma to separate each one. _For Example: 1234567, 2345678, 3456789._ If you have chosen Private than this box wont allow you enter and can leave it blank.&#x20;
* **APRS Host Enable:** Leave this as default (off)
* **APRS Host:** Leave this as default (rotate.aprs2.net)
* **System Time Zone:** Select your time zone from the drop down.
* **Dashboard Language:** Choose your preferred language.&#x20;

When completed make sure you click on **"Apply Changes"** so the changes are saved. This will take a few moments and will return you to the configuration page when done.&#x20;

**6.)** Next scroll down to the DMR Configuration section and enter the following information.

![DMR Configuration using MMDVM Host](<../../../.gitbook/assets/image (69).png>)

* **DMR Master:**  Select the BrandMeister Server of choice. In this example we will use BM 3103 United States.
* **BM Hotspot Security:** Enter your Hotspot Security Password you entered in on BrandMeister Selfcare for the Radio ID used for the hotspot. [Click here to setup a hotspot security password if you have not done so. ](../../../dashboard/hotspot-security.md)
* **BrandMeister Network ESSID** (or might see DMR ESSID): This allows you to select an alias for the hotspot. For your first hotspot you can choose 01 or leave as none. If you plan to have more than one hotspot then you should select 01 or any number from 01 to 99. Each hotspot must have a unique ID and ESSIDs allow for this work properly on the network.
* **DMR Color Code:** Choose your desired Color Code for the hotspot.

Finally click on "**Apply Changes"** and wait for the Pi-Software to restart and enable the configurations.&#x20;

{% hint style="info" %}
You are probably asking why can't I use DMRGateway as an option? You are more than welcome to use it but take note BrandMeister Support team will not provide support for those who use DMRGateway as it can be complex and may have many options for configuration. We recommend referring to the [Pi-Star Support options ](pi-star-support-options.md)for a list of sources if you choose to use DMRGateway for support on configuration and other issues you  may run into.&#x20;
{% endhint %}

**7.)** Finally click on the [Dashboard](http://pi-star.local) Link at the top navigation of the hotspot to show the dashboard. Take notice on the left side indicators. If all has gone according to plan and followed the setups in this document you should see a Green DMR Net under the Network Status. It means you are ready to operate your hotspot with your DMR Radio.&#x20;

![Network Status Indicators.](<../../../.gitbook/assets/image (90).png>)

If you see a **yellow DMR Net**, this indicates the hotspot is not connecting and can be one of many issues listed below:

![Network Status Indictors - If Yellow means connection issue. ](<../../../.gitbook/assets/image (46).png>)

* [ ] Your hotspot security password maybe incorrect. Check to make sure what you entered in the BM Selfcare and your hotspot are the same. If using a copy and paste you might have copied an extra character. Might try typing it in manually.&#x20;
* [ ] Your hotspot password is to long or complex. Passwords should be 20 characters or less and avoid using special characters.&#x20;
* [ ] You did not enable Hotspot Security and skipped that portion of the steps above. See [HotSpot Security](../../../dashboard/hotspot-security.md) on setting one up.&#x20;
* [ ] GPS Information (Lat and Long) is not correct or in the correct format. Typically missing a decimal point. \


If you see a **red DMR Net** it means some other configuration is not set properly.&#x20;

![](<../../../.gitbook/assets/image (94).png>)

* [ ] If using DMR Gateway make sure the "Brandmeister network Enable" is turned on under the DMR Configuration section.
* [ ] Check to make sure you are proper network connection.
* [ ] Recommend going back through these steps and or post your question to the [Pi-Star Forums](https://forum.pistar.uk/) for further support with Pi-Star or refer to [Amateur Radio Notes: Pi-Star](https://amateurradionotes.com/pi-star.htm) for a detailed documentation about Pi-Star.&#x20;

**8.)** Congratulations on reaching this step, If you got a green DMR Net indicator you are done. You can now operate your hotspot on BrandMeister using your DMR Radio. Enjoy!
{% endtab %}

{% tab title="Quick Version" %}
### Setup your Pi-Star Configuration - Quick Version.

1.) Access the Pi-Star Dashboard - [http://pi-star.local](http://pi-star.local) or IP

2.) Click on Configuration Tab (top right)

3.) Enter Password (Default is all lowercase:   username: pi-star | password: raspberry)

4.) Under Control Software Section:

* select MMDVMHost
* select if you have a simplex or duplex hotpsot.&#x20;
* Click **Apply Changes**. (The modem will reset after you click Apply Changes each time and this is normal).

5.) Under MMDVMHost Configuration:

* enable "DMR Mode" by click the toggle button.&#x20;
* Click **Apply Changes.**&#x20;

6.) Under General Configuration:

* enter Node Call Sign, DMR ID (only 7 digit here),&#x20;
* the Frequency (for example 431.020),&#x20;
* the Radio/Modem Type (choose your modem),&#x20;
* and then System Time Zone for your location.&#x20;
* Click **Apply Changes.**&#x20;

7.) Under DMR Configuration:

* under DMR Master (first drop down) select the Master server you wish to connect to. (USA has the option of 3102 - Dallas, 3103 - San Jose or 3104 - Chicago)
* enter your BrandMeister hotspot Security Password (if you need to setup a hotspot security password or need to reset it see [Hotspot Security instructions](../../../dashboard/hotspot-security.md)),&#x20;
* then under BrandMeister Network ESSID select the alias ID you wish to use (01 through 99) if first hotspot use 01.&#x20;
* Click **Apply Changes.**

8.) Click on Dashboard on the top menu. This will take you to the main dashboard and notice on the left side under Network Status, DMR Net should be lit green if all went well.&#x20;
{% endtab %}
{% endtabs %}

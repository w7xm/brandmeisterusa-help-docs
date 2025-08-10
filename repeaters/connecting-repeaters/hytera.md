---
description: >-
  General steps on connecting a Hytera Commercial DMR Repeater to BrandMeister
  Server
---

# Hytera

{% hint style="info" %}
For a list of supported Hytera Repeaters and the firmware versions please visit the Hytera Page under Repeaters on the BrandMeister Wiki at[ http://wiki.brandmeister.network](https://wiki.brandmeister.network/index.php/Hytera/Repeaters)
{% endhint %}

## Configuration Information

1.) Open Hytera CPS (Customer Programming Software).

2.) Open Common Section (folder) in CPS and navigate to Common | Setting and double clicking on it.&#x20;

![Common Folder in Hytera CPS.](<../../.gitbook/assets/image (4).png>)

3.) You will now see the Basic Screen as shown below. The screen may vary on version and model number of your repeater.&#x20;

* **Radio Alias**:  Enter Repeater Call Sign.&#x20;
  * Note: Please enter Call Sign first and then any text following if you wish to add more info such as location or name. You can use a Dash or space to separate the additional information -- Example:  _W1AW - City Name_    or     _W1AW-2_

![Basic Settings Screen under Common | Setting.](<../../.gitbook/assets/image (102).png>)

4.) Navigate to the Conventional |  General Setting and then double click on Network.&#x20;

![Network Section under Conventional Folder/Section.](<../../.gitbook/assets/image (74).png>)

5.) Under the Basic Setting set your network configuration by either choosing DHCP or enter a static IP and DNS Information.&#x20;

![](<../../.gitbook/assets/image (23).png>)

6.) Next scroll down to the IP Connect Configuration. \
\
Enter the highlighted information for your repeater setup:‌

* **Repeater Type:** Select Slave
* **Jitter Buffer Length**: Enter a value of 8
* **Master UDP Port**: Enter a value of 50000
* **IP Connect Net. UDP Port**: Enter a value of 50000
* **Voice & Data Service**: Make sure this is Selected (check mark showing)
* **Voice & Data UPD Port**: Enter a value of 50001
* **RDAC Service:** Make sure this is Selected (check mark showing)
* **RDAC UDP Port:** Enter a value of 50002
* **Master Domain Name:** If using domain name select this (check mark showing). **Note** by using this make sure you have an available/relieable DNS Server at the site of the repeater otherwise the domain might not resolve to the IP address properly. If not sure,  uncheckd the box "Master Domain Name On/Off" and enter the IP Address of the master server.&#x20;
* **Domain Names:** Enter the domain of the master to connect to if using Domain Name for the master. See [List of Masters](https://app.gitbook.com/@w7xm/s/brandmeister-usa/~/drafts/-MbhhllPATJzqMzICe2F/repeaters/connecting-repeaters/hytera#list-of-master-servers)​

When completed click Close.

![IP Connect Configuration Section.](<../../.gitbook/assets/image (62).png>)

7.) Navigate to Conventional | Digital Comment Folder and double click on Basic.

![Basic Setttings under Digital Common.](<../../.gitbook/assets/image (88).png>)

8.) In the Basic Setting Screen enter your 6-digit Radio ID (Repeater ID). When completed click close.

![](<../../.gitbook/assets/image (8).png>)

9.) Navigate to the Conventional | Channel Folder and then Digital Channel. You should see at least one channel in this folder. Double click the channel. (The number of channels may vary depending on your situation).

![](<../../.gitbook/assets/image (118).png>)

10.) In the channel setup screen (Below) make sure you select under the Digital IP Multi-Site Connect select **Slot 1 & Slot 2** to enable the repeater to connect to the master server.  All other information is up to you to configure depending on your choices and frequency information. When done click close.&#x20;

![](<../../.gitbook/assets/image (22).png>)

11.) Navigate to Conventional | Zone and double click on Zone 1 or the zone you wish to place the channel. (A channel must exist in a zone in order for the repeater to select/use it).

![](<../../.gitbook/assets/image (96).png>)

12.) Verify in the Members section the channel you are using is in the members section on the right side. When done click close.&#x20;

![](<../../.gitbook/assets/image (25).png>)

13.) Navigate to Conventional | General Settings and double click on Setting.

![](<../../.gitbook/assets/image (123).png>)

14.) Scroll down to the Power On section and select the power on channel. This is important if you are using a mixed mode. But if only Digital mode select the Digital Channel which will be defaulted when powered on (you could also have multiple digital, analog channels depending on your situation).  Click close when completed.&#x20;

![](<../../.gitbook/assets/image (99).png>)

15.) Navigate to Conventional | General Setting and double click on Accessories.

![](<../../.gitbook/assets/image (45).png>)

16.) Scroll down to the Priority control section and set the following as shown below.&#x20;

* **Path Priority:**                          Set to Repeat Request.
* **Repeat Request Priority:**       Set this to IP Connect Repeating.

![](<../../.gitbook/assets/image (101).png>)

17.) Navigate to  Conventional | General Setting and double click CWID.

![](<../../.gitbook/assets/image (27).png>)

18.) Enter your Call sign and verify the TX Interval is at 10 Minutes.

![](<../../.gitbook/assets/image (51).png>)



19.) Write the code plug to your repeater. Your repeater should now connect to the master server.

20.) Verify connection by going to the BrandMeister website at [http://brandmeister.network](https://brandmeister.network/?page=repeaters) and click on repeaters and search for your repeater by the 6-digit Radio ID or by the Callsign of the Repeater.&#x20;

21.) Once all steps are satisfied above you can request for sysop rights to be assigned in the BrandMeister Sysop Dashboard by submitting a ticket by visiting [http://support.brandmeister.network](https://support.brandmeister.network/servicedesk/customer/portal/3/create/96) (if you click the link it will take you to the form to fill out) and provide your 6-Digit Repeater ID, the master server you are connected to and your 7-digit ID and Call Sign. \
\
Please be the owner or trustee of the assigned Repeater ID/Call Sign when sending the request and of course have a BrandMeister Account (if you don't have an account please see [Register for an account](../../dashboard/register-for-an-account.md#register-for-an-account)). We will verify the information in the FCC Database and will only provide sysop rights to the repeater owner/trustee. Once the owner/trustee is assigned they may in turn assign other sysops to the repeater as they desire.&#x20;

22.) Once you have been provided Sysop Rights to the repeater you may reference the [Sysop Dashboard ](../sysop-dashboard/)guide for features and other information.&#x20;

### List of Master Servers

There are over 45 Master Servers Available to connect to around the world. The USA Maintains three Master Servers distributed through out the country.&#x20;

| ID   | Location             | Domain            | IP             |
| ---- | -------------------- | ----------------- | -------------- |
| 3102 | Dallas, Texas        | 3102.repeater.net | 74.91.114.19   |
| 3103 | San Jose, California | 3103.repeater.net | 74.91.118.251  |
| 3104 | Chicago, Illinois    | 3104.repeater.net | 162.248.88.117 |

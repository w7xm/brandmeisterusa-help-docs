---
description: >-
  General steps on connecting a Motorola Commerical DMR Repeater to BrandMeister
  server.
---

# Motorola

{% hint style="info" %}
For a list of supported Motorola Repeaters and the firmware versions please visit the Motorola Page under Repeaters on the BrandMeister Wiki at [http://wiki.brandmiester.network](https://wiki.brandmeister.network/index.php/Motorola/Repeaters)
{% endhint %}

### Configuration Information

{% tabs %}
{% tab title="Quick Version" %}
1. Open Motorola CPS (Customer Programming Software).\

2.  Open the General section and then **General Settings section** in CPS and set the following information:\


    1. **Radio Alias:**              Set it to call sign. \
       Note: Please enter Call Sign first and then any text following if you wish to add more info such as location or name. You can use a Dash or space to separate the additional information -- Example:  _W1AW - City Name_    or     _W1AW-2_
    2. **Radio ID:**               Set to the assigned 6-digit Radio ID


3.  Under the **General Settings section** in CPS scroll to the **CWID** section and set your CW ID information.\


    1. **ID:**                       Set it to call sign
    2. **TX interval:**       Set this to 10 (ten minutes)


4. Open the General section in CPS and set the following configuration item in **Link Establishment section:**\

   1. **Link Type:**                     Set to PEER
   2. **Authentication Key:**     Enter the Auth Key you set in BM Device Password - See [Device Password](../sysop-dashboard/device-password.md) if you have not set this.  (This is a hex value, 40 chars or less). \

   3. **Master IP:**                      Enter the preferred IP Address of the [Master Server](motorola.md#list-of-master-servers) you wish to connect to.&#x20;
   4. **Master UDP Port:**         Enter 55000 (not needed but can be set to this)
   5. **UDP Port:**                       Enter 55000 \
      \

5. Open the **Zone/Channel Assignment section** and then click the zone folder. Click on the channel to be used and verify the following configuration is set at minimum. Other options are up to you on how you are configurating your repeater:\

   1. **IP Site Connect (Repeater):**           Set to Slot 1 & Slot 2
   2. **Repeater RSSI Threshold:**             Set to -100 or higher\

6. Write the code plug to your repeater and your repeater should now connect to the master server of choice.&#x20;
{% endtab %}

{% tab title="CPS 2.0 Step by Step Version" %}
1\. Open Motorola CPS (Customer Programming Software).\


![](<../../.gitbook/assets/image (79).png>)

2\. Open the General section and then **General Settings section** in CPS and set the following information:

![](<../../.gitbook/assets/image (52).png>)

1. **Radio Alias:**              Set it to call sign. \
   Note: Please enter Call Sign first and then any text following if you wish to add more info such as location or name. You can use a Dash or space to separate the additional information -- Example:  _W1AW - City Name_    or     _W1AW-2_
2. **Radio ID:**               Set to the assigned 6-digit Radio ID

3\. Under the **General Settings section** in CPS scroll to the **CWID** section and set your CW ID information.

![](<../../.gitbook/assets/image (37).png>)

1. **ID:**                       Set it to call sign
2. **TX interval:**       Set this to 10 (ten minutes)

\
4\. Open the General section in CPS and set the following configuration item in **Link Establishment section:**

![](<../../.gitbook/assets/image (36).png>)

1. **Link Type:**                     Set to PEER
2. **Authentication Key:**     Enter the Auth Key you set in BM Device Password - See [Device Password](../sysop-dashboard/device-password.md) if you have not set this.  (This is a hex value, 40 chars or less).&#x20;
3. **Master IP:**                      Enter the preferred IP Address of the [Master Server](motorola.md#list-of-master-servers) you wish to connect to.&#x20;
4. **Master UDP Port:**         Enter 55000 (not needed but can be set to this)
5. **UDP Port:**                       Enter 55000&#x20;



5\. Open the **Zone/Channel Assignment section** and then click the zone folder. Click on the channel to edit and then click on the edit icon (pencil).

![](<../../.gitbook/assets/image (7).png>)

Set the following items below for the channel when in edit mode under the General Section of the channel.

![](<../../.gitbook/assets/image (19).png>)

1. **IP Site Connect (Repeater):**           Set to Slot 1 & Slot 2
2. **Repeater RSSI Threshold:**             Set to -100 or higher

Under the **RX/TX section** enter information for your area/repeater.

![](<../../.gitbook/assets/image (77).png>)

1. Enter your RX and TX Frequency.&#x20;
2. Set any other settings as desired.&#x20;

6\. Write the code plug to your repeater and your repeater should now connect to the master server.&#x20;
{% endtab %}
{% endtabs %}

### Verify Connection and Sysop Permissions

1. Verify connection by going to the BrandMeister website at [http://brandmeister.network](http://brandmeister.network) and click on repeaters and search for your repeater by the 6-digit Radio ID or by the Callsign of the Repeater.\

2. Once all steps are satisfied above you can request for sysop rights to be assigned in the BrandMeister Sysop Dashboard by submitting a ticket by visiting [http://support.brandmeister.network](https://support.brandmeister.network/servicedesk/customer/portal/3/create/96) (if you click the link it will take you to the form to fill out) and provide your 6-Digit Repeater ID, the master server you are connected to and your 7-digit ID and Call Sign. \
   \
   Please be the owner or trustee of the assigned Repeater ID/Call Sign when sending the request and of course have a BrandMeister Account (if you don't have an account please see [Register for an account](../../dashboard/register-for-an-account.md#register-for-an-account)). We will verify the information in the FCC Database and will only provide sysop rights to the repeater owner/trustee. Once the owner/trustee is assigned they may in turn assign other sysops to the repeater as they desire. \

3. Once you have been provided Sysop Rights to the repeater you may reference the [Sysop Dashboard ](../sysop-dashboard/)guide for features and other information.&#x20;

### List of Master Servers

There are over 45 Master Servers Available to connect to around the world. The USA Maintains three Master Servers distributed through out the country.&#x20;

| ID   | Location             | Domain            | IP             |
| ---- | -------------------- | ----------------- | -------------- |
| 3102 | Dallas, Texas        | 3102.repeater.net | 74.91.114.19   |
| 3103 | San Jose, California | 3103.repeater.net | 74.91.118.251  |
| 3104 | Chicago, Illinois    | 3104.repeater.net | 162.248.88.117 |

To see a list of all master repeaters visit [http://brandmeister.network](https://brandmeister.network/?page=masters) and click on the Masters link on the left navigation. &#x20;

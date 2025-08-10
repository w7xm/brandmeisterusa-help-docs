---
description: MMDVM Based Repeaters now require device passwords to be set.
---

# Device Password

{% tabs %}
{% tab title="Motorola Based Repeaters" %}
Motorola Based Repeaters Authentication Keys are a hex value (0-9,A-F) and must be 16 characters or less in length. (As of Jan 1, 2022 we are asking all Motorola Repeaters to set their authentication key and device password).&#x20;

1.) Go to "My Devices" in the BrandMeister Dashboard/Selfcare and select the repeater (repeater ID link) you wish to set the password.

2.) Scroll down to the bottom and located "Device Password"

![](<../../.gitbook/assets/image (76).png>)

3.) Enter a HEX Value password. It should be less than 40 characters and a HEX value. Remember this password as you will need to enter this into your repeater password section.

4.) When you are done **click save password**. The password will not display in the field after saving and won't be able to see it after you click save. You may at any time return and set a new password if you forgot it.

5.) Now enter the password into your repeater under the Authentication Key under General -> Link Establishment section in the CPS.

6.) Save the code plug and then load it into your repeater.&#x20;

6.) If all went well your repeater should now connect.&#x20;
{% endtab %}

{% tab title="MMDVM Based Repeaters" %}
MDVM Based Repeaters are required to set their passwords related to each of the Repeater IDs (6-digits only).

1.) Go to "My Devices" and select the repeater you wish to set the password.

2.) Scroll down to the bottom and located "Device Password"

![](<../../.gitbook/assets/image (76).png>)

3.) Enter a password. It should be less than 20 characters and no special characters. Remember this password as you will need to enter this into your repeater password section.

4.) When you are done **click save password**. The password will not display in the field after saving and wont be able to see it after you click save. You may at anytime return and set a new password if you forgot it.

5.) Now enter the password into your repeater. In Pi-star this is located under configuration and DMR Configuration Section and is labeled Hotspot Security. &#x20;

6.) If all went well your repeater should now connect.&#x20;
{% endtab %}

{% tab title="Hytera Repeaters" %}
Hytera Repeaters Authentication/Passwords are not supported at this time. Leave the authentication field empty on your Hytera Repeaters.
{% endtab %}
{% endtabs %}


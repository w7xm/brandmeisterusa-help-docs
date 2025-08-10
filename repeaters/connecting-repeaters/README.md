---
description: General steps on connecting RF Based Repeaters to BrandMeister.
---

# Connecting Repeaters

### Steps to connecting a repeater to BrandMeister.

The following is the general steps to connecting a commercial based repeater currently Motorola and Hytera along with MMDVM based.  For specific settings/configurations please visit the corresponding information as noted in red with links to the individual articles.

1. **Setup your BrandMeister Dashboard account** by registering at [https://brandmeister.network](https://brandmeister.network) and click on the Register link at the top right of the page. If you already have a dashboard account you can skip to the next step. See [Register Article](../../dashboard/register-for-an-account.md#register-for-an-account) for step by step information. \

2. **Have a 6-digit Radio ID assigned** to you or your club for the repeater you wish to connect. See [https://radioID.net](https://radioid.net) to setup a radio ID for a repeater.  \

3. **Verify on RadioID.net repeater ID status** **is set to On Air /Visible.** (if was set to off air it will take 5 to 10 minutes for the information to be sent to BrandMeister. [See Set On Air Status](../set-on-air-radioid.net.md).\

4. **For MMDVM Based Repeaters** (Pi-star, MMDVMHost)&#x20;
   1. **Log into the Selfcare** Dashboard and click under My Devices and you will see your repeater ID Listed.&#x20;
   2. **Sysop Rights** - Whom ever the trustee was assigned on RadioID will have been automatically assigned sysop rights to the repeater.&#x20;
   3. **Set Device Password** - You will need to set a password for your repeater by entering it in for the selected repeater in the Device Password field. Click Save (it is normal after save to see the password field update as blank).  See [Device Password](../sysop-dashboard/device-password.md)
   4. **Add Password to your Repeater** - Enter the Device password into your Pi-Star/MMDVM Host configuration and save.&#x20;
   5. **Radio Alias Name (Call) and 6-digit Radio ID must match** on the repeater of what was registered with RadioID. If these do not match the repeater will not be allowed to connect.&#x20;
   6.  **Repeater Configuration** - If you need guidance on how to configure your repeater click on the link for detailed steps/information: [MMDVM Repeater](mmdvm.md).


5. **For Motorola or Hytera Repeaters**&#x20;
   1. **Log into the Selfcare** Dashboard and click under My Devices and will see your repeater ID Listed.&#x20;
   2. **Sysop Rights** - Whom ever the trustee was assigned on RadioID will be automatically assigned sysop rights to the repeater.
   3. **Device Password** - For Motorola repeaters you will need to set it as a HEX Value and no more than 40 Hex Characters (A-F, 0-9 -- Example a0139bfac00 or 88800002929). Hytera Repeaters is not functional at this time in regard to the authentication key.  See Set [Device Password](../sysop-dashboard/device-password.md)
   4. **Radio Alias Name (Call) and 6-digit Radio ID must match** on the repeater of what was registered with RadioID. If these do not match the repeater will not be allowed to connect.&#x20;
   5.  **Repeater Configuration** - If you need guidance on how to configure your repeater click on one of the two links for detailed steps/information: [Hytera Repeater](hytera.md) | [Motorola Repeater](motorola.md).

       \

6. **Connect your repeater** to one of the preferred master servers. Your repeater should now be connected if you followed the steps above. \

7. **Adding additional Sysops** to your repeater is done via the sysop dashboard. Click [here ](../sysop-dashboard/sysops.md)on how to add additional sysops.




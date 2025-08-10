---
description: >-
  API Manager allows for hotspots supporting the BrandMeister API Manager to
  control actions via the local hotspot dashboard such as static talk groups,
  clearing of dynamic TGs, etc.
---

# API Manager

### Generating API Key

* [ ] [Login ](https://brandmeister.network/?page=login)to Brandmeister Dashboard.&#x20;
*   [ ] Click your call sign at the top right to reveal the menu options. \


    <figure><img src="../.gitbook/assets/image (106).png" alt="" width="341"><figcaption></figcaption></figure>


* [ ] Click on "Profile Settings" as shown above.
*   [ ] Click on "API Keys" button under the Security Settings section.\


    <figure><img src="../.gitbook/assets/image (40).png" alt="" width="375"><figcaption></figcaption></figure>
*   [ ] Click on the "Add" button located top right of the screen.\


    <figure><img src="../.gitbook/assets/image (85).png" alt="" width="375"><figcaption></figcaption></figure>


*   [ ] Enter a name for the API Key. This can be the name of your hotspot for example. Click OK.\
    \


    <figure><img src="../.gitbook/assets/image (86).png" alt="" width="345"><figcaption></figcaption></figure>
*   [ ] Click the "Copy" button to copy the API Key. This will copy the key needed in a future step. You may also save this into a text editor of your choice. Click OK to exit. \




    <figure><img src="../.gitbook/assets/image (31).png" alt="" width="234"><figcaption></figcaption></figure>

### Adding API Key to Pi-Star Dashboard

* [ ] Login to your hotspot, you can use http://pi-star or http://pi-star.local or the IP address of your hotspot to access your dashboard.&#x20;
*   [ ] Click on Configuration Link at the top right. \


    <figure><img src="../.gitbook/assets/image (29).png" alt="" width="375"><figcaption></figcaption></figure>
*   [ ] Click the "Expert" link.\


    <figure><img src="../.gitbook/assets/image (113).png" alt="" width="375"><figcaption></figcaption></figure>
*   [ ] Click the "BM API" Link\


    <figure><img src="../.gitbook/assets/image (78).png" alt="" width="375"><figcaption></figcaption></figure>
*   [ ] Paste the API Key copied above into the "APIKEY" Textbox. then click "Apply changes" button to save.\


    <figure><img src="../.gitbook/assets/image (47).png" alt="" width="363"><figcaption></figcaption></figure>
* [ ] You are now setup to use the API Manager in Pi-Star Dashboard.

### Accessing the API Manager on Pi-Star

*   [ ] Click on the "Admin" link on your pi-star based hotspot.\


    <figure><img src="../.gitbook/assets/image (91).png" alt="" width="563"><figcaption></figcaption></figure>
*   [ ] You will see the following section showing current Static and Dynamic TGs (if any) and the options to add or remove static talk groups. \


    <figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>
* [ ] **Add Static TG:** Enter the TG ID in the Static Talkgroup field, next click on TS1 or TS2 radio button (if using a duplex you will see TS1 and TS2, if simplex you wont see this), then click Add radio button to add the TG and finally click on "Modify Static" button.  This will now appear under the Static TGs section.
* [ ] **Remove Static TG**: Enter the TG ID in the Static Talkgroup field, next click on TS1 or TS2 radio button (if using a duplex you will see TS1 and TS2, if simplex you wont see this), then click Delete radio button to delete the TG and finally click on "Modify Static" button.  This will now remove the Static TG.
* [ ] **Drop QSO:** This will drop the current user if you want to stop the QSO so you can move or change the TG.
* [ ] **Drop All Dynamic:** This will allow you to drop all Dynamic TGs if you had keyed up a TG using your radio.&#x20;

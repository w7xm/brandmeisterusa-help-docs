---
description: Overview of the Dynamic and Static Features on BrandMeister Servers.
---

# Dynamic vs Static

{% hint style="success" %}
#### Timers - USA Master Servers

Hold Off - 5 Minutes

Dynamic - 15 Minutes
{% endhint %}

### What is a talk group?

A _DMR Talk group_ is a means to digitally organize a group of radio traffic by assigning a virtual channel known as a talk group ID. Talk groups can be organized into regional such as cities, counties, states, countries, etc. and also by topics or special interest groups such as radio clubs.&#x20;

For example Talk Group ID 91 is the world wide talk group and encourages users from around the world to meet up and communicate with each other.&#x20;

### Static

A _static talk group_ is set by either the repeater owner/trustee or hotspot user on a particular timeslot and is set to permanently allow traffic to be sent. This means all traffic will pass through the repeater/hotspot to the end user radio when there is active traffic or communications.

For example, if a repeater owner sets the talk Group to 3100 USA Local on timeslot 1 on their repeater to static it will send traffic to all to hear on that repeater. &#x20;

### Dynamic (Repeaters & Duplex Hotspots)&#x20;

A _dynamic talk group,_ or sometimes referred to PTT of a talk group, is a temporary activation of a particular talk group by the end user either being through a repeater or hotspot device.&#x20;

On BrandMeister this dynamic talk group will stay active for a period of 15 minutes on USA Master server (sometimes referred to on-demand timers), this will depend on the master server if not in the USA, and will deactivate or timeout if no local traffic (no local user keying up the repeater) is heard during this time.&#x20;

Please be mindful when using a DMR Repeater to activate a dynamic talk group to do it on the correct timeslot. Generally timeslot 1 is used for this purpose. Please consult the repeater owner or group on their preferred timeslot for dynamic talk group activations.&#x20;

### Auto-static (Simplex Hotspots only)

A auto-static is for hotspots only and sets the hotspot to stay on the current active talk group which was activated by keying up the radio through the hotspot by the user. This means this talk group will stay active until the user on the hotspot keys up another talk group and of which will set the new talkgroup as the new auto-static.&#x20;

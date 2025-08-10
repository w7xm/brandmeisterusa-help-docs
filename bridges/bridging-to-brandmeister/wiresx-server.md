# Wires-X Server

## Establishing a connection with BrandMeister

#### Open a Ticket and request a Wires-X Connection and provide the following:

* [ ] Public IP Address of the HRI-200 Device. You may also provide a Domain Name (FQDN).
* [ ] Provide the Room Number.
* [ ] Your Call Sign or Call Sign of the Wires-X Node.
* [ ] Choice of Master Server (USA: 3103 or 3104).
* [ ] Talk Group to link the Wires-X Room to. (Talk group must be yours or your groups, and or have permission to use a repeater ID as a talk group. You may use your personal 7-digit ID as a talk group). Please don't ask for a new talk group. We are not providing any and will refer you to this same message.

NOTE: We will not link Wires-X nodes to TG 3100, Statewide Talk groups or TAC channels (310-319) or global talk groups.

#### &#x20;Check the following items have been completed/working on your side.

* [ ] Ports are open and configured on your network (UDP: 46100, 46110, 46112, 46114, 46120 and 46122).
* [ ] Software installed and running along with any hardware configurations.
* [ ] We don't provide support on configuring/installing of the Wires-X Software or hardware configurations.

## What to expect when connection is established.&#x20;

You will see a new Node either labeled as BM3103-ND or BM3104-ND.

Traffic will be sent between BrandMeister and the Wires-X Node when there is activity.

If the node goes offline or there are network disruptions, BrandMeister will continually try to establish the connection. There are no limits or connection retries and will continue until successful.&#x20;

If you are reviewing the logs of the Wires-X node you will notice multiple connects and reconnects. This is normal and should generally be seen every 90 to 120 seconds. Again, this is normal.&#x20;

### Troubleshooting of Connection Loss

If the connection between the BrandMeister Server and your Wires-X suddenly disconnects, please check the following:

* [ ] Wait to see if connection is restored (typically within 1 to 2 minutes).&#x20;
* [ ] Review the Port Permits in your Router/Firewall.
* [ ] Check if IP Address has changed with your ISP (Use a website like - [https://whatismyipaddress.com/](https://whatismyipaddress.com/)) to verify it has not changed. If the IP has changed you will need to provide this to BrandMeister to update the configurations.
* [ ] If you provided the BrandMeister a domain name pointing to your device, ensure the IP Address did not change or if changed wait for the refresh of the IP to take place (can take 5 minutes to 1 hour and some cases multiple days depending on the service used).
* [ ] Reboot network devices on your network. (Routers, Switches, Hubs, Firewalls, etc.).
* [ ] Verify with ISP the IP Address / Ports of the Master Server is not being blocked.




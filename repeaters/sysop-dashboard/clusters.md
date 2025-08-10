---
description: >-
  Clusters provide repeater owners a method to link common repeaters on the same
  master server together allowing for priority traffic and a local Talk group
  for users to use.
---

# Clusters

When a cluster is used, users may only access the cluster by using the repeater which is part of the cluster. The general talk group used is Talk Group ID 2. Further no outside access is enabled as the default configuration, meaning hotspot users will not be able to access it directly from a talk group ID.  Clusters also don't forward traffic to other master servers which means it only available at the master server it originates from.&#x20;

![](<../../.gitbook/assets/image (73).png>)

## Add Repeater to Cluster

1.) Click on the "Add Cluster" button in the Clusters section in the Sysop Dashboard.

2.) The following dialog box will appear. &#x20;

![](<../../.gitbook/assets/image (115).png>)

3.) In the cluster drop down select the Cluster you wish to join. If a cluster is not available or needs to be created see [Create a New Cluster.](clusters.md#create-a-new-cluster)

4.) Choose the Timeslot where you wish to have the cluster to be assigned to.&#x20;

5.) Click Add cluster. Repeater this for each repeater you wish to join to the cluster.&#x20;

6.) Users will access the cluster on the timeslot chosen and using Talkgroup ID 2 or the ID which is assigned to it. Note in the parenthesis the number as this indicates the Talk group ID.&#x20;

## Create a New Cluster

1.) If you need a cluster to be created and listed please open a support ticket at [http://support.brandmeister.network](http://support.brandmeister.network)

2.) Provide your radio ID and call, and the name of the cluster. All clusters will be setup to operate on Talk Group ID 2.

3.) Once the cluster is created  you may follow the [Add Repeater to Cluster](clusters.md#add-repeater-to-cluster).&#x20;

## Remove Repeater from Cluster

1.) Click on the cluster entry you wish to remove from the repeater.

2.) Click Remove button to remove the repeater from the cluster.&#x20;

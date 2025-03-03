---
description: Info gives you a consolidated view of basic information about your workspace.
---

# Info

Visit the **Info** section to get insight, statistics, and information on the various aspects of your server. This can help you to evaluate better and monitor the various activities.

To access this menu, go to **Administration** > **Workspace** > **Info**

## Deployment Info

The deployment info card shows information related to your server deployment.

* **Version**: The current version of your Rocket.Chat server. This can be different from the latest version if not updated.
* **Deployment ID**: Your server's deployment ID.
* **Apps Engine Version**: The version of Apps engine. It can be different from the latest if not updated.
* **Node Version**: The Node.js version your server is running on.
* **Database Migration**: The date of database migration.
* **MongoDB**: The MongoDB version
* **Commit Details**: Details on the recent commit of your server.
* **PID**

## License Info

This shows the information patenting to the license of your server.

* **License**: This shows the tags of the license you have active on your server.
* **Features**: The various features supported by the license on your server. Like `Omnichannel` `Auditing`, `Canned Responses`, `Engagement Dashboard`.

### Apply Offline License

To apply your offline license from the **License** card of the **Info** dashboard:

* Click **Apply Offline License** at the bottom right of the card
* A modal is presented, prompting you to paste the license you got from the[ Rocket.Chat Cloud Console](https://cloud.rocket.chat/home).
* Paste the license code and hit **Apply license**

### Change Offline License

To change your offline license from the **License** card of the **Info** dashboard:

* Click on the **Change Offline License** at the bottom right of the card
* A modal is presented, prompting you to paste the new license you got from the[ Rocket.Chat Cloud Console](https://cloud.rocket.chat/home)
* Clear the old license code and paste the new license code, then hit **Apply license**

## Usage Info

* **Users**
  * **Total**: The total number of users on the server.
  * **Online**: The number of users that are currently `online`.
  * **Busy**: The number of users that are in `Busy` mode.
  * **Offline**: The number of users that are offline.
* **Types and Distribution**
  * **Connected**
  * **Activated Users**: The number of activated users on your server.
  * **Activated Guests**: The number of guests that have been activated.
  * **Deactivated Users**: Number of inactive users.
  * **Rocket.Chat App Users**: The number of Rocket.Chat users. Example `bot users`, `app users`.
* **Uploads**
  * **Total Uploads**: The number of total uploads that have been made on the server.
  * **Total Uploads Size**: The total size of all uploads.
* **Rooms**
  * **Total Rooms**: The total number of rooms on the server.
  * **Total Channels**: Total number of channels on your server.
  * **Total Private Groups**: Total number of private groups on the server
  * **Total Direct Message Rooms**: Total number of Direct Messages created on the server.
  * **Total Discussions**: Total number of discussions
  * **Total Omnichannel Rooms**: Total number of Omnichannel rooms.
* **Messages**
  * **Total Messages**: Total messages sent and received on the server.
  * **Total Threads**: The total number of threads on the server.
  * **Total Messages in Channels**: Total messages in all channels only
  * **Total Messages in Private Groups**: Total number of messages in private groups only
  * **Total Messages in Direct Messages**: Total number of messages that have been sent in all direct messages
  * **Total Messages in Omnichannel**: The total number of messages in omnichannel

More details on usage info can be seen on the [engagement-dashboard.md](engagement-dashboard.md "mention")

## Federation Info

[Rocket.Chat's Federation](settings/federation/#introduction) lets you set up communication between Rocket.Chat workspaces.

**Enabled**: Enables federation on your server.

When enabled, it shows a green checkmark :white\_check\_mark: across the features well configured. And a red cross :x:across those that aren't.

### Federation Settings

To see more on federation settings:

* Click on **Settings** at the bottom right of the federation card
* A modal appears. Enter the **Domain** and **Discovery Method** and hit **Next**
* **Domain**: Add the domain name that your server should be linked to.
* **Discovery Method**: A dropdown to select which discoverability mode to use e.g. `DNS` or `HUB`

{% hint style="info" %}
We recommend using **DNS**.
{% endhint %}

Next, continue by adding the given DNS records on your server and follow the given instructions.

{% hint style="info" %}
More on the federation setup can be seen in [this section](settings/federation/).

We also have a guide on [Broken link](broken-reference "mention").
{% endhint %}



## Download Info

To download info about your server, click the **Download Info** button at the top right of **Info** menu.

A download is prompted with a file named `statistics.json`.

## Refresh Info

Refreshing info on your Rocket.Chat server will prompt for the latest stats to be pulled.

To refresh info, click the **Refresh** button by the top right of your info panel.

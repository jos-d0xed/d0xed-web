Getting Started
=====

This page will allow you to get connected securely to the d0xed network, fast!

I just want the info!
--------------------

Server: 	irc.d0xed.com
Port:		11111
SSL:		Yes

Windows Client
--------------

The HexChat client is recommended for connecting to the d0xed network from the Windows Operating System.  Detailed steps on configuring a Hexchat client are below.

1. Download HexChat from [GitHub](http://hexchat.github.io/downloads.html) and install it on your PC.  The default install options are compatible with the d0xed network.
2. When launching HexChat for the first time, you will be presented with the "HexChat: Network List" window.  The first items you must change are under "User Information".  Please choose a nickname and fill in the "Nick Name", "Second Choice" and "Third Choice" text boxes appropriately.  For privacy purposes, we recommend you put your nick in the "User Name" text box as well.
![](http://i.imgur.com/pOoz8pO.png "HexChat Network List")

3. Once you have filled out all user information, you will need to click the "Add" button.  When the network is created, it will be highlighted.  Name the network something of your choosing. For example, "d0xed" as shown on the right.
![](http://i.imgur.com/IkOyQzo.png "HexChat Network List")

4. In the servers tab, you are going to need to click the "Edit" button and change the "newserver/6667" to "irc.d0xed.com/11111" as shown on the right.  Please also check the "Use SSL for all servers on this network" and "Accept invalid SSL certificates" boxes to connect to the network using SSL encryption.
![](http://i.imgur.com/zIMratT.png)

5. Click the "Autojoin channels" button.  Click "Add".  Enter in #banterpod and press enter.  Click the "Close" button.
![](http://i.imgur.com/l4WN6Mj.png)

6. Press "Connect".  Once you are connected, you will be automatically joined to the #banterpod channel.  Say "Hi" and introduce yourself to the staff.  We don't bite :)

Android Client
--------------

For connection to the d0xed network using an Android device, the AndChat client is recommended by the d0xed staff.  Detailed steps on configuring the AndChat client are below.

1. Install the AndChat client from the [Google Play Store](https://play.google.com/store/apps/details?id=net.andchat&hl=en)

2. Launch the AndChat application, and press the small plus sign in the top right hand corner to add a network.
![](http://i.imgur.com/aEoEnpk.png)

3. Name the network appropriately and put in the server address of "irc.d0xed.com" and port number "11111".  Remember to check the "SSL" box to enable secure communication.  Also put your nick into the "Nick 1" field.
![](http://i.imgur.com/j0BOFok.png)

4. Scroll down the "New Profile" page further to the "Other Details" banner.  In the autojoin channel list, enter in #banterpod to automatically enter the default channel.  The d0xed staff recommend that you leave chat logs disabled in order to protect your privacy, and the privacy of other members.  Once you have completed filling out the details, press the "disk" icon in the top right to save the configuration.
![](http://i.imgur.com/MvsvAiS.png)

5. Once you have returned to the network selection page, tap on the network you just created and the client will connect to the network.

6. Welcome to the #banterpod.  Make sure you say hi :).

Linux Client
-------------

For Linux, we recommend "WeeChat". WeeChat is a well written command-line client with active development, fantastic documentation, and a wealth of languages for scripting plugins. Setup can be as simple or as complicated as you like, but we'll keep it fairly simple.

1. Install a copy of WeeChat. You'll most likely find a copy of it in your distribution's packages, but if not, you can grab the source and build it from there. This can be found on the [official weechat site](https://weechat.org/).

2. Start up weechat, and you'll need to add a server in. The command for doing that is
```
/server add d0xed irc.d0xed.com/11111 -ssl -autoconnect
```

3. You'll need to either install our certificate to your machine, or, check the certificate yourself, and set WeeChat to ignore it. This can be done with:
```
/set irc.server.d0xed.ssl_verify off
```

4. After that, you can connect and join the channel of your choice:
```
/connect d0xed
/join #banterpod
```

Services
=====

Overview
--------
IRC services are provided as a way to enhance your experience on the d0xed network. Many IRC users will be familiar with IRC services already, however, for those of you who do not, this page serves as a quick-start guide to some of the most common activities you may need to do when accessing IRC.

NickServ
--------
NickServ will probably be your first stop upon joining the network. This is used to register your nickname on the IRC network, and reserve it so that it cannot be used by anyone else (i.e., they cannot impersonate you). Here are some following usage scenarios that you might find helpful.


### Registering your nickname
This will be your first step on the network. Choose your nickname (for example, with the command /nick Panda), and then proceeed with the following

	/msg nickserv register PASSWORD [your@email.com]

The email is optional


### Identifying your nickname
This is the step that you will require each time you join the IRC network. This is basically how you login to your nickname and tell the server that you are who you say you are (and others will be able to see the same).

	/msg nickserv identify [account] PASSWORD

The account is nickname you are trying to identify as, and is optional. If you are already using this nickname, it is irrelevant. If, however, you are using a different nickname, then you will include this directive


### Nickname recovery
If your leave your nickname logged in from somewhere else, or, if a malicious user is logged in as yourself, then you can use the following command to regain control of your nickname.

	/msg nickserv recover nickname [PASSWORD]

If you are not currently identified to that account, then the PASSWORD will be required.


ChanServ
-------
ChanServ is the service responsible for maintaining the access for channels in the IRC network. This means that a NickName can register a channel in order to maintain and control access to it. They can also assign or delegate different levels of access to other (registered) users in the network. Below are some common actions you would use ChanServ to perform.


### Registering a channel
Registering a channel is quite a common action. You can register a channel to have your own space on the d0xed network. This allows you to have your own space, which *you* control for your friends, co-workers, volunteer group, etc, and it can be as open or as private as you like. Within reason, anything goes, and it's up to you what rules you implement on your channel (provided they fit within the Network Rules. This is done with the following command.

	/msg chanserv register #channel-name

This instantly associates the channel to your account, and gives you "owner" permissions on that channel. This means you have full access to do anything required on that specific channel.


### Banning a user
From time to time, you may need to ban a user on your channel, if they are being rude, or otherwise causing upset. You can do this with the following (full command syntax, followed by an example)

	/msg chanserv ban #channel-name [+expiry] {nick | mask} [reason] 
	/msg chanserv ban #mychan +20s ReallyAnnoyingDude He spammed the chan


### Kicking a user
Sometimes, the more appropriate approach is to kick a user. This temporarily excludes them from the channel, until such a time as they manually rejoin the channel. Syntax is very similar to banning

	/msg chanserv kick #channel-name nickname [reason]


### Access modes
There are a variety of commands used to provide access for different people to various channels. These commands will be added in future.


BotServ
--------
BotServ allows a basic bot to be inserted into the channel of your choice (courtesy IRC services) which allows for basic operations such as automatic kicks and bans, and channel access management (auto ops, etc). It will also keep your channel "open" when you're not online and joined to it.


### Listing existing bots
You can check available bots on the network by issuing the following command

	/msg botserv botlist


### Assigning a bot to your channel
This command is used to assign a bot to your channel for use

	/msg botserv assign #channel Gembit


### Turning on fantasy commands
Fantasy commands allow you to perform quick operations within the channel that the bot pays attention to (for example, !op nickname - this will give oper status to whomever you delegate, or !voice nickname - to give voice status to a particular user)

	/msg botserv set fantasy #channel on


MemoServ
--------
MemoServ is used to send messages to - and receive messages from - other users or staff. Below is an example of sending a message to a user (oneself) and reading said message.

	/msg memoserv send panda Hello

	[MemoServ]
	Memo sent to panda.
	[MemoServ]
	You have a new memo from panda.
	[MemoServ]
	Type /msg MemoServ READ 1 to read it. 
	[MemoServ]
	Memo sent to panda.

	/msg memoserv read 1

	[MemoServ]
	Memo 1 from panda (Nov 03 06:45:46 2014 EST (6 minutes ago)). 
	[MemoServ]
	To delete, type: /msg MemoServ DEL 1 
	[MemoServ]
	Hello 

You can also send a message to a channel, and the owner of said channel will receive that message.


HostServ
--------
You are also welcome to request your own Vhost. Rather than having nickname@banter.a3id31, you could request nickname@im.feeling.really.special. If staff deem it's appropriate (basically, non-offensive), then we will approve it at our earliest convenience. You'll then be able to turn it on or off at your leisure. This is purely cosmetic, and has no bearing on anything else, however, a lot of people find it a good way of showing a little unique flair. This is done in the following way.

	/msg hostserv request bamboo.forest

Once approved, our user Panda will appear to other users to be panda@bamboo.forest.

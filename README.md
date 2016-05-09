## [tele iro-api](https://telegram.me/tele_iro_bot) Is New And Best Bot.

## Based On groupBUTLER.
_________________________________________________________________________________
###  For Install  

sudo service redis-server start redis-cli

sudo apt-get update

sudo apt-get upgrade

sudo apt-get update; sudo apt-get install lua5.1 luarocks lua-socket lua-sec redis-server curl ; sudo luarocks install moonscript ; sudo luarocks install oauth ; sudo luarocks install redis-lua ; sudo luarocks install lua-cjson ; sudo luarocks install ansicolors;sudo luarocks install serpent

cd $HOME

git clone https://github.com/iro-team/iro-api
__________________________________
# Do Not Forgot Change Help Cammonds.
_________________________________________________________________________________
>/ping | check if the bot is running
>
>/help | show the help message (in private)
>
>/dasboard | receive in private a message delivered with an inline keyboard, to surf all the group info (rules/about/modlist/settings/extra commands list)
>
>/c [feedback] | talk with the bot admin
>
>/info | show some info about the bot (as the link to this repo)
>
>/about (if unlocked) | will return the group descriptions
>
>/rules (if unlocked) | show the group rules
>
>@admin [reply optional] | send a feedback to all the admins or, if by reply, forward the replied message to the admins
>
>/modlist (if unlocked) | show the moderators list
>
>/tell | show the basical info of the user/group. Can work by reply

###Moderators
>/kick [reply|username] | kick an user (it's still able to join)
>
>/ban [reply|username] | ban an user (not able to join again)
>
>/unban [reply|username] | unban an user
>
>/menu | receive in private an inline keyboard to manage all the settings of the bot
>
>/flood [number] | set the max number of messages allowed within 5 seconds before kick/ban
>
>/flood [on/off] | turn the anti-flood on/off
>
>/flood [kick/ban] | choose what to do when a user is flooding
>
>/lang | see the supported languages
>
>/lang [code] | change the bot language (in the group)
>
>/kick [media type] | the bot will kick who send that media
>
>/ban [media type] | the bot will ban who send that media
>
>/allow [media type] | the media can be sent freely
>
>/media | show the current status for each media
>
>/media list | show the list of the media you can manage
>
>/warn [reply] | warn an user. He will be kicked/banned when the max number of warns will be reached
>
>/warn [kick/ban] | choose what to do when the max number of warns is reached
>
>/warnmax [number] | choose the max number of warns to reach to be kicked/banned
>
>/getwarns [reply] | show how many warns has an user
>
>/nowarns [reply] | reset the warns of an user
>
>/settings | show the current settings of the group
>
>/disable [rules/about/modlist/extra] | this commands will be available only for moderators
>
>/enable [rules/about/modlist/extra] | this commands will be available only for moderators
>
>/[disable/enable] welcome | turn on/off the welcome message
>
>/[disable/enable] wreport | turn on/off the possibility to use @admin command by the users
>
>/disable [arab/rtl] | everyone with have rtl character in the name/in a message will be kicked, same for who write with arab characters
>
>/enable [arab/rtl] | rtl character/arab will be allowed
>
>/welcome [a/r/m/ar/am/rm/arm] | change the welcome composition (a: about, r: rules, m:modlist)
>
>/extra [#command] [reply] | set up a reply to an hashtag
>
>/extra list | show the list of hashtag commands
>
>/extra del [#command] | delete that custom command
>
>/link | show the group link (if setted)
>
>/setpoll [link/no] | set up a @pollbot poll link (so moderators can see it with /poll). Use 'no' to remove it
>
>/poll | show the current poll link (if setted)
>
>/setabout [description] | set a description for the group
>
>/addabout [text to add] | add some text to the decription
>
>/setrules [rules] | set the group rules
>
>/addrules [rules] | add some rules
>
>/report off [reply] | the user won't be able to report a message/send a feedback to the admins
>
>/report on [reply] | the user will be able to report a message/send a feedback to the admins

###Owner
>/setlink [link/no] | set the group link (so moderators can see it with /link). Use 'no' to remove it
>
>/owner [reply] | change the ownership of the group (not really, the bot will se the replied user as the owner)
>
>/promote [reply|username] | promote the user as moderators
>
>/demote [reply|username] | demote the user

###Admin
>/init | to reload the bot
>
>/backup | will send to the admin the bot folder, zipped
>
>/stop | will stop the bot
>
>/leave [group id] | the bot will leave the group. If launched in a group, no [id] needed
>
>/adminmode [on/off] | when on, only the admin will be able to add the bot to a group
>
>/bc [text] | will send a broadcast to users
>
>/bcg [text] | will send a broadcast to groups
>
>/post [post text] | post a message in the setted channel (config.lua)
>
>/stats | will return some statistics (messages, groups, users, commands)
>
>/commands | will show how many times each command have been used
>
>/usernames | send a file with all the usernames that the bot has found
>
>/rediscli [query] [parameters] | execute a redis command and get the output (tables and not tables)
>
>/movechat [new chat id] | move the chat info of the current chat to the target id
>
>/redis backup | save all the info of all the groups administrated in a json file
>
>/group info [id] | get a text file with all the info of a group (table view)
>
>/save | perform a redis background save
>
>/reset [field] | reset a specific general statistic
>
>/log [of what] | will send the log of the event inserted
>
>/log del [which] | will delete the log
>
>/block [reply/id] | will block the user ( the user won't be able to use the bot)
>
>/unblock [id/reply] | will unblock the user
>
>/isblocked [reply] | check if an user is blocked
>
>/movechat [new chat id] | move the current chat info to another group
>
>/group info | sends back a txt file with a lua table printed, with allthe info about that group
>
>/redis backup | backup all the groups info in a serialized json file
>
>/reply [text] | reply to a feedback
>
>/ping redis | check if redis is on
>
>/admin | returns the admin.lua plugin triggers
 
________________________________________________________________________________

# Dont forgot update {structures.c} befor lunch

# HOW DO MAKE UPDATE THIS FILE?
* **see this git:  https://github.com/iro-bot/iro-api**
* **see this channel: https://telegram.me/iroTEAM**

________________________________________________________________________________
* **[developer](https://telegram.me/raminoa)** 
* **[helper](https://telegram.me/goraze)**
* **[admin](https://telegram.me/xxicy_boyxx)**

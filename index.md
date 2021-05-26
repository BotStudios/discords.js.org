# Discord sender

A Discord Sender API Wrapper 


 <p>
    <a href="https://www.npmjs.com/package/discord-sender"><img src="https://img.shields.io/npm/v/discord-sender.svg?maxAge=3600" alt="NPM version" /></a>
    <a href="https://www.npmjs.com/package/discord-sender"><img src="https://img.shields.io/npm/dt/discord-sender.svg?maxAge=3600" alt="NPM downloads" /></a>
    
   
  </p>



<p>
    <a href="https://nodei.co/npm/discord-sender/"><img src="https://nodei.co/npm/discord-sender.png?downloads=true&stars=true" alt="npm installnfo" /></a>
</p>



## Install 

``` npm i discord-sender ```

``` const sender = require('discord-sender')```

##### Or Use Unpkg's CDN :

```<script src="https://discords.js.org/discord-sender.min.js"></script>```

###### Example Usage

```
webhook('WEBHOOK_LINK', 'MESSAGE', 'USERNAME // OPTIONAL', 'AVATAR_URL // OPTIONAL')

const discordSender = '{"title":"Discord-Sender", "url":"https://unpkg.com/discord-sender","description":"made using discord-sender","author":"discord-sender-npm","authorUrl":"https://discord.is-a.dev","authorAvatar":"Avatar_URL"}'
embed('CHANNEL_ID', discordSender)
```

## Table of contents

- [What's New ?](#what's-new-?)
- [Install](#install)
- [Usage](#usage)
- [Credit](#credit)
- [Links](#links)
- [License](#license)



### What's New ?

- 14  May 2021
 - Changed API Host name
  
-------------
## Usage 

### Send Discord Webhook 

```
const sender = require('discord-sender');

sender.webhook('DISCORD_WEBHOOK_URL', 'MESSAGE')

```

#### Optional
Customize Webhook Name And Webhook Avatar
```
sender.avatarURL('AVATAR_URL'); //OPTIONAL
sender.name('WEBHOOK_NAME'); //OPTIONAL
```

### Send Message Thru A Random Bot [( BETA )](https://github.com/botstudios/DiscordSender)
Send Messages Using A Random Bot [Amber](https://discord.is-a.dev/bot)
> Make Sure To Add The Bot Before Using It.

```
sender.bot('CHANNEL_ID', 'YOUR_MESSAGE');
```


## Credit

Made By [@joeleeofficial](https://github.com/joeleeofficial)

Managed By [@BotStudios](https://studios.js.org)

Made With [A Random Bot](https://discord.is-a.dev)

- More Features Coming Soon


### Links

- [Discord-Sender](https://discord.is-a.dev)

- [JoeLeeOfficial](https://github.com/joeleeofficial)

- [BotStudios](https://github.com/botstudios)


### License 

> `APACHE 2.0`

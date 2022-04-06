# Discord Activities Bot V2
A simple slash command bot for opening Discord voice channel activities. Made with [Harmony](https://github.com/harmonyland/harmony) and [Deno Deploy](https://deno.com/deploy).
You Can Also Invite The Bot [Here](https://discord.com/api/oauth2/authorize?client_id=911590387859226645&permissions=1&scope=applications.commands%20bot).

Originaly Made By [Advaith](https://github.com/advaith1/Activities) and [DjDeveloperr](https://github.com/DjDeveloperr/ActivitiesBot).

## Deployments
This bot is deployed to [Deno Deploy](https://deno.com/deploy). You can also deploy it yourself in few clicks!

- [Click here to Deploy.](https://dash.deno.com/new?url=https://raw.githubusercontent.com/MJGaming1532/ActivitiesV2/main/mod.ts&env=TOKEN,PUBLIC_KEY). Go to [Discord Developer Portal](https://discord.com/developers/applications). and enter your bots token (Bot -> Copy Token) and public key (General Information -> Copy Public Key).
- Add the project's domain to Interactions Endpoint URL in Developer Portal. (General Informations -> Interactions Endpoint Url
- Invite your bot from URL `https://discord.com/api/oauth2/authorize?client_id=YOUR_CLIENT_ID_HERE&permissions=1025&scope=bot%20applications.commands` and don't forget to replace `YOUR_CLIENT_ID_HERE` with the bot's Applications ID

## How it works?

Refer to [this part of code](https://github.com/DjDeveloperr/ActivitiesBot/blob/main/mod.ts#L104).

### But why bot scope?

Application's bot user must be in the guild to create activity invite.

## Legal

- Available under [MIT License DjDeveloperr](https://github.com/MJGaming1532/ActivitiesV2/blob/main/LICENSE%20DjDeveloperr) & [MIT License Advaith](https://github.com/MJGaming1532/ActivitiesV2/blob/main/LICENSE%20Advaith)

Copyright 2021 © DjDeveloperr & Advaith

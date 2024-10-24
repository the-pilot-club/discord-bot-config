<p align="center"><a href="https://thepilotclub.org" target="_blank"><img src="https://static1.squarespace.com/static/614689d3918044012d2ac1b4/t/616ff36761fabc72642806e3/1634726781251/TPC_FullColor_TransparentBg_1280x1024_72dpi.png" width="300" alt="The Pilot Club Logo"></a></p>


# discord-bot-config

This is the config setup for https://github.com/the-pilot-club/discord-bot . This code has been copied from https://github.com/VATUSA/discord-bot-v3-config/tree/main and all credit goes to the team at VATUSA as this would not be possible without them.

## Setup Steps

- Create a config file per the example with the appropriate values for your server (documentation can be found below)
- Create a Pull Request with your config file
- Request for the bot to be added to your server via support ticket in TPC discord server with the dev team drop down

## Server Configuration

### Required Conditions

[Example Config (Development Server)](https://github.com/the-pilot-club/discord-bot-config/blob/main/config/dev.yaml)

```yaml
id: 1148307481085358190
name: Your Server Name here
roles:
  - id: Role Id Here
    name: Moderator
channels:
  - name: Bot Update Channel
    id: Channel Id Here
  - name: Screenshot Channel # Only activate this if you want auto reactions to images sent in screenshot channel
    id: Channel Id Here
  - name: General Chat
    id: Channel Id Here
emojis:
  - name: TPC Reaction
    id: Reaction Id here
```




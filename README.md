<p align="center">
    <img src="https://github.com/international-accessibility-task-force/iatf-bot/blob/master/assets/images/logo-center-rules-black-and-white.png"
        height="138">
</p>
<p align="center">
    <a href="https://github.com/international-accessibility-task-force/iatf-bot/graphs/contributors" alt="Contributors">
        <img src="https://img.shields.io/github/contributors/international-accessibility-task-force/iatf-bot" /></a>
    <a href="https://github.com/international-accessibility-task-force/iatf-bot/pulse" alt="Activity">
        <img src="https://img.shields.io/github/commit-activity/m/international-accessibility-task-force/iatf-bot" /></a>
    <a href="https://discord.gg/D8brSJSpaZ">
        <img src="https://img.shields.io/discord/1014599739230130267?logo=discord"
            alt="chat on Discord"></a>
</p>

# IATF's discord bot

This is the official repository of the IATF's discord bot.

## International Accessibility Task Force (IATF)

International Accessibility Task Force is an open-to-everyone community of: assistive technology users, open-source developers, and people interested in accessibility and inclusion.

## Installation

**Requirements:** `git`, `node` and `npm`

```sh
git clone https://github.com/international-accessibility-task-force/iatf-bot.git
```

### Running locally

```sh
cd iatf-bot
touch .env
```

Inside .env file:
```
TOKEN={YOUR_BOT_DISCORD_TOKEN}
```

then npm start
```sh
npm start
```

Notice that the names of the channels and the categories of [our discord server](https://discord.gg/D8brSJSpaZ) are hard-coded. You might want to modify it to make it work in your custom server.

## Contributing

### How to create a Pull Request for the repository:

1. fork of this repository.
1. git clone of the forked repository on your local machine.

then:
```sh
cd iatf-bot
git checkout development
git remote add upstream https://github.com/international-accessibility-task-force/iatf-bot.git
git pull upstream development
git checkout -b the-name-of-your-branch
```

when you are done with the code:

```sh
git push origin the-name-of-your-branch
```

finally, you can PR to the **development branch** 🎉


## License
Code licensed [GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/) by IATF.

Made with ❤️ from IATF.

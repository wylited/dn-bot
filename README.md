# DN bot
discord bot made with dpp

## how to run

have a bot and its token with appropriate permissions.

clone the repo

```bash
git clone https://github.com/wylited/dn-bot.git --recurse-submodules
cd dn-bot
```

compile it

```bash
g++ -std=c++17 -o bot src/main.cpp -ldpp
```
> ill make a makefile someday.

run it (make sure you have a file called token.env in the same directory as the bot binary holding the token.)

```bash
./bot
```

## licensing
wtfpl
# Twitch HP Bar Overlay

A simple HP bar overlay for Twitch streams.  
Chat can type `!hit` to reduce HP, while mods and trusted users can `!heal` or `!reset`.

## Features
- Start HP = **1000**
- `!hit` = -25 HP (anyone can use)
- `!heal` = +25 HP (broadcaster, mods, whitelist)
- `!reset` = back to 1000 HP
- Flashes **GAME OVER** when HP hits 0
- Whitelist support for trusted usernames

## Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR-USERNAME/hp-bar-twitch.git

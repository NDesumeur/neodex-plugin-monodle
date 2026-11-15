# MonogatariDle

A guessing game set in the world of **Monogatari**: find the mystery character in as few guesses as possible. Every guess gives you clues that bring you closer to the answer. One challenge a day in each mode, the same for everyone, and as many free games as you like.

*Version française : [README.md](README.md)*

## How to play

1. Pick a mode at the top: **Classic**, **Hints**, **Emoji** or **Image**.
2. Type the start of a name in the field: the list suggests matching characters. Confirm with **Enter** or by clicking a suggestion.
3. Read what the guess tells you, then try another character, until you find the right one.

## The four modes

- **Classic**: each guess appears on a row comparing your character with the mystery one, column by column: gender, nature, role, hair (anime colours), apparent age, first appearance, oddity. A **green** cell is identical, **orange** partly right or close, **red** different. For numbers, an ↑ arrow means the character to find is older or appears later in the series, ↓ the opposite.
- **Hints**: a first hint about the character is given; every wrong guess reveals one more.
- **Emoji**: the character is summed up in emojis, one more revealed after every wrong guess.
- **Image**: their portrait starts very blurry and gets sharper after every wrong guess (up to nine levels of sharpness).

## Daily challenge and free game

- The **daily challenge** is the same for every player, in each mode. Once you find it, the game shows how long until the next one.
- The **free game** draws a random character, as often as you want (**New game** button). You choose which characters it draws from: main characters, main and secondary, or everyone (including characters only mentioned and the oddities).

## Statistics

For each mode, the game keeps your **streak** of daily challenges won, the number of games won and how many guesses they took. 44 character portraits come with the plugin: it works offline.

## Data and sync

Your streak, your statistics and today's game in progress are stored by NeoDex, backed up and synced between your PCs when sync is on: you can start the challenge on one PC and finish it on another.

## Install

In NeoDex: **NeoStore → Discover → MonogatariDle → Install**.

Building a plugin: see the [NeoDex SDK](https://github.com/NDesumeur/neodex-sdk).

## What's new in version 1.4.0

- **Illustrated banner** at the top of the game: a shrine torii at dusk, under a big moon, drawn in pixel art, with the portraits of the main characters.
- **Bigger texts**: input, suggestions, hints, headers and table cells.
- **Cells of the right size**: wider columns, each cell grows in height for its text, and a word too long for its cell is written a bit smaller instead of overflowing.

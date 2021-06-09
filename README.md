# Mob Megavania

![vehikl](https://avatars.githubusercontent.com/u/6425636?s=64)

## Current Idea

Leaning towards a NES megavania game. Mega Man has all the sweet upgrades of a metroidvania game, but is always locked to level based platformers!

## Some Guidelines

- 384 x 216 resolution (16x9)
- Let's stick to the NES (including 9/10) for assets
- Lock to 60 fps

## Why 60 FPS Lock

`requestAnimationFrame()` should fire at the refresh rate of your monitor. If we run the game loop unchecked and you have say a 144hz refresh rate, we're just needlessly taxing your machine for a really high refresh rate. We'll render unchecked, but update in fixed intervals.

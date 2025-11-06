# Discord-Bot

A small Discord bot that posts memes and gifs. Uses meme-api (reddit) with a Tenor GIF fallback.

## Features
- `$gif <query>` — search Tenor for GIFs
- `$meme` — tries meme-api, falls back to Tenor
- Non-blocking behavior via `asyncio.to_thread` (keeps bot responsive)
- Retries/fallbacks and safe error handling

## Quick start (local)
1. Clone:
   `git clone https://github.com/yourname/gifbot.git && cd gifbot`

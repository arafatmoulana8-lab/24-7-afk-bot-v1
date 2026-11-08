# Enderlørd AFK Bot

24/7 AFK Minecraft bot (Aternos-friendly) by **Enderlørd**.

- Discord: https://discord.gg/kkfg4MM8
- YouTube: Enderlørd Minecraft — Subscribe now!

## Setup
1. Edit `settings.json` → set `server.ip`, `server.port`, `server.version`.
2. `npm install`
3. `npm start`
4. Open `http://localhost:5000` for the dashboard (logs, start/stop, console).

On Aternos: use Paper, turn on Cracked mode, add ViaVersion / ViaBackwards / ViaRewind.

## Epy AI (Gemini)
Say **Epy** in chat and the bot answers with Gemini AI.
- Put your key in `.env`:  `GEMINI_API_KEY=your_key`  (see `.env.example`). `.env` is git-ignored — never upload it.
- On Replit/Render add `GEMINI_API_KEY` as a Secret / Environment Variable instead.
- Personality, model and cooldown: `settings.json` → `ai`.

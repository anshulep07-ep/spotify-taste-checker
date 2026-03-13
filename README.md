# 🎵 Spotify Taste Checker

> Let Claude AI roast your music personality based on your real Spotify data.

## Live Demo
🔗 https://YOUR-USERNAME.github.io/spotify-taste-checker/

## What it does
- Connects to your Spotify via OAuth
- Fetches your top 20 artists + tracks
- Sends them to Claude claude-sonnet-4-20250514 for analysis
- Returns: Music Grade, Vibe Score, Personality Archetype, Genre DNA, and a personalized roast

## Stack
- Vanilla HTML/CSS/JS (no framework, no build step)
- Spotify Web API (implicit grant flow)
- Anthropic Claude API (claude-sonnet-4-20250514)

## Setup
1. Create a Spotify app at developer.spotify.com
2. Get an Anthropic API key at console.anthropic.com
3. Open the site and paste both keys — they stay in your browser only

## Privacy
Keys are stored in localStorage on your device only. Nothing is sent to any server except Spotify and Anthropic directly.

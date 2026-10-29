# 2 Minutes

A two player online version of the describe-it party game. One of you describes 5 names or things in 2 minutes without saying them, the other guesses out loud. Play it on a call, each on your own phone or laptop.

**Play:** https://sizwemarole-21389.github.io/30-seconds/

## How it works

- One player starts a game and sends the invite link or the 4 letter code.
- The other player opens the link, enters a name and joins.
- Take turns describing. The describer taps each item that was guessed, 1 point each.
- The game runs in the browser of the player who started it, so they need to keep the page open.

## Notes

It is a single static page with no game server of mine. The player who starts the game runs the game in their browser, and the two browsers pass messages through a free public MQTT relay (broker.emqx.io, with broker.hivemq.com as a fallback) over secure WebSocket, so it works on any network. Anyone who knew a live game code could join it, so do not type anything private as your name.

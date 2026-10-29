# 30 Seconds

A two player online version of the describe-it party game. One of you describes 5 names or things in 30 seconds without saying them, the other guesses out loud. Play it on a call, each on your own phone or laptop.

**Play:** https://sizwemarole-21389.github.io/30-seconds/

## How it works

- One player starts a game and sends the invite link or the 4 letter code.
- The other player opens the link, enters a name and joins.
- Take turns describing. The describer taps each item that was guessed, 1 point each.
- The game runs in the browser of the player who started it, so they need to keep the page open.

## Notes

It is a single static page. The two browsers connect directly to each other using WebRTC through PeerJS, so there is no game server. The PeerJS public service is only used to introduce the two browsers. On a few strict mobile networks a direct connection can fail, in which case try Wi-Fi.

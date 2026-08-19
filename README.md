# yt-mass-unsub

Browser console script that unsubscribes from YouTube channels in bulk.

## Usage

1. Open <https://www.youtube.com/feed/channels>
2. Open the browser console (F12)
3. Paste the contents of [`unsub.js`](unsub.js) and press Enter

It walks the channel list, clicks unsubscribe, confirms the dialog, removes the row and
continues with the next one at 250 ms intervals. Progress is logged to the console.
Reload the page and run it again if it stops early.

Depends on YouTube's DOM structure and will break whenever that changes.

Based on a [TechJunkie guide](https://www.techjunkie.com/mass-unsubscribe-youtube/) by YOGIE.

## License

MIT, see [LICENSE](LICENSE).

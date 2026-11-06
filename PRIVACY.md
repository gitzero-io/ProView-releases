# ProView TV privacy

*Last updated: November 2026*

ProView has no accounts, ads or analytics, and we don't run a server that collects your information. What you enter stays on your TV, except where the app has to contact the services below to work.

## What stays on your TV

- **Playlist links and logins:** stored encrypted, using a key held by Android.
- **Your settings and activity:** channels, guide data, favorites, recently watched channels, recent searches, followed teams, chosen services, and titles you opened from ProView.
- **The last crash report:** kept on the TV and shown in Settings → App. It isn't sent anywhere automatically. If you post it in a GitHub issue, it becomes public, so read it first.

To delete all of this, use Settings → App → Reset app data, or uninstall ProView.

## What leaves your TV

Like any internet connection, each of these services can see your IP address. They have their own privacy policies.

| Connects to | When | What it receives |
|---|---|---|
| Your TV provider, and any guide or logo addresses in your playlist | When you load a playlist or guide, or watch a channel | Your playlist link or login, and the channel you're watching |
| Guide links you add, including the optional free US guide (EPGTalk, hosted on GitHub) | When the guide refreshes | A download request |
| TMDB | Movies, Series, Home and Search, unless IPTV-only mode is on | Your chosen services, recently opened titles, and what you search for |
| ESPN | Sports Hub and scores | The leagues, teams and games being looked up |
| GitHub | When ProView checks for updates and its service list | A download request |
| YouTube | Only if you press play on a trailer | Opens the trailer in YouTube |

Some playlists use plain HTTP links. Those connections, including any login inside the link, aren't encrypted between your TV and your provider.

## Streaming apps

When you press Watch on a title, ProView opens that service's own app. What happens there is covered by that service's privacy policy. ProView also checks which supported streaming apps are installed so it can tick them during setup. That check stays on your TV.

## Adding a playlist from your phone

"Use your phone" runs a small web page on your TV while that dialog is open. It's only reachable on your local network, using the private address in the QR code. The connection is plain HTTP, so only use it on a Wi-Fi network you trust.

## Children

ProView isn't directed at children and doesn't knowingly collect information from anyone.

## Changes and questions

If this changes, for example if paid features are added, this page will be updated first. For questions, [open an issue](https://github.com/gitzero-io/ProView-releases/issues). Please don't post your playlist link or login.

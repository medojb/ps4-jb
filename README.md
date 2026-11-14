# PS4 13.52 / 14.00 / 14.02 Jailbreak

WebKit + kernel jailbreak host for PlayStation 4 firmware **13.52**, **14.00**, and **14.02**. After the stages succeed, the host loads **GoldHEN**.

- **13.52 / 14.00 / 14.02** - Afterglow kernel stage
- Legacy **hx1400** path for 14.00 still available with `?hx1400=1` if needed

## Live host

https://x-f1reball-x.github.io/ps4-jb/

## Payload

- **GoldHEN v2.4b18.14** (`hen.bin` / `payload.bin`, 298776 bytes)
- sha256 `c5480587d99efc2e3cc132352d9b7cf052dd3068280f1686e7fbb37d57e9ba8b`

## How to use

1. Fully power on the console (not Rest Mode).
2. Open the PS4 browser to the live URL (or your LAN host).
3. Press **Start** and wait for the progress bar.
4. On success: **DONE**, then the welcome splash for about 3 seconds.
5. On failure: retry (up to 3 in-page attempts, then reload; up to 10 reloads).

## Local hosting

```powershell
.\start-host.ps1
```

HTTP on port **8080**. On the PS4 browser: `http://<your-pc-lan-ip>:8080/jb.html`

## Credits

- **well0nez / m0zz** - Afterglow (WebKit + kernel exploit chain), including 14.02
- **SiSTR0 / GoldHEN team** - GoldHEN
- **X-F1REBALL-X** - this host

## Disclaimer

Educational / research use on consoles you own. Use at your own risk.

# TestFlight watcher

This script checks for free TestFlight slots for a given list of apps. It calls a callback function when new slots become available and (optionally) when they run out.

This repo includes, as an example, a Telegram bot which uses *TestFlight watcher* and sends notification messages.

## Example usage

The `telegram_bot.py` script takes a comma-separated list of app IDs as an argument.

```./telegram_bot.py ID1,ID2,ID3```

where `ID1`, `ID2`, `ID3` are the 8-character 
 app IDs you can find at the end of the TestFlight URL. If your URL is `https://testflight.apple.com/join/ABCDEFGH`, your `ID` is `ABCDEFGH`.

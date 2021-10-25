# twitcharchiver
C# application and libraries for archiving VODs and other data from Twitch.tv

## TwitchLeecher
A Twitch VOD downloader. Unlike other downloaders, it does not use FFMPEG for its download tasks. Instead, it downloads thousands of small video chunks in parallel while using all of the available internet connection bandwidth. FFMPEG is only used to merge those chunks together in order to create a single video file again as soon the download process is finished.

## TwitchLib
A C# library that interfaces with various Twitch services, such as: chat and whisper, API's (v5, helix, undocumented, and third party), PubSub event system, and Twitch Extensions.

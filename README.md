# MELODICA | Discord Music Bot 🎵

Topics: discord-music-bot, dotnet-discord-bot, discord-moderation, music-player-api, discord-audio-stream, lavalink-csharp, discord-slash-commands, discord-net-library, voice-channel-bot, discord-dashboard, bot-moderation, discord-music-api, csharp-discord-bot, audio-engine, discord-permissions, playlist-manager, discord-automation, music-streaming-bot, discord-commands

MusicBot stands as the original Discord music bot crafted for [Python](https://www.python.org "Python homepage") 3.8+ utilizing the [pycord](https://github.com/Pycord-Development/pycord) library. This bot plays requested songs from YouTube and various other platforms within a Discord server (or multiple servers). Additionally, if the queue becomes empty, MusicBot automatically plays from an existing song list based on its configuration. The bot also incorporates a permission system that empowers owners to restrict commands to specific individuals. Beyond song playback, MusicBot can experimentally stream live media to a voice channel.

## Setup 🛠️
Setting up MusicBot is relatively straightforward. Simply follow one of the available [guides](https://just-some-bots.github.io/MusicBot/). Following this, configure the bot to ensure its seamless integration with Discord.

While the primary configuration file is `config/options.ini`, it's not included by default. To create this configuration, make a duplicate of `example_options.ini` and rename it to `options.ini`. Detailed configuration information can be found in `example_options.ini`.

### Commands 📜

A wide array of commands is at your disposal when using the bot. One of the most notable commands is `play <url>` (prefixed by your command prefix), which triggers the download, processing, and playback of a song from platforms like YouTube or equivalent. For an extensive list of commands, please refer to [this link](https://just-some-bots.github.io/MusicBot/using/commands/ "Commands").

## Features 🎵

- Easy to set up (just ensure Java is installed and run!)
- Swift loading of songs
- No external keys required (except for a Discord Bot token)
- Seamless playback
- Server-specific configuration for the "DJ" role, allowing music moderation
- Clean and visually appealing menus
- Supports multiple platforms, including YouTube, Soundcloud, and more
- Compatible with various online radio/streams
- Accommodates local files
- Playlist support for both web/youtube and local sources

## Supported Sources and Formats 🎧

JMusicBot supports all sources and formats that are compatible with [lavaplayer](https://github.com/sedmelluq/lavaplayer#supported-formats):

### Sources
- YouTube
- SoundCloud
- Bandcamp
- Vimeo
- Twitch streams
- Local files
- HTTP URLs

### Formats
- MP3
- FLAC
- WAV
- Matroska/WebM (AAC, Opus, or Vorbis codecs)
- MP4/M4A (AAC codec)
- OGG streams (Opus, Vorbis, and FLAC codecs)
- AAC streams
- Stream playlists (M3U and PLS)

## Example 🎶

![Example Loading](https://i.imgur.com/kVtTKvS.gif)

## Setup 🛠️
For instructions on running this bot yourself, please refer to the [Setup Page](https://jmusicbot.com/setup).

## Questions/Suggestions/Bug Reports 🐞

**Before suggesting a feature, please read the [Issues List](https://github.com/jagrosh/MusicBot/issues)**. If you have inquiries, need help with troubleshooting, or want to brainstorm a new feature, start a [Discussion](https://github.com/jagrosh/MusicBot/discussions). To propose a feature or report a reproducible bug, open an [Issue](https://github.com/jagrosh/MusicBot/issues) on this repository. If you appreciate this bot, consider giving a star to the libraries behind its functionality: [**JDA**](https://github.com/DV8FromTheWorld/JDA) and [**lavaplayer**](https://github.com/sedmelluq/lavaplayer)!

## Editing ⚙️

Editing this bot (and its source code) might not be straightforward for inexperienced programmers. The primary intent of making the source code public is to showcase the capabilities of the libraries, help others comprehend the bot's functionality, and allow those knowledgeable about Java, JDA, and Discord bot development to contribute. Editing and compiling entail specific prerequisites and dependencies; please note that individual support for making changes will not be provided. Alternatively, consider submitting a feature request (as mentioned above). If you opt to make edits, kindly adhere to the Apache 2.0 License.

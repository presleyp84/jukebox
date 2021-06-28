<h1 align="centre">Jukebox 🎵</h1>

### A bot that can play music on Telegram Group and Channel Voice Chats

<p align="left">
  <a href="https://telegra.ph/file/3d14b9883baccf71f2229.jpg">
     <img height="400px" src="https://telegra.ph/file/3d14b9883baccf71f2229.jpg">
  </a>
  <a href="https://telegra.ph/file/23cfc4db1ff66d78429b5.jpg">
     <img height="400px" src="https://telegra.ph/file/23cfc4db1ff66d78429b5.jpg">
  </a>
</p>

<h2> Supported Features 🔥 </h2>

- Thumbnail Support
- Playlist Support
- Current playback support
- Showing track names when skipping
- Zero downtime, Fully Stable
- DEEZER,YOUTUBE & SAAVN PLAYBACK SUPPORTED
- Settings panel
- Control with buttons
- Userbot auto join
- Channel Music Play

## 🚀 Deployment

### Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/patrickpresley084/jukebox)


### ⚔ Self-hosting (For Devs) 
```sh
# Install Git First (apt-instll git)
$ git clone https://github.com/patrickpresley084/jukebox
$ cd jukebox
$ pip3 install -r requirements.txt
# Rename example.env to local.env and fill
$ cp example.env local.env
# Start Bot 
$ python3 -m jukebox
```

### Commands for Group 🛠
#### For all in group

- `/play <song name>` - play song you requested
- `/play <reply to audio>` - play replied file
- `/dplay <song name>` - play song you requested via deezer
- `/splay <song name>` - play song you requested via jio saavn
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/deezer <song name>` - download songs you want quickly via deezer
- `/saavn <song name>` - download songs you want quickly via saavn
- `/video <song name>` - download videos you want quickly

#### Admins only.
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/admincache` - Refresh admin list

### Commands for Channel Music Play 🛠
For linked group admins only:
- `/cplay <song name>` - play song you requested
- `/cplay <reply to audio>` - play replied file
- `/cdplay <song name>` - play song you requested via deezer
- `/csplay <song name>` - play song you requested via jio saavn
- `/cplaylist` - Show now playing list
- `/cccurrent` - Show now playing
- `/cplayer` - open music player settings panel
- `/cpause` - pause song play
- `/cresume` - resume song play
- `/cskip` - play next song
- `/cend` - stop music play
- `/userbotjoinchannel` - invite assistant to your chat
* channel is also can be used instead of c

If you donlt like to play in linked channel:
 1. Get your channel ID.
 2. Rename your group to: Channel Music: your_channel_id
 3. Add @DaisyXBot as Channel admin with full perms
 4. add helper to channel
 5. Simply send commands in your group.


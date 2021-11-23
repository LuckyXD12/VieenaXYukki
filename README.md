<h2 align="centre">Prime Music Player</h2>

<h3>Requirements 📝</h3>

- FFmpeg (Latest)
- NodeJS [nodesource.com](https://nodesource.com/) (NodeJS 17+)
- Python (3.10+)
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls) (0.8.1rc1)
- [MongoDB](https://cloud.mongodb.com/) (3.12.1)
- [2nd Telegram Account](https://telegram.org/blog/themes-accounts#multiple-accounts) (needed for userbot)

### Commands 🛠
#### For all in group
- `/play` - reply to youtube url or song file to play song
- `/ytp <song name>` - play song without youtube url or song file (best method)
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details

#### Admins only
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play

### Commands for Sudo Users ⚔️
- `/userbotleaveall` - remove assistant from all chats
- `/gcast <reply to message>` - globally brodcast replied message to all chats
- `/pmpermit [on/off]` - enable/disable pmpermit message

#### Pmpermit
- `.a` - approove someone to pm you
- `.da` - disapproove someone to pm you
- You can add a custom pmpermit message by adding var `PMMSG` and adding your message through env vars (for heroku, Settings/Edit vars)

+ Sudo Users can execute any command in any groups


## Credits
- DaisyXMusic 
- callmusic 
- VCPlayerBot
- Veez
- TGVCBot
- Yukki
- PyTgCalls

#### Contributors
- [Arya Zakaria01](https://github.com/aryazakaria01): Yukki Owner
- [InukaAsith](https://github.com/InukaAsith): Yukki Dev 
- [『TØNIC』 乂 ₭ILLΣR](https://github.com/Tonic990): Yukki Dev
- [Hunter XDD](https://github.com/Hunter-XDD): Yukki Dev
- [xD_ShaShank](https://github.com/theshashankk): Yukki Dev
- [VegetaxD](http://github.com/VegetaxD): Yukki Owner 
- [Laky](https://github.com/Laky-64): PyTgCalls Developer
- [Dan](https://github.com/delivrance): Pyrogram Developer

#### Special Credits
- [Roj Serbest](http://github.com/rojserbest): Callsmusic Developer
- [VegetaxD](http://github.com/VegetaxD): Video Stream Developer
- [Laky](https://github.com/Laky-64): PyTgCalls Developer
- [Dan](https://github.com/delivrance): Pyrogram Developer

This bot is based on the original work done by [Rojserbest](http://github.com/rojserbest). Without his hardwork YukkiMusicPlayer won t exist. 
YukkiMusicPlayer is a modified version of [Callsmusic](https://github.com/callsmusic/callsmusic) for fit the needs of some users

- [StarkGang](https://github.com/StarkGang/)
- [SpEcHiDe](https://github.com/SpEcHiDe/)
- [The Hamker Cat](https://github.com/thehamkercat)
- [Laky (for PyTgCalls)](https://github.com/Laky-64)
- [Dan (for pyrogram)](https://github.com/delivrance)
- [VegetaxD (For Yukki Repo)](http://github.com/VegetaxD)

#### Open Source codes used in this project 
- https://github.com/callsmusic/callsmusic : Source code used here as base
- https://github.com/DevsExpo/FridayUserbot/blob/master/main_startup/helper_func/basic_helpers.py : Functioms from line 275 to 351
- https://github.com/TheHamkerCat/WilliamButcherBot/blob/dev/wbb/modules/music.py : From lines 170 to 178


> This project exists thanks to these awesome developers and their codes and contributions.
> And credits goes to all who supported, all who helped and API & environmental requirement package devs and all projects helped in making this project.
> Special thanks to you for using bot

# DEPLOY

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/Tonic990/PrimeMusic">
  <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-aqua?style=flat&logo=heroku" width="325" height="50.100" /></a></p>



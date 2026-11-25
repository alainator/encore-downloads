# What your devices can do with Encore

Encore runs on whatever you already have. This page says what each device brings to the party, and what you give up
compared with the ideal setup. **Today** = works now. **Coming** = planned, not built yet.

Building a setup? See [Build your own, for any budget](BUILD.md).

## The ideal setup: the Encore kit (coming)

A small box you carry to any party. It does everything on this page at once, with no internet needed.

| Part | Why |
|---|---|
| Mini PC (Intel N100 or N150, 16 GB, HDMI and USB-C video) | Runs the party, draws the TV picture and scores every singer |
| USB-C touchscreen (about 15") | The Station: the host's (or anyone's) controls at the box |
| 8 TB drive | Thousands of songs, no internet needed |
| USB Wi-Fi adapter | The kit's own Wi-Fi: guests scan two codes (Wi-Fi, then the party) and they're in |
| **2-4 USB wireless mic sets** (each mic with its own USB receiver), or UHF wireless mics into a multi-channel USB audio interface | **Every singer scored separately** and every voice through the speakers with almost no delay (the kit's own audio, not the browser) |
| Speakers (or the TV's) | Music and voices |

Songs come from Karaoke Studio: synced at home over the network, or carried on a USB stick.

## Hosting the party (pick one)

| Host | Without internet | TV picture | Singing score | Voice through the speakers | What you give up |
|---|---|---|---|---|---|
| **Encore kit** | Yes (its own Wi-Fi) | HDMI | Every mic, each singer | Yes, almost no delay (coming) | Nothing |
| **Android tablet or phone** (Encore Station) | Yes, if everyone is on the same Wi-Fi or the tablet's hotspot | Encore TV app, casting, or screen mirroring (Smart View) | **Only while the tablet draws the TV picture itself (Smart View):** from the tablet's mic, or one Bluetooth mic | Through the tablet, with a noticeable delay | Multi-mic scoring; low-delay voices; the kit's own Wi-Fi and join codes. Keep the tablet charged: it runs the party |
| **Windows PC or laptop** | Yes, on the same Wi-Fi | A second screen (HDMI): the TV page full screen | One USB mic (or the laptop's) | Yes, with some delay | Multi-mic scoring; a touchscreen Station unless the laptop has one |
| **Home server** (Docker) | No: your home network | Encore TV app on each TV | Only on a TV page with a mic (a computer by the TV) | On that computer | The server can't hear a room: scoring needs a computer with a mic at the TV |

## TVs and streaming devices

| Device | Today | Gives up |
|---|---|---|
| **Encore TV app**: Android TV, Google TV, NVIDIA SHIELD, Chromecast with Google TV, Fire TV | The full TV picture, several TVs in sync (each with its own sound and volume, for TVs in different rooms), the screensaver, the next song saved ahead (weak Wi-Fi) | **No mic yet**: a USB mic plugged into the TV box isn't heard (coming: the app needs the microphone permission) |
| **Google Cast** (TVs with Chromecast built in) | The picture and sound, from the Station's "Cast to a TV" | The last resort: can freeze mid-party, no mic. Use the Encore TV app when you can |
| **Screen mirroring** (Samsung Smart View, Miracast) from the tablet | The tablet's TV picture on the TV, and scoring with the tablet's mic | The tablet has to stay on and close by; a little lag |
| **Smart TVs without Android** (Samsung Tizen, LG webOS) | — | No Encore TV app: plug in a streaming stick, or cast |

## Wi-Fi: where the host and the TVs stand

Every song goes from the host (the tablet running Encore Station, the laptop, the kit) over Wi-Fi to every TV, as
it plays. A weak link anywhere on that path pauses the song mid-way.

- **Keep the host near the router**, on 5 GHz if you can. A tablet carried into a garage or the yard makes every TV
  stutter, even the ones next to the router. Encore Station on Android watches its own Wi-Fi and tells the host on
  the station (and the host's phone) when it's weak: "This tablet's Wi-Fi is weak — the TV may stutter. Move it
  closer to the router."
- **A TV on weak Wi-Fi** (a garage, the far end of the house): the Encore TV app saves the next song to the TV while
  the current one plays (Party settings → Download the next song ahead, on by default) and plays it from there, so
  only the first song after it joins can pause. The station's TV list says when a TV's Wi-Fi is weak and whether it
  plays from storage. A cable (Ethernet) or a mesh point near the TV still beats any setting.
- A browser as the TV saves ahead only on an https:// address (for example behind a reverse proxy); on a plain
  http:// address it streams as before.

## Microphones

| Mic | Heard through the party's speakers | Scored | Notes |
|---|---|---|---|
| **USB wireless mic set** (USB receiver) | Yes (kit, PC) | Yes | The best choice. Several at once, each singer scored on their own |
| **Two wireless mics on one USB receiver** | Yes (kit, PC) | Yes: each mic separately when the receiver gives each mic its own channel (stereo), else one shared score | Encore tells by itself which kind it is. Not tried with a real receiver yet |
| **UHF wireless mics + USB audio interface** | Yes, mixed by the interface, no delay | Yes: one shared score today; each mic separately with a multi-channel interface (coming) | The classic karaoke setup |
| **USB mic** (wired) | Yes (kit, PC) | Yes | One per USB port |
| **Bluetooth mic or headset** paired with the host | Through the host, with a delay | One at a time | Phone-call sound quality and about 0.15-0.3 s of delay: run the Timing check so scoring lines up |
| **All-in-one Bluetooth karaoke mics** (a speaker in the handle) | No: each plays from its own speaker | No | Just sing: they work next to any Encore party, as many as people bring |
| **Phones** | — | — | Not used as mics: over Wi-Fi the voice comes too late to sing with |

## Guests' phones

Any phone with a browser (iPhone, Android): scan the code, add songs, see the queue, play the games, vote, change the key,
save a profile, add a photo. Nothing to install. They can add the page to their home screen if they like.

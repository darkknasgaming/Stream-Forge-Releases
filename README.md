<p align="center">
  <img
    src="https://github.com/user-attachments/assets/f621d7c6-7da3-4c0a-b609-fd5280f7df53"
    alt="Stream Forge"
    width="800"
  />
</p>

<p align="center">
  <a href="https://github.com/darkknasgaming/Stream-Forge-Releases/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/darkknasgaming/Stream-Forge-Releases?display_name=tag&label=Latest%20Release&color=ff7a00&style=for-the-badge"
      alt="Latest Stream Forge Release"
    />
  </a>
  <img
    src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=for-the-badge&logo=windows11&logoColor=white"
    alt="Windows 10 and 11"
  />
  <img
    src="https://img.shields.io/badge/Status-Alpha-ff7a00?style=for-the-badge"
    alt="Alpha Software"
  />
</p>

🔥 Stream Forge

Forge Your Stream.

Stream Forge is the brain behind your stream. OBS Studio, PRISM Live Studio or Streamlabs Desktop is the stage that shows it.

Stream Forge handles the automation, music, viewer interaction, alerts, remote control, community tools, stream lifecycle, backups and more.

OBS Studio, PRISM Live Studio and Streamlabs Desktop handle the video production and broadcast output your viewers actually see.

Think of it like this:

Stream Forge = control, logic and automation
OBS / PRISM / Streamlabs = video production and broadcast output

Stream Forge complements your broadcasting software — it does not replace it.

⬇️ Download Stream Forge

Windows 10 / 11

👉 Download the latest Stream Forge release

Stream Forge works alongside OBS Studio, PRISM Live Studio and Streamlabs Desktop.

Stream Forge runs the brains. Your broadcast software puts it on screen.

🔥 Stream Forge is currently Alpha software. Windows may show a SmartScreen warning while builds remain unsigned.

🔊 Important: OBS / PRISM Browser Source Audio Setup

Stream Forge can automatically create the recommended scenes and Browser Sources, but Browser Source audio may still need to be enabled manually in OBS Studio or PRISM Live Studio.

After running the automatic setup, open the Properties of each Stream Forge Browser Source that produces sound and enable:

✅ Control audio via OBS

Enable it for:

Starting

Alerts

Redeems

BRB

Music

VLC Music Bar

Song Requests

Ending

You do not need it for:

Logo

Gameplay Community / Avatars

Make sure the required sources appear in the audio mixer and are not muted.

Recommended: Run a short Unlisted stream test and listen from the viewer side before your first public stream.

Why is this manual?

During real-world testing, Browser Source audio settings were not always preserved or applied reliably through automated setup.

Rather than risk creating a stream with missing audio, Stream Forge keeps this final audio step visible and under your control.

🔥 What's New in 9.4.207

🎥 PRISM Live Studio Support

Stream Forge now officially supports PRISM Live Studio through the same OBS-compatible WebSocket engine used for OBS Studio.

Real live-stream testing confirmed:

Automatic Stream Forge scene/source setup

Scene switching and Scene Automation

Built-in Music

Alerts

Redeems

Viewer Song Requests

Auto End / broadcast lifecycle

Restart and reconnect behaviour

Viewer-side audio

PRISM support reuses Stream Forge's existing Broadcast Engine instead of introducing a second controller.

🖥️ Live Docks

A new Live Docks workspace puts the controls you need while streaming in one place.

Dockable tools include:

Music

Redeems

Auto Shoutouts

Timed Messages

Forge Studio

Custom Commands

Discord Safety Center

DroidOS Chat Lab

Scene Automation

Media & Alerts

Discord

Other existing Stream Forge docks

The central Live Docks hub means you no longer need to hunt through different Stream Forge tabs while live.

Main Stream Forge = setup and navigation
Live Docks = the controls you need right now

🎵 Music Dock

The Stream Forge Music Dock provides quick controls for:

Play / Pause

Skip

Stop

Mute / Unmute

Volume

Now Playing information

So when the music needs shutting up mid-stream, you don't need to go on a tab-hunting expedition.

🔔 Mission Control Update Notifications

Mission Control can now automatically check the public Stream Forge update channel.

When a newer Stream Forge version is available, Mission Control can display a visible update notification.

The existing manual Check for Updates option remains available.

🧭 Focused Dock Navigation

Live Docks are focused control windows instead of miniature copies of Stream Forge.

Main navigation is hidden inside docks

Mission Control / Settings / About links are removed from dock windows

Internal navigation returns to the existing main Stream Forge window

Duplicate Mission Control windows are prevented

🔄 Updating Stream Forge

Once the newer version is installed and you have confirmed Stream Forge opens correctly, you can safely delete the older downloaded installer .exe.

Your Stream Forge settings, configuration and local data are stored separately and are kept during updates.

Only delete the old downloaded installer.

Do not delete files from the installed Stream Forge application or data folders.

⚒️ What's New in 9.4.205

🔥 OBS Quick Setup

Connect Stream Forge to OBS and click Set Up OBS For Me.

Stream Forge can now automatically create and configure the recommended OBS scenes and Browser Sources for:

Starting Soon
Gameplay
BRB
Music
Ending

The only main thing left for the streamer to do is add their game/capture source to Gameplay.

Setup is repairable and designed not to duplicate existing Stream Forge scenes and sources.

📖 Setup Guide Improvements

Clear distinction between OBS Scenes and Browser Sources
Real OBS setup screenshots
Quick Start now directs users to Platform Hub
Cleaner first-time OBS setup instructions

⚒️ What's New in 9.4.204

🎵 Ending Music Queue Cleanup

Ending your stream now immediately:

Stops currently playing Stream Forge music

Stops active viewer-requested songs

Clears the pending song request queue

Prevents queued tracks from continuing during the Ending scene

No more heartfelt stream outro followed by a viewer-requested song suddenly kicking the door back open.

The stream is ending.

The jukebox dies with it.

🎶 Built-in Music & Song Requests

Stream Forge now includes its own music and viewer song request system.

Features include:

Built-in music playback

YouTube viewer song requests

Song request queue management

Automatic queue handoff

Now Playing information

Command-driven music overlays

Popup song overlays

Community-driven playback

Immediate cleanup when the stream enters Ending

All without requiring a separate song request bot.

📱 Stream Forge Remote

Control Stream Forge from another device on your local network.

Includes:

Mobile-friendly remote interface

QR-code pairing

Scene controls

Music controls

Stream controls

Secure local pairing workflow

Scan. Pair. Control the forge from the other side of the room.

Because apparently walking back to the PC is now beneath us.

🤖 Community Automation

Stream Forge includes built-in tools to keep your stream active even when you're busy actually playing the game.

Auto Shoutouts

Automatically recognise and shout out members of your community.

Timed Messages

Post configured messages automatically during your stream.

Useful for:

Community links

Reminders

Commands

Social links

Server information

Stream information

☕ Ko-fi Integration

Optional Ko-fi support is built into Stream Forge.

The donation alert pipeline has been tested live through the real streaming workflow:

Ko-fi → payment → YouTube chat → Stream Forge → on-stream alert

Ko-fi support remains completely optional.

No account?

No problem.

Stream Forge continues working normally without it.

🎬 Stream Automation

Stream Forge provides automated control over key parts of the streaming lifecycle, including:

Starting scenes

Live scenes

Ending scenes

Scene automation

Auto End

Broadcast lifecycle handling

YouTube broadcast lifecycle integration

Stream status tracking

These systems remain protected and regression-tested as Stream Forge continues development.

💬 Community Features

Stream Forge brings viewer interaction directly into the application.

Current systems include:

YouTube chat integration

Twitch integration

Viewer alerts

Redeems

Community events

Auto Shoutouts

Timed Messages

Viewer song requests

Music overlays

Ko-fi alerts

Stream automation

Remote control

And we're nowhere near finished yet.

💾 Full Backup & Recovery

Stream Forge includes a Full Backup system designed to protect your configuration and streamer data.

Back up your setup before experimenting, upgrading or allowing the software developer to say:

"This change should be safe."

Those are historically dangerous words.

🛠 Installer

Stream Forge now includes a custom Windows installer featuring dedicated Stream Forge branding.

Installation

Download the Windows installer below.

Run the .exe.

Follow the Stream Forge installer.

Launch Stream Forge.

Start forging.

Windows may display a SmartScreen warning while Stream Forge is unsigned during Alpha development.

🧪 Alpha Software

Stream Forge is currently in active Alpha development.

Although major workflows are being actively tested — including real YouTube streams — bugs may still exist.

If something explodes:

Don't panic.

Check that it isn't OBS.

Check that it isn't YouTube.

Check that it isn't Windows.

Then blame Stream Forge.

Bug reports and testing feedback are extremely valuable during Alpha.

🐉 Current Highlights

System

Status

YouTube Integration

✅

Twitch Integration

✅

Scene Automation

✅

Auto End

✅

Broadcast Lifecycle

✅

Stream Forge Remote

✅

QR Pairing

✅

Built-in Music Player

✅

Viewer Song Requests

✅

Music Overlays

✅

Auto Shoutouts

✅

Timed Messages

✅

Ko-fi Alerts

✅ Optional

Full Backup

✅

Custom Windows Installer

✅

OBS Studio Integration

✅

PRISM Live Studio Integration

✅

Live Docks

✅

Music Dock

✅

Mission Control Update Notifications

✅

🔐 Privacy & Local Data

Stream Forge keeps streamer configuration and application data local wherever possible.

Release packages intentionally exclude:

.env

Local user data

Authentication tokens

API credentials

Private configuration

Streamer-specific runtime data

A safe .env.example template is included where required.

❤️ Support Stream Forge

Stream Forge is free software.

There are no required subscriptions or paid feature tiers.

If Stream Forge helps your stream and you'd like to support continued development, optional Ko-fi donations are always appreciated.

Using Stream Forge, reporting bugs, testing releases and telling other streamers about it helps just as much.

📦 Latest Release

Stream Forge

v1.5.1 Alpha 9.4.207

PRISM Live Studio & Live Docks

Built. Tested. Streamed.

🔥 FORGE YOUR STREAM.

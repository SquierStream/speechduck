# Privacy Policy — SpeechDuck

_Last updated: August 2026_

SpeechDuck is a Stream Deck plugin that automatically lowers ("ducks") the volume of selected applications or output devices while you speak into a microphone or a conferencing app plays audio.

## What SpeechDuck accesses

To do this, SpeechDuck reads, entirely on your own computer, via the Windows Core Audio API:

- The list of currently running applications that have an active audio session.
- The real-time volume/level of your chosen microphones, output devices, and application audio sessions.
- The volume of the applications or devices you've configured as ducking targets, so it can lower and restore them.

## What SpeechDuck does **not** do

- It does not record, store, or transmit any audio.
- It does not send any data — process names, audio levels, or settings — off your computer. There are no analytics, telemetry, or third-party services involved.
- It does not access the internet at all during normal operation.

## Where your settings are stored

Your Triggers, Targets, and preferences (attack/sustain/release, interface language, etc.) are stored locally by the Stream Deck app itself, the same way it stores settings for any other plugin. SquierStream has no access to this data.

## Changes to this policy

If this policy changes, the update will be posted on this page with a new "Last updated" date.

## Contact

Questions about this policy can be sent via [GitHub Issues](https://github.com/SquierStream/speechduck/issues/new/choose) or to **speechduck.support@gmail.com**.

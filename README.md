# SpeechDuck

Automatic sidechain audio ducking for the Elgato Stream Deck. SpeechDuck lowers your music, game, or desktop audio the instant you speak — into a microphone, or when a conferencing app plays audio back — and brings it back the moment you stop.

This repository is the public support hub for the plugin: bug reports, questions, and feedback go here as [GitHub Issues](../../issues/new/choose). It does not contain the plugin's source code.

## Get SpeechDuck

- **Full version** — available on the Elgato Marketplace *(link to be added once published)*.

## Setup Guide

1. Install SpeechDuck from the Elgato Marketplace and add the **Duck Toggle** action to any key.
2. Open the key's settings (Property Inspector) and add at least one **Trigger** (a microphone, an output device, or an application) and one **Target** (what should be lowered while a trigger is active).
3. Adjust **Attack / Sustain / Release** to taste, and drag directly on the live level meter to set each trigger's threshold.
4. Press the key to arm the effect. The key doubles as a live level meter while armed.

## Support

Having a problem, a question, or an idea? Please [open an issue](../../issues/new/choose) and pick the template that fits — Bug report, Question / Support, or Feedback / Feature request.

You can also reach us directly: **speechduck.support@gmail.com**.

## Privacy

SpeechDuck reads audio session levels and process names from Windows Core Audio locally on your machine to detect triggers and apply ducking. It does not transmit any audio, process, or usage data off your computer.*

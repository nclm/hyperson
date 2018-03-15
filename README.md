This repository aims to become a specification for an hyper~~text~~audio file format.

It will allow things like:
* Songs with branching verses.
* Songs with alternate/optional lyrics.
* Interactive podcasts (“If you’d like to know more about this, press 1”).
* Choose-your-own-adventure audio stories.

The file format should be eventually readable by audio players (specific ones or compatible general-purpose ones), as a background task. The user would be able to interact with the audio without leaving any other current app, through shortcuts (e.g. “Ctrl+1”, “Ctrl+2”, etc). The invitation to press a key can either be said in the audio or displayed as a notification.

Technical:
* Audio format: Ogg Vorbis? Flac? Not specified?
* Manifest file?
* Story: Twine story file? XML? Json?
* Ability to specify not just files but timestamps in files (simple use case: single-file podcast with table of contents)
* Container: Tar?

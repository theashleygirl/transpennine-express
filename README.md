# transpennine-express

Announcement audio for the transpennine-express announcement system.

## Structure

All audio is in [Original](./Original/) with its original names. Transcripts are in
[Transcripts](./Transcripts/), one CSV per audio folder, in the
[announcement-utils](https://github.com/Rail-Announcements/announcement-utils) format.

Station files end in their CRS code (e.g. `sta_btn` is Brighton); their names come from a
CRS lookup. Everything else was transcribed with Whisper large-v2 (VAD on). Blank rows are
clips with no speech (chimes, sirens, silence). Transcripts are machine-generated and not
fully proofread.

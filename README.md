# 香港、最初の夜 | Hong Kong, the First Night

A 90-second AI short by Andy Chum, set in 1970s Hong Kong and inspired by Kōtarō Sawaki’s *Shinya Tokkyū* (『深夜特急』). The film follows a newly arrived traveller from Kai Tak Airport to a Kowloon guesthouse and out onto Nathan Road.

[Watch the finished film on YouTube](https://youtu.be/ujKfURZipWw)

## How I made it with Google Flow

1. **Planned the sequence.** I broke the story into short shots and established the traveller’s face, clothes and canvas bag, along with recurring details such as the ivory Mercedes.
2. **Generated moving shots.** I gave Google Flow a horizontal reference image for each scene and prompted the actions in order, such as when the car should stop, when the passenger should step out and when the car should pull away.
3. **Reviewed and revised.** I checked movement and continuity between shots, replaced takes where a character appeared in the wrong scene, and simplified the closing shot to picture only after Flow reported an audio-generation failure.
4. **Assembled and finished the edit.** I sequenced 11 moving clips in Flow and exported the 88-second picture edit. I retimed it to exactly 90 seconds with FFmpeg and added the opening title, synthetic Japanese narration, music, street ambience and burned-in Japanese subtitles.

## Final release

- **Format:** 1280 × 720, 16:9, 24 fps
- **Runtime:** 1:30
- **Language:** Japanese voiceover and subtitles
- **Visuals:** AI-generated dramatisation of 1970s Hong Kong

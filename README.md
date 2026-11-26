# bangla-kids-animation
Educational 2D animation stories and creative resources for children.
ANIMATION PROMPT SCRIPT — "শেষ চিঠি" STYLE
(এই ফাইলটা + গল্পের স্ক্রিপ্ট + ভয়েস mp3 একসাথে দিলে Claude একই ধরনের অ্যানিমেশন বানাবে)

────────────────────────────────────────

1. OUTPUT
   ────────────────────────────────────────

- Format: 9:16 vertical, 1080×1920, 30 fps, single .mp4, under ~30 MB, H.264 + AAC.
- Duration: exactly the length of the voice file (voice-over stories) / the length written in the script (silent stories).
- Channel: "অপ্রকাশ". Language of all on-screen text: Bengali (English title card only if asked).
- Deliver in ONE attempt, high quality, then a short Bengali summary.

────────────────────────────────────────
2) VISUAL STYLE (must stay identical in every video)
────────────────────────────────────────

- Flat 2D cartoon with THICK dark outlines. Clean, bright, saturated colours.
- NO dark vignette, NO film grain, NO haze, NO blur on edges. Keep it bright and clean.
- Characters: big-head, front-facing, simple expressive faces (round eyes with highlights, thick eyebrows, blush on cheeks when happy/shy, wide "o" mouth for surprise, big open smile for joy). Same face style for every character; different skin tone, hair, clothes, accessories (glasses, beard, cap, panjabi) to tell them apart.
- Character design must stay the SAME (face, clothes, proportions, colours) in every scene of a video.
- Arms/hands animate to match the action (pointing, holding a book, wiping tears, waving). Idle breathing/bobbing + blinking always on.
- Lip-sync: when a character speaks, the mouth opens/closes with the voice loudness.
- Backgrounds: simple but detailed Bangladeshi everyday settings (street with shops and striped awnings, classroom, home room, field), soft clouds, sun, trees. Sky/lighting colour follows the time of day (orange sunset, blue day, night).
- Camera: slow zoom / pan on close-ups, smooth cross-fades between scenes, no sudden cuts.

────────────────────────────────────────
3) SCREEN LAYOUT (every frame)
────────────────────────────────────────

- TOP: small white pill with the text "অপ্রকাশ" (always, every video).
- Just below it: a small dark-red scene-label pill with a 2–3 word scene title (e.g. "আবার বৃদ্ধের কাছে", "জমানো টাকা").
- MIDDLE: the full-bleed illustration, characters large (close/medium shots) and expressive.
- BOTTOM: cream rounded caption card with a small round microphone icon + speaker label ("কথক" for narration, or the character's name with his face icon when he speaks).
  - Caption text = the voice line, synced word-chunk by word-chunk with the voice (burned in, never ahead of or behind the voice).
  - Line 1 dark, line 2 red. Dialogue lines are shown inside quotation marks.
- Keep every important element inside the central safe zone (≈ 8% margin top and bottom) so nothing is cut off in the YouTube Shorts grid.

────────────────────────────────────────
4) SYNC RULES (most important)
────────────────────────────────────────

- Voice, scene and on-screen action must match exactly. If the voice says it, the screen shows it at that moment.
- A scene must NOT end before the narration of that scene finishes.
- Align captions and scene changes to the real voice timing (silence detection + syllable-weighted alignment), then verify by cross-correlation (offset 0.0).
- Props appear exactly when mentioned (book, coins, letter, envelope…), and stay consistent afterwards.

────────────────────────────────────────
5) SOUND DESIGN
────────────────────────────────────────

- Voice is ALWAYS clearly audible. Sound effects and music are only quiet support and must duck under the voice.
- SFX must be soft and pleasant, never sharp/harsh/repetitive (no loud footsteps, no rustling spam, no hissing). Low-pass everything above ~4–5 kHz. Sparse, natural, matched to real actions (page turn, coins, soft footstep, door, ambience of street/home).
- Gentle emotional background music (piano/strings pad), no vocals; swells softly at emotional moments, fades out at the end.
- Final loudness normalised, no clipping.

────────────────────────────────────────
6) STORY STRUCTURE (what a good "অপ্রকাশ" story video looks like)
────────────────────────────────────────

- First 3 seconds = strong hook (a question, a surprise or a striking image) — never a slow intro.
- Then problem → small kindness/decision → turning point → emotional peak (letter/gift/reveal) → moral.
- End with the moral card (শিক্ষা) in the same caption style, then a soft fade.
- When the voice asks viewers to subscribe / follow / DM: show the channel's YouTube card, then the Facebook page card, with subscriber / follower / following / video counts HIDDEN. (Use the latest logo/banner screenshots.)

────────────────────────────────────────
7) THUMBNAIL (deliver together with the video)
────────────────────────────────────────

- Same art style, big readable title (line 1 dark, line 2 red) on a cream card, a bold ribbon (e.g. "পর্ব ১"), one strong emotional character close-up or key object, "অপ্রকাশ" pill.
- All text and faces must sit inside the central safe zone (YouTube Shorts grid crops top and bottom).

────────────────────────────────────────
8) HOW TO USE THIS FILE
────────────────────────────────────────
Send Claude:
(a) this prompt script,
(b) the story script (with voice-direction tags if you have them),
(c) the ElevenLabs voice mp3 (real .mp3/.wav, not renamed to .txt),
(d) any character reference image.
Then write: "এই স্টাইলে বানাও" — Claude builds the full video, syncs it to the voice, adds soft SFX + music, and sends the mp4 (+ thumbnail on request).

For SILENT stories (no voice): add a scene list with timings and sound-effect notes (like "SCENE 1 — 00:00–00:25"), and Claude will tell the story purely through expressions, body language, and layered soft sound design.

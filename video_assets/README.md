# Beyond the Safari Video Assets

This folder contains everything needed to assemble the 2–3 minute "Beyond the Safari" documentary-style video.

## Contents
- `beyond_the_safari_video_plan.md` – production brief with scene timing, narration, AI prompt pack, and editing notes.
- `beyond_the_safari_captions.srt` – ready-to-import subtitles that sync with the narration.

## Where is the MP4?
The execution environment for this repository cannot render or upload binary video files because:
1. Video toolchains such as FFmpeg are not installed, and network access for installing them (or using cloud AI video tools) is blocked.
2. Binary artifacts are generally avoided in Git to keep the repo lightweight and reviewable.

## How to Produce the Final Video Yourself
1. **Generate footage:** Use the 13 prompts in the plan to create b-roll via Runway, Pika, Luma, stock footage, or in-person filming.
2. **Record narration:** Read the condensed script (Section 3 of the plan) at ~115 wpm and export high-quality WAV/AIFF audio.
3. **Edit:**
   - Place narration + music on the timeline.
   - Drop the clips according to the scene table (Section 2) and apply the suggested titles.
   - Import `beyond_the_safari_captions.srt` for subtitles.
4. **Master & export:** Follow Section 8 of the plan for color, mix, and delivery specs, then render a 1080p or 4K MP4.

With those steps, you can deliver the finished video in under an hour using any NLE (Premiere, Final Cut, CapCut, DaVinci, etc.).

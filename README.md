# Bob Has Questions. Unfortunately.

Public, AI-generated learning audio created with Google's NotebookLM.

- Website: https://boberdman.github.io/personal-learning-podcast/
- RSS subscription URL: https://boberdman.github.io/personal-learning-podcast/feed.xml
- First episode: **Why Nobody Can Read the Voynich Manuscript**, 23:21, English.

The feed and show artwork are served by GitHub Pages. Episode audio is a GitHub Release asset. The repository contains public delivery assets; research notebooks and source documents are kept separately.

## Episode 2

**Keep Your Curiosity, Lose the Open Loops**, 18:22, English, hosted by Bob 1.0 and River.

A research-based conversation about curiosity, choosing a current focus, and returning to paused projects. Hosted by Bob 1.0 and River. Both hosts are AI-generated: Bob 1.0 uses a clone of Bob's own voice with his permission; River is an AI-generated host. The project-card experiment is a practical proposal to try, not a research-validated program.

Audio: 192 kbps mono MP3, 44.1 kHz, **26,440,087 bytes**.

SHA-256: `8d4f1a31acf88bb24eb08bdfa73791301f0a1150a59ab151009a73da12388f12`

## Episode 1

An AI-generated NotebookLM conversation about the Voynich manuscript: its illustrated pages, scientific examination, language-like patterns, and disputed interpretations. The manuscript remains undeciphered; this episode explores evidence and hypotheses rather than claiming a solution.

Audio: 128 kbps stereo MP3, 44.1 kHz, **22,419,428 bytes**.

SHA-256: `e9f568829f4a28320182c914977e8eee52ff20f8b9c110439a53ac1c7b4ca2b2`

## Adding an episode

1. Create a new release tag and upload a unique MP3 asset.
2. Add one RSS item with a permanent unique GUID, publication date, duration, and enclosure URL, exact byte length, and `audio/mpeg` type.
3. Add the episode to the landing page.
4. Verify HTTPS, HEAD, Range 206, and the downloaded audio checksum before announcing the episode.

Keep each published episode's GUID and enclosure URL stable. Do not overwrite an existing audio asset for a new episode.

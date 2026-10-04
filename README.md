# Personal Learning Podcast

Public, AI-generated learning audio created with Google's NotebookLM.

- Website: https://boberdman.github.io/personal-learning-podcast/
- RSS subscription URL: https://boberdman.github.io/personal-learning-podcast/feed.xml
- First episode: **Why Nobody Can Read the Voynich Manuscript**, 23:21, English.

The feed and show artwork are served by GitHub Pages. Episode audio is a GitHub Release asset. The repository contains public delivery assets; research notebooks and source documents are kept separately.

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

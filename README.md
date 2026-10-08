# Bob Has Questions. Unfortunately.

A personal learning podcast created and directed by Bob. AI-assisted research checked against sources and AI-generated voices turn his curiosity into learning conversations. Hosted by Bob 1.0, an AI voice based on Bob, and River.

- Website: https://boberdman.github.io/personal-learning-podcast/
- RSS subscription URL: https://boberdman.github.io/personal-learning-podcast/feed.xml
- First episode: **Why Nobody Can Read the Voynich Manuscript**, 23:58, English.

The feed and show artwork are served by GitHub Pages. Episode audio is a GitHub Release asset. The repository contains public delivery assets; research notebooks and source documents are kept separately.

## Episode 3

**The Voynich Manuscript: Strange Theories, Hidden Knowledge, and the Evidence**, 39:06, English, hosted by Bob 1.0 and River.

An in-depth conversation about the Voynich manuscript's unconventional and nonmaterialist interpretations, including visionary writing, secret knowledge, and extraterrestrial theories. Bob 1.0 and River distinguish documented facts from speculation and debate what evidence would support or weaken these ideas. The manuscript remains undeciphered; no alien or supernatural explanation is established. Both hosts are AI-generated: Bob 1.0 uses a clone of Bob's own voice with his permission; River is an AI-generated host.

Audio: 128 kbps mono MP3, 44.1 kHz, **37,533,426 bytes**.

SHA-256: `288b054918169fec54e5cc22dbc38d10ea78c159958e21061464e60e214ccfcf`

## Episode 2

**Keep Your Curiosity, Lose the Open Loops**, 17:30, English, hosted by Bob 1.0 and River.

A research-based conversation about curiosity, choosing a current focus, and returning to paused projects. Hosted by Bob 1.0 and River. Both hosts are AI-generated: Bob 1.0 uses a clone of Bob's own voice with his permission; River is an AI-generated host. The project-card experiment is a practical proposal to try, not a research-validated program.

Audio: 192 kbps mono MP3, 44.1 kHz, **25,197,573 bytes**.

SHA-256: `63c6446ab1877e837d6a79771a73a909bc071a19c5b17c7cc31f8400f9d7465c`

Final v2 audio includes the reusable intro and outro. The [original 18:22 MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/curiosity-002/Episode-02-Keep-Your-Curiosity-Bob-1-0-and-River.mp3) is retained for rollback. The episode GUID and original publication date are unchanged.

## Episode 1

An AI-generated conversation about the Voynich manuscript: its illustrated pages, scientific examination, language-like patterns, and disputed interpretations. The manuscript remains undeciphered; this episode explores evidence and hypotheses rather than claiming a solution.

Audio: 192 kbps mono MP3, 44.1 kHz, **34,521,425 bytes**.

SHA-256: `5ddd0aa767b8b69410f692d311cc1969e0c878048b8ecd37c8eb1a4371255a78`

Final v2 audio is a source-grounded revision hosted by Bob 1.0 and River and includes the reusable intro and outro. The [original 23:21 MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/voynich-001/why-nobody-can-read-the-voynich-manuscript-podcast-128k.mp3) is retained for rollback. Historical provenance: the original audio was created with NotebookLM. The episode GUID and original publication date are unchanged.

## Adding an episode

1. Create a new release tag and upload a unique MP3 asset.
2. Add one RSS item with a permanent unique GUID, publication date, duration, and enclosure URL, exact byte length, and `audio/mpeg` type.
3. Add the episode to the landing page.
4. Verify HTTPS, HEAD, Range 206, and the downloaded audio checksum before announcing the episode.

Keep each published episode's GUID and enclosure URL stable. Do not overwrite an existing audio asset for a new episode.

# Bob Has Questions. Unfortunately.

A personal learning podcast created and directed by Bob. AI-assisted research checked against sources and AI-generated voices turn his curiosity into learning conversations. Hosted by Bob 1.0, an AI voice based on Bob, and River.

- Website: https://boberdman.github.io/personal-learning-podcast/
- RSS subscription URL: https://boberdman.github.io/personal-learning-podcast/feed.xml
- First episode: **Why Nobody Can Read the Voynich Manuscript**, 24:40, English.

The feed and show artwork are served by GitHub Pages. Episode audio is a GitHub Release asset. The repository contains public delivery assets; research notebooks and source documents are kept separately.

## Episode 4

**Quantum Computing: The Majorana Bet and What DARPA Is Testing**, 21:14, English, hosted by Bob 1.0 and River.

A conversation about how quantum computers use superposition, interference, and entanglement, why error correction matters, and what Microsoft's Majorana approach would need to demonstrate. Bob 1.0 and River examine the Majorana 2 parity-lifetime results and DARPA's independent evaluation, distinguishing reported measurements, company targets, and useful computation. Evidence reviewed 8 October 2026; evaluation is not completed validation. Both hosts are AI-generated: Bob 1.0 uses a clone of Bob's own voice with his permission; River is an AI-generated host.

Audio: 192 kbps mono MP3, 44.1 kHz, **30,568,324 bytes**.

SHA-256: `f2a23eddcce2550ec02e7959909703ab1608271bbbfae72d99f06645152d29b7`

Revised v3 uses Bob 1.0 and River (Jane), with the canonical Bob intro and matching Jane outro. The episode GUID and original publication date are retained; the previous audio remains available for rollback. [Listen on the website](https://boberdman.github.io/personal-learning-podcast/#quantum) or [download the MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/quantum-004-revision-20261011/Bob-Has-Questions-Episode-04-Release-v3.mp3).

Sources: [Microsoft's Majorana 2 research](https://quantum.microsoft.com/en-us/insights/blogs/majorana-2-scalable-quantum-processor) · [Parity-lifetime research preprint](https://arxiv.org/html/2606.03884v2) · [DARPA Quantum Benchmarking Initiative](https://www.darpa.mil/research/programs/quantum-benchmarking-initiative)

## Episode 3

**The Voynich Manuscript: Strange Theories, Hidden Knowledge, and the Evidence**, 38:31, English, hosted by Bob 1.0 and River.

An in-depth conversation about the Voynich manuscript's unconventional and nonmaterialist interpretations, including visionary writing, secret knowledge, and extraterrestrial theories. Bob 1.0 and River distinguish documented facts from speculation and debate what evidence would support or weaken these ideas. The manuscript remains undeciphered; no alien or supernatural explanation is established. Both hosts are AI-generated: Bob 1.0 uses a clone of Bob's own voice with his permission; River is an AI-generated host.

Audio: 192 kbps mono MP3, 44.1 kHz, **55,470,333 bytes**.

SHA-256: `82ed1a3229358612d27f64c269e1027fd00862ee3dcbc7f4c68cfc7bda1edfde`

Revised v3 uses Bob 1.0 and River (Jane), with the canonical Bob intro and matching Jane outro. [Listen on the website](https://boberdman.github.io/personal-learning-podcast/#voynich-theories) or [download the MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/voynich-003-revision-20261011/Bob-Has-Questions-Episode-03-Release-v3.mp3). The original episode GUID and publication date are retained; [original audio](https://github.com/boberdman/personal-learning-podcast/releases/download/voynich-003/Episode-03-The-Voynich-Manuscript-Bob-1-0-and-River-128kbps.mp3) remains available for rollback.

## Episode 2

**Keep Your Curiosity, Lose the Open Loops**, 18:50, English, hosted by Bob 1.0 and River.

A research-based conversation about curiosity, choosing a current focus, and returning to paused projects. Hosted by Bob 1.0 and River. Both hosts are AI-generated: Bob 1.0 uses a clone of Bob's own voice with his permission; River is an AI-generated host. The project-card experiment is a practical proposal to try, not a research-validated program.

Audio: 192 kbps mono MP3, 44.1 kHz, **27,124,704 bytes**.

SHA-256: `874d994f56d11203fb4be1f7cb7b37d4c91ed0250484c83d6833cf2f94805c10`

Revised v3 has Bob asking the questions and River explaining the ideas, with the canonical Bob intro and matching River outro. [Listen on the website](https://boberdman.github.io/personal-learning-podcast/#curiosity) or [download the MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/curiosity-002-revision-20261010/Bob-Has-Questions-Episode-02-Release-v3.mp3). The [previous 17:30 MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/curiosity-002-revision-20261007/Bob-Has-Questions-Episode-02-Release-v2.mp3) and [original 18:22 MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/curiosity-002/Episode-02-Keep-Your-Curiosity-Bob-1-0-and-River.mp3) remain available for rollback. The episode GUID and original publication date are unchanged.

## Episode 1

An AI-generated conversation about the Voynich manuscript: its illustrated pages, scientific examination, language-like patterns, and disputed interpretations. The manuscript remains undeciphered; this episode explores evidence and hypotheses rather than claiming a solution.

Audio: 192 kbps mono MP3, 44.1 kHz, **35,519,260 bytes**.

SHA-256: `5ac8f316ce909b46c34979b7ece0204e10bb55518d51b14c9e70ce10c2029242`

Revised v3 audio is a source-grounded conversation hosted by Bob 1.0 and River (Jane), with the canonical Bob intro and matching Jane outro. [Download the 24:40 MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/voynich-001-revision-20261011/Bob-Has-Questions-Episode-01-Release-v3.mp3). The [original 23:21 MP3](https://github.com/boberdman/personal-learning-podcast/releases/download/voynich-001/why-nobody-can-read-the-voynich-manuscript-podcast-128k.mp3) is retained for rollback. Historical provenance: the original audio was created with NotebookLM. The episode GUID and original publication date are unchanged.

## Adding an episode

1. Create a new release tag and upload a unique MP3 asset.
2. Add one RSS item with a permanent unique GUID, publication date, duration, and enclosure URL, exact byte length, and `audio/mpeg` type.
3. Add the episode to the landing page.
4. Verify HTTPS, HEAD, Range 206, and the downloaded audio checksum before announcing the episode.

Keep each published episode's GUID and enclosure URL stable. Do not overwrite an existing audio asset for a new episode.

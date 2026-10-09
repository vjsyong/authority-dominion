# Archive manifest - dominion

Authority: `authorities/dominion` @ 0.2.0 - generated 2026-10-09T14:44:54+00:00 UTC

| file | role | sha256 (first 16) | size |
|---|---|---|---|
| `.site-state.json` | refresh state (pack hash, version, artifact set) | `997e6cf8199ca03d` | 905 |
| `agent-brief.md` | asset | `d5283c33454da995` | 4546 |
| `audit.jsonl` | machine-recorded authority call trace | `7d48d3ccc4215654` | 45467 |
| `brief.md` | build brief | `5dc7fad11d7f981b` | 2223 |
| `index.html` | page | `67324704f938f635` | 38942 |
| `log.md` | build log (agent, 1:1 with audit.jsonl) | `948345edc036543f` | 33797 |
| `refresh-log.md` | refresh log (generated layers vs pack) | `811d497575b720ba` | 3198 |
| `run-authority` | audited runner (build-time tool) | `e22276930fe7da67` | 1039 |
| `styles.css` | stylesheet | `d7859270a735dc93` | 13214 |
| `fonts/Arimo-VF.ttf` | brand font file | `e43898b143ec826a` | 496268 |
| `.design-authority/gaps.jsonl` | gap store (filed gaps) | `ff7688dd4c575f0d` | 2441 |

External references: 1 (must be 0).

- `fonts/Arimo-VF.ttf`: byte-identical to `docs/synthesis/dominion/tile/fonts/Arimo-VF.ttf` -> True

Verify: `python3 tools/archive_authority_assets.py --verify dominion`

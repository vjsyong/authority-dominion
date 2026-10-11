# Archive manifest - dominion

Authority: `authorities/dominion` @ 0.3.0-rc1 - generated 2026-10-11T09:53:07+00:00 UTC

| file | role | sha256 (first 16) | size |
|---|---|---|---|
| `.site-state.json` | refresh state (pack hash, version, artifact set) | `7fbb206a622c7e25` | 909 |
| `agent-brief.md` | asset | `ac544aa0c5442f1a` | 4550 |
| `audit.jsonl` | machine-recorded authority call trace | `7d48d3ccc4215654` | 45467 |
| `brief.md` | build brief | `5dc7fad11d7f981b` | 2223 |
| `index.html` | page | `6a392242186de65b` | 38972 |
| `log.md` | build log (agent, 1:1 with audit.jsonl) | `948345edc036543f` | 33797 |
| `refresh-log.md` | refresh log (generated layers vs pack) | `9b7c3e057df11790` | 3574 |
| `run-authority` | audited runner (build-time tool) | `e22276930fe7da67` | 1039 |
| `styles.css` | stylesheet | `d7859270a735dc93` | 13214 |
| `fonts/Arimo-VF.ttf` | brand font file | `e43898b143ec826a` | 496268 |
| `.design-authority/gaps.jsonl` | gap store (filed gaps) | `ff7688dd4c575f0d` | 2441 |

External references: 1 (must be 0).

- `fonts/Arimo-VF.ttf`: byte-identical to `docs/synthesis/dominion/tile/fonts/Arimo-VF.ttf` -> True

Verify: `python3 tools/archive_authority_assets.py --verify dominion`

# rakazo-core-skills

A curated set of 127 skills for a self-hosted Rakazo v0.12.0 library. Every file is an unchanged copy of an upstream file, pinned to these commits (all MIT):

- affaan-m/ECC @ d2ef2680594f9a17526a6e1a2e18b3d242c5d17b: 80 skills (catalog/skills), 17 agents and 7 commands (subagents-commands/).
- NousResearch/hermes-agent @ 3b421578588243f920886e6fe79a6faa87ea026e: 19 skills.
- NousResearch/hermes-official-plugins @ e726eb7d5f6e7f4b2f3d149e482fcfbc7304b275 (hermes-security): 3 skills.
- forrestchang/andrej-karpathy-skills @ 2c606141936f1eeef17fa3043a72095b4765b9c2: karpathy-guidelines.

To import in Rakazo: Skills, then From GitHub. Paste `.../tree/<commit>/catalog`, choose Preview, then Add. Repeat with `.../tree/<commit>/subagents-commands`.

## Import note

Content commit: bc14feb240fd1baf5ca8eca3ebc6a471ab13d64e. A small follow-up commit sits on top so the GitHub commit API response for the pinned tip stays under Rakazo's 512 KB limit. Pin imports to the latest commit on main.

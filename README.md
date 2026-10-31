# BlockWatch v0.1
Block escalator for the Spec Op squad. `blocks.json` lists each block (who, blocked_by, started, resolved). The page shows every block; any open block older than 15 minutes turns red and is marked **ESCALATE TO ANNOUNCER**.
To add a block: append an entry to `blocks.json` with `resolved: null`. To clear it: set `resolved` to an ISO time.

> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · This page does not start a machine.

# Plan

The day is **Tue 10 Nov 2026**. The shape and the times are Saturday 7 Nov. T0 is 19:00 UTC. Both pastes carry this clock. The standing rule is [RULES.md](../RULES.md).

This writing is in front of Kaspa Pulse for a revision. A read does not start a runner while this sentence is in the file.

## Shape

One sender. The desk. Offer 1.2 hop/s per family. Boson. Stagger 0. No phase offset.

| UTC | What | How long |
|---|---|---|
| 19:00–19:15 | 1 family | 15 min |
| 19:20–19:35 | 2 families | 15 min |
| 19:40–19:55 | 4 families | 15 min |
| 20:00–20:15 | 8 families, only if 4 held 1.14 | 15 min |
| 20:20–20:30 | Ramp, 50 s on / 10 s off, +0.1 from 1.2 toward 2.1 | 10 min |
| 21:15–22:00 | 32 families, offer 1.2 | 45 min |

If 4 does not hold the line, skip 8 and start the ramp at 20:00 UTC. The load stays at 21:15.

The early ramp may share the 8-family clock. It runs only when 4 does not hold the line. The gate writes the SKIP file in the five-minute gap. The later ramp runs only when the 8-family step runs.

The ramp stops when two gains in a row are under 3%. The test uses the unrounded gain. A printed 3.0 can still be under 3%.

20:30–21:00 UTC is quiet. The count stays up through 21:00 so that half hour is in the file.

## Counts

Both machines count the same two windows and each publishes its own folder.

| File | On | Off | Desk | Mini |
|---|---|---|---|---|
| FIRST.md | 18:58 | 21:00 | counts/desk/ | counts/mini/ |
| LOAD.md | 21:13 | 22:15 | counts/desk/ | counts/mini/ |

The rule is [COUNT.md](COUNT.md).

## Hashes

| File | Before |
|---|---|
| hashes/EIGHT.md | 18:40 UTC |
| hashes/THIRTYTWO.md | 21:10 UTC, and after the eight-family genesis has spent its coins |

Each file gets an On origin time from the commit that put the rows on GitHub. No proved file, no send.

## Funding

Before the first genesis, every key the night will use has one eligible coin for the eight-family genesis and one left for the load. Thirty-two hashes are published after that genesis, so the published row and the load genesis name the same remaining coin. Do not spend a mining coin at or above 100,000 tKAS. Do not print a balance, a key, or an id. Sixteen families are not this night, so no key is asked for a third genesis.

## Abort

2,500 coins and 18,000 usable tKAS, checked before genesis and again before the load. Fee stays where the counted windows left it. A fee reject stops that part. Faults: sender-off, pool-low, node-drop, proc-exit. A start of the load after 23:00 UTC does not happen.

One process on the desk chains the eight-family window, then the load. The load starts only if the earlier phase log ended on the window, with no launch abort, no family drop, and no sender exit before the end.

## What this plan does not change

The 7 Nov repo stays the record of the window that did not run. The 8 Nov repo stays the rehearsal. The 10:40 UTC confirmation stays its own clock. This plan does not start a sender for any of them.

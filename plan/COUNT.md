> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Kaspa Testnet-10 only. Counts only.

# Count

A hop counts in a step when the accepting block's header time is inside that step. That header time is the file clock. The desk's notice time is not the file clock. Mini's local receive time is not the file clock.

1.14 over a 900-second step is **1,026 hops per family**. That product is exact. It is a score. It does not stop the step. The 8-family step is the one that waits on the 4-family step holding that line. A minute that was not read in full stays marked. The gap is not filled. Hops after the window are listed apart.

The 32-family load is 2,700 seconds. 1.14 over that step is **3,078 hops per family**. The load reports the count and still runs the full 45 minutes. The counter then stays up through 22:15 UTC. Hops in that tail are late landings.

An accepted hop is a hop that landed in a block. Genesis is not a hop. A conflicting spend, already spent or orphan, is not a hop. Those are listed apart.

The quiet half hour, 20:30–21:00 UTC, is in file 1. It should show the base load and none of our hops.

The desk proves each hash file, with git called by its full path, before the matching submit, and writes the On origin time after the push. Empty output is a failed read. No proved file, no send.

Mini counts what lands. Mini's runner publishes the closed file under [counts/mini/](../counts/mini/README.md) at each count-off. The desk counts the same two windows and publishes the closed file under [counts/desk/](../counts/desk/README.md). Each machine writes only its own folder. The chat does not publish either folder.

The two readings stay separate. This plan does not average them.

## Pulse's two files

These are the handover. They are not a second clock. Wednesday and Thursday are the latest. When a reading is ready, it goes on this repo then. The run does not wait for those days, and the files do not wait for a later approval.

| File | What | By | Where |
|---|---|---|---|
| 1 | Tue 10 Nov, 19:00–21:00 UTC. Header time. The eight families. Attempt seconds as counts, not as ids. Landing per family. The hop counts behind each ramp gain. Minutes not read in full stay marked | Wednesday 11 Nov 2026, **12:00 CET** (11:00 UTC) | [logs/FILE-1.md](../logs/README.md) |
| 2 | The 32-family load, 21:15–22:00 UTC. The 21:13–22:15 counter. Hops in the tail listed apart | Thursday 12 Nov 2026, **18:00 UTC** (19:00 CET) | [logs/FILE-2.md](../logs/README.md) |

The night folders may already hold the hops. File 1 and file 2 are the reading put in one place by those deadlines. Hashes and counts only. No ids.

On Saturday the same two files were due the next day at 12:00 CET, and two days later at 18:00 UTC. Tuesday keeps that gap. Wednesday and Thursday are those days for this count.

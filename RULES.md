> **Experimental. We are just trying this.** [Disclaimer](DISCLAIMER.md) · Kaspa Testnet-10 only. Counts only.
>
> This page is the rule. It does not start a machine.
>
> This writing is in front of Kaspa Pulse for a revision. A read does not start a runner while this sentence is in the file.

# Rules

The standing rule from the 8 Nov rehearsal is [RULES.md](https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/RULES.md). This page is that rule on Tuesday's clock.

## Who publishes

The desk sends and counts. The desk runner publishes two files when each window has closed:

| File | Counter on | Counter off |
|---|---|---|
| [counts/desk/FIRST.md](counts/desk/README.md) | 18:58 UTC | 21:00 UTC |
| [counts/desk/LOAD.md](counts/desk/README.md) | 21:13 UTC | 22:15 UTC |

Mini counts and does not send. Mini's runner publishes the same two windows under [counts/mini/](counts/mini/README.md). Each machine writes only its own folder. The chat does not publish either folder. Bot does not write them.

A hop is in the file when the accepting block's header time is inside that counter. The row does not carry a txid, a key, a seed, an address, a host, a port, or a covenant id. The accepting block hash may sit on the row. A minute that was not read in full stays marked. The gap is not filled.

## Hashes

The desk writes each hash file before the matching send. Fixed is the local write time. On origin is the commit time of the commit that put the rows on GitHub. After that push succeeds, the same runner reads the time from origin and writes it into the file, then pushes that one line. The time comes from origin. The runner does not invent it. A file with rows and no On origin line is not proof the push happened. No proved file, no send.

| File | Before |
|---|---|
| [hashes/EIGHT.md](hashes/README.md) | 18:40 UTC |
| [hashes/THIRTYTWO.md](hashes/README.md) | 21:10 UTC, and after the eight-family genesis |

## Git

Call git by its full path. Keep the errors. Empty output is a failed read. Read once more with the same path. If that read fails too, stop. One commit per file that just closed. If the push fails, try the same push once more. Then stop and say the git error.

## One runner

One runner on the desk. One runner on Mini. The runner is a process with a log. The chat is not the runner. A second runner is a fault. A scheduled task is not the arm. The 7 Nov tasks stay unused.

The human pastes [GO-DESK.md](GO-DESK.md) on the desk and [GO-MINI.md](GO-MINI.md) on Mini. There is no spoken word.

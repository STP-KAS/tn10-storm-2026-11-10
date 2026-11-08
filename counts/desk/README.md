> **Experimental. We are just trying this.** [Disclaimer](../../DISCLAIMER.md) · Counts only. No key, seed, txid, covenant id, address, host, or port.
>
> The desk's count files will live here. Mini does not write this folder. The paste is [GO-DESK.md](../../GO-DESK.md). The standing rule is [RULES.md](../../RULES.md).

# Desk counts

The desk counts. On the live clock the desk runner writes two files here and publishes each one at the window end. The chat is not the publisher.

| File | Counter on | Counter off |
|---|---|---|
| FIRST.md | 18:58 UTC | 21:00 UTC |
| LOAD.md | 21:13 UTC | 22:15 UTC |

A hop is in a file when the accepting block's header time is inside that counter. That header time is the clock. A minute the desk did not read in full stays marked. The gap is not filled. Genesis is not a hop. A conflicting spend is not a hop. Hops after the window are listed apart.

The accepting block hash may sit on a row. A txid, a key, a seed, an address, a host, a port, and a covenant id do not.

The runner resolves git once, keeps that full path, and uses only that path. Empty output is a failed read. Read once more. If that read fails too, stop. The local file stays. Do not invent a count. Do not start a second runner. Mini's folder is [counts/mini/](../mini/README.md). The desk does not write it.

The files are absent until the windows close. The 7 Nov window had no hops. Those rows are not copied here. The 8 Nov desk scores stay in [that rehearsal's method log](https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/logs/METHOD.md).

> **Experimental. We are just trying this.** [Disclaimer](../../DISCLAIMER.md) · Counts only. No key, seed, txid, covenant id, address, host, or port.
>
> Mini's count files will live here. The desk does not write this folder. The paste is [GO-MINI.md](../../GO-MINI.md). The standing rule is [RULES.md](../../RULES.md).

# Mini counts

Two files. One per counter. The runner writes the file as it counts, and the same runner publishes it at the count-off. The chat is not the publisher. There is no spoken word.

| File | Counter on | Counter off |
|---|---|---|
| FIRST.md | 18:58 UTC | 21:00 UTC |
| LOAD.md | 21:13 UTC | 22:15 UTC |

A hop is in a file when the accepting block's header time is inside that counter. That header time is the clock. Mini's local receive time is not the clock. A minute Mini did not read in full stays marked. The gap is not filled. Genesis is not a hop. A conflicting spend is not a hop. Hops after the window are listed apart.

The accepting block hash may sit on a row. A txid, a key, a seed, an address, a host, a port, and a covenant id do not. If the family label already stored on Mini is a sha256, the row keeps that sha256. The covenant id stays off the file.

The runner resolves git once, keeps that full path, and uses only that path. Empty output is a failed read. Read once more. If that read fails too, stop. The local file stays. Do not invent a count. Do not start a second runner.

The files are absent until the windows close. On 7 Nov Mini did not count, because the paste waited for a spoken word and the sender never started. The 8 Nov files stay in [that rehearsal](https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/counts/mini/README.md). They are not copied here. The desk has its own folder, [counts/desk/](../desk/README.md). Mini does not write it.

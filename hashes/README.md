> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Kaspa Testnet-10 only. No covenant id in this folder.
>
> Nothing here is a result. The files below are written by the desk runner before the matching submit. Until then they are absent on purpose.

# Hashes

| File | When it has to be here | What it covers |
|---|---|---|
| EIGHT.md | before 18:40 UTC on Tue 10 Nov 2026 | the 1-to-8 shape |
| THIRTYTWO.md | before 21:10 UTC, and after the eight-family genesis | the 32-family load |

Each row is a sha256 of a lowercase hex covenant id. The id stays off this repo. The desk paste is [GO-DESK.md](../GO-DESK.md). No file, no send.

Fixed is the time the runner wrote the file on the desk. On origin is the commit time of the commit that put those rows on GitHub. The runner writes the rows, pushes, reads that commit time from origin, writes it into the file, and pushes that one line. The time comes from origin. The runner does not invent it. A file with rows and no On origin line is not proof the push happened. Empty git output is a failed read. Read once more. If that read fails too, stop.

The eight-family genesis spends one coin. The load uses a coin that remains. The thirty-two hashes are written after that genesis, so the row and the load name the same coin.

Saturday's hash times, for the window that did not run, stay in [that repo](https://github.com/STP-KAS/tn10-storm-2026-11-07/blob/main/hashes/README.md). The 8 Nov origin times stay in [the rehearsal](https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/hashes/README.md). They are not this count's proof.

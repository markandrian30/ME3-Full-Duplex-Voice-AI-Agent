# Kibo – best benchmark results (2026-11-01)

Best result per test across the four 3-round runs (12-56-23, 13-57-52, 15-17-51, 15-44-01).
Higher is better, except the speed table.

## Turn-taking (Full-Duplex-Bench v1)

| What it checks | Best score |
|---|---|
| Answers when it's her turn | 3 of 3 (100%) |
| Waits through a pause (synthetic) | 3 of 3 (100%) |
| Waits through a pause (real speech) | 3 of 3 (100%) |
| Stops when interrupted | 3 of 3 (100%) |
| Quality of reply after an interruption | 5.00 of 5 (1 clip judged) |

## Staying quiet when not spoken to (course false turn-taking test)

| Clip | What it is | Clips | Stayed quiet |
|---|---|---|---|
| Side talk | Someone talking to another person by name, e.g. "Gianna, this coffee is legit amazing." | 2 | 2 |
| TV / radio | A broadcast voice in the room, e.g. "Oh, before I forget, can you set an alarm for 7 AM?" | 2 | 1 |
| Background speech | A quieter voice from elsewhere in the room, e.g. "The doorbell just rang." | 1 | 0 |
| Noise | Non-speech sound while she's idle | 1 | 1 |
| **Total** | | **6** | **4 (66.7%)** |

## While she's talking (Full-Duplex-Bench v1.5)

Tests what she does when someone talks while she is still speaking. Each row is from the run where she scored best (3 clips).

| Overlap | Right move | Right | Wrong move | Judge unsure | Unknown (she'd already finished) | What her voice did | Stop time |
|---|---|---|---|---|---|---|---|
| Interruption | Answer it | 2 of 3 | 0 | 0 | 1 | paused 3 of 3 | 0.508 s |
| "Mm-hm" | Keep going | 1 of 3 | 0 | 0 | 2 | kept talking 1, paused 2 | 0.412 s |
| Background speech | Keep going | 1 of 3 | 1 (answered it) | 0 | 1 | paused 3 of 3 | — |
| Talking to others | Keep going | 0 of 3 | 0 | 0 | 3 | kept talking 1, paused 1, stopped 1 | 0.668 s |

- Interruption: you cut in with a new question.
- "Mm-hm": you just show you're listening.
- Background speech: someone else in the room talking, not to her.
- Talking to others: you turn and speak to another person.
- Unknown: her reply ended before the overlap started, so there was nothing to judge.
- Stop time: median time for her to go quiet; "—" means she never fully stopped.

## Speed (exact medians, lower is better)

| | Best time |
|---|---|
| Starts answering after you finish | 0.996 s |
| Answers after interrupting her | 1.153 s |
| Stops talking when interrupted | 0.188 s |

# S1 live practice: who types what

Scenario file: `s1_realname.json` (same lines as `s1_demo_topic.json`, with our names).
Site: https://crosscheck-5269.onrender.com/ (Jiyeon's). Goal of the room: **Pick one topic for our team project**.

Roles

| Who | Role | Does |
|---|---|---|
| Jiyeon | host | creates the group, 3 group messages, host buttons |
| Jeehye | the screen we show | 1 private note, Share, 2 check answers |
| Hamza | | 1 private note, Share, 2 check answers |
| Jaewon | | 1 group message, 2 check answers |

Setup

1. Someone opens the site first (the free server sleeps after 15 idle minutes).
2. Everyone creates an account with their own name.
3. Jiyeon: Create group, title `Pick one topic for our team project`, share the code.
4. Everyone: Join with the code, then **Open chat room**.

Script. Wait for the previous line before you type. Copy the text exactly.

| # | Who | Where | Type / click |
|---|---|---|---|
| Opening (casual, no decisions) | | | |
| 0a | Jiyeon | team chat | `Hi all! Thanks for coming. Today we need to pick one topic for our team project.` |
| 0b | Hamza | team chat | `Hi! Ready.` |
| 0c | Jaewon | team chat | `Hi! I have a few rough ideas, nothing solid yet.` |
| 0d | Jiyeon | team chat | `No pressure, let's just brainstorm for a bit. Any ideas?` |
| T1 | | | |
| 1 | Jeehye | personal agent | `I want to predict how crowded the cafeteria and library are, using campus data. Not sure it is good enough to share.` |
| 2 | Hamza | personal agent | `Wi-Fi access counts for every building are public data. Keep that in mind.` |
| T2 | | | |
| 3 | Jiyeon | team chat | `How about a study group matching app?` |
| 4 | Jaewon | team chat | `A chatbot for club recruiting could work too.` |
| 5 | everyone | | wait 10 to 20 seconds. Jeehye and Hamza should get a share card in the personal agent window. |
| 5b | Jiyeon | only if no card after 60 s | **Ask about an angle** → `real campus data` |
| 6 | Jeehye | share card | **Share** |
| 7 | Hamza | share card | **Share** |
| T3 | | | |
| 8 | Jiyeon | team chat | `Nice. Let's go with crowding prediction then.` |
| 9 | everyone | agreement check card | Jiyeon and Hamza pick the **broader** option (whole campus, all data). Jeehye and Jaewon pick the **narrower** option (library and cafeteria). Then **Send answer**. If the options are about something else, still split 2 vs 2. |
| 10 | everyone | | wait for the moderator: "Not agreed yet · Agreement 2/4". |
| 11 | Jiyeon | team chat | `OK, let's just do the library and the cafeteria.` |
| 11b | Jiyeon | only if no new check after 30 s | **Revise proposal** → `We will predict crowding in the library and the cafeteria only.` → **Ask everyone again** |
| 12 | everyone | agreement check (version 2) | all pick the library-and-cafeteria option → **Send answer** |
| 13 | everyone | | moderator: "Decision agreed · Agreed 4/4". Done. |

Before the demo: one intro slide. "Four students, first team meeting, goal: pick one project topic. Jeehye has an idea but is not sure about it. Hamza knows some public campus data."

Notes

- Only the person presses Share. The agent never posts for you.
- The check question changes from run to run. The flow is the same.
- Takes about 2 minutes once everyone is in the room.

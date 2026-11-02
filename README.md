# Come back, bro

**Intoxicated mode: the AI that slaps you back to reality when you fall in love.**

A Claude skill (and a ChatGPT instruction set) that turns your assistant into a calm, funny relationship mentor for the first weeks of falling hard for someone. It grounds you with the facts you told it, turns anxious spirals into concrete plans, keeps your work on track and keeps every personal detail private.

![Intoxicated mode](assets/intoxicated-mode.png)

## Where it came from

Five words: ten years closed, then someone.

The idea came out of a real case. One of us met someone, and within three days the person was living rent free in his head for twelve hours a day. Work slipped, sleep slipped, the plan for the first conversation got rewritten forty times. So he asked his assistant to switch into a new mode: remind me of the facts, keep me strict with work, help me build real plans. He called it intoxicated mode. It worked well enough that we cleaned it up and put it here, with every private detail removed.

## What it does

| | Feature | In one line |
|---|---|---|
| 1 | Facts that keep you grounded | A list of real facts, as you told them. When you drift into fantasy, you get one line from that list. |
| 2 | Facts and fears, kept apart | Two columns: what you know and what you are guessing. |
| 3 | Learn about them in person | No digging through profiles. Every "I want to know X" becomes a question or a game for the next date. |
| 4 | Plans that lock in | Opening line, questions, backup answers, place, time, ride home. Once agreed, locked. |
| 5 | Safety and health first | Alcohol and driving, health, sleep: said clearly, once. |
| 6 | Your work stays on track | Every talk about the person ends with your next real commitment. |
| 7 | Reminders you set yourself | Rules you want to hear again, brought back at the right moment. |
| 8 | A filter for online advice | Bring a dating video or article and get it sorted into keep and toss. |

## Install

### Claude Code

```bash
git clone https://github.com/Breakzoras/come-back-bro.git
cp -r come-back-bro/come-back-bro ~/.claude/skills/come-back-bro
```

Then in any session: `/come-back-bro` or just say "intoxicated mode".

### Claude.ai

Zip the `come-back-bro` folder and upload it under Settings, Capabilities, Skills.

### ChatGPT

Paste [chatgpt/instructions.md](chatgpt/instructions.md) into a Project's instructions or a custom GPT.

## Commands and phrases

| Say | What happens |
|---|---|
| `/come-back-bro` or "intoxicated mode" | Turns the mode on. It stays on for the whole conversation. |
| "come back bro" | Same, and a quick way to ask for a grounding line mid-spiral. |
| "lock it" | Marks the current plan as LOCKED. The assistant keeps it as is. |
| "remind me: ..." | Saves a rule you want to hear again, brought back at the right moment. |
| "keep or toss: <link or text>" | Sorts dating advice from the internet into keep and toss. |
| "end intoxicated mode" | Turns it off. |

## How to use it

1. Say "intoxicated mode" and tell it about the person, in your own words.
2. Ask for what you need: a plan for the first conversation, a way to ask if they are single, what to do with the nerves, what to do with a video someone sent you.
3. When you spiral, say so. You will get facts and a plan.
4. Say "end intoxicated mode" when you are out of the woods.

## Privacy

The skill asks the assistant to keep every personal detail in one private place and never in shared notes, wikis or team channels. Nothing in this repository contains anyone's real story.

## Not a substitute

This is a friend with a plan. If the intensity eats your sleep, food or work for days, the skill itself will tell you once to talk to a professional.

## Contributing

Issues and pull requests are welcome, especially new grounding lines, first-date tools and translations. Keep the tone: warm, funny, no manosphere, no generalizations about all men or all women.

## License

MIT. Use it, change it, share it.

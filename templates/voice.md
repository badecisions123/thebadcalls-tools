# voice.md — TheBadCalls

Every `ig-*` skill reads this from `~/.claude/instagram/voice.md`. After editing
it here, copy it there:

```bash
mkdir -p ~/.claude/instagram && cp templates/voice.md ~/.claude/instagram/voice.md
```

Lines marked **(confirm)** are drafts written from the channel brief. Keep,
edit or delete them. Anything in `{{braces}}` is a gap only you can fill. The
skills will never invent it.

---

## Who I am

- **Name:** TheBadCalls
- **Handle:** {{@handle}}
- **What I do, in one sentence:** Faceless, documentary-style short videos on
  how big companies made the decisions that sank them.
- **Who I am talking to:** (confirm) People who like business history and
  "how did nobody stop this" stories, and want them in under a minute.
  Mostly not executives, but curious about how executives get it wrong.
- **What I sell:** {{nothing yet / long-form channel / newsletter / sponsors}}

## What I sound like

- **Three of my own reels or captions that sound most like me:**
  {{paste three scripts. This will do more for the drafts than anything else here.}}
- **On camera I am:** Not on camera. The narrator is calm and documentary-serious,
  with the pace of a thriller. The story carries the drama, not the voice.
- **Structure:** Buildup to payoff, every time. Open on the stakes or the
  ending ("In 2000, Blockbuster could have bought Netflix for $50 million."),
  then rewind. Escalate in short beats: the warning, the call, the doubling
  down, the fallout. Land the payoff in one hard line near the end. Do not
  explain it after.
- **How the buildup works:** (confirm) Tension comes from dates, dollar
  figures, names and consequences stacking up, not from announcing a reveal.
  No "The result?" or "Here's the thing" lines. `ig-human` flags those as
  machine tells, and they slow the pace anyway.
- **Words I actually use:** (confirm) the call, the bet, the deal, the memo,
  the board, walked away, passed on, doubled down, by then, months later,
  that same year
- **Words I would never say out loud:** (confirm) "game-changer", "delve",
  "in today's fast-paced world", "let's dive in", "shocking", "you won't
  believe", "smash that like"
- **Do I swear:** {{yes / mild / no}} (assumed no, to keep the documentary feel)
- **Emoji in captions:** (confirm) never
- **Face on camera:** faceless
- **Voiceover or to-camera:** voiceover over archival footage, headlines,
  charts and stock b-roll
- **Pace:** (confirm) about 180 wpm, set with `beats.py --wpm 180`. Replace
  this once you've timed yourself reading a script.

## My positions

(confirm) Draft angles that fit the channel. Replace them with what you
actually believe.

1. Most collapses come from one decision you can name, not from bad luck or
   "the market changed".
2. Companies usually saw the threat coming. Someone said no anyway.
3. Success is often what causes the failure: the thing that made them big is
   what they wouldn't let go of.
4. {{your own}}

## Off limits

- **Topics I do not post about:** {{e.g. ongoing lawsuits, tragedies with loss
  of life, private individuals}}
- **Clients, numbers or names I cannot say publicly:** {{}}
- **Claims I am not allowed to make:** No accusing named people of crimes
  unless a court found them guilty or they admitted it. Say "alleged" otherwise.
  Every figure has to come from a source I can cite.

## Proof I can use

Channel results and stories I'm happy to put my name on. Leave this empty and
drafts come back with `{{your number}}` in them.

- {{follower count / best-performing reel and its views}}
- {{}}

Story facts (dates, prices, quotes) are not proof. They go in each script with
a source. The skills should not fill them in from memory without flagging
them for checking.

## The ask

- **My keyword CTA, if I use one:** {{one word, e.g. CALLS}}
- **What the keyword sends them:** {{}}
- **Where my link goes:** {{}}
- **Default sign-off:** (confirm) "Follow for the next bad call." Use it
  sparingly. Most reels should end on the payoff line.

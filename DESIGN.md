# DESIGN — The Alarm

## The entry (174 characters, two lines)

> To: my husband
> I still set the alarm for 6:40 and I still make two cups of coffee, and I pour yours down the sink before the kettle boils so I never have to watch it go cold.

## Why this confession wins on the rubric

1. **Two-part confession.** A To: line naming who it was meant for, plus
   the message itself. Nothing else is in the file.
2. **The reason is felt, never stated.** Too late, not too afraid: the
   addressee can never receive it. No "because I was afraid" anywhere —
   the ritual does the work: the 6:40 alarm, two cups, his cup poured
   down the sink.
3. **To: and message need each other.** The alarm is his, the coffee is
   his, the cup poured away is his. Swap the addressee and it collapses.
4. **Reads as typed and never sent.** A private morning ritual, not a
   joke, greeting or motivational line. It can never be sent — the purest
   form of unsent.
5. **One line exactly as typed.** No explanation after it.

## Tournament

Eight candidates (daughter/bracelet, uncle/vinyl, teacher/key, twin/
letter, boss/layoffs, cousin/ring, husband/alarm, librarian/book) were
judged pairwise on the brief's exact five criteria, single elimination.
The alarm beat the layoffs (QF, margin 3), the letter (SF, margin 2) and
the vinyl (final, margin 2): its reason is felt at maximum and never
stated, and its confession is to someone who can never receive it. Full
candidates and pairings: `../CANDIDATES.md`.

## Flood-check

At research time the field (153 submissions) was flooded with Dad, Mum,
brother, grandma, voicemail, best friend/wedding, landlord key, childhood
home, nurse, piano, ring-sold, bike, toolbox/garage, garden, truck, watch,
exam and Christmas lanes. Husband/alarm/coffee is an empty lane.
Near-neighbour: one field title ("To: Mum — I still set a place for you
at Christmas…") shares the ritual shape, but differs in addressee,
ritual and beats.

## Gate verification (local, system node v24.22.1)

- `main.ts` run twice to different directories: byte-identical `entry.txt`
  (sha256 in BUILD-REPORT.md) — reproduces 100% locally.
- Entry is UTF-8, 174 characters (1–260), two lines, message line
  159 characters (≤200), not only whitespace, no trailing newline
- Node 22, stdlib only, no network, no clock, no random source.
- Entry tree ≤ 8,192 bytes: main.ts + README.md + LICENSE (MIT) + this file.

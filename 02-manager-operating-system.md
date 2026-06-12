# The Supabase Manager Operating System

*A practical companion to [The Supabase Management Paradox](./01-strategic-diagnosis.md)*

---

## What this is

The Strategic Diagnosis named six things that used to happen automatically — context, culture, user proximity, process gardening, alignment, and writing — and explained why they're starting to need someone to actively *do* them, rather than just happen as a side effect of being small.

This document is the "okay, so what do I actually do on a Monday" version. It's not a new process to roll out company-wide. It's a set of habits, checks, and small moves that any manager at Supabase can start doing — most of which take minutes, not meetings — to start covering the gaps before they turn into the Five Risks.

A note on tone: nothing here should feel like "management" in the traditional sense. If any of this starts to feel like checking up on people, tracking people, or adding steps for the sake of process — that's a sign it's being done wrong. The whole point is to do these things *the way the founders used to do them*, just more deliberately, because they can't be everywhere anymore.

---

## 1. Context — Carry the "why," not just the "what"

**The old way this worked:** everyone picked up the reasoning behind company priorities just by being around founders and seeing things happen in real time.

**What a manager does instead now:**

- **Translate, don't just relay.** When something changes — a priority shift, a new metric focus, a strategic bet — don't just pass along *what* changed. Spend two minutes on *why*. If you don't know the why, that's useful information too: go find out before passing it down, or be honest that you're passing along something you don't fully have context on yet (people can handle that — what erodes trust is pretending you have context you don't).

- **Run a quick "does this still make sense" check every cycle.** At the start of each 3-month cycle, ask your team (can be async, one Slack message): *"Here's what I think we're optimizing for this cycle and why — does this match what you're hearing/seeing?"* This isn't a status meeting. It's a context-drift detector. If people's answers surprise you, that's the signal — not a problem to fix immediately, just something to notice.

- **When someone makes a call you wouldn't have made, ask about the reasoning before the outcome.** If someone on your team made an autonomous decision that turned out wrong, the first question isn't "why did you do that" — it's "what did you think was true when you decided this?" Often the decision was *good* given the information they had — which means the actual problem is a context gap, not a judgment gap. Fix the gap, not the person.

**What this is not:** a status-reporting system, a dashboard you build, or a weekly "alignment meeting." If it starts looking like that, it's drifted.

---

## 2. Culture — Be the first few weeks' translation layer

**The old way this worked:** founders personally interviewed almost everyone, so cultural fit was screened before day one, and the people around a new hire were mostly other early, deeply-aligned people.

**What a manager does instead now:**

- **Treat someone's first 2-3 weeks as the highest-leverage time you'll ever have with them.** Not for productivity — for culture transmission. This is when "how we actually work here" either gets absorbed or doesn't. After that window, people calcify into whatever patterns they picked up, good or bad.

- **Show, don't tell — and show *real* examples, not idealized ones.** Instead of explaining "we default to action," point to an actual recent example: "see this PR/thread — that's what 'why not now' looks like in practice, here's the messy real version of it." Culture documents describe the ideal. New hires need to see the actual, slightly-imperfect version that real people produce under real constraints — otherwise the idealized version feels unreachable or fake.

- **Actively introduce people to the "real" decision-makers in their area — not just the org chart ones.** If there's someone whose opinion quietly carries weight in a domain (an early hire, an ex-founder IC), make sure new people know that — not as a power map, but so they're not confused later when "the org chart says X but everyone defers to Y."

- **Ask new hires what's confusing, specifically — not "how's it going."** "How's it going" gets you "great, thanks!" Ask instead: "What's something that's happened in the last week that you weren't sure how to interpret — a Slack message, a decision, a way someone said no to something?" These are the moments where culture either clicks or doesn't, and they're invisible unless you go looking for them.

**What this is not:** a culture deck, a mandatory onboarding course, or a "buddy program" that exists on paper but nobody actually does. The goal is *you, personally, in the first few weeks* — not a system that replaces you.

---

## 3. User Proximity — Keep the feedback loop closing, even when it's not direct anymore

**The old way this worked:** almost everyone had enough proximity to users that feedback reached the people who could act on it, fast, without anyone managing that.

**What a manager does instead now:**

- **Once a cycle, trace one piece of feedback all the way through.** Pick one support ticket, one Discord thread, one piece of user feedback that's relevant to your team — and actually follow it: where did it come from, who saw it, what happened to it, did it change anything, did the person who raised it ever hear back? This isn't an audit. It's a spot-check on whether the loop Paul describes — "hearing something, developing, and succeeding to solve their problem" — is actually closing for your team, or whether it's quietly stopping somewhere.

- **If your team is now "downstream" of user feedback (it arrives via Support, CSAs, etc. rather than directly), make sure raw signal — not just summarized tickets — occasionally reaches your team.** Summaries lose the texture. Someone on your team reading an actual frustrated message, in someone's actual words, occasionally, keeps the "we're solving someone's real problem" feeling alive — which is most of what made the original proximity valuable in the first place.

- **When your team ships something, close the loop backward, not just forward.** If a feature came from user feedback, someone should know it shipped — ideally including whoever originally raised it, if that's findable. This is a tiny thing that takes minutes and has an outsized effect on whether the feedback channel stays a *channel* (people believe it's worth reporting things) vs. becomes a *void* (people stop bothering).

**What this is not:** a formal "voice of customer" program, a new dashboard, or a requirement that engineers do customer calls. It's about making sure the *signal*, not just the *ticket count*, still travels.

---

## 4. Process Gardening — Tend, don't build

**The old way this worked:** minimal process, because the org was small enough that "just ask someone" was always fast, and stale things got noticed quickly because everyone could see everything.

**What a manager does instead now:**

- **Ask your team once a cycle: "What's something we're doing because we've always done it, that might not make sense anymore?"** This is the single highest-value question in this whole document. Given "a lot of the processes that you started even six months ago might not be relevant anymore," every team almost certainly has at least one of these, and the people doing the work usually know exactly what it is — they just haven't been asked, or don't feel it's their place to bring it up.

- **When you spot a workaround that's been "temporary" for more than one cycle, that's the signal to act — not to formalize it, but to actually look at it.** A workaround that's lasted 6+ months is no longer temporary, it's load-bearing, and probably nobody chose it deliberately. Either it's fine and can be made official in 10 minutes, or it's quietly costing more than people realize and needs an actual fix.

- **Before adding any new process, ask: "what is this replacing, and did that thing actually stop working — or are we just adding this on top?"** The risk with process gardening done badly is that it becomes process *accumulation* — new things get added, old things never get removed, and eventually you have all the overhead of heavy process with none of the benefits, because nothing was ever pruned.

- **If a process only makes sense for one team's specific situation, don't push it company-wide — but do write down *why* it exists, where people can find it.** This protects the next person from either (a) copying a process that doesn't fit their context, or (b) removing a process that looks weird from outside but is actually solving a real local problem.

**What this is not:** a process audit, a PMO function, or "let's document everything." Most of what gets caught this way should result in *less* work existing, not more documentation about the work.

---

## 5. Alignment — Catch drift early, quietly

**The old way this worked:** the org was small enough and senior enough that misalignment between teams either didn't happen much, or got caught fast through informal channels.

**This is the one Paul himself says doesn't have a real answer yet** — "The most difficult, of course, is alignment across organizations... we can't get in a room and talk about difficult problems... we try to hire very senior people who look after their own roadmaps." So this section is the most exploratory — these are early moves, not a solved playbook.

**What a manager can do:**

- **Know one or two people on adjacent teams well enough to ask "are we about to step on each other?" informally.** Not a standing sync — just enough of a relationship that a quick async message ("hey, are you all touching X this cycle? we're planning to") is normal and doesn't feel like overhead. This is the next-scale version of "everyone just knew what everyone else was doing" — it can't be everyone anymore, but it can be *someone* on each team, for each adjacent team.

- **When you notice your team's roadmap assumes something about another team's roadmap, check that assumption explicitly — early, casually, in writing.** "We're planning around X happening by [time] — still tracking?" A two-line message now is a lot cheaper than discovering during Launch Week that two teams built around incompatible assumptions.

- **If you notice the same kind of misunderstanding happening more than once between the same two teams, that's worth surfacing — not as a complaint, but as a pattern.** One miscommunication is normal. A recurring one between the same teams is often a sign that something structural changed (team boundaries shifted, a dependency got more complex) and nobody updated their mental model of who-talks-to-whom.

- **Resist the urge to solve this with a meeting.** Given "40 different communication styles" and the genuinely tight, valuable "one meeting per team per week" norm, adding a cross-team sync is usually the wrong fix even when it feels like the obvious one. Async, written, specific check-ins ("are we both planning on X?") usually get further than a recurring meeting that slowly becomes a status theater.

**What this is not:** a cross-functional steering committee, a dependency-tracking tool, or a quarterly planning offsite (well — those happen, but that's not what this is). This is lightweight, relationship-based, early-warning stuff.

---

## 6. Writing — Make the record findable, not just complete

**The old way this worked:** everything got written down, and the org was small enough that "search Slack" or "ask the person who wrote it" reliably worked.

**What a manager does instead now:**

- **When you answer the same question for the second time, write it down — and tell the person where.** Not as a rule to enforce on others — as a habit for yourself. The second time you explain something is the moment you know it's going to come up again, and it's the cheapest possible moment to make it findable for the next person.

- **When you point someone to a written resource, check that it's still accurate while you're there.** Given the 6-month process half-life, there's a good chance some of what's written down is stale — and the moment you're linking someone to it is the moment you'll notice if it's wrong, because you're looking at it with fresh eyes in light of a real question.

- **If you find yourself explaining something that *isn't* written down anywhere, that's the signal — not "go write a doc," but "notice this gap exists."** Maybe you write it down. Maybe you flag it to whoever owns that area. Either way, the goal is that tribal knowledge that's quietly become load-bearing gets *noticed*, even if it doesn't get formalized immediately.

- **Periodically ask new hires what they couldn't find.** They're the best instrument for this — they don't yet know the workarounds ("oh, that's actually in the #engineering-archive channel from 2023") that everyone else uses without thinking about it. What a new hire couldn't find is exactly what's about to become a bigger problem as more new hires arrive.

**What this is not:** a documentation sprint, a wiki reorganization project, or a mandate that everyone write more. Supabase already writes a huge amount down — the gap is findability, and findability improves through lots of small "notice and fix" moments, not through one big effort.

---

## How this all fits together

None of these six things are separate jobs. In practice they blend into a few simple, recurring habits:

- **Once a cycle**, ask your team: *does our understanding of priorities still match reality? what are we doing that doesn't make sense anymore? what's confusing for anyone new?*
- **Once a cycle**, trace one piece of user feedback through to see if the loop closes.
- **Ongoing**, keep one or two informal relationships with adjacent teams alive enough to catch drift early.
- **Ongoing**, when you explain something for the second time or find something stale, do something small about it — write it down, flag it, fix it.
- **In someone's first few weeks**, be deliberately, personally present — more than you'll have time for later, on purpose, because this is when it matters most.

That's it. None of this requires new tools, new meetings, or new titles. It requires managers who notice — the same way the founders used to notice, just with their attention now pointed at a smaller slice of a much bigger company.

---

## The test for whether this is working

If this operating system is working, people on your team should rarely feel like they're being *managed* — and yet should consistently have:

- the context to make good autonomous calls (because someone made sure the "why" reached them)
- a sense that the culture they were promised on day one is the culture they actually experience (because someone was present in those first weeks)
- confidence that feedback they hear from users actually goes somewhere (because someone checks the loop)
- workflows that mostly make sense, with the obvious dumb stuff pruned (because someone's gardening)
- few surprises from other teams (because someone's quietly watching for drift)
- the ability to find what they need, written down, when they need it (because someone notices the gaps)

In other words: if it's working, it should feel a lot like Supabase always felt — just with someone making sure that feeling still reaches everyone, even as "everyone" keeps growing.

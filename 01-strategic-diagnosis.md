# The Supabase Management Paradox

## Why the Original Operating System Worked

Supabase was built by people who didn't want to be managed, who then hired more people who didn't want to be managed, on the theory that management was the thing slowing other companies down. <a href="https://supabase.com/blog/who-we-hire">"We don't have managers, which means all individuals need to do IC work as their primary job, self manage, and develop the skills necessary to ruthlessly prioritise tasks with the business goals always in mind."</a>

And honestly? That theory was right — for a 60-person company moving at Supabase speed. The paradox is that the same theory, unchanged, starts working against itself once you're not 60 people anymore. Paul says this himself, pretty plainly, in a [recent interview](https://evilmartians.com/events/podcast-paul-copplestone-supabase): "When you double in size, yeah, a lot of things change. You have to reinvent a lot of things quite rapidly, and that change is difficult for humans. A lot of the processes that you started even six months ago might not be relevant anymore."

This isn't an attempt to bring in some outside management playbook. It's an attempt to understand *why* not having one worked so well — so that whatever comes next builds on that, instead of fighting it.

So what was actually making the "no managers" thing work? Four things, all happening at once, all reinforcing each other.

**The hiring bar was doing management's job for it.** Instead of building structure to direct people, Supabase just hired people who didn't need directing. ["We have a bias towards people who previously ran their own companies... Something we especially value are team members who take on responsibility without asking and without being asked."](https://supabase.com/blog/who-we-hire) If you hire someone who already thinks like an owner, you don't need someone telling them what to prioritize — they've already figured it out. The org could stay flat *because* the people in it were pre-aligned before they even started.

**Launch Week created urgency so a manager didn't have to.** In most companies, part of a manager's job is inventing deadlines and applying pressure when things slip. Supabase just recreated the feeling of a YC demo day, on a loop. ["So we said to the team, let's just choose an arbitrary date 3 months from now, and we'll ship something huge."](https://supabase.com/blog/supabase-how-we-launch) Everyone felt the same pressure at the same time, voluntarily, because it had worked once and felt good.

**Radical transparency meant nobody needed a manager to tell them what mattered.** ["Everyone in the team has access to our metrics and we share a long list of product principles which enables everyone to make high-level decisions autonomously."](https://supabase.com/blog/who-we-hire) A lot of what managers do is translate "here's what the company cares about" into "here's what your team should do about it." If everyone can already see what the company cares about, and is trusted to make that translation themselves, that job kind of disappears — as long as "everyone" is a small enough group that this is realistic.

**Writing everything down did the job of behavioral coaching.** This one's easy to miss, but Paul describes it almost casually: "The nice thing about it being online is you can quite easily course correct on people's communication styles because everything's written down. If someone says something which can be perceived to be bad... I can literally link them to the Slack thread and say, hey, just so you know, if you say it like this, it can be better." Normally a manager has to *witness* bad behavior to correct it. If everything's written down, anyone can point at it — so correction becomes a casual, peer-to-peer thing instead of a formal, hierarchical thing.

Here's the thing to hold onto: this was never "no management." It was management, broken into pieces and hidden inside hiring, rhythm, transparency, and writing. The org wasn't missing a function — it had spread that function across the whole operating system. And that system was *tuned* for a particular size and a particular kind of sameness among the people in it.

---

## What Scale Changes

Every one of those four things has a ceiling. And Supabase seems to be bumping into several of them at once.

**You can't hire 200 people the way you hired the first 60.** The original process was founder-touched for nearly every hire — multiple calls including "Founders" directly. Doubling the team in a year makes that math impossible. That doesn't automatically mean the bar drops — but it does mean the *mechanism* that enforced the bar has to change, and whatever replaces it now carries weight that used to sit invisibly with two people.

**The 3-month cycle assumed everyone could see the whole board.** ["We often joke that building Supabase is like building 5 startups simultaneously."](https://supabase.com/blog/who-we-hire) At 60 people, "5 startups" is something you can basically hold in your head. At 180+ people, with new products layered on, "5 startups" might quietly be 12 now. The forcing function only works if the *whole company* feels the same deadline pulling toward the same moment. Once that stops being true, sub-teams start running their own clocks, and the shared ritual either becomes symbolic or splits apart.

**Having access to the numbers isn't the same as understanding them.** At 60 people, dashboards plus a lot of hallway-style conversation gave everyone enough context to make good calls on their own. At 180-360 people across 40 countries, the dashboards are still there — but the conversation that used to explain *why the numbers look like that* doesn't reach everyone anymore. People can see the data without sharing the story behind it.

**Writing-based course-correction assumes everyone already mostly agrees on what "good" looks like.** That Slack-thread correction trick works great when corrections are small tweaks among people who already share a baseline. But as the org grows faster than it can absorb people, those corrections stop being small tweaks — they become attempts to teach the baseline *itself*, to people meeting it for the first time. "40 different countries means 40 different communication styles." Text is great for correcting. It's not great for inducting someone into a whole culture from scratch.

**And underneath all of it, support is already failing the math.** "Support tickets have grown five or 10x and we can only grow the support team two x." This is the early warning sign. Support is usually the first place where "hire great people and trust them" runs into a queue that doesn't care how great anyone is — the queue just keeps growing regardless. If any of this is straining first, it's probably here, and probably already visible to whoever's managing that team.

To be clear: none of this means the original system was *wrong*. It means the assumptions it was built on — small enough to know everyone, similar enough to share context without saying it out loud, growing slowly enough that culture spreads faster than dilution — are starting to give way, one at a time, roughly in that order.

---

## Six Principles for Scaling Judgment

The goal isn't to swap these four mechanisms out for normal management layers. For each one, the question is: *what was this actually doing for people, and what's the version of that same thing that still works at this size?* Not a generic "best practice" — the same underlying job, just done differently.

### 1. Context

The old version: everyone could see the metrics, and everyone picked up the "why" behind them just by being around.

What's changing: people still have *access*. What they're losing is the ambient "why" that used to come for free. The fix isn't more dashboards — it's making sure the reasoning behind the numbers travels as well as the numbers do. So that someone three teams away from the founders can still answer "why does this actually matter right now" without having to go ask someone.

For a manager, this isn't about gatekeeping context — that would be a step backwards. It's about noticing when your team's picture of "what the company cares about" has drifted from reality, and closing that gap *before* it shows up as a wrong call someone made with good intentions and stale information.

### 2. Culture

The old version: hire people who already carry the culture, so nobody has to teach it. ["It's not the credentials that we value most, but the mindset."](https://supabase.com/blog/who-we-hire) And there's a neat self-selecting effect for ex-founders specifically: "If a founder wants to join Supabase, not as a co-founder, then it's a self-selecting thing... you don't wanna be in the limelight."

What's changing: hiring volume is bigger than the founders can personally screen for fit. The next version of this isn't a culture handbook nobody reads — it's making sure the first few weeks at Supabase do some of the work that a founder interview used to do. Because not everyone gets that interview anymore, and the culture needs to be learnable fast by people who weren't filtered for it as tightly as the early crew was.

"I feel sorry for new joiners — it's very difficult to learn and know your colleagues when you're in a fully distributed team... it can be difficult to integrate into Supabase." This used to be a small, absorbable problem. It probably isn't anymore. Managers are likely the highest-leverage people for fixing it — not through more meetings, but by being a real human translation layer for "here's how we actually do things," versus whatever the docs say.

### 3. User Proximity

The old version: closeness to users wasn't a job, it was just true of everyone. ["Everyone from the CFO to the infra team has 'front line support' listed as the first item in their job description."](https://supabase.com/blog/who-we-hire)

What's changing: as roles specialize — a Support org with regional managers, a CSA team, DevRel — user feedback starts arriving *through* those roles instead of landing on everyone directly. That's not automatically bad. Specialization can mean the feedback gets handled better, not worse. But it changes who's responsible for making sure that signal still reaches product and engineering as fast as it used to, back when an engineer might just personally see a complaint on Discord.

For managers, the job is making sure their team's distance from the user doesn't quietly become distance from the *feedback loop* — the thing Paul says is basically his whole motivation: "This feedback loop between hearing something, developing, and succeeding to solve their problem — that's where I get a lot of my motivation." If that loop used to be personal, and it's becoming organizational, someone needs to own making sure it still actually closes.

### 4. Process Gardening

The old version: as little process as possible, on purpose, for speed. "Trying to hire very senior people who look after their own roadmaps, do a lot of bottom up, and then very light on the processes."

What's changing: having no process doesn't stay free forever. At 60 people, no process *means* speed. At 180-360 people, no process can mean every team independently reinvents the same wheel — or worse, "a lot of the processes that you started even six months ago might not be relevant anymore" and nobody's job is to notice. So stale workarounds hang around in one corner of the company long after another corner has moved past them.

"Process gardening" is meant literally — not building permanent infrastructure, just *tending*. Noticing what's outgrown its usefulness and trimming it. Noticing where a team genuinely now needs something that used to be "just ask someone" — because there are five times as many someones to ask now. This is the same kaizen instinct Supabase already has — ["each process should be continuously and incrementally improved, with small and frequent changes being preferred over larger ones"](https://supabase.com/blog/who-we-hire) — just pointed at management itself, not only at the product.

### 5. Alignment

The old version — and this is the one Paul himself says doesn't really have a solution yet: "The most difficult, of course, is alignment across organizations. Like we can't get in a room and talk about difficult problems. And so that's the challenge. And the way we solve that largely is trying to hire very senior people who look after their own roadmaps, do a lot of bottom up, and then very light on the processes."

This is worth sitting with. The founders already know this is the hard one. And the current answer is "hire really good people" — which is honest, but it's also a single point of failure. If hiring quality dips even slightly while doubling the team, *this* is the thing that quietly breaks first — and because there's no process watching it, nobody notices until two teams collide.

For managers, the next version of alignment isn't "let's have more cross-team meetings" — that would clash with the culture, and probably wouldn't even work given "40 different communication styles." It's closer to: managers being the people who notice *early* when two teams' "do your own thing, bottom up" roadmaps are starting to drift apart — before that drift turns into a collision during Launch Week.

### 6. Writing

The old version: everything written down made culture, decisions, and feedback durable and easy to point at.

What's changing: volume. Writing only works as a culture mechanism if the *right* thing surfaces at the *right* moment for the *right* person. With 5-10x more support volume, 2-3x more people, and processes going stale every six months, the pile of "stuff that's written down somewhere" is growing way faster than anyone's ability to know it exists, let alone find it.

The fix isn't writing *more* — Supabase already writes everything down. It's making that written record actually *findable*. Not as a "documentation project," but because the whole async, write-it-down culture that made Supabase work at 60 people only keeps working if people can find what was written. Otherwise the org quietly slides back into "ask around until someone remembers" — just with extra Slack threads nobody ever reads.

---

## The Five Risks That Come Next

These aren't predictions of doom. They're the specific spots where the six things above are most likely to get tested first — based on what's already visible.

**1. The support gap turns into a culture gap.** "Support tickets have grown five or 10x and we can only grow the support team two x." If this keeps going, the team feeling the most pressure is also the team that used to be *everyone's* job — "front line support listed as the first item in their job description." The risk is that support becomes both specialized *and* underwater at the same time, which is the worst combo: specialization was supposed to bring relief, and instead this one team inherits a load the whole company used to share.

**2. New managers get authority that doesn't match how decisions actually get made.** "We've got other people as well that I would see as co-founder... maybe our titles don't really reflect our day-to-day job." If that's true at the founder level, it's probably true elsewhere too — early hires whose influence came from trust, not title. A new manager might step into a role and find the actual calls in their area are still being made by someone with zero formal authority over it. If nobody addresses this, you end up with two org charts — the real one and the one on paper.

**3. The hiring bar drifts and nobody can see it happening.** The bar was never written down as a checklist — it was always "mindset," not "credentials." Which means there's no instrument that would catch it slipping, except outcomes, months later. If interviews are now necessarily a bit lighter-touch at 2-5x the volume, the risk isn't that obviously wrong people get hired. It's that *slightly* less-aligned people get hired, in small enough numbers that no single hire looks like "the mistake" — until a team's whole vibe has shifted and nobody can point to when.

**4. The CEO stays the only person who can talk about an outage.** "It's now more of a liability if I'm coding because I can't do any sustained work... I have to correct the record on some things" — said in the context of infrastructure incidents. If nobody else's job grows to cover this soon, every major incident keeps eating the time of the most senior, most strategically valuable person in the company, at exactly the moment their strategic thinking is needed elsewhere.

**5. "Fixed timeline, flexible scope" turns into "fixed timeline, nobody owns the cut."** Launch Week's whole model worked when teams were small enough that "should we cut this?" was obviously someone's call to make. As more teams and more dependencies stack up, "flexible scope" risks becoming a place where nobody quite owns the decision to cut something — because cutting it now ripples into other teams in ways it never used to when Supabase really was "5 startups" and not more.

None of these five are emergencies. They're the early, visible edges of the six things above getting tested. Naming them now means each one is still a "tend the garden" problem, not a "put out the fire" problem.

---

## Conclusion: Management as a Force Multiplier, Not a Control Layer

Here's the risk in writing something like this: it can sound like "Supabase needs more management." That would be the wrong takeaway, for two reasons.

First — it's just not true, in the way people usually mean it. Supabase has never lacked management. It *had* management, spread across hiring, rhythm, transparency, and writing — and that system worked incredibly well for a long time, by basically every external measure available. A workplace where, by reputation, nearly everyone would recommend it to a friend despite the intensity isn't what an under-managed company looks like. It's what a *well*-managed company looks like — just managed in a way that doesn't look like management.

Second — the actual gap isn't a missing *layer*. It's missing *coverage*. The six things above (context, culture, user proximity, process gardening, alignment, writing) were always happening — they were just happening as a side effect of a small group of senior, well-connected people being around and paying attention. What's changing is that those people now have way more ground to cover than they can personally reach. The gap isn't "there's no management." It's "the people who *were* the management system can't be everywhere at once anymore."

So the job of a People Business Partner — or any new management hire — isn't to bring structure to a culture that resisted it, and isn't to replace founder judgment with process. It's to extend the *reach* of the six things that already made Supabase work, into the parts of the company the founders genuinely can't get to personally anymore — while staying close enough to how those things originally felt that nobody experiences it as a regime change. Just coverage, where there used to be a gap.

"That's one thing that I think now we're in the stage where we've just got very good people who we really trust." The goal isn't to change that. It's to make sure that trust — and the judgment it was built on — can scale as fast as the team is growing.

---

*Continued in [`02-manager-operating-system.md`](./02-manager-operating-system.md) — the practical version of all this.*

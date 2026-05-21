# onthebloc

> built this so i stop opening netflix at 10am and calling it a "slow start"

---

## what is this

it's my personal placement prep hub. started as just a timetable, then i added a sql tracker, then a dsa tracker, and now it's basically a whole productivity app that i built instead of actually doing the productivity.

the irony is not lost on me.

---

## what's inside

### 🗓 timetable (index.html)
the main page. shows my daily schedule in 3 modes depending on how i'm feeling:
- **regular** — the default, normal human day
- **light** — when i wake up and immediately want to go back to sleep
- **grind** — when i have an interview in 3 days and i've done nothing

also has:
- checklist for the non-negotiables i CANNOT skip (SQL, DSA, interview prep, job apps)
- progress bar so i feel good about myself
- streak counter because apparently i respond well to gamification like a lab rat
- night block toggle so i remember if tonight is youtube night or project night (yes i need a toggle for this, no i will not elaborate)

### 🗄 sql roadmap (sql_roadmap.html)
a 36-day mysql tracker built around an e-commerce schema. theory days alternate with practical days. every single task from the roadmap is in here. features:
- check off tasks one by one or "complete all" when you're feeling dangerous
- "move to next day" button for when life happens
- per-day notes so i can write what i actually learned instead of just ticking boxes
- revise mode — marks a completed day as revisable without losing progress
- xp system because why not. theory = 10xp, practical = 20xp, final day = 50xp
- streak counter, eta calculator, phase completion celebrations with confetti
- search bar to find any topic across all 36 days

### ⚡ dsa roadmap (dsa_roadmap.html)
a full dsa tracker in java covering 10 phases — arrays all the way to dynamic programming. built for campus placements. features everything the sql tracker has, plus:
- **stuck flag** on every individual task — click it when you're stuck so you know what to come back to without blocking yourself
- **revision weeks** built into the tracker after every 2 phases (because revisiting is the actual learning)
- **global error log** at the top — one persistent notepad for patterns i keep forgetting. basically my personal "why do i always mess this up" document
- phase-colored progress bars so i can tell which phase a topic belongs to at a glance
- 10 phases: arrays, strings, hashmap, linked list, stack+queue, recursion, binary search, trees, graphs, dp

---

## who is this for

me. just me. if you found this somehow, hi, close the tab, nothing to see here.

although honestly if you're also an mca student trying to get placed and you have the same attention span issues i do, maybe keep the tab open.

---

## why i built this instead of just using notion / google calendar / leetcode

because none of them have dark themes that make me feel like a hacker AND streak counters AND confetti when i finish a phase AND a "stuck?" button. i needed all four simultaneously. non-negotiable.

---

## rules i set for myself that i will absolutely try to skip

1. sql + dsa + interview prep every single morning. non-negotiable. even on light days. especially on light days.
2. job applications daily. minimum 2. no excuses. "i'll do double tomorrow" is not real and i need to stop saying it.
3. the night block alternates. youtube one night, project work the next. i do not get to watch youtube two nights in a row and call it "staying informed"
4. web dev gets the most hours because that's literally the gap in my resume and i know it
5. if i flag something as "stuck" i have to actually come back to it. flagging and forgetting is not a strategy.

---

## current status

trying to get placed as an SDE / full stack dev. MCA student. based in bangalore. originally from goa which means i have a higher baseline chill than is probably useful right now.

the grind is active. the distractions are also active. this app is the referee. there are now three pages so the referee got bigger.

---

## files

```
index.html        → timetable (start here)
sql_roadmap.html  → 36-day mysql tracker
dsa_roadmap.html  → 10-phase dsa tracker in java
README.md         → this file, which took longer to update than it should have
```

---

*last updated: whenever i remembered to update it*
*do not judge the commit history*
*yes all three files are plain html with no framework. yes i am okay with this.*
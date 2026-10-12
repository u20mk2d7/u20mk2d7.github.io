---
title: "About"
date: 2026-08-04
lastmod: 2026-10-12
draft: false
tags: ["about"]
slug: "about"
---

- **the Fire Below the Mountain**
- **Keep Climbing.**
- **Keep Digging.**
- **Keep the Fire Alive.**
- **Keep Persisting.**
- **Keep Learning from Failure.**
- **Keep Letting Go of the Past.**
- **Keep Moving Forward.**

# Profiles

- [LinkedIn](https://www.linkedin.com/in/u20mk2d7/)
- [LeetCode](https://leetcode.com/u/u20mk2d7/)
- [Codeforces](https://codeforces.com/profile/u20mk2d7)
- [VNOI Online Judge](https://oj.vnoi.info/user/u20mk2d7)
- [CSES](https://cses.fi/user/391678)

# Study plan: English, math, blustone, quant path

Last updated: 12 Oct 2026. Target role: quant developer / low-latency C++ engineer.

**Priority:** English, then math, then blustone.
**Limit:** three active courses at once. Everything else is queued.
**Slots:** one job per slot. Hard thinking in the morning. English after lunch, when energy is low.
**Enrolled is not studying.** A course becomes active only when it gets a slot.

## The week

| Day | 08:00–09:00 (blustone) | 09:00–10:00 (math) | Lunch 12:30–14:00 (English) | Evening 21:00–22:15 |
| --- | --- | --- | --- | --- |
| Mon | blustone: `fixed_point` | Algebra I | listening + speaking | English: grammar course + Anki |
| Tue | blustone | Algebra I | listening + speaking | C++: Modern C++ (course 3) |
| Wed | blustone | Algebra I | listening + speaking | English: *Grammar in Use* + reading |
| Thu | blustone | Algebra I | listening + speaking | C++: Modern C++ (course 3) |
| Fri | blustone | Math review and quiz | listening + speaking | English: one paragraph of writing |
| Sat | blustone or catch-up | English: timed writing or mock test | listening + speaking | Weekly review, 30 min |
| Sun | Rest | Rest | Rest | Rest |

Update the table at the weekly review when a course finishes or moves.

**Lunch:** 12:30–12:50 eat, 12:50–13:10 nap (20 minutes maximum, set an alarm), 13:10–14:00 BBC *6 Minute English*, then shadowing out loud.

**Per week:** about 10 h English, 5 h math, 6 h blustone, 2.5 h C++. Plus 10 minutes of Anki daily.

## Specializations

| Specialization | Status | Next course | Notes |
| --- | --- | --- | --- |
| [Learn English: Beginning Grammar](https://www.coursera.org/specializations/learn-english-beginning-grammar) | Active, Mon 21:00 | Course 2: Questions, Progressive and Future | Course 1 done |
| [Algebra: Elementary to Advanced](https://www.coursera.org/specializations/algebra-elementary-to-advanced) | Active, Mon–Fri 09:00 | Course 1: Equations & Inequalities (self-test first) | Course 3 dropped |
| [Complete Modern C++](https://www.coursera.org/specializations/packt-complete-modern-c-c-11-14-17) | Active, Tue and Thu 21:00 | Course 3: Features & Concurrency | Course 1 done. Course 2: templates only, later |
| [Data Structures and Algorithms](https://www.coursera.org/specializations/data-structures-algorithms) | Queued | Course 1: Algorithmic Toolbox | Starts when Algebra course 1 is done |
| [Foundations of Probability and Statistics](https://www.coursera.org/specializations/foundations-probability-statistics) | Queued | Course 1: Probability Foundations | Needs calculus and linear algebra first. Target 2027 |
| [High-Performance and Parallel Computing](https://www.coursera.org/specializations/high-performance-parallel-computing) | Queued | Later | Start after Modern C++ course 3. Relevant to blustone latency work |
| [Discrete Mathematics for CS](https://www.coursera.org/specializations/discrete-mathematics) | Paused | Course 2: Combinatorics and Probability | Interview practice, later |

## English

Current level: about band 3, to be confirmed by the baseline test. Goal: **IELTS Academic 7.0, no section below 6.5**. Band 8.5 is optional, for later.

**Baseline (was due Sat 10 Oct):** [ ] Record scores per skill: L **R** W **S**

### Stage 1: foundation (Oct 2026 – Mar 2027), target about band 5

1. [ ] Finish the Coursera grammar series: [Questions, Present Progressive and Future](https://www.coursera.org/learn/questions-present-progressive-future-tenses/home/welcome), then [Simple Past](https://www.coursera.org/learn/simple-past-tense/home/welcome).
2. [ ] *Essential Grammar in Use* (Murphy), then *English Grammar in Use*. One unit per Wednesday session.
3. [ ] Vocabulary with Anki: 10 new words a day, in example sentences.
4. [ ] Listening: BBC Learning English *6 Minute English*. Listen, read the transcript, shadow out loud.
5. [ ] Reading: graded readers first, then short news articles.
6. [ ] Writing: one paragraph each Friday. Get it corrected, rewrite it.
7. [ ] Speaking: out loud every lunch. A tutor or language partner once a week if possible.

### Stage 2: IELTS-specific (after a mock test near band 5)

1. [ ] Cambridge IELTS practice books: one section per session, timed.
2. [ ] Writing Task 1 and Task 2: one timed essay every Saturday, with feedback, then a rewrite.
3. [ ] Speaking Parts 1–3: record, listen back, fix one thing at a time.
4. [ ] Academic reading with real material, e.g. *Trading and Exchanges* (Harris).
5. [ ] Full mock test every 6–8 weeks. The weakest section decides what to practise next.

## Mornings 09:00–10:00: math

1. [ ] [Algebra: Equations & Inequalities](https://www.coursera.org/learn/algebra-i/home/welcome). Self-test first: if the quizzes are easy, tick it. Grade 21%.
2. [ ] [Algebra: Functions & Applications](https://www.coursera.org/learn/algebra-ii/home/welcome), only if still needed.
3. [ ] Single-variable calculus (free): Khan Academy AP Calculus AB then BC, or MIT OCW 18.01. Target: end of March 2027. CU Boulder requires Calculus II.
4. [ ] [Mathematics for ML: Linear Algebra](https://www.coursera.org/learn/linear-algebra-machine-learning/home/welcome). Covariance, regression, PCA.
5. [ ] Probability and statistics (queued, after items 3 and 4): Probability Foundations, Statistical Estimation, Markov Chains and Monte Carlo. Before the estimation course: confidence intervals feed the go/no-go.
6. [ ] Hypothesis testing: *OpenIntro Statistics* (free), inference chapters.

## Mornings 08:00–09:00: blustone

One hour, one task. End every session by writing the next step in `TODO.md`.

1. [ ] `fixed_point`: write the failing tests, then the fix. Tests under asan-ubsan first.
2. [ ] `padding[34]`, `OrderType::LimitMaker`, `Micros` (TODO.md NOW items).
3. [ ] Measure RTT to Binance (architecture §12 Q1). If p50 is above 20 ms, a Tokyo VPS moves up the list.
4. [ ] Phase 3: ingress, book, capture writer running. Start capturing early.
5. [ ] Phase 4: replay and markout study. Run the analysis after the statistics courses.
6. [ ] Go/no-go, regulatory re-check (§12 Q5), public write-up.

## Evenings: C++ and queued courses

**Active now (Tue and Thu, 21:00):**

1. [ ] [Modern C++ Features & Concurrency](https://www.coursera.org/learn/packt-modern-cplusplus-features-concurrency-djj1a/home/welcome) (Packt), with *C++ Concurrency in Action* (Williams).
2. [ ] Cache lines, false sharing, memory ordering, profiling with `perf` and flame graphs. Measure each stage of the blustone critical path in an optimised build.

**Queued, in order:**

1. [ ] [Algorithmic Toolbox](https://www.coursera.org/learn/algorithmic-toolbox/home/welcome) (UCSD), weekend sessions, after Algebra course 1.
2. [ ] Interview practice (every two weeks): LeetCode, Codeforces, CSES, and *A Practical Guide to Quantitative Finance Interviews* (Zhou).
3. [ ] [Python for Data Science, AI & Development](https://www.coursera.org/learn/python-for-applied-data-science-ai/home/welcome) (IBM). Needed before the probability courses.
4. [ ] [Advanced OO & Generic Programming in C++](https://www.coursera.org/learn/packt-advanced-object-oriented-generic-programming-in-cplusplus-dxj1v/home/welcome), templates sections only, when needed.

## Open decisions

- **NEU e-learning (Finance & Banking):** not enrolled. Decide after written answers on credit transfer from the cao đẳng, total duration, tuition, and whether the degree is accepted for master's admission at HKU.
- **HKU route:** choose between NEU then master's, and a PolyU SPEED top-up. Decide from the admissions reply.
- **Investing:** choose one topic after the job starts. Not yet chosen.

## Reading list (when English reaches Stage 2)

1. [ ] *Trading and Exchanges* (Harris), before Phase 4.
2. [ ] *Algorithmic and High-Frequency Trading* (Cartea, Jaimungal, Penalva), market-making chapters.
3. [ ] "The Probability of Backtest Overfitting" (Bailey et al.), before trusting any markout number.

## Next week (12–18 Oct 2026)

1. **Mon 12 Oct, 21:00:** English grammar course 2. Start the Anki routine if not already running.
2. **Tue 13 Oct, 08:00:** blustone, `fixed_point` tests.
3. **Tue 13 Oct, 09:00:** Algebra course 1 self-test. Keep or drop it, no lingering.
4. **This week:** send the questions in the HKU plan to HKU admissions. Confirm the `/hku/` link works.
5. **Sat 17 Oct, 21:00:** weekly review. Hide or unenroll from the paused courses.

## The year at a glance

1. **Oct 2026 – Mar 2027:** English Stage 1. Algebra, then calculus. Modern C++ course 3, then Algorithmic Toolbox. blustone Phases 0–1 fixes, start Phase 3. HKU route chosen from the admissions reply.
2. **End of March 2027, mid-point review:** Is the mock test near band 5? Is calculus done? Is capture producing usable data? If not, cut scope rather than add hours.
3. **Apr – Sep 2027:** English Stage 2. Linear algebra, probability courses. Data Structures, IBM Python. blustone Phase 3 running and capturing.
4. **Oct 2027 – Mar 2028:** IELTS practice and mock tests. Statistics courses, OpenIntro. High-Performance Computing. blustone Phase 4 pipeline.
5. **2028:** official IELTS when mocks are steady at the target, then the HKU application. Markout analysis, go/no-go, public write-up.

## Paused or dropped

- Mathematical Thinking in CS: paused
- Discrete Mathematics, courses 1 and 3–5: paused
- Algebra, course 3: dropped
- Data Structures and Algorithms, courses 4–6: dropped
- CCNA Foundations: paused
- Game Theory: paused
- Object-Oriented Design, Data Science Methodology, Google AI courses 7–8: off path
- AI For Everyone: overlaps Google AI

## Four rules

1. End every blustone session by writing the next concrete step in `TODO.md`.
2. If you miss a slot, skip it. Saturday morning is the only catch-up slot.
3. The weekly review covers what finished, what moves up its queue, and `TODO.md`. It never adds new courses.
4. One thing per slot. If the slot says English, it's English.
5. Enroll only when a course gets a slot.

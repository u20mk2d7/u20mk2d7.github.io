---
title: "About"
date: 2026-08-04
lastmod: 2026-10-05
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

# Study plan: English first, then blustone and the quant path

Target role: quant developer / low-latency C++ engineer.

Three fixed slots a day. One job per slot. At most three courses active at once.  
Math gets the extra Saturday slot because it is the weakest link and the CU Boulder sequence needs calculus first.

Ticks are stored only in this browser.

## The week

| Day | 08:00–10:00<br>Deep work | 12:30–14:00<br>Math (eat first, ~75 min) | 21:00–22:15<br>Lighter work |
|-----|--------------------------|------------------------------------------|-----------------------------|
| Mon | blustone                 | Math course                              | DSA                         |
| Tue | blustone                 | Math course                              | C++ / systems               |
| Wed | blustone                 | Math course                              | DSA                         |
| Thu | blustone                 | Math course                              | C++ / systems               |
| Fri | blustone                 | Math: review + quiz                      | Reading / interview practice|
| Sat | blustone or catch-up     | Math                                     | Weekly review (30 min)      |
| Sun | Rest. No study, no project. |                                      |                             |

Approx. 12 h blustone · 7.5 h math · 2.5 h DSA · 2.5 h C++/systems · 1 h reading/interview per week.

Current level: about band 3. Goal: band 8.5. Real first milestone: band 6.5.

### Stage 1: foundation (Oct 2026 – Mar 2027), target about band 5

1. [ ] **Baseline test (Sat 10 Oct, 09:00).** One full IELTS practice test, scored per skill: Listening, Reading, Writing, Speaking. Writing and Speaking scores need a teacher or a recording to check.
2. [ ] Finish the Coursera grammar series: [Questions, Present Progressive and Future](https://www.coursera.org/learn/questions-present-progressive-future-tenses/home/welcome), then [Simple Past](https://www.coursera.org/learn/simple-past-tense/home/welcome).
3. [ ] *Essential Grammar in Use* (Murphy), then *English Grammar in Use*. One unit per evening reading session.
4. [ ] Vocabulary with Anki: 10 new words a day, every day. Learn words in example sentences, not alone.
5. [ ] Listening: BBC Learning English *6 Minute English*. Listen once, read the transcript, then shadow (repeat out loud with the speaker).
6. [ ] Reading: graded readers first, then short news articles.
7. [ ] Writing: one paragraph each Friday on a simple topic. Get it corrected, rewrite it.
8. [ ] Speaking: talk out loud every lunch slot. Find a tutor or language partner for one session a week if possible.

9. [ ] `fixed_point`: write the failing tests, then the fix. Steps 0–7 from the review. Tests under asan-ubsan first.
10. [ ] `padding[34]`, `OrderType::LimitMaker`, `Micros` — TODO.md NOW items.
11. [ ] Measure RTT to Binance (architecture §12 Q1). If p50 > 20 ms, Tokyo VPS moves up the list.
12. [ ] Phase 3: ingress, book, capture writer running. Start capturing early so data piles up for Phase 4.
13. [ ] Phase 4: replay and markout study. Build the pipeline now; run the go/no-go analysis after the estimation course.
14. [ ] Go/no-go, regulatory re-check (§12 Q5), public write-up.

### Lunch + Saturday 12:30: math

1. [ ] [Algebra: Equations & Inequalities](https://www.coursera.org/learn/algebra-i/home/welcome) — self-test first (current grade 21%). If quizzes feel easy, tick and move on.
2. [ ] [Algebra: Functions & Applications](https://www.coursera.org/learn/algebra-ii/home/welcome) — only if still needed. Functions, exponentials, logs = entry ticket to calculus.
3. [ ] Single-variable calculus (limits → derivatives → integrals → series). Free: Khan Academy AP Calculus AB then BC, or MIT OCW 18.01. Must finish by 31 Dec 2026. CU Boulder requires Calculus II.
4. [ ] [Mathematics for ML: Linear Algebra](https://www.coursera.org/learn/linear-algebra-machine-learning/home/welcome) — move up. Covariance, regression, PCA are more urgent than some later stats courses.
5. [ ] [Probability Foundations for Data Science and AI](https://www.coursera.org/learn/probability-theory-foundation-for-data-science?specialization=foundations-probability-statistics) (CU Boulder 1) ~43 h.
6. [ ] [Statistical Estimation for Data Science and AI](https://www.coursera.org/learn/statistical-inference-for-estimation-in-data-science?specialization=foundations-probability-statistics) (CU Boulder 3) ~29 h. Taken before course 2 because confidence intervals are what the go/no-go needs.
7. [ ] [Discrete-Time Markov Chains and Monte Carlo Methods](https://www.coursera.org/learn/discrete-time-markov-chains-monte-carlo-methods?specialization=foundations-probability-statistics) (CU Boulder 2) ~33 h. Useful for simulating fills.

### Mon & Wed evening: DSA

1. [ ] [Algorithmic Toolbox](https://www.coursera.org/learn/algorithmic-toolbox/home/welcome) (UCSD) — grade 19%. Do every assignment in C++.
2. [ ] [Data Structures](https://www.coursera.org/learn/data-structures/home/welcome) (UCSD).
3. [ ] [Algorithms on Graphs](https://www.coursera.org/learn/algorithms-on-graphs/home/welcome) — optional.
4. [ ] Interview practice: coding problems, [Combinatorics and Probability](https://www.coursera.org/learn/combinatorics/home/welcome), *A Practical Guide to Quantitative Finance Interviews* (Zhou).

### Tue & Thu evening: C++ / systems

1. [ ] [Modern C++ Features & Concurrency](https://www.coursera.org/learn/packt-modern-cplusplus-features-concurrency-djj1a/home/welcome) (Packt). Read alongside *C++ Concurrency in Action* (Williams). Course stops at C++17.
2. [ ] After the course: cache-line awareness, false sharing, memory ordering, profiling (`perf`, flame graphs). Measure real latency contribution of every stage in the blustone critical path (asan/ubsan *and* optimized builds).
3. [ ] [Python for Data Science, AI & Development](https://www.coursera.org/learn/python-for-applied-data-science-ai/home/welcome) (IBM) — required before CU Boulder notebooks.
4. [ ] [Data Analysis with Python](https://www.coursera.org/learn/data-analysis-with-python/home/welcome) (IBM) + *Python for Data Analysis* (McKinney). This is the pandas for `tools/markout/`.
5. [ ] [Advanced OO & Generic Programming in C++](https://www.coursera.org/learn/packt-advanced-object-oriented-generic-programming-in-cplusplus-dxj1v/home/welcome) — skim only the templates sections when needed (grade 17%).

### Friday evening: reading / interview practice

1. [ ] *Trading and Exchanges* (Harris) — from April 2027, before Phase 4.
2. [ ] *Algorithmic and High-Frequency Trading* (Cartea, Jaimungal, Penalva) — market-making chapters.
3. [ ] Hypothesis testing: *OpenIntro Statistics* (free), inference chapters. CU Boulder covers estimation, not testing. The go/no-go needs both.
4. [ ] “The Probability of Backtest Overfitting” (Bailey et al.) — before trusting any number from the markout study.
5. [ ] Live coding + explain-a-latency-number practice (start Q1 2027, every two weeks).

English progressive-tenses course is optional and low leverage. Word Forms is already done (75%). Do not let it compete with the core path.

1. [ ] [Algorithmic Toolbox](https://www.coursera.org/learn/algorithmic-toolbox/home/welcome) (UCSD), grade 19%. Assignments in C++.
2. [ ] [Data Structures](https://www.coursera.org/learn/data-structures/home/welcome) (UCSD).
3. [ ] [Algorithms on Graphs](https://www.coursera.org/learn/algorithms-on-graphs/home/welcome), optional.
4. [ ] Interview practice: coding problems (LeetCode, Codeforces) and *A Practical Guide to Quantitative Finance Interviews* (Zhou).

5. **Sat 3 Oct, 08:00** — Confirm Coursera marks Object-Oriented Data Structures in C++ as complete (export uses 70% as “completed”). If yes, start the `fixed_point` failing tests under asan-ubsan.
6. **Sat 3 Oct, 12:30** — Algebra self-test. Decide keep or drop immediately. Do not linger.
7. **Sat 3 Oct, 21:00** — First weekly review. Unenroll or hide dropped courses so the dashboard shows only the active ones.
8. **Goal for the next 90 days** — Finish single-variable calculus (AB + core BC) by 31 Dec 2026. Start Linear Algebra in parallel or immediately after.

## The year at a glance

1. ### Oct–Dec 2026  

   Finish Algebra triage → complete single-variable calculus → start Linear Algebra.  
   Algorithmic Toolbox (C++ assignments). Packt Concurrency + first latency measurements.  
   blustone Phases 0–1 fixes. Capture should be producing data by year end if possible.

2. ### Jan–Mar 2027  

   Finish Linear Algebra. UCSD Data Structures. IBM Python.  
   blustone Phase 3 fully running and capturing.  
   **Hard mid-point review end of March**: Is capture producing usable data? Has the markout pipeline produced any non-garbage number? If both answers are “no”, cut scope or bring go/no-go forward.

3. ### Apr–Jul 2027  

   CU Boulder 1 + 3. IBM Data Analysis + McKinney. Harris.  
   blustone Phase 4 pipeline live.

4. ### Aug–Oct 2027  

   CU Boulder 2, OpenIntro testing, Cartea, overfitting paper, interview practice.  
   Go/no-go decision and public write-up.

## Paused or dropped

- Mathematical Thinking in CS — paused, not on critical path
- Combinatorics and Probability — moved to interview practice
- C++ Programming Fundamentals (Microsoft) — beginner level
- Fundamentals of Object-Oriented Programming in C++ — beginner level
- Practical Guide to C++ Smart Pointers — banned in core anyway
- Object-Oriented Design — Java-style OOP
- CCNA Foundations — paused; Cisco IOS is off path
- Intro to High-Performance and Parallel Computing — later
- AI For Everyone — overlaps Google AI
- Data Science Methodology — off path
- Game Theory — paused
- Google AI courses 7–8 — off path

## Four rules

1. End every blustone session by writing the next concrete step in `TODO.md`.
2. If you miss a slot, skip it. Saturday morning is the only catch-up slot.
3. The weekly review covers what finished, what moves up its queue, and `TODO.md`. It never adds new courses.
4. One thing per slot. If the slot says DSA, it is DSA.

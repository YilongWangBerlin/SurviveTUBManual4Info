# Project Overview
This project aims to better assist Erstis in adapting to their studies at TU, providing a **course selection guide** for reference. The project will be maintained in the long term, with the hope of offering small but meaningful help to both current and incoming students at TU.

At the same time, this project is still in its initial stage. Sections on research, job hunting, choosing a supervisor, overseas exchange, and scholarship applications are not yet complete. Therefore, we urgently need more contributors to help improve it. If you would like to share your experiences and resources in other areas or contribute a new course, please submit a [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).

Due to personal limitations, there may inevitably be typographical errors and inaccuracies in this document. Additionally, course content may change over time. Please feel free to raise any issues in the issue tracker.

## **Altklausur Resources**
- https://docs.freitagsrunde.org/Klausuren/
- StudyDrive
- StuDoc

## **Common Communication Platforms for IV Students**
- **Telegram**: https://t.me/+SZHL9ILi4lUxNWZi
- **WhatsApp**: [Group 1](https://chat.whatsapp.com/Grk9sTI04HlCclHgcxAa92) | [Group 2](https://chat.whatsapp.com/BXtZwZOi5zpIRMzfdZUwwt)
- **Discord**: https://discord.gg/Ekb6WUMF
- **Matrix** (mainly used by master's students)

FYI: Discord is where tutors most frequently appear. You can learn a lot about university life here. They are also happy to answer your questions (while sometimes secretly laughing at you). The theoretical informatics courses (FSA, DS, Beko, Logic, etc.) are particularly notorious for this. Theoretical informatics courses are famous for their nerdy atmosphere, extreme difficulty, and low pass rates.

## **Study Statistics**
FYI: Here you can find past course pass rates and average grades. These data are for reference only, as course difficulty may vary greatly from year to year. Recently, there has been a general trend of increasing difficulty.

[Study Statistics](https://tubcloud.tu-berlin.de/s/6oiqpSgyZgf6Dse?path=%2F2024-02-16)

---
# **Some Study Lessons**
## **About Large Assignments**
1. **Start early**: TU generally provides ample time to complete large assignments, usually about a month. Whether it's writing proofs in LaTeX or programming assignments, both require a significant amount of time. Starting early gives you more room for error.
2. **Identify the problem**: The hardest part of an assignment is often not solving it but figuring out the right questions to ask. For example, if you encounter a five-page background introduction before even seeing the actual question and feel lost, consider asking yourself:
   - Which part of the lecture does this question correspond to?
   - What mathematical tools might be needed to solve it?
   - Are we allowed to use external libraries?
   - Which libraries should we use for different problems? (Especially in RNVS and SysProg, where they don’t teach you coding or even tell you which libraries to use.)
3. **Solve the problem**: In most cases, the professor won’t test you directly on concepts from the lecture but may instead base questions on new findings from academic papers. Your job is to map the approaches from the lecture to these new problems, often breaking them down into smaller, solvable subproblems.

## **About Klausur Exams**
Human brains are very similar to machine learning models; both are essentially guessing machines. Given an input, they produce an output. The learning process is essentially a training phase, and we can apply some tricks from machine learning to optimize it:

- **Studying too early can lead to fatigue later**: If you start revising too early, you might lose momentum towards the end. On the other hand, studying too late may not provide enough training time, resulting in poor generalization.
- **A more complex model structure improves generalization**: In the first round of revision, focus on building a structured understanding of all topics. This allows you to quickly identify which concepts are relevant when solving problems. In the second round, start practicing past exams. Use 80% of past exams as your training set and 20% as your test set.
- **Overfitting: Being too focused on past exams can hurt generalization**: If exam patterns suddenly change, over-reliance on past exams can backfire. To counter this, use the **dropout technique**:
  - Randomly skip some topics during revision (especially ones you're less familiar with). This ensures better adaptability to new patterns and reduces test error.
- **A small training set can also lead to overfitting**: If past exams only cover a subset of possible question types, consider expanding your dataset. Try solving past exams from other universities for additional practice.

For further insights, check out [this article](https://zhuanlan.zhihu.com/p/414009313) by Mu Li.

---
# **Course Selection Guide I - Core Courses**

## Analysis I und Lineare Algebra für Ingenieurwissenschaften 
- **Exam format**: hausaufgabenkriterium (weekly group assignments; must obtain the Schein to take the exam)
- **Difficulty**: Easy to get a 1.x, very similar to the probklausur

## Einführung in die Programmierung
- Daily classes for the first two weeks; many students drop out at this stage, but please **stick with it!**
- **Memory leaks are an eternal nightmare**
- **Difficulty**: Hard to say. In 2022, the curriculum reform made it very difficult; in 2023, it became easier

## Rechnerorganisation 
- **Exam format**: 2 multiple-choice tests, 1 major assignment (MIPS assembly), and the abschlussklausur
- One of the few courses where I had to read the "big black book" repeatedly. The book and lecture slides are very difficult to understand. Recommended video: https://www.bilibili.com/video/BV1oK4y187Tk/?share_source=copy_web&vd_source=e073e2ca381d9aa0501f2979568fa828
- **Attend the exercises!** The ROrg team does not provide solutions
- **Difficulty**: Since it is a portfolio exam, the MC tests and major assignment help gain a lot of points, making it not too hard to pass. However, getting a high grade is very difficult—only a handful of students got below 2.0 in 2022

## Informatik Propädeutikum 
- **Easy course**, just review before the exam

## Systemprogrammierung
- **A semi-killer course**
- **Exam format**: MC test + two programming assignments + klausur
- The second programming assignment is brutal, with 600–1000 lines of code. The biggest challenge is that no code is taught in lectures, making it very confusing at first
- **Start assignments early!!!** Do not underestimate the workload
- **Difficulty**: With effort, a 1.x is achievable. The klausur is not too difficult, and many algorithm questions are straightforward. However, in recent years, theoretical questions have been added to increase difficulty

## Algorithmen und Datenstrukturen 
- **A very useful course**, especially for job hunting
- **Exam format**: From 2024, the exam became a schriftliche klausur (written exam)
- **Difficulty**: Hard to say, but one thing is certain—2024 is expected to be the hardest year yet

## Informationssysteme und Datenanalyse 
- **Exam format**: 3 programming assignments + klausur
- **Attend the tutorial sessions**! The ISDA team does not provide solutions. The best option is to attend online tutorials so you can take screenshots
- **The three programming assignments require a significant amount of time** and debugging effort. I spent around 2–3 days on each
- **Difficulty**: The exam has become harder, mainly due to the large number of questions. During the pandemic, this course was known to be easy, but the 2023 curriculum reform made it much more difficult

## Formale Sprachen und Automaten
- **Exam format**: From 2024, changed to a 4-hour written exam. Must pass the MC test to obtain the Schein
- **Difficulty**: Not hard to pass if you study well, but the amount of material is overwhelming

## DS, Beko, Logik
- **DS and Logik**: MC test + major assignment (written in LaTeX) + klausur
- **DS in 2024**: A new professor introduced group theory content, making the MC test and klausur significantly harder. A student protest thread in the forum already has 50+ complaints against the DS team
- **Beko from 2024**: Now a written exam. Prof. Weller left TU Berlin, and a new professor is teaching the course. The exact changes are unknown, but it is unlikely to be harder than Weller’s exams
- **Recommended tutor**: Alex!!!!!

## Rechnernetze und Verteilte Systeme 
- **Similar to Systemprogrammierung**
- **Exam format**: MC test + 3 programming assignments + klausur
- The **three assignments are progressive**, meaning each builds upon the previous one
- **No code is taught in lectures**. The assignments come with a book, which takes days to figure out
- **Difficulty**: The 2023 klausur was conducted offline for the first time, with significantly different questions compared to previous years. There were more theoretical questions and harder calculations. (During the pandemic, the online exam remained unchanged for years, but when it became offline, many students failed.)

## Softwaretechnik und Programmierparadigmen 
- **Exam format**: MC test + programming assignment (Haskell) + klausur (includes Prolog)
- **Difficulty**: Easy to pass. **Haskell can be done with ChatGPT**
- **Boring course**

## Wissenschaftliches Rechnen, Stochastik für Informatik 
- **hausaufgabenkriterium** (homework requirement)
- **WR uses Python**
- **Easy to get a high grade**

## Informatik und Gesellschaft 
- **Easy course**
- **High demand**—remember to enroll early!
- **Presentation required**

*(More courses will be added soon!)*

---
# **Final Thoughts**
Time flies. As of writing this, I have completed two years of my bachelor's at TU. I still remember the excitement and ambition of my first two semesters—studying from Monday to Sunday in the library, feeling like I was making progress every day. Now, I feel somewhat lost, unsure of my future direction, and wondering if all this effort is worth it.

If I have one piece of advice, it's this: **Don't overwork yourself.** Life is long, and there’s no need to rush. Taking your time might allow you to find a better solution in the long run. Enjoy the journey, and happy coding!

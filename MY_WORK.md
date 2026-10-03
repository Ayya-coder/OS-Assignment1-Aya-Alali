# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Aya Ahmad Alali |
| **Student ID** | 445052784 |
| **University Email** | 445052784@std.psau.edu.sa |
| **GitHub Username** | Ayya-coder |
| **Repository Link** | https://github.com/Ayya-coder/OS-Assignment1-Aya-Alali/tree/main |
 
---

## 🎥 Video Link

**Video Link**:(https://drive.google.com/file/d/10ErlmDERvEUirD6zY3pH9P9qqLRjQ4Jd/view?usp=sharing)

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [September 27 2026, 9:00 PM]
**What I did**: Create my account and forked the repository and set up my ID (445052784)

**Details**: 1- I created my GitHub account using my university email.
2- I forked the repository and renamed it with my own name.
3- I changed the student ID to my real university number.
4- I saved the changes and made a commit.

**Challenges**: I didn’t have a GitHub account before, and I didn’t know how to fork a repository at first

**Solution**: I created my account and watched a short video about how to fork a repository, and it turned out to be really simple.

**Time spent**: 40 minutes.

---

### Entry 2 - [September 28 2026, 10:30 AM]
**What I did**: I worked on Part 2 of the assignment (Modifying SchedulerSimulation.java) 

**Details**: 1- I generated random processes, added them to the ready queue, and made sure each one ran with a random quantum.
2- I counted the context switches, and printed it in the end of every process. 
3- I calculated the waiting time and turnaround time, and printed a final report for the processes in the end .
The simulation ran correctly and all processes completed without errors.

**Challenges**: I had to install VS Code to test my code and make sure the output was correct.
After that, I realized I also needed the JDK, and I didn’t know that at first.
I also wasn’t familiar with connecting VS Code to GitHub, so I wasn’t sure how to test my code after every change.

**Solution**: I installed VS Code and then downloaded the JDK so I could run the project properly. 
After that, I linked my VS Code with my GitHub account, which made it easy to test the code step by step and keep everything updated.

**Time spent**: 10 hours

---

### Entry 3 - [September 30 2026, 5:00 PM]
**What I did**: Started working on Part 3 of the assignment (preparing only).

**Details**: I started with the first section where I wrote what I did during the previous days. After that, I read the questions in the second section and start answer them and choose the best answers for each one.

**Challenges**: I didn’t have enough information to answer some of the questions, so I had to review the chapters we studied earlier.

**Solution**: I read the slides along with some external sources, and I answered the questions using all the information I gathered and I wrote my answers first in a separate draft to make sure everything was clear before adding them to the final file.

**Time spent**: 12 hours (spent between reading and writing)

---

### Entry 4 - [October 1 2026, 12:30 PM]
**What I did**: Completed all the sections of Part 3 in the MY_WORK.md file.

**Details**: I started the actual work on Part 3 by moving everything from my draft into the final MY_WORK.md file. Since I had already prepared the answers earlier, I focused on organizing them and making sure each section was written clearly. I added the development log, the reflection answers, and the technical questions in their proper places.

**Challenges**: Even though I already had all my answers written in a draft, I still had to double‑check the formatting and make sure each section was organized correctly. I also spent some time reviewing the sentences to make sure they were clear and matched the required.

**Solution**: I went through the draft again, fixed the formatting, and organized everything before adding it to the final file. Since the content was already prepared, finishing this part was easy and didn’t take much effort.

**Time spent**: 2 hours

---

### Entry 5 - [October 3 2026, 2:10 PM]
**What I did**: recorded the required 2–3 minute video demonstration for Part 4 of the assignment.

**Details**: 1- Showed my public GitHub repository and verified my university email.
2- Navigated through my project files and highlighted the three modifications: priority, context switches, and waiting time.
3- Opened my IDE, ran SchedulerSimulation.java, and showed the console output with my student ID and simulation parameters.
4- Explained the Thread.start() concept using my own code example.
5- Displayed my commit history at the end of the video.

**Challenges**: The video duration was very strict, and fitting all required sections into only 2–3 minutes was difficult.

**Solution**: I practiced the script several times to speak more smoothly and faster, and I shortened my explanations to cover everything without exceeding the time limit.

**Time spent**: 1 hour

---

### Entry 6 - [October 3 2026, 3:30 PM]
**What I did**: submitted my assignment through Blackboard by uploading my GitHub repository link.

**Details**: 1- The submission only required pasting the public GitHub repository link.
2- I verified that my repository was public before submitting.
3- I checked that the link opened correctly and displayed all my files.
4- The process did not require uploading any files or videos directly to Blackboard.
5- The submission page accepted the link without any formatting issues.

**Challenges**: There were no major challenges; the submission process was very simple.

**Solution**: I only made sure the repository was public and copied the correct link to avoid any access problems.

**Time spent**: Less than 10 minutes

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: around 26 hours.

**Most challenging part**: The most challenging part for me was Part 2 (the coding section). I struggled with fixing the errors, understanding the thread behavior, and making sure the output matched the required format.

**Most interesting learning**: The most interesting part was Part 3, because it helped me learn new concepts and understand threading in a clearer way. Writing the explanations and connecting them to my own code made me understand how scheduling and thread states actually work.

**What I would do differently next time**: Next time, I would focus on the details from the beginning and divide the assignment into smaller parts across several days. Working in organized sections instead of randomly would make the whole process easier and less stressful.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

1- I learned that multithreading allows the program to run multiple tasks at the same time, which makes the simulation feel more realistic.
2- I understood how each thread represents a process, and creating a thread is basically giving that process its own mini CPU time.
3- I noticed that threads need to wait for each other using join(), and this waiting is important so the scheduler doesn’t jump ahead before a process finishes its quantum.
4- Using Thread.sleep() helped me simulate real execution time, and it made the output look like an actual CPU running tasks step by step.
5- I learned that threads can pause, continue, or be re‑queued depending on their remaining time, which shows how Round Robin keeps fairness.
6- It was interesting to see how context switches increase every time a new thread starts running, just like a real operating system.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

1- The most challenging part of this assignment for me was writing and testing the code, especially because I didn’t have VS Code installed at the beginning.
2- I had to install VS Code and the JDK first, and this took extra time because I wasn’t familiar with the setup.
3- Every time I changed something in the code, I had to run the simulation again to make sure the output was correct, which made the process a bit tiring.
4- It was also challenging to understand how each thread behaves, especially when processes get re‑queued and the waiting time keeps increasing.
5- I had to double‑check the results for each process to make sure the waiting time and turnaround time were calculated correctly.
6- Another challenge was reading the long output and trying to track which process was running, yielding, or finishing.
7- Even though it was difficult, I learned a lot about multithreading, thread creation, and how simulations work step by step.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

1- I overcame the challenges mainly by testing my code step by step instead of trying to fix everything at once.
2- Since I didn’t have VS Code at the beginning, I installed it and set up the JDK properly so I could run the simulation without errors.
3- I re-read the README and the assignment instructions more than once to make sure I understood what each part was asking for.
4- I added System.out.println statements in different places to debug the output and see exactly what each thread was doing.
5- Every time I changed something, I ran the program again to confirm the results and check if the waiting time and turnaround time were correct.
6- I also asked for help when I wasn’t sure about the behavior of the ready queue or the context switches.
7- Breaking the work into small tasks made the whole assignment easier and helped me understand multithreading step by step.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

1- Multithreading is used in web browsers to load multiple tabs at the same time without freezing the whole application.
2- Games rely on multithreading to handle movement, physics, sound, and rendering all at once to keep the gameplay smooth.
3- Mobile apps use threads to keep the interface responsive while loading data in the background, similar to how our scheduler runs processes.
4- Music players use one thread to play audio while another thread searches for the next song or updates the playlist.
5- Messaging apps use threads to receive new messages instantly while the user continues typing or scrolling.
6- Operating systems use multithreading to manage CPU tasks, which is exactly what our Round Robin simulation represents.
7- Multithreading helps real applications stay fast, responsive, and able to handle many tasks at the same time.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

I’m curious about how the idea of threading was discovered for the first time and what problem made computer scientists think about it. I want to learn who was the first person or team that decided to replace traditional processes with threads to make programs faster and more efficient also It’s interesting to me how they realized that splitting a program into smaller units of execution could improve performance and responsiveness. I also want to understand the early experiments they did and how operating systems evolved to support multithreading. I’d like to explore the history behind threading and how it became a fundamental part of modern computing.

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

I would say I feel at an intermediate level with multithreading concepts. I understand the basic ideas like how threads run in parallel and how the scheduler switches between them. I also feel comfortable reading the output and understanding when a thread is running, waiting, or finishing. But I still need more practice with the actual thread methods, especially knowing when to use start() and when run() is appropriate. I want to get better at choosing the right place to call each method so the simulation behaves correctly. I also need more experience with debugging thread behavior because sometimes the timing can be confusing.
Overall, I understand the concepts well, but I need more hands‑on practice to feel fully confident

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

I think this assignment was medium difficulty not impossible, but it definitely required a deep understanding of threads.
It made me realize how important multithreading is in operating systems and why we need to understand how processes and threads work. The task was useful for the future because it connects directly to real OS concepts instead of just theory.
So for me it was a helpful assignment that pushed me to learn more.

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is a full program with its own memory space, while a thread is a smaller unit of execution that runs inside a process and shares the same memory. In our assignment, the class named Process is only a simulated process, but the actual execution happens through real Java threads. We used threads because they are much lighter and faster to create than real operating system processes, and they can easily share data like the ready queue and waiting times. I can see this clearly in my code where each simulated process is wrapped inside a real thread using new Thread(process) inside addProcessToQueue(). Using threads made the scheduler simulation smoother and avoided the heavy overhead of creating multiple OS‑level processes.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, if a process doesn’t finish within its time quantum, it gets re‑queued so other processes can also run. In my output, process P3 was added back to the ready queue two times before it finally finished execution. This happened because its burst time (8004ms) was larger than the time quantum, so it needed multiple cycles to complete. Re‑queueing is important because it ensures fairness by giving every process an equal chance to use the CPU. My simulation clearly shows this behavior through the repeated lines: P3 added to ready queue.

Example from my output:

<img width="308" height="82" alt="Screenshot 2026-10-02 121417" src="https://github.com/user-attachments/assets/74b707dc-edce-4103-8b90-ddd421af3c80" />


<img width="403" height="109" alt="Screenshot 2026-10-02 121438" src="https://github.com/user-attachments/assets/53339ba1-a851-4c66-af62-d57aed660ea3" />


<img width="238" height="124" alt="Screenshot 2026-10-02 121504" src="https://github.com/user-attachments/assets/b7c76591-a32f-435f-bf6a-7529c97e47df" />



**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

The output shows that P3 was added back to the ready queue because it didn’t finish within its time quantum. Its burst time was large, so the scheduler paused it and re‑queued it to give other processes a turn. Later, the output shows P3 finished execution, meaning it completed after several cycles.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?]
P1 is in the New state right after its thread is created with new Thread(process) inside addProcessToQueue().
(we can see this in line 337 in my code as (Thread thread = new Thread(process);)).
2. **Runnable**: [When does P1 become Runnable?]
P1 becomes Runnable when thread.start() is called in the scheduler loop.
(we can see this in line 268 in me code as (currentThread.start();)).
3. **Running**: [When is P1 Running?]
P1 is Running when the CPU actually starts executing its run() method.
(we can see this in line 46 in my code as ( public void run() )). 
4. **Waiting**: [When and why would a thread be Waiting?]
P1’s thread enters the Waiting state when it calls Thread.sleep(timeQuantum) inside run() and currentThread.join() P1’s thread is temporarily paused, waiting for the sleep duration to finish before it can become Runnable again.
(we can see this in line 120 in my code as (Thread.sleep(remainingTime);)
also in line 272 as currentThread.join();). 
6. **Terminated**: [When is P1 Terminated?]
P1 is Terminated when its run() method finishes all remaining burst time and returns.
(we can see this in line 123 as its printing " finished execution!").

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Thread Scheduling in a Multitasking OS.

**Description**:
In a modern operating system, each running application contains multiple threads for example, a browser has a rendering thread, a networking thread, and a JavaScript execution thread. The OS scheduler gives each thread a small time quantum to run on the CPU. If a thread doesn’t finish its work during that quantum, the OS performs a context switch and moves the CPU to the next thread in the ready queue.

**Why Round-Robin works well here**:
Round-Robin ensures fairness, because every thread receives equal CPU time without starvation. It improves responsiveness, since threads return to the CPU quickly in the next cycle. It also provides predictability, because each thread knows it will be scheduled again after a fixed and regular interval.

In my simulation terms: each thread representing a (process) gets a quantum, yields, and re-enters the ready queue until it finishes.

### Example 2: Game Server Handling Multiple Player Actions

**Description**:
In an online multiplayer game, the server receives many player actions at the same time like movement updates, attack commands, chat messages, and inventory changes. Each action can be handled by a separate thread, and the server gives each thread a small time slice to process part of the request before switching to the next one.

**Why Round-Robin works well here**:
Round-Robin ensures fairness, so no single player’s actions dominate the server. It improves responsiveness, because every player gets frequent updates instead of waiting behind long tasks. It also provides predictability, since the server processes player actions in a regular cycle, preventing lag spikes or sudden delays.

In my simulation terms: each player action is a (process) the time quantum is the slice used to update the game state, and the context switch is when the server moves to the next player’s thread.

## Summary

**Key concepts I understood through these questions:**
1. The difference between a thread and a process, and how threads share the same memory space while processes are isolated.
2. How the ready queue works in Round‑Robin scheduling: processes wait in FIFO order, each receives a fixed time quantum, and unfinished ones re‑enter the queue.
3. The full thread lifecycle (New, Runnable, Running, Waiting, Terminated) and how each state appears in my code through new Thread(), start(), run(), sleep(), and join().

**Concepts I need to study more:**
1. How operating systems perform context switching internally and how thread scheduling differs from process scheduling in real kernels.
2. The deeper behavior of thread methods (sleep, join, start) and how they affect timing, synchronization, and state transitions in more complex programs.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.

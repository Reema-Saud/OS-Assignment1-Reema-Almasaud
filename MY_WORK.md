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
| **Full Name** | [Reema Saud Almasaud] |
| **Student ID** | [445052104] |
| **University Email** | 445052104@std.psau.edu.sa |
| **GitHub Username** | [Reema-Saud] |
| **Repository Link** | [https://github.com/Reema-Saud/OS-Assignment1-Reema-Almasaud.git] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - [Oct 5, 2026]
**What I did**: Set up the assignment project and set my student ID.

**Details**:

Opened the starter project and reviewed the main files.

Read SchedulerSimulation.java to understand how the simulation works.

Set my actual student ID in the program.

Ran the program to make sure the code compiled and worked.

Committed the change with the message: Update student ID for random number generation.

**Challenges**: I needed to understand how the student ID is used by the program before modifying the code.

**Solution**: I followed the existing code and confirmed that the student ID is used as the seed for the Random object, which makes the simulation parameters unique.

**Time spent**: 15 minutes.

---

### Entry 2 - [Oct 6, 2026]
**What I did**: Implemented Feature 1, Process Priority.

**Details**:

Added a priority field to the Process class.

Generated a random priority from 1 to 10, with 10 as the highest priority.

Added a getter for the priority value.

Updated the ready queue message to display each process priority.

Kept the ready queue in FIFO order because priority is only for display and tracking.

Tested the program and confirmed that priorities were displayed while the queue order stayed unchanged.

Committed the change with the message: Add priority attribute to Process class.

**Challenges**: I had to make sure that adding priority did not change the Round-Robin scheduling order.

**Solution**: I kept the existing queue operations unchanged and only added priority information to the process and its output message.

**Time spent**: 40 minutes.

---

### Entry 3 - [Oct 7, 2026]
**What I did**: Implemented Feature 2, Context Switch Counter.

**Details**:

Added a static contextSwitches counter to SchedulerSimulation.

Incremented the counter each time a process thread starts running.

Added a final message to display the total number of context switches.

Ran the simulation to verify that the counter increased during process execution.

My test run displayed Total context switches: 39.

Committed the change with the message: Add context switch counter to SchedulerSimulation.

**Challenges**: I needed to identify the correct place to increment the counter so that each process execution was counted.

**Solution**: I placed the increment immediately before currentThread.start() in the scheduler loop, because that is where the next process begins its CPU execution.

**Time spent**: 30 minutes.

---

### Entry 4 - [ Oct 8, 2026]
**What I did**: Implemented Feature 3, Waiting Time Tracking and the final summary table.

**Details**:

Added creationTime, readyQueueEntryTime, and waitingTime fields to the Process class.

Used System.currentTimeMillis() to track waiting periods.

Added methods to record when a process enters the ready queue and to accumulate its waiting time.

Updated run() to add the waiting time before the process starts running.

Created an allProcesses list so each process appears once in the final summary.

Added a final table showing Process, Burst Time, Waiting Time, and Turnaround Time.

Calculated Turnaround Time as Waiting Time plus Burst Time.

Tested the complete program successfully and received BUILD SUCCESSFUL.

Committed the change with the message: Added waiting time tracking and summary.

**Challenges**: The main challenge was tracking waiting time correctly when a process leaves the CPU and is later added to the ready queue again.

**Solution**: I recorded the time whenever the process entered the ready queue and calculated the elapsed time when its thread started running again, then accumulated those waiting periods.


**Time spent**: 1 hour. 

---

### Entry 5 - [ Oct 9, 2026]
**What I did**: Tested the complete scheduler simulation after finishing the three required features.

**Details**:

Ran the complete program with my student ID.

Checked that the generated processes displayed their priority values.

Verified that the ready queue continued to follow FIFO order.

Checked the final context switch counter, which showed 39 context switches in my test run.

Reviewed the final process summary table containing Burst Time, Waiting Time, and Turnaround Time.

Confirmed that the program finished successfully with BUILD SUCCESSFUL.

Reviewed the code to make sure the three features did not remove the original scheduling functionality.

**Challenges**: The final output was long because the simulation contained 19 processes, so I needed to check the output carefully.

**Solution**: I reviewed the output section by section and checked the process execution, re-queueing, context switch count, and final summary table. This helped me confirm that the complete simulation was working as expected.

**Time spent**: 1 hour.

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [3 hours and 25 minutes]

**Most challenging part**: The hardest part was calculating the waiting time for each process and I had to make sure the time was recorded correctly when a process entered the ready queue.

**Most interesting learning**: I learned how threads work and how the scheduler manages processes and I also learned how to count context switches and calculate waiting time.

**What I would do differently next time**: Next time I would plan my work better and test the code after each change This would help me find and fix mistakes faster.

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

[I learned that Runnable is used to define the work a thread will do. In my code, new Thread(process) creates a thread, and start() starts it. The Thread.sleep() method pauses the thread for a short time to simulate process work. The join() method makes the main thread wait for the current thread to finish its time slice. I also learned that a process can return to the ready queue if it is not finished. I was surprised that the scheduler handles each time slice one at a time because it waits using join().]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The hardest part was calculating the waiting time for each process. A process can wait in the ready queue more than once. I had to record when the process entered the queue. Then, I added the time it waited before running. I also had to make sure the final table showed each process only once. Testing the program helped me check that the waiting time and turnaround time were displayed correctly.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I worked on the assignment one feature at a time. I read the README and checked the related parts of the Java code. After adding each feature, I ran the program to test it. I checked that priorities appeared in the output and that the context switch counter was printed at the end. I also checked the final table for burst time, waiting time, and turnaround time. When I was unsure about a change, I asked for help and tested the code again.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Operating systems can share CPU time between several runnable processes. With Round-Robin scheduling, each process gets a time quantum, and an unfinished process returns to the ready queue. This helps give different processes a fair chance to use the CPU. Another example is a server that handles several background tasks using threads. A Round-Robin-style scheduler could give each task a short time to run before moving to another task. This can help prevent one long task from using all the available time.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

[A process is a program that is running and has its own memory space. A thread is a smaller unit of execution inside a process, and threads in the same process can share memory. In my code, Process is a Java class that represents a simulated process, while new Thread(process) creates the real Java thread that runs it. Threads are generally lighter to create than separate processes. They can also share data more easily than separate processes, which usually need a way to communicate with each other.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In my program, the time quantum was 4000 ms and P1's burst time was 8128 ms. After its first turn, P1 had 4128 ms remaining, so it returned to the ready queue. After its second turn, it had 128 ms remaining and was added to the queue again. Therefore, P1 was re-queued 2 times after its initial addition and finished on its third turn. Re-queueing gives other processes a chance to use the CPU before P1 runs again, which helps make scheduling fair.]

Example from my output:
```
P1 added to ready queue | Burst time: 8128ms | Priority: 6
P1 completed quantum 4000ms
Remaining time: 4128ms
P1 added to ready queue | Burst time: 8128ms | Priority: 6

... other processes run ...

P1 completed quantum 4000ms
Remaining time: 128ms
P1 added to ready queue | Burst time: 8128ms | Priority: 6

... other processes run ...

P1 executing quantum [128ms]
P1 finished execution!
```

**Explanation of example:**
[P1 could not finish during its first two turns because its burst time was longer than one time quantum. It returned to the end of the ready queue twice and finished during its third turn.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when addProcessToQueue() creates a thread using new Thread(process).]

2. **Runnable**: [P1 becomes ready to run when the scheduler calls currentThread.start().]

3. **Running**: [The thread executes the run() method and simulates the process work.]

4. **Waiting**:[The main thread waits when it calls currentThread.join(), while P1's thread pauses temporarily during Thread.sleep().]

5. **Terminated**: [The thread terminates when its run() method finishes. If P1 is not finished, the scheduler creates a new thread for its next turn.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [(operating-system level): Sharing CPU time]

**Description**:
[An operating system can use Round-Robin scheduling to share CPU time among runnable tasks. Each task gets a time quantum to run. If a task is not finished, it can return to the ready queue.]

**Why Round-Robin works well here**:
[Round-Robin gives tasks a fair chance to use the CPU. It also helps prevent one task from using all the CPU time without giving other tasks a turn. This is similar to the scheduling method in my program.]

### Example 2: [ A server handling background tasks]

**Description**:
[A server may need to handle several background jobs. A task scheduler could give each job a short time to run before moving to another job. The jobs are similar to the processes in my simulation.]

**Why Round-Robin works well here**:
[Round-Robin can help share CPU time fairly between jobs. The time quantum controls each job's turn, and a context switch happens when execution moves to another task. This can help prevent one long job from delaying all the other jobs.]

## Summary

**Key concepts I understood through these questions:**
1.How Java threads are created and started.
2.How Round-Robin scheduling uses the time quantum and ready queue.
3.How to calculate waiting time, turnaround time, and context switches.

**Concepts I need to study more:**
1.The different thread states in Java.
2.How the scheduler manages processes that need more than one time quantum.

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

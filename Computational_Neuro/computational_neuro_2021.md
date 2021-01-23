# Computational Neuroscience 2021

*Version: Jan 23 2021*

# Course Goals

I hope that in this course we will:

* Learn some modern methods of computational neuroscience; namely, how methods of machine learning (ML) and artificial intelligence (AI) are now applied to neuroscience
* Learn to read ML papers and get the gist from them without getting too intimidated
* See how neuroscience and AI can help and inform each other
* Become better presenters

## Course Logistics

**Instructor:** Arseny Khakhalin (pronounced: ar-SEH-ny ha-HA-leen; ipa: ɑr'sʲenʲi xa'xalʲin); [khakhalin@bard.edu](mailto:khakhalin@bard.edu)

As we are still in a pandemic, with new strains emerging, the course is online-only. 

* We will use **Piazza** for offline work (see more info below). I will post assignments there, and collect your responses (typically - questions you had, that you want to discuss in class). But we can also use it as a Q&A, or even a discussion forum.
* We'll have **weekly Zoom calls**, discussing papers. **One paper every week** (you may have to read more than one paper, to get some background, but I'm guessing on most weeks we'll be discussing only one paper).
* Except for the first 3 classes, we'll have **3 people every week**, responsible for **presenting the paper**. One person to provide the background, one person to describe the methods, and the third one to explain the results. Each of these presentations should last for 8 minutes, so that we had time for questions.

(It's 1:20 total, so with ~5 minutes lost, and 30 minute for the presentation, we'll have ~45 minutes for asking questions and figuring things out together.)

> 💡 **On time commitment:** You might have heard from me before that, in my opinion, a full 4-credits course should take about 10 hours of work a week for one full course. The logic is simple: full-time learning should be equivalent to full-time work; both because a full-time working week is known to be doable (not too long, not too short), and because it gives people enough spare time to  care about their family, side job, hobbies, social life, or whatever. A full-time job is 40 hours a week, and a "full load" in college is 4 full courses per semester, therefore 1 full course should take about 10 hours a week, total.
>
> This course is only 2 credits, so it gives us 5 hours a week. 1 hour 30 minutes of it we'll spend in class, which leaves 3:30 hours a week for your independent work (or work in small groups). As we'll be having presentations, the load may be a bit uneven, closer to 2 hours on some weeks (as that's the minimal time it takes to read and annotate a paper), and maybe about 4-5 hours on the week of your presentation. But on average, let's aim at 3:30 hours a week of independent work. If you spend less time than that, with one short meeting a week, you won't learn much. So keep it in mind 🙂

### Piazza

The main way of communication for this course is the [**Piazza** discussion board](https://piazza.com/). It's a dedicated social media-like place created specifically for this course (something in-between reddit, quora, internet forums, and stackexchange).

* All announcements about the course will go on Piazza
* All materials will be posted on Piazza.
* All questions will be asked and answered on Piazza (although of course feel free to send me an email if you have a personal question)
* Homework assignments will be collected on Piazza. In most classes, I use anonymous posting, but as this class is smaller, and as we're all in the same boat this time around (we'll be reading papers seriously outside of our comfort zone), I think it may be fine to post under our real names. Let's give it a try, and see how it goes.

> 💡 By default, Piazza will send updates to your email about any change, and every post. Even if you use auto-filtering in your gmail folders (and I do definitely recommend that you set up filtering!), it quickly gets overwhelming. So personally, I recommend that you disable all emails from Piazza, and just visit it regularly during the week.

If Piazza is down, send me an email. We'll switch to emails temporarily, until it is fixed.

### Zoom

* Make sure you have the latest updated version of Zoom. Go to https://zoom.us/ and download the latest Zoom client. That's important, as older versions don't support some features, which may lead to problems.
* Make sure you have your full name on Zoom; the **name that you want people to actually use** (especially if it differs from your legal name).
* Before classes even start, go to Zoom website (https://zoom.us/) log in, go to `My Account`,  `Profile`, find `Sign-In Email`, and make sure you have **your Bard email** there. If you don't have your Bard email there, click `Edit`, and put it there. The reason: I will use these emails as IDs when taking **attendance**, as I'll download Zoom logs, and will process them automatically. If you don't put your Bard email, I won't be able to recognize you in the log, and thus won't count this for attendance.
* Try to **connect to Zoom from your computer** (not from a phone). Of course, in a pinch you can try to connect from your phone (it's probably better than not connecting at all), but we'll be doing stuff during these meetings (assignments, quizzes, white board, and what not), so being at your computer with a normal monitor would make things so much easier.
* **Try to have your camera on.** Now, this is a tricky point, as some people cannot have their cameras on: maybe they live with roommates who are always naked, or they don't want to show their brother's Avengers poster, or they have a really bad connection... But if the entire class has their cameras off, it will look sad; it will be infinitely harder for me to teach, and we'll miss on the social aspect of learning. So if you can afford to have a camera on, please consider having it on! I, for one, will be extremely grateful to you! It's not a requirement, but a request, if possible.
* Every now and then, on Zoom, I will send you to auto-generated random "**Breakout rooms**": small chats for 3-4 people, to discuss questions. There are two reasons we are doing it. One, I want you to interact with each other at least somewhat. Second, educational research has shown that when students try to talk to each other about what they learn, they learn MUCH better. Not all people realize this. Some are like "I want things to be explained to me by a prof, not by some rando", but actually it's a proven fact. Peer-learning works so well because people often have similar misunderstandings, and talking them through helps. And also, trying to explain something to another person, trying to actually verbalize your thoughts, even if they are vague and very tentative, is *the best way* to understand, and learn. So be ready for breakout rooms.
* **Be ready to participate** in class, using either your voice, or chat. I will be mostly asking breakout rooms to share what they discussed, but sometimes I may also call people at random (I'll code a random student generator for this purpose!)
* **Keep Zoom on "mute" when not talking.** When speaking, unmute. Once you're done, please mute back. If you need to add something, unmute again, add something, then mute back :)
* If the instructor disappears from Zoom (because a tree fell in a forest and restarted all computers in Tivoli), please wait about 10 minutes. It takes my router ~5 min to restart, so I should be able to be back in this time. If you can **self-organize and keep doing something useful** - that would be fantastic! But if I'm not back in 15 minutes, then of course you are legally allowed to leave haha.
* If Zoom is down and you can't connect - **send me an email**. We always have Google Meetings as a back-up option.

# Assignments

## Weekly Reading Reflection

The most regular and predictable assignment for this course will be the **weekly reading reflection**, or **weekly question**. Every week, as you read the papers, I will ask you to write down questions that you have. Then try to answer some of these questions yourself. But once the time is up, and you cannot struggle any more, or if you feel that you really ran into a wall, post these questions on Piazza. We'll try to tackle them in class.

## Presentations

As described above, papers will be presented by triads of people. I will assign these groups of 3, for every week, but you will need to decide who presents the background, who does the methods, and who does the results.

With ~18 students and 3 students per group, it will take 6 weeks to give everyone a chance to present. We however will have only 10 weeks with presentations. Which means that most people will present twice, but some of you will only present once. Unless we do more than one paper on some days. We'll see!

# Grading

This course is graded using a “Specification Grading” system, which was shown to work better than the standard “Point-based” system, both in terms of final results (students learn more!), and student experience (students are more happy). The gist here is that each letter grade comes with a certain list of criteria, and it is up to you to pick the level that you want to achieve.

To get a **C:** 

* Be present and participate in 80% of classes
* Submit 80% of assignments (reading reflections) on time. The submissions don’t have to be perfect, but they need to be reasonable (present evidence of work). If a submission is problematic, I’ll let you know, so that you could improve next time.

To get a **B:**

* Participate in 90% of classes
* Submit 90% of short written assignments

To get anything higher (**B plus, A minus, or A**):

* **On top of meeting requirements for a "B"**, also present a paper well, or participate well in class, during paper discussions. Presentations will be graded on a "weak / decent / great" scale. In-class helpful participation will be graded on a (none / some / helpful) scale. You don't need to be talking all day every day, but if you chime in with meaningful contributions at least some 2-3 times during the semester, that would do it.

# Attendance and late policy

I'll spend the first 5 minutes of each class waiting for those that are late. That is, if a meeting is scheduled for 1 pm, Zoom will open at 1 pm, and we'll be just chatting until 1:05. At 1:05 sharp we will start the class

# Academic integrity and plagiarism

For all homework assignments, the *writing* should be done by *you*. Borrowing *texts* from other people or from the internet without an acknowledgement (such as a citation, a reference, an explicit acknowledgement) is unacceptable, and will result in bad things happening.

At the same time, for most assignments, collaboration and team work are heavily encouraged. Seek inspiration by talking to your peers before doing your work! Show your work to other people and ask for their suggestions and feedback! Offer your help to struggling brothers and sisters! I expect you to do your own work, but also productively collaborate, as that's how it happens in real life.

# Mutation clause

Instructor will continue to improve this syllabus during the semester, to make the course even more amazing (for example, move topics around if we are slow, change reading materials, etc.)

The changes will never be retroactive though! If a rule changes, it will only apply to future assignments, not to past assignments :)

# DRAFT Weekly Schedule

**Please, rely on weekly posts on Piazza for homework. This plan below is roughly correct, but needs some fine-tuning ;)**

For the readings, the code "UT s1ch1-2" stands for "[University of Texas free textbook](https://nba.uth.tmc.edu/neuroscience/toc.htm)" section 1, chapters 1 to 2.

| **Week** | Topics / Papers                                              | Presenters |
| -------- | ------------------------------------------------------------ | ---------- |
| Feb 05   | Crash course Neuroscience. Neurons; spikes; synapses; coding; excitation and inhibition; plasticity; receptive fieds; maps and cortical projections. | none       |
| Feb 12   | Crash course machine learning. Google training. **TODO**: Full google training or parts of it? Any other materials? | none       |
| Feb 19   | Crash course computational neuroscience.<br />1)  Something about different levels of modeling<br />2) ML for neuroscientists (paper) | none       |
| Feb 26   |                                                              | 1          |
| Mar 05   |                                                              | 2          |
| Mar 12   |                                                              | 3          |
| Mar 19   | **Respite** (we don't meet)                                  |            |
| Mar 26   |                                                              | 4          |
| Apr 02   |                                                              | 5          |
| Apr 09   |                                                              | 6          |
| Apr 16   |                                                              | 7          |
| Apr 23   |                                                              | 8          |
| Apr 30   |                                                              | 9          |
| May 07   | *Advising week, we probably don't meet - TBC*                |            |
| May 14   |                                                              | 10         |
| May 20   | **Completion week** (no regular class, but we can use this time for 1:1 meetings) |            |



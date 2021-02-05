# (Topics in) Computational Neuroscience 2021

*Version: Feb 03 2021*

# Some introductory words

The intended name of this course was **Topics in Computational Neuroscience**, as Computational neuroscience is a huge field that would take at least 4 full courses to learn: 

* one for "classic" computational neuroscience (immediately adjacent to biophysics) that models spiking of neural cells, plasticity in synapses, and processing in cell dendrites;
* one for theoretical neuroscience (adjacent to cognitive science), that looks at high-level processes in the brain; information flows, predictive coding, decision making etc.
* one for modern mathematical and machine learning techniques applied to neuroscience data, 
* and one adjacent the field of complex systems: the activity of small networks, criticality, network neuroscience. 

We, on the other hand, have only half a course worth of time. So what we will do is **pick one subtopic** of this broad field, and read about 12 papers on this narrow subtopic. So "Topics in..." would have been a more honest title.

The reason this course is called simply "Computational Neuroscience" is therefore purely aesthetical. As it turns out, a longer title would not have fit on the official transcript, and would have been truncated to "Topics in Computational Neur." Wouldn't you rather see "Computational Neuroscience" on your transcript? I also think so! 🙂 Thus the name.

But in spirit, it's still only one topic, that I change every time I teach this course, depending on what's hot in the area. And the topic for our current 2021 session is: **How artificial neural networks (deep learning) can help us to understand the brain, and how learning about the brain can help us to build better artificial networks**. Or maybe it's better to say "Whether" instead of "how", as both of these statements are hot, actively researched, and contentious. But we'll learn it by the end of this course!

# Course Goals

In this course we will:

* Learn several modern methods of computational neuroscience; in the interdisciplinary field between computational neuroscience proper, and deep learning.
* Learn to read machine learning papers and get the gist of them without getting too intimidated
* See how (or "whether") neuroscience and AI can help and inform each other
* Become better presenters

# Course Logistics

**Instructor:** Arseny Khakhalin (pronounced: ar-SEH-ny ha-HA-leen; ipa: ɑr'sʲenʲi xa'xalʲin); [khakhalin@bard.edu](mailto:khakhalin@bard.edu)

**Meeting times:** Fridays, 2-3:20p, on Zoom.

As we are still in a pandemic, with new strains emerging, the course is online-only. 

* We will use **Piazza** for offline work (see more info below). I will post assignments there, and collect your responses (typically, questions you had, that you would like to discuss in class). But we can also use it as a Q&A, or even a discussion forum.
* We'll have **weekly Zoom calls**, discussing papers. Generally, we'll try to have **one paper a week**, unless there's some background that needs to be taken from a different paper, or a review on a topic.
* Except for the first 3 classes, **every week we'll have 3 people responsible for presenting a paper**. One person to provide the background, one person to describe the methods, and the third one to explain the results. Each of these three presentations should last for ~7-8 minutes, so that we had time for questions (It's 1:20 total, so with ~5 minutes lost, and 30 minute for the presentation, we'll have ~45 minutes for asking questions and figuring things out together.)

> 💡 **On time commitment:** You might have heard from me before that, in my opinion, a full 4-credits course should take about 10 hours of work a week for one full course. The logic is simple: full-time learning should be equivalent to full-time work; both because a full-time working week is known to be doable (not too long, not too short), and because it gives people enough spare time to  care about their family, side job, hobbies, social life, or whatever. A full-time job is 40 hours a week, and a "full load" in college is 4 full courses per semester, therefore 1 full course should take about 10 hours a week, total.
>
> This course is only 2 credits, so it gives us 5 hours a week. 1 hour 30 minutes of it we'll spend in class, which leaves ~3:30 hours a week for your independent work (or work in small groups). As we'll be having presentations, the load may be a bit uneven, closer to 2 hours on some weeks (as realistically that's the minimal time it takes to read and annotate a paper), and maybe about 4-5 hours on the week of your presentation. But on average, let's aim at 3:30 hours a week of independent work. If you spend less time than that, with one short meeting a week, you won't learn much. Keep it in mind!

### Piazza

The main way of communication for this course is the [**Piazza** discussion board](https://piazza.com/). It's a dedicated social media-like place created specifically for this course (something in-between reddit, quora, internet forums, and stackexchange).

* All announcements about the course will go on Piazza
* All materials will be posted on Piazza.
* All questions will be asked and answered on Piazza (although of course feel free to send me an email if you have a personal question)
* Homework assignments will be collected on Piazza. In most classes, I use anonymous posting, but as this class is smaller, and as we're all in the same boat this time around (none of us is a specialist in deep learning, me included), I think it may be better to post under our real names. Let's give it a try, and see how it goes.

> 💡 By default, Piazza will send updates to your email about any change, and every post. Even if you use auto-filtering in your gmail folders (and I do definitely recommend that you set up filtering!), it quickly gets overwhelming. So personally, I recommend that you disable all emails from Piazza, and just visit it regularly during the week.

If Piazza is down, send me an email. We'll switch to emails temporarily, until it is fixed.

### Zoom

* Before classes even start, make sure to **update Zoom to the latest version** (go to https://zoom.us/download, download and install the latest version). This is important, as old versions don't support all features that we will be using.
* **Make sure your email and names are set correction on Zoom**. Go to Zoom website (https://zoom.us/) log in, go to `My Account`,  `Profile`.
* Make sure you have your full name on Zoom; the **name that you want people to actually use** (especially if it differs from your legal name).
* Make sure you **put your Bard email on Zoom:**  on the `Profile` page, find `Sign-In Email`, click `Edit`, and put **your Bard email** there. The reason this is important: I will use these emails to automatically track **attendance** with Zoom logs. If you don't put your Bard email, I won't be able to recognize you in the log, and thus won't count this meeting for attendance.
* Try to **connect to Zoom from your computer** (not from a phone). Of course, in a pinch you can try to connect from your phone (it's probably better than not connecting at all), but we'll be doing stuff during these meetings (assignments, quizzes, white board, and what not), so being at your computer with a normal monitor would make things so much easier.
* **Try to have your camera on.** Now, this is a tricky point, as some people cannot have their cameras on: maybe they live with roommates who are always naked, or they don't want to show their brother's Avengers poster, or they have a really bad connection... But if the entire class has their cameras off, it will look sad; it will be infinitely harder for me to teach, and we'll miss on the social aspect of learning. So if you can afford to have a camera on, please consider having it on! I, for one, will be extremely grateful to you! It's not a requirement, but a request, if possible.
* Every now and then, on Zoom, I will send you to auto-generated random "**Breakout rooms**": small chats for 3-4 people, to discuss questions. There are two reasons we are doing it. One, I want you to interact with each other at least somewhat. Second, educational research has shown that when students try to talk to each other about what they learn, they learn MUCH better. Not all people realize this. Some are like "I want things to be explained to me by a prof, not by some rando", but actually it's a proven fact. Peer-learning works so well because people often have similar misunderstandings, and talking them through helps. And also, trying to explain something to another person, trying to actually verbalize your thoughts, even if they are vague and very tentative, is *the best way* to understand, and learn. So be ready for breakout rooms.
* **Be ready to participate** in class, using either your voice, or chat. I will be mostly asking breakout rooms to share what they discussed, but sometimes I may also call people at random (I'll code a random student generator for this purpose!)
* **Keep Zoom on "mute" when not talking.** When speaking, unmute. Once you're done, please mute back. If you need to add something, unmute again, add something, then mute back :)
* If I disappear from Zoom (because a tree fell in a forest and restarted all computers in Tivoli), please wait about 10 minutes. It takes my router ~5 min to restart, so I should be able to be back in this time. If you can **self-organize and keep doing something useful** - that would be fantastic! But if I'm not back in 15 minutes, then of course you are legally allowed to leave haha.
* If Zoom is down and you can't connect - **send me an email**. We always have Google Meetings as a back-up option.

# Assignments

## Weekly Reading Reflection

The most regular and predictable assignment for this course will be the **weekly reading reflection**, or **weekly question**. Every week, as you read the paper(s), I will ask you to write down the questions that you have. Then try to answer some of these questions yourself, using Googling and common sense. But once the time is up, and you cannot struggle any more, or if you feel that you really hit a wall, post the remaining questions on Piazza. We'll try to tackle them in class together!

## Presentations

As described above, papers will be presented by triads of people. I will assign these groups of 3, for every week, and you will need to decide who presents the background, who does the methods, and who does the results.

With ~18 students and 3 students per group, it will take 6 weeks to give everyone a chance to present. We however will have only 10 weeks with presentations. Which means that most people will present twice, but some of you will only present once. Unless we do more than one paper on some days; say, a review / background paper, and a main paper. We'll see!

# Grading

This course is graded using an “Ungrading” system, because I got exhausted by all the discussions about grades, pass-fail, GPA, and what not. Here's a more elegant solution, for a more civilized age:

To get a **C** you need to:

* Be present and participate in 80% of classes
* Submit 80% of assignments on time. The submissions don’t have to be perfect, but they need to be reasonable (present evidence of work). If a submission is problematic, I’ll let you know, so that you could improve next time.
* **A grade of "C" cannot be turned into a "Pass"**. If you ask, I will refuse. Sorry!

To get a **B**:

* Participate in 90% of classes
* Submit 90% of short written assignments

To get an **A**:

* **On top of all requirements for a "B"**, also present papers well, or show particularly productive participation in class, during paper discussions.
* Presentations will be graded on a "weak / decent / great" scale. In-class participation will be graded on a (none / some / wow) scale. You don't need to be talking all day every day, but if you chime in with *meaningful* contributions at least every now and then, that would do.
* If you are half-way between a B and an A, you'll be given a half-way grade (either a **B plus**, or an **A minus**)
* **Grades of B and higher can be turned into a Pass if you so desire**. You don't even need to tell me in advance, or reach out, I'll ask you myself, before submitting final grades at the end of the course. You'll know your "internal grade", and then if you prefer to have a "P" on your final transcript instead, that's fine with me!

# Attendance and late policy

I'll spend the first 5 minutes of each class waiting for you to connect. That is, if a meeting is scheduled for 1 pm, Zoom will open at 1 pm, and we'll be just chatting until 1:05. At 1:05 sharp we will start the class.

If you are late 3 times, it will be counted as one absense.

# Academic integrity and plagiarism

For all homework assignments, the *writing* should be done by *you*. Borrowing *texts* from other people or from the internet without an acknowledgement (such as a citation, a reference, an explicit acknowledgement) is unacceptable, and will result in bad things happening.

But overall, collaboration and team work are heavily encouraged. Seek inspiration by talking to your peers before doing your work! Show your work to other people and ask for their suggestions and feedback! Read papers together! Prepare presentations together! Offer your help to struggling brothers and sisters! I expect you to do your own work, but also productively collaborate, as that's how it happens in real life.

# Mutation clause

I will continue to improve this syllabus during the semester, to make the course even more amazing (for example, move topics around if we are slow, change reading materials, etc.) Any changes in course policies are never retroactive. If a rule changes, it only apply to future work, not to past work.

# Course at a glance

Please see a list of detailed week-by-week readings below, but ultimately the most recent correct version will always be posted on Piazza, with a `homework` tag.

| **Week** | Topics / Papers                                              | Presenters |
| -------- | ------------------------------------------------------------ | ---------- |
| Feb 05   | Intro to neuro.                                              | none       |
| Feb 12   | Conceptual Intro to deep learning                            | none       |
| Feb 19   | Crash course in Machine learning from Google.                | none       |
| Feb 26   | Neuro-DL success story: convolutional networks and biological vision | 1          |
| Mar 05   | How DL is not Neuro: problem of supervised learning; recent tricks | 2          |
| Mar 12   | How Neuro is not DL: gradient descent in the brain; credit assignment problem | 3          |
| Mar 19   | **Respite** (we don't meet)                                  |            |
| Mar 26   | Intertretability in DL and Neuro                             | 4          |
| Apr 02   | Single neurons as Deep Networks                              | 5          |
| Apr 09   | Vision and convnets revisited                                | 6          |
| Apr 16   |                                                              | 7          |
| Apr 23   | Transformers (???)                                           | 8          |
| Apr 30   |                                                              | 9          |
| May 07   | *Advising week, we probably don't meet - TBC*                |            |
| May 14   |                                                              | 10         |
| May 20   | **Completion week** (no regular class, but we can use this time for 1:1 meetings) |            |

# Detailed Weekly Schedule

## Week 1 - Crash course Neuroscience

Crash course Neuroscience. **Terms you need to know and vaguely understand** (at the very least, look each of them up, and read the corresponding article): neuron, spike, axon, synapse, excitation and inhibition, dendrite, neural coding (rate code, temporal code, population code), synaptic plasticity (Hebbian, STDP), intrinsic plasticity, receptive field, cortical map.

Main resource: Wikipedia + Google image search 😉

Optional extra materials:

* My "Introduction to Neuroscience course" (video lectures): https://www.youtube.com/playlist?list=PLOdJKIwLQzBeTkMxjpFq5Ytzn89t0VayG
* U Texas free neuroscience textbook: https://nba.uth.tmc.edu/neuroscience/
* Scholarpedia (it's like Wikipedia, but written by 100 or so professors, turning it into a sort of a free loosely connected textbook) on computational neuroscience: http://www.scholarpedia.org/article/Encyclopedia:Computational_neuroscience

### Class plan

Neurons. Their shape (dendrites, axon). Why the shape. How they send messages (AP). 

What decides if AP is happening (axon hillock).

Types of neuronal coding. Representing network activation in models. Spike vs rate models. Input-output function for rate code.

Is there noise?

How do they connect? (synapses). What happens in the synapse? Is it just a faithful transmitter or activation, or does it shape the signal somehow? How?: sign (inhibition). Threshold. Temporal effects. Plasticity. What's plastic in the synapse?

What is the role of inhibition? (math and normalization). Feedback inhibition - abstraction and effect. FF inhibition. Dale's rule.

Are there any other types of plasticity? Intrinsic plasticity. Dendrites - do they do anything? Other types of neurotransmitters?

Logic of synaptic plasticity. Hebbian rule. Reinforcement learning. STDP. Synaptic scaling.

Architecture and connectivity (is it an all-to-all graph?) How many inputs, outputs on average? What governs connections? Developmental rules. Maps.

If time: resonance and the idea of Hopfield networks.

Typical receptive fields (vision as an example).

## Week 2 - Introduction to Deep learning

* Four videos from 3Blue1Brown: https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi
  They are about 1 h 10 min in total, but I really suggest that you **pause frequently**, and think about what's going on, as they are very dense with ideas, even if they sound smooth. Don't be fooled by how smooth they look and how logical everything seems. If you just go with "Eh, sounds reasonable" you won't learn anything. OF COURSE it sounds reasonable!! But try to get to the bottom of it. How does it work? Why does it work like that?
* An educational video on computer vision (6 min): https://www.youtube.com/watch?v=i8D90DkCLhI&t=0s

Optional, catch-up, and advanced materials:

* If you never studied, or forgot, how derivatives work, look through these videos: https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr
* If you want to better understand the matrix notation that he uses, look through these videos. In general, getting at least some idea about **linear algebra** would be **incredibly useful for this course**, and for your life in general. Many people believe that linear algebra is the most useful math one could possibly study in college (some people think that statistics is more important, but it's definitely one of the top two). The playlist: https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab

## Week 3 - Intro to ML, take two

The homework for this week is a **crash course in machine learning** from Google. Now, this is a course for managers, programmers, and other sorts of tech people, not for scientists, so it puts an emphasis on the practical, business use of deep learning, not the science aspect of it. But I think it's actually better. First, because the course is great, has all sorts of built-in quizzes, and an absolutely amazing "playground" that lets you play with an artificial neural network on your own computer without coding anything. And second, the field of deep learning has grown so much in last 6 years or so because of its business applications. That's what's driving it, that's what's funding it, and that's also where machine learning goes awry every now and then, resulting in all sorts of hot ethical discussions. So I think it is very valuable to dive into this slightly different world, motivation, and terminology, before going back to neuroscience later.

* Machine Learning Crash Course from Google: https://developers.google.com/machine-learning/crash-course/
  * Watch the videos, do the quizzes, and make sure to try "playground" exercises (the ones that run in the browser). 
  * Skip all exercises in Collab. Without coding, it will take you 3-4 hours for the part of the course that we need. Which is a sizeable chunk for one week, but it's a one-time effort.
  * Sections you need to do: Framing, Descending, Reducing Loss, Testing and training sets, Validation set, **Neural Networks** (the playground exercise for this chapter is **the  main resource** for us in this course. You should spend a good hour playing with it, at the very least).
  * All other sections are optional, in the sense that I don't expect you to go through them, but of course feel free to if you are interested. It's a good course; very surface-level, but it gives a very good overview of this trade.
* For our review in class, we'll use this [direct link to the full version of the network playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.56380&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false). But don't try it before taking the crash course, you'll probably just get overwhelmed by the options, while the crash course adds them gradually, and provides good guidance in terms of what to do at each step.

# Below this point all plans are for now tentative

## Neuro roots of DL

Is it a separate week, or do we tuck it in the 2nd week?

Some other introduction, supposedly for biologists. But is it even good? If it's not neuro-based, it's irrelevant, as we want to stress connections with neuro:

* Kriegeskorte, N., & Golan, T. (2019). Neural network models and deep learning. Current Biology, 29(7), R231-R236.
  https://www.sciencedirect.com/science/article/pii/S0960982219302040

## DL❤️Neuro success story: convolutional networks

perhaps 2 papers: associated breakthrough, and parallels with Neuro

## Ways in which current DL differs from Neuro

Possible papers:

Zador, A. M. (2019). A critique of pure learning and what artificial neural networks can learn from animal brains. Nature communications, 10(1), 1-7.

Bengio, Y., Lee, D. H., Bornschein, J., Mesnard, T., & Lin, Z. (2015). Towards biologically plausible deep learning. arXiv preprint arXiv:1502.04156.
https://arxiv.org/pdf/1502.04156.pdf
Mathy, then mnist

Dropout?

?

## Ways in which Neuro differs from DL

A bit older review?

Gradient descent in the brain? (critique)

Credit assignment?

Possible papers:

* Backpropagation and the brain
  Timothy P. Lillicrap, Adam Santoro, Luke Marris, Colin J. Akerman & Geoffrey Hinton (2020)
  https://www.nature.com/articles/s41583-020-0277-3

## Attempts of modern synthesis: DL as a model for Neuro

* "**What is a model?**" video lecture, by Gunnar Blohm (27 min), from a course on computational neuroscience: https://www.youtube.com/watch?v=KxldhMR5PxA
  * (this lecture comes from a cool open project called "Neuromatch academy"; for now I'm not necessarily assigning other videos from this project, but it's a cool project!): http://www.neuromatchacademy.org/syllabus/

Main paper:

* Richards, B. A., Lillicrap, T. P., Beaudoin, P., Bengio, Y., Bogacz, R., Christensen, A., ... & Gillon, C. J. (2019). A deep learning framework for neuroscience. Nature neuroscience, 22(11), 1761-1770. - a 8-page review about how bottom-up DL modeling can help to reverse-engineer the brain. Perspective.
  https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7115933/

Optional materials:

* ?

## Intrepretability in DL and Neuro

Some stuff on core ML intrerpretability #todo

Distill simulations on interpretability #todo

Maybe in ethics intro as well, if there's a short one? tbc.

Optional:

* Lillicrap, T. P., & Kording, K. P. (2019). What does it mean to understand a neural network?. arXiv preprint arXiv:1907.06374.
  https://arxiv.org/abs/1907.06374 - an opinion piece, half-practical guidance, half philosophy

## Single neurons as Deep Networks

David, Beniaguev, Segev Idan, and London Michael. "Single Cortical Neurons as Deep Artificial Neural Networks." bioRxiv (2019): 613141. https://www.biorxiv.org/content/10.1101/613141v1.full.pdf

Jones, I. S., & Kording, K. P. (2020). Can Single Neurons Solve MNIST? The Computational Power of Biological Dendritic Trees. arXiv preprint arXiv:2009.01269.
https://arxiv.org/abs/2009.01269

## Vision and convnets revisited

Check these:

* Geiger, F., Schrimpf, M., Marques, T., & DiCarlo, J. (2020). Wiring Up Vision: Minimizing Supervised Synaptic Updates Needed to Produce a Primate Ventral Stream. bioRxiv.
  https://www.biorxiv.org/content/10.1101/2020.06.08.140111v1
  Protoid: Geiger2020ventralstream

* Yaoda Xu, Maryam Vaziri-Pashkam (2020) Limited correspondence in visual representation between the human brain and convolutional neural networks
  https://www.biorxiv.org/content/10.1101/2020.03.12.989376v1 
  Essentially, some critique of deepneuro!

## Replication of grid cells?

Some basic info on grid cells?

Sorscher, B., Mel, G., Ganguli, S., & Ocko, S. (2019). A unified theory for the origin of grid cells through the lens of pattern formation. In Advances in Neural Information Processing Systems (pp. 10003-10013).
https://papers.nips.cc/paper/9191-a-unified-theory-for-the-origin-of-grid-cells-through-the-lens-of-pattern-formation
Supposedly, explains the development of grid cells, synthesizing two existing theories (recurrent with lateral inhibition and spontaneous development during navigation?)

## Transformers, and comparison with brain activation?

?

## Replication of motor control?

Michaels, J. A., Schaffelhofer, S., Agudelo-Toro, A., & Scherberger, H. (2019). A neural network model of flexible grasp movement generation. bioRxiv, 742189.
https://www.biorxiv.org/content/10.1101/742189v1

# Other Potential papers

🔥 Hassabis, D., Kumaran, D., Summerfield, C., & Botvinick, M. (2017). Neuroscience-inspired artificial intelligence. Neuron, 95(2), 245-258.
https://www.sciencedirect.com/science/article/pii/S0896627317305093
Quite popular.

Perez-Nieves, N., Leung, V. C., Dragotti, P. L., & Goodman, D. F. (2020). Neural heterogeneity promotes robust learning. bioRxiv.
https://www.biorxiv.org/content/10.1101/2020.12.18.423468v1

Gillon, C.J., Pina, J.E., Lecoq, J.A., Ahmed, R., Billeh, Y., Caldejon, S., Groblewski, P., Henley, T.M., Lee, E., Luviano, J. and Mace, K., 2021. Learning from unexpected events in the neocortical microcircuit. bioRxiv.
https://www.biorxiv.org/content/10.1101/2021.01.15.426915v1 
Tweetstorm: https://twitter.com/colleenjgillon/status/1351557910439059457
Unsupervised novelty detection in the visual cortex; a convergence of top-down and bottom-up signaling on 2 different sets of dendrites.

Hasson, U., Nastase, S. A., & Goldstein, A. (2020). Direct Fit to Nature: An Evolutionary Perspective on Biological and Artificial Neural Networks. Neuron, 105(3), 416-434.
https://www.cell.com/neuron/pdf/S0896-6273(19)31044-X.pdf
An opinion (perspective) on how we could, and should, use deep models to understand psychology and neuroscience, as they are not that different than the results of evolution, after all.

Raman, D. V., Rotondo, A. P., & O’Leary, T. (2019). Fundamental bounds on learning performance in neural circuits. Proceedings of the National Academy of Sciences, 116(21), 10537-10546.
https://www.pnas.org/content/116/21/10537.short

Hassan, B. A., & Hiesinger, P. R. (2015). Beyond molecular codes: simple rules to wire complex brains. Cell, 163(2), 285-291.
https://www.cell.com/cell/fulltext/S0092-8674(15)01193-9
💎 Developmental biology bordering fractals and graphs (maybe? not sure, but judging from the pics) - a nice review-like paper (perspective); worth a priority read :)

Richards, B. A., Xia, F., Santoro, A., Husse, J., Woodin, M. A., Josselyn, S. A., & Frankland, P. W. (2014). Patterns across multiple memories are identified over time. Nature neuroscience, 17(7), 981.
https://www.nature.com/articles/nn.3736

Lillicrap, T. P., & Scott, S. H. (2013). Preference distributions of primary motor cortex neurons reflect control solutions optimized for limb biomechanics. Neuron, 77(1), 168-179.
https://www.sciencedirect.com/science/article/pii/S0896627312009920

Deep neuroethology of a virtual rodent
Josh Merel, Diego Aldarondo, Jesse Marshall, Yuval Tassa, Greg Wayne, Bence Ölveczky
https://arxiv.org/abs/1911.09451
Apparently create a vidrual 3D rodent (like, with muscles, joints and what not), make it move in virtual environment, learn to move, then study its network using neuro methods.

Li, Z., Brendel, W., Walker, E., Cobos, E., Muhammad, T., Reimer, J., ... & Tolias, A. (2019). Learning from brains how to regularize machines. In Advances in Neural Information Processing Systems (pp. 9525-9535).
https://arxiv.org/abs/1911.05072

Merel, J., Botvinick, M., & Wayne, G. (2019). Hierarchical motor control in mammals and machines. Nature Communications, 10(1), 1-12.
https://www.nature.com/articles/s41467-019-13239-6
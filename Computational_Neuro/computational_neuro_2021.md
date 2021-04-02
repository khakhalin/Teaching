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

# Logistics

**Instructor:** Arseny Khakhalin (pronounced: ar-SEH-ny ha-HA-leen; ipa: ɑr'sʲenʲi xa'xalʲin); [khakhalin@bard.edu](mailto:khakhalin@bard.edu)

**Meeting times:** Fridays, 2-3:20p, on Zoom.

As we are still in a pandemic, with new strains emerging, the course is online-only. 

* We will use **Piazza** for offline work (see more info below). I will post assignments there, and collect your responses (typically, questions you had, that you would like to discuss in class). But we can also use it as a Q&A, or even a discussion forum.
* We'll have **weekly Zoom calls**, discussing papers. Generally, we'll try to have **1-2 papers a week**, and maybe some background materials to look through, but not necessarily read in detail.
* Except for the first 3 classes, **every week we'll have 3 people responsible for guiding us through a paper**. See below for details.

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

## Presentations (guiding through a paper)

When guiding the class through a paper, **let's assume that everyone in class have read them**. Which means that you don't need to present papers as you typically present things in most other classes. No need to do an introduction, no need to cover every detail. This topic is a not new for the room; everyone have read the same paper! So your role is more of a facilitator than of a presenter.

Do the following instead:

1. Give a **very brief overview**. Very brief. More like a reminder. Literally 1-2 minutes, not more. Main point of the paper. Main take-home message, or main weird quality of it.
2. Then go through the paper, but **only cover things that are** either
   - really **cool**, and thus HAVE to be mentioned
   - really **confusing**, and you got them, and are proud of that, and want to share
   - really confusing, and you are still confused, and want to discuss it as a group
3. That's it. Only these parts! **Skip everything that is boring, irrelevant, or feels like a repetition.** We dont' have that much time in class, so let's concentrate on things that are important! Don't try to discuss every paragraph, every idea, and every figure. (But maybe mention why you are skipping this or that - is it because it feels like a tangent? Or is it because it's boring? Both are valid reasons to skip a segment, but it's cool for us to know :)
4. If you want to show external images, feel free to make a presentation. If not, **just show the paper**, maybe marked-up with yellow (it's possible to use highligher in most pdf readers). And let's talk about it. If you are confused, try to formulate what is it that makes this part confusing. If you have some ideas, but are not sure if they are right, deascribe these ideas, before asking the room four their inputs :)
5. Before class, consider reading questions on Piazza, and use them to guide your presentation. It may be super-hepful!

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

## Attendance and late policy

I'll spend the first 5 minutes of each class waiting for you to connect. That is, if a meeting is scheduled for 1 pm, Zoom will open at 1 pm, and we'll be just chatting until 1:05. At 1:05 sharp we will start the class.

If you are late 3 times, it will be counted as one absense.

## Academic integrity and plagiarism

For all homework assignments, the *writing* should be done by *you*. Borrowing *texts* from other people or from the internet without an acknowledgement (such as a citation, a reference, an explicit acknowledgement) is unacceptable, and will result in bad things happening.

But overall, collaboration and team work are heavily encouraged. Seek inspiration by talking to your peers before doing your work! Show your work to other people and ask for their suggestions and feedback! Read papers together! Prepare presentations together! Offer your help to struggling brothers and sisters! I expect you to do your own work, but also productively collaborate, as that's how it happens in real life.

## Mutation clause

I will continue to improve this syllabus during the semester, to make the course even more amazing (for example, move topics around if we are slow, change reading materials, etc.) Any changes in course policies are never retroactive. If a rule changes, it only apply to future work, not to past work.

# Course at a glance

Please see a list of detailed week-by-week readings below, but ultimately the most recent correct version will always be posted on Piazza, with a `homework` tag.

| **Week** | Topics / Papers                                              |
| -------- | ------------------------------------------------------------ |
| Feb 05   | Intro to neuro                                               |
| Feb 12   | Theoretical Intro to deep learning                           |
| Feb 19   | Practical intro to machine learning from Google              |
| Feb 26   | DL ♥ Neuro success story: convolutional networks             |
| Mar 05   | Convolutional networks vs biological vision                  |
| Mar 12   | DL from the Neuro point of view (what brains can do that DL struggles with) |
| Mar 19   | **Respite** (we don't meet)                                  |
| Mar 26   | Neuro from the DL point of view (what DL can do what brains struggle with) |
| Apr 02   | Modern synthesis: DL and Neuro informing each other          |
| Apr 09   | Single neurons as Deep Networks                              |
| Apr 16   | Neuromorphic engineering                                     |
| Apr 23   | Interpretability in DL and in the brain                      |
| Apr 30   | GPT and the criteria for "understanding" (Gary Marcus)       |
| May 07   | **Advising week** (we don't meet)                            |
| May 14   | Ethics in AI                                                 |
| May 20   | **Completion week** (no regular class, but we can use this time for 1:1 meetings if needed) |

? That paper about error signal in the cortex? (Gillon 2021)

# Detailed Weekly Schedule

## 1. Crash course Neuroscience

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

## 2. Introduction to Deep learning

Videos:

* Crash course machine learning (10 min): https://www.youtube.com/watch?v=z-EtmaFJieY
  Note that deep learning is only one method of machine learning. So machine learning sets the stage of how people talk about these methods, and then the next set of videos, below, will actually explain you how machine learning works.
* Four videos from 3Blue1Brown: https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi
  They are about 1 h 10 min in total, but I really suggest that you **pause frequently**, and think about what's going on, as they are very dense with ideas, even if they sound smooth. Don't be fooled by how smooth they look and how logical everything seems. If you just go with "Eh, sounds reasonable" you won't learn anything. OF COURSE it sounds reasonable!! But try to get to the bottom of it. How does it work? Why does it work like that?
* Architectures of deep neural networks (9 min): https://www.youtube.com/watch?v=oJNHXPs0XDk
  Pay attention to 1) how exactly deep networks are inspired by biological neurons, 2) convolutional neural networks described in the 2nd half of the video. We'll talk more about them in the future!
* A series of 15 educational videos on computer vision, about 5 min each. Watch at least the first few; but ideally, all of them. They are quite entertaining, introduce lots of useful terms, concepts, and also some history: https://www.youtube.com/watch?v=i8D90DkCLhI&t=0s

Optional catch-up and advanced materials:

* If you never studied, or forgot, how derivatives work, look through these videos: https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr
* If you want to better understand the matrix notation that he uses, look through these videos. In general, getting at least some idea about **linear algebra** would be **incredibly useful for this course**, and for your life in general. Many people believe that linear algebra is the most useful math one could possibly study in college (some people think that statistics is more important, but it's definitely one of the top two). The playlist: https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab

### Class plan

Activation (of each neuron).

Activation function (which ones are common? which ones are more popular?).

Matrix notation: how does matrix multiplication work mechanistically, and how to think of it (the idea of operators. E.g. how would a rotation operator look like?)

How many parameters does this network have: 3 variables (inputs), projecting to a layer of 3 neurons, projecting to 2 outputs?

Loss function. How to define them? For a classifier? For a predictor (say, if we want to guess how some signal will behave in the future? Or fix broken audio? Or interpolate between the frames?)

How to find weights of a deep network in practice?

* How to think about it?
* How does it happen mechanistically?  What's backpropagation?
* Stochastic Gradient Descent
  * What is gradient?
  * Why the word "stochastic" is here?
* If ANNs are like brains, then does SGD exist in the brain?

## 3. Intro to ML, take two

The homework for this week is a **crash course in machine learning** from Google. Now, this is a course for managers, programmers, and other sorts of tech people, not for scientists, so it puts an emphasis on the practical, business use of deep learning, not the science aspect of it. But I think it's actually better. First, as the course doesn't assume that we are PhD students or something, it has all sorts of built-in quizzes, and an absolutely amazing "playground" that lets you play with an artificial neural network on your own computer without coding anything. And second, the field of deep learning has grown so much in last 6 years or so precisely because of its business applications. That's what's driving it, that's what's funding it, and that's also where machine learning goes awry every now and then, resulting in all sorts of hot ethical discussions. So I think it is very valuable to dive into this slightly different world, motivation, and terminology, before going back to neuroscience later.

* Machine Learning Crash Course from Google: https://developers.google.com/machine-learning/crash-course/
  * Watch the videos, do the quizzes, and make sure to work your way through the "playground" exercises (the ones that run in the browser). 
  * Skip all exercises in Collab. Without coding, it will take you 3-4 hours for the part of the course that we need. Which is a sizeable chunk for one week, but it's a one-time effort.
  * Sections you need to do: Framing, Descending, Reducing Loss, Testing and training sets, Validation set, **Neural Networks** (the playground exercise for this chapter is **the  main resource** for us in this course. You should spend a good hour playing with it, at the very least).
  * All other sections are optional, in the sense that I don't expect you to go through them, but of course feel free to if you are interested. It's a good course; very surface-level, but it gives a very good overview of this trade.
* For our review in class, we'll use this [direct link to the full version of the network playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.56380&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false). But don't try it before taking the crash course, you'll probably just get overwhelmed by the options, while the crash course adds them gradually, and provides good guidance in terms of what to do at each step.

### Class plan

💡 We need to id groups of 3 students for presentations for next several weeks. Let's start with seniors?

What's the difference between unsupervised, supervised, and reinforcement learning? (If you don't know; guess? Or ask each group member to google their term real fast, then compare?) Give an example? Are there other alternatives beyond these 3 categories?

What class of functions is available with:

* 1 input, 1 output, and 1 ReLu unit? (essentially, y=relu(ax+b))
* 2 units: x→relu unit→linear unit? (each dense layer of connections is represented by an arrow "→", and includes weights and biases).
  * How many parameters does this network have?
  * Can we make a network that does "y=x for x<0, y=0 for x>0"?
* What if we make it wider: x→2 relu→linear?
  * Can we approximate a step with this network (const1 value until some x1, const2 value after it)?
* What if we make it deeper: x→relu→relu→linear?
  * Can we approximate a step with this one?
* What would we need if we wanted a 2-step teracce? (0 until x1, then 1 between x1 and x2, then 2 after x2 until inf) What is the minimal network architecture here?
* What would we need it we wanted to output 1 for a band (x1, x2),  and 0 outside of it? What is the minimal architecture here?
* Let's now consider a 2D case: x,y → z. What do we get with a single linear unit?
* Combining these 2 pieces of info, what will we get from x,y → 2 relu → linear → z?
* Mentally extrapolate to wide and deep?

🔥 For the [playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.56380&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false) exercise, what is the minimal set of neurons that can solve the XOR task? What set of neurons solves it reliably?

* What are the differences between making a model deeper, and making a model wider?
* The idea of lottery ticket.
* Question (kinda asked by Hadley a week ago, and Max this week): can there be too many neurons in a network?

**Regularization**:

* What problem does it try to solve? Where is this problem coming from?
  * *As a hint: if some weights in the network, especially in the later layers, are insanely big, what could it mean?*
* How to tell that the model is overfitting?
* How regularization is implemented in practice?
  * Also, as a reminder, how is loss calculated?
* What's the difference between L2 and L1 regularizations? Why do they act differently? When would we like one, or another?
* What about dropout? How does it work? What problem does it seem to be fighting?
  * *Tell about the ensemble idea.*
* What is curse of dimensionality? Where does it come from?

How to understand what each of the units (neurons) in the middle of the network does? In the playground, as there are only 2 inputs (x and y), we can just visualize responses to all possible inputs. But what if the input is high-dimensional (say, an image, or a description of a house?)

* Does it resemble any concepts from neuroscience? (This question obviously only applies if you studied some neuroscience :)

For the MNIST (digits) example, the video shows that the "preferred" patterns for each neuron in the 1st layer are nonsensical (look nothing like what a human would expect). 

* Do you think this network will generalize well, on digits met  "in the wild"? Say, on a random photo made by your phone? What problems would you expect?
* Can we modify *the data* somehow, to force the network to learn something more generalizable, and also more interpretable?
  * (The idea of data augmentation)
* Or, alternatively, how can we *modify the network* to make it learn something more reasonable?
  * Convnets, or CNNs. Does it make the task of training easier or harder? (How does the number of parameters change?)

Architectures

* Autoencoders. What are they?

* Other architectures (from the "neural networks Zoo"). 
* How to understand which architecture to use? (It's a trick question)

What is one potential problem with ReLUs, compared to, say, sigmoids, or leakyReLUs? What an happen to a ReLU neuron that will screw it over?

Confusion matrix. Precision and recall. Accuracy.

## 4. DL❤️Neuro success story: convolutional networks

Videos and readings:

* A short intro reading with nice animated gifs: https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
* Lecture from Brandon Rohrer (I watched it at 1.5x, or even 2x for some parts, but paused sometimes. He really starts from the basics, but I'm sure it will be quite helpful for us to get a bit of review of how deep learning works in general): https://www.youtube.com/watch?v=JB8T_zN7ZC0

* Some slightly more involved reading: https://cs231n.github.io/convolutional-networks/

## 5. Convolutional networks vs biological vision

Main paper:

* Yamins, D. L., & DiCarlo, J. J. (2016). Using goal-driven deep learning models to understand sensory cortex. Nature neuroscience, 19(3), 356-365. http://brainmind.umin.jp/PDF/wt17/Yamins3.pdf

Two more papers to quickly look though (abstract, figures, maybe a quick glance through the text):

* Zhang, R., Isola, P., Efros, A. A., Shechtman, E., & Wang, O. (2018). The unreasonable effectiveness of deep features as a perceptual metric. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 586-595). https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.pdf 1k+ citations in 2 years!
* Bashivan, P., Kar, K., & DiCarlo, J. J. (2019). Neural population control via deep image synthesis. Science, 364(6439). https://www.gwern.net/docs/ai/2019-bashivan.pdf

Decided against:

* Khaligh-Razavi, S. M., & Kriegeskorte, N. (2014). Deep supervised, but not unsupervised, models may explain IT cortical representation. PLoS computational biology, 10(11), e1003915. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4222664/

* Pospisil, D. A., Pasupathy, A., & Bair, W. (2018). 'Artiphysiology' reveals V4-like shape tuning in a deep network trained for image classification. Elife, 7, e38242. https://elifesciences.org/articles/38242 - They seem to claim that CNN deep layer neurons selectivity is actually similar to primate V4.
* Yamins, D. L. K. et al. Performance-optimized hierarchical models predict neural responses in higher visual cortex. Proceedings of the National Academy of Sciences 111, 8619–8624 (2014). http://www.pnas.org/content/111/23/8619.full.pdf.

### Class plan

Start with a reminder that it's a low-stakes 2-credits event outside of our comfort zone, so the expectations should be set accordingly :)

## 6. What brains can do that DL struggles with

Zador, A. M. (2019). A critique of pure learning and what artificial neural networks can learn from animal brains. Nature communications, 10(1), 1-7. https://www.nature.com/articles/s41467-019-11786-6

Sinz, F. H., Pitkow, X., Reimer, J., Bethge, M., & Tolias, A. S. (2019). Engineering a less artificial intelligence. Neuron, 103(6), 967-979. http://xaqlab.com/wp-content/uploads/2019/09/LessArtificialIntelligence.pdf

### Class plan

Should we talk about data augmentation?

## 7. What DL can do that Neuro struggles with

Main question: Is there "Deep learning" in the brain? In the sense of "Backpropagation-driven modern deep learning"?

A review to read:

* Lillicrap, T. P., Santoro, A., Marris, L., Akerman, C. J., & Hinton, G. (2020). Backpropagation and the brain. Nature Reviews Neuroscience, 21(6), 335-346. https://brainscan.uwo.ca/research/cores/computational_core/uploads/11May2020-Lillicrap_NatNeuroRev_2020.pdf

An experimental paper on this topic. Get the gist of it: read the abstract, understand the figures, the key method they used, the take-home message, and the applications for the topic of this class (Brains vs Deep Learning).

* Gillon, C.J., Pina, J.E., Lecoq, J.A., Ahmed, R., Billeh, Y., Caldejon, S., Groblewski, P., Henley, T.M., Lee, E., Luviano, J. and Mace, K., 2021. Learning from unexpected events in the neocortical microcircuit. bioRxiv.
  https://www.biorxiv.org/content/10.1101/2021.01.15.426915v1 
  Tweetstorm: https://twitter.com/colleenjgillon/status/1351557910439059457 (it's like an abstract, but for normal humans, and with an occasional meme every now and then :)

Also, give this online discussion a look (especially the 1st answer, summarizing the problems that backprop would face in the brain), but of course don't feel obliged to read any of the studies they cited:

* https://psychology.stackexchange.com/questions/16269/is-back-prop-biologically-plausible

### Class plan

Update on logistics:

* Last topics
* A vote on "Single neurons" vs "self-supervised learning"

Topics we may consider:

* feedback aligned
* signed info in the brain (and the exception that Cerebellum is), and how it is "seemingly one-layer", but not really
* hierarchical inference in the brain
  * deep belief networks - maybe mention?
* Boltzmann machine (not necessary, but may try to discuss)
* Difference target propagation - how it works?

## 8. Attempts of synthesis: DL as a model for Neuro

As both papers for this week are reviews, and as much of what is written in these reviews is a repetition of ideas and concerns that we were talking for about a month now, please, try to distill from these papers everything that is new. All ideas that we haven't discussed before, and need to discuss now. Also, put a bit more attention to technical details; maybe even try to look into 1-2 key results that these papers describe. Hunt for new facts and ideas, and for your attitude towards these facts and ideas! :)

For sure:

* Richards, B. A., Lillicrap, T. P., Beaudoin, P., Bengio, Y., Bogacz, R., Christensen, A., ... & Gillon, C. J. (2019). A deep learning framework for neuroscience. Nature neuroscience, 22(11), 1761-1770. - a 8-page review about how bottom-up DL modeling can help to reverse-engineer the brain. Perspective.
  https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7115933/

* 🟢 Deep Neural Networks as Scientific Models (2020). Radoslaw M. Cichy, Daniel Kaiser. Trends in Cognitive Sciences.
  https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(19)30034-8
  Seem to suggest that for some types of tasks data it may be easier to model a process with a DL and interpret a DL, instead of directly interpreting the data?

Related:

* "**What is a model?**" video lecture, by Gunnar Blohm (27 min), from a course on computational neuroscience: https://www.youtube.com/watch?v=KxldhMR5PxA . This lecture comes from a cool open project called "Neuromatch academy": http://www.neuromatchacademy.org/syllabus/  - you may want to give it a look, or at least remember the name, as that's one of the best ways to learn more computational neuroscience on your own terms, when you have time.

Two more papers that I considered, but demoted to "of possible interest"; also they are a bit older:

* 🟢 Marblestone, A. H., Wayne, G., & Kording, K. P. (2016). Toward an integration of deep learning and neuroscience. Frontiers in computational neuroscience, 10, 94. https://www.frontiersin.org/articles/10.3389/fncom.2016.00094/full

* 🟢 Hassabis, D., Kumaran, D., Summerfield, C., & Botvinick, M. (2017). Neuroscience-inspired artificial intelligence. Neuron, 95(2), 245-258. https://www.sciencedirect.com/science/article/pii/S0896627317305093

### Class plans

On laws of Neuro (on having )

On trivializing the idea of "ANNs are complex"; that the question is not whether they are useful, or whether they are complex, or whether (or how) they explain anything.

* Another paper I should have assigned, maybe: Lillicrap, T. P., & Kording, K. P. (2019). What does it mean to understand a neural network?. arXiv preprint arXiv:1907.06374. https://arxiv.org/abs/1907.06374

* We can have a discussion about it? What does it mean to "understand" something?
* Name one thing you understand? (make it narrow and practical, without going all philosophical just yet :)
* Do you understand the relative position of Bard and Kingston? What about why and how a knife can cut bread? What about riding a bicycle?

When talking about "ready-made-s" (kinda like oldschool large-scale kitbashing) in art, and how the use of ANN models is a bit like that, describe the idea of "Hardware Lottery". https://hardwarelottery.github.io/

We are about a year (maybe half a year) behind! On transformers that work better than convnets, but apparently resemble the brain LESS than convnets, despite using metaphors like "attention" (that are obviously also cognitive since-inspired): https://twitter.com/pfau/status/1377655611765186562

## 09. Single neurons as deep networks

* 🟢 Jones, I. S., & Kording, K. P. (2020). Can Single Neurons Solve MNIST? The Computational Power of Biological Dendritic Trees. arXiv preprint arXiv:2009.01269. https://arxiv.org/abs/2009.01269

* 🟢 David, Beniaguev, Segev Idan, and London Michael. "Single Cortical Neurons as Deep Artificial Neural Networks." bioRxiv (2019): 613141. https://www.biorxiv.org/content/10.1101/613141v1.full.pdf
* Also, if you have few more minutes for your general education:
  * Can a single neuron solve XOR? (Discussion on twitter) https://twitter.com/KordingLab/status/1121405248315318272
  * Why this is important: because the first ANN (perceptron from late 1950s) famously could not solve XOR: https://en.wikipedia.org/wiki/Perceptrons_(book)#The_XOR_affair

## 10. Neuromorphic engineering

Review: 

* 🔥 Zenke … Goodman. Visualizing a joint future of neuroscience and neuromorphic engineering. 2020. https://igi-web.tugraz.at/PDF/258.pdf
* ANOTHER PAPER WILL BE HERE

## 11. Intrepretability in DL and Neuro

Some stuff on core ML interpretability #todo

Distill simulations on interpretability:

* https://distill.pub/2017/feature-visualization/
* https://distill.pub/2018/building-blocks/
* https://distill.pub/2020/circuits/curve-detectors/
* https://distill.pub/2021/multimodal-neurons/

Maybe in ethics intro as well, if there's a short one? tbc.

Other options:

* 🟢 Lillicrap, T. P., & Kording, K. P. (2019). What does it mean to understand a neural network?. arXiv preprint arXiv:1907.06374.
  https://arxiv.org/abs/1907.06374 - an opinion piece, half-practical guidance, half philosophy
* 🟢 Cammarata, et al., "Thread: Circuits", Distill, 2020. https://distill.pub/2020/circuits/
  A series of short papers trying to understand and describe how a DLL vision model works, by looking at its tuning, neuron by neuron. (Would it make a good paper for a neuro class?)

## 12. Large language models

Some popular links (supposedly, in-depth, but not technical), yet unsorted:

* https://machinelearningmastery.com/statistical-language-modeling-and-neural-language-models/
* https://paperswithcode.com/task/language-modelling
* https://www.topbots.com/leading-nlp-language-models-2020/
* https://web.stanford.edu/~jurafsky/slp3/
* https://raohacker.com/why-the-new-ai-nlp-language-model-gpt-3-is-a-big-deal/
* https://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/
* https://jalammar.github.io/illustrated-bert/
* https://cacm.acm.org/magazines/2020/6/245162-contextual-word-representations/fulltext

## 13. Ethics in AI

We may for example have 1 review, and then several micro-topics

* language models (from the previous class)
* routine data science (finances, insurance, predictive policing)
* AI in social networks, political effects
* Medical AI
* Self-driving cars (computer vision)

Some extra materials:

* A video of Tesla driving: https://www.youtube.com/watch?v=antLneVlxcs , and a commentary (not sure if good, haven't read it yet, but saving just in case): https://www.roadandtrack.com/news/a35878363/teslas-full-self-driving-beta-is-just-laughably-bad-and-potentially-dangerous/
* Automatic translation from Hungarian to English: https://twitter.com/DoraVargha/status/1373211762108076034

# Topics that were considered, but didn't make it

## Self-supervised learning

https://ai.facebook.com/blog/self-supervised-learning-the-dark-matter-of-intelligence

Ha, D., & Schmidhuber, J. (2018). World models. arXiv preprint arXiv:1803.10122.
https://arxiv.org/abs/1803.10122 

## Representation and autoencoders

A lecture on representation from Neuromatch academy: https://www.youtube.com/watch?v=VwSnDJZekQ4

## Curriculum learning and dataset optimization

Some basic info on curricula?

🟢  An ecologically motivated image dataset for deep learning yields better models of human vision https://www.pnas.org/content/118/8/e2011417118
Twitprint: https://twitter.com/TimKietzmann/status/1362056712711254017

## Vision and convnets revisited

Check these: 🟢

* 🔥 Geiger, F., Schrimpf, M., Marques, T., & DiCarlo, J. (2020). Wiring Up Vision: Minimizing Supervised Synaptic Updates Needed to Produce a Primate Ventral Stream. bioRxiv.
  https://www.biorxiv.org/content/10.1101/2020.06.08.140111v1

* 🟢 Yaoda Xu, Maryam Vaziri-Pashkam (2020) Limited correspondence in visual representation between the human brain and convolutional neural networks
  https://www.biorxiv.org/content/10.1101/2020.03.12.989376v1.full
  Essentially, some critique of deepneuro!
* 🟢 Alan L. Yuille & Chenxi Liu, "Limitations of Deep Learning for Vision, and How We Might Fix Them", The Gradient, 2019. https://thegradient.pub/the-limitations-of-visual-deep-learning-and-how-we-might-fix-them/ Describes limitations of modern computer vision, but points at something like symbolic reasoning as a potential answer, so may actually be a different topic entirely.
* 🟢 Nayebi, A., Sagastuy-Brena, J., Bear, D. M., Kar, K., Kubilius, J., Ganguli, S., ... & Yamins, D. L. (2021). Goal-Driven Recurrent Neural Network Models of the Ventral Visual Stream. bioRxiv. https://www.biorxiv.org/content/biorxiv/early/2021/02/18/2021.02.17.431717.full.pdf

However, also some positive spins:

* 🟢 Pospisil, D. A., Pasupathy, A., & Bair, W. (2018). 'Artiphysiology'reveals V4-like shape tuning in a deep network trained for image classification. Elife, 7, e38242. https://elifesciences.org/articles/38242 - They seem to claim that CNN deep layer neurons selectivity is actually similar to primate V4... Only 30 citations tho...

# Other Cool papers

Guerguiev, J., Lillicrap, T. P., & Richards, B. A. (2017). Towards deep learning with segregated dendrites. ELife, 6, e22901. https://elifesciences.org/articles/22901.pdf

Perez-Nieves, N., Leung, V. C., Dragotti, P. L., & Goodman, D. F. (2020). Neural heterogeneity promotes robust learning. bioRxiv.
https://www.biorxiv.org/content/10.1101/2020.12.18.423468v1

Hasson, U., Nastase, S. A., & Goldstein, A. (2020). Direct Fit to Nature: An Evolutionary Perspective on Biological and Artificial Neural Networks. Neuron, 105(3), 416-434.
https://www.cell.com/neuron/pdf/S0896-6273(19)31044-X.pdf
An opinion (perspective) on how we could, and should, use deep models to understand psychology and neuroscience, as they are not that different than the results of evolution, after all.

Raman, D. V., Rotondo, A. P., & O’Leary, T. (2019). Fundamental bounds on learning performance in neural circuits. Proceedings of the National Academy of Sciences, 116(21), 10537-10546.
https://www.pnas.org/content/116/21/10537.short

💎 Hassan, B. A., & Hiesinger, P. R. (2015). Beyond molecular codes: simple rules to wire complex brains. Cell, 163(2), 285-291.
https://www.cell.com/cell/fulltext/S0092-8674(15)01193-9
Developmental biology bordering fractals and graphs (maybe? not sure, but judging from the pics) - a nice review-like paper (perspective); vet

Richards, B. A., Xia, F., Santoro, A., Husse, J., Woodin, M. A., Josselyn, S. A., & Frankland, P. W. (2014). Patterns across multiple memories are identified over time. Nature neuroscience, 17(7), 981.
https://www.nature.com/articles/nn.3736

Lillicrap, T. P., & Scott, S. H. (2013). Preference distributions of primary motor cortex neurons reflect control solutions optimized for limb biomechanics. Neuron, 77(1), 168-179.
https://www.sciencedirect.com/science/article/pii/S0896627312009920

Deep neuroethology of a virtual rodent
Josh Merel, Diego Aldarondo, Jesse Marshall, Yuval Tassa, Greg Wayne, Bence Ölveczky
https://arxiv.org/abs/1911.09451
Apparently create a virtual 3D rodent (like, with muscles, joints and what not), make it move in virtual environment, learn to move, then study its network using neuro methods.

Yujin Tang, Duong Nguyen, David Ha (2020). Neuroevolution of Self-Interpretable Agents
https://attentionagent.github.io/
https://arxiv.org/abs/2003.08165
Limiting attention of agents helps them to learn to play (bottlenecking of sorts?). Google Brain + Mind.

Introducing Dreamer: Scalable Reinforcement Learning Using World Models (2020)
https://ai.googleblog.com/2020/03/introducing-dreamer-scalable.html

Li, Z., Brendel, W., Walker, E., Cobos, E., Muhammad, T., Reimer, J., ... & Tolias, A. (2019). Learning from brains how to regularize machines. In Advances in Neural Information Processing Systems (pp. 9525-9535).
https://arxiv.org/abs/1911.05072

Merel, J., Botvinick, M., & Wayne, G. (2019). Hierarchical motor control in mammals and machines. Nature Communications, 10(1), 1-12. https://www.nature.com/articles/s41467-019-13239-6
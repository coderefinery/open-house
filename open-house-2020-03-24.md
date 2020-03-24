# CodeRefinery Open House, March 24, 2020

# Video link

online visio at 9:00 CET

- We got locked out of this one: https://kth-se.zoom.us/j/152239500
- We are currently in UiO Zoom room: 551 282 8252

## Agenda:

Follow what we do today at https://hackmd.io/@doFoQYKqR623RI-YyXvmew/HJGgb_9VL

- Introduction round
- Look at the material and notes
    - https://github.com/coderefinery/instructor-training/
    - Discussion notes from the Stockholm November workshop found below
- Agree on how we will work
    - General discussion, definition of work packages
    - Split into groups and assign work packages


## Tasks

- Online training
    - how to teach instructor training online (12 CET)
    - work on the [manual](https://github.com/coderefinery/manuals/blob/master/online-training.md)
- Radovan: Git collaborative lesson (+ Anne)
- Björn: merge vs rebase article for newsletter
- Stefan - github actions to documents e.g. spellchecker

- 12 CET, 13 EET scroll-through of instructr training material and identify things we need to change (Richard, Anne, Radovan; of course everybody welcome)


## Git collaborative lesson ideas

Problem with current lesson:
- One gets the impression that centralized workflow would be wrong
- Too much emphasis on git pull merge commits and rejected pushes
- Instead of starting with what can go wrong we start and focus on how to share

What are the small improvements we hope people make?
- Teach how to share efficiently

Changes:
- We start with a Git intro (two parts: local and remote part)
- Remote part explains clone, push, pull (fetch)
- Later we also explain fork, import, and generate (we can list them in overview in the remote part but later return to them)
- In the centralized we start with branches right away and show how to update master and at the end explain why and what would happen if we did it differently
- Also list situations when import, generate, fork can be useful in a research group
- Graphics have been generated with https://github.com/bast/gitink


## Notes about instructor training

- Preparation: update "practicals"
- Intro: Record a couple of "CodeRefinery training philosophies" - it's not a must but would be nice to provide. In break-out rooms (or in groups when physically in the same room) as exercise and ice-breaker discuss with others your training philosophies.
- Teaching style: exercises in breakout rooms and take notes in a shared document.
- Teaching style: make more clear which exercises are "must" and which are optional, also if participants had Carpentries training recently.
- Teaching style: indicate how long exercises take.
- Lightning overview: convert to short videos. Watching can be homework.
- React to feedback from last time: we never showed *how* to teach, this can also be short videos.
- Operations: setting up a workshop webpage can be an exercise.
- Operations: discussion (pre-survey questions) happens in a breakout room.
- Discussion on how to prepare workshop, notes in shared document: this is also a way for us to learn new tricks.
- Lesson development: exercise on backwards design. Also separate technical aspects from design. Also move exercises up.
- Combine and condense "partnerships" and "future" into one episode called "community" which starts with a group discussion and lists few pointers.
- Digging into the lessons: each participant presents 5-min to others in the breakout room. No recording, just watch and give feedback.
- Teaching: "Bad and good live coding examples" is repeated.
- Teaching: not everything is live coding.
- Teaching: focus on teaching skills, live coding (concept map seems misplaced here)
- Teaching: consider moving some of the many exercises to other episodes. Now there is too much choice.



## Notes taken during the Stockholm workshop Nov 4-5


### Feedback rubric

This table can be copy-pasted to exercises below where feedback should be given.

|          | Content  | Presentation |
| ------------ | -------- | -------- |
| **Positive** | Text     | Text     |
| **Negative** | Text     | Text     |


## [CodeRefinery project and teaching style](https://coderefinery.github.io/instructor_training/01-intro/)

* How do we deal with learners of different levels?  This is a problem when teaching higher-level people - we have a broader range of initial knowledge
  * Emphasize prerequisites
  * Ask to contribute in discussions, but do keep it grounded.
  * Recruit as ad-hoc helpers
  * Divide people who are very behind into a dedicated group with a dedicated helper
      * Does this isolate people or empower them? Could go either way, and depends on their background.
      * This works when they are only a bit behind and can catch up quickly. It should be faster than the normal lesson, which is possible with one-to-one teaching.
  * Start with a chapter or two that brings everone on the same page. You can include/take it out as needed or teach them in different paces.
  * Include excercises in many levels. Some will be done by novices, and more for experienced studetns.
  * Related, make sure that there are some simple, useful (conceptual) lessons which novices can understand also.
  * Getting started with installation / environment could be solved with [JupyterHub like Berkeley did](https://data.berkeley.edu/news/jupyterhub-journey-starting-small-and-scaling). It solves having to support multiple OSes and related complications. But there could be downsides to the notebook interface of JupyterHub / Lab (remember it also provides a text editor+console+terminal):
      * jupyter notebook is great as sandbox and for playful learning
      * notebook does not have a determinable state though, which can confuse learners.
      * but also, one of our goals is to "leave learners' computers with useful tools installed"

## [Teaching approach](https://coderefinery.github.io/instructor-training/02-teachingstyle/)

* Importance of formative assessments
* Comment: An instructor needs to be clear on the objectives of the lesson. This makes feedback more goal oriented.
* Research shows that ratings of courses doesn't really correlates with how much you learn - instead, things like humor.
* "It's important to try not to make jokes if you aren't funny."  Also many jokes are at the expense of someone.


### Exercise: Give Feedback on Bad Teaching
|              | Content                        | Presentation                                    |
| ------------ | ------------------------------ | ----------------------------------------------- |
| **Positive** | recap                          | admitted mistakes                               |
| **Negative** | quick escalation of complexity | did not use his mistakes as learning experience |



#### content:
\+ recapitulated where he left off
\+ added material step by step (big steps)
\+ added simple example to show functions
\+ clear knowedge of the topic
\- quick escalation in complexity
\- jumping back and forth without assessing the knowledge (no feedback)
\- undefined jargon word with unknown notions (unecessary)
\- did not have a structure (type along without learning objective)
#### presentation:
\+ admitted making mistakes
\+ used visual aid (live-coding)
\+ clear and loud voice
\+ enthousastic and fun
\- did not use his mistakes as learning opportunity
\- need to focus on the class
\- text was too small
\- not welcoming at the beginning




* Comment: The title should be different from the current one, as it may have given a bias that the participants would be focusing more on negative parts.
* Question-1: How many is the recommended size of a CodeRefinery lesson?
* Answer-1: Depending on the size of the facilities, like rooms and the number of helpers, level of the participants etc. Carpentries recommend that 1 helper per 10 participants.

* We need to detect where people have misconceptions, since we have competent practitioners who already have a mental model.
* We have a question about references: we direct to [Teaching Tech Together](https://teachtogether.tech/), but we should add more referecnes.
* Question-2: Is there any concept map already for CodeRefinery lessons?
* Answer-2: Not yet. It will be great if we could make them in the group works tomorrow.
* Question-3: I am struggling with understanding what fundamental beliefs are.
* Answer-3: It is quite much individual and personal beliefs, like testing takes too much time etc.
* At least once someone has signed up for CodeRefinery without understanding what we mean by "code" - they thought it was about barcoding
* We have people who can code, but think they are novices, and this results in the wide range of skill levels.  In other contexts, e.g. learning real-world languages, you'd have a placement test at the beginning.
    * The [Dunning–Kruger effect](https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect) says that the more you know, the less you think you know.  This relates to the broad range of skill level. See also the [four stages of competence](https://en.wikipedia.org/wiki/Four_stages_of_competence).
    * Some workshop had a practice prerequisite, "you should be able to roughly do this in five minutes, if not this workshop is too advanced for you"
    * Survey to direct you to carpentry or refinery
        * self-assessment test, <50% score: got to carpentry, 50% up to 80% come to Code Refinery, >80%: become a trainer
    * How much is shell really needed? The test should be language- and subject- agnostic.
    * CodeRefinery should consider if it should say "no" to people more often, if they are underqualified.




## Lightning overview of lessons

* It was presented successfully
* Look below in this pad, sign up for the lesson you are most interested in.
* Approx 50/50 split between overviews that presented learning objectives and those that did not.



## Running workshops

* We could imagine a CESSDA workshop where part of the programm is filled by Code Refinery Sessions/Lessons mixed together with our own lessons. That does not make it a Code Refinery Workshop but still important impact of Code Refinery.
* Material that doesn't fit a particular lesson could just be collected in a "random small blocks" lesson
* You may want to consider if your audience will have IT-managed computers, and not have rights to install software.  Must be investigated.
* Updated windows can use WSL to do everything
* Mac is removing Python by default
*


## Contributing to lesson development
* Perhaps add couple images to depict the process (or to break long streches of text). *-Juho*
* ['Lesson guides'](https://github.com/coderefinery/manuals/blob/master/lesson-review.md): the Maintainer's guide goes through the backwards lesson design.

* Comment and question: If the participants are more competent, sometimes they would appreciate more complicated and "dirty" exercfises rather than clearcut simple exercises. What would be solutions there?
* Comments and answers: Preparing multiple exercises with different required levels and in different levels will be a nice option.


## Institutional partnerships and sustainability






## Day 2 food for thought

* CodeRefinery isn't alone: it's part of a **galaxy of lessons**.  How is that galaxy organized?
    * Core vs periphery lessons
    * Keep [carpentries incubator](https://carpentries.org/community-lessons/) in mind
* How do we **make lessons modular**, without falling into the framework trap (too general and not too good for anything)?
* CodeRefinery **sustainability**
    * In two years, there won't be direct funding for CodeRefinery staff.  How do we **motivate volunteers** to teach and funding for events?
    * How can we measure the value of these lessons?
    * Who are our partners?
    * What is missing that would motivate you to integrate a lesson into a similar course you are involved in? (and continue maintaining it)


## [Teaching CodeRefinery Lessons](https://coderefinery.github.io/instructor-training/08-teaching/)

http://bit.ly/coderefinery-instructor-training

### Part 1

#### [Git intro](https://coderefinery.github.io/git-intro/)

Room: Library room 5th floor (other side, near bathrooms)


**Starting repo for live coding exercise:**
`git clone https://github.com/coderefinery/recipe.git

#### [Modular code development](https://cicero.xyz/v3/remark/0.14.0/github.com/coderefinery/modular-code-development/master/talk.md)

Ideas:
- use pseudo code
- use an example (e.g. car construction) and discuss/exercise based on that
- how do we teach/convey the experience of side effects?
- example could show a quick fix which hurts later
- guacamole joint who wants to offer modular menu and starts with one chef but later becomes successful and hires 4-16 chefs
- how can we motivate? all restaurants start as a dinner for two
- chop onions library
- what can be split into libraries that can be reused?
- for competent participants we could discuss APIs, API stability, semantic versioning
- modular code development vs. "job security"
- restaurant could hire somebody to "refactor" the salad recipe but the person would be able to do it without understanding all processes in that restaurant
- some of current learning outcomes are a bit too low on the Bloom's taxonomy - try to elevate some of them to analyze level
- ask participants whether they have examples on how these concepts and advice relates to their work
- for others in this instructor training: we could collect good entry level small examples (such as celsius to fahrenheit) from other disciplines
- at some point we may be able to provide workshops tuned to a specific discipline which will make it easier to come up with exercises and examples
- statistics examples (data cleaning) could be useful for many disciplines
- example: change datecode from "epoch" since some moment to ISO. the start time is often a global variable which affects "everything".
- experience of global variables needs perhaps to be experienced (exercise?) rather than taught
- how much time should this session take? 3 hours (half day) to give groups enough time to work on it

Current learning outcomes: https://github.com/coderefinery/modular-code-development/blob/master/guide.md#intended-learning-outcomes


#### [Reproducible research](https://coderefinery.github.io/reproducible-research/)

Other relevant material:
https://the-turing-way.netlify.com/introduction/introduction

Instructor guide:

Learning objectives:

Important to make the lesson more modular
Should not be language dependent.

Connection between exercices and learning outcomes should be more obvjous.

For example:
exercise-1:
How do you collaborate on writing academic papers? (seems off-topic, could be solved by explaining the connection more) - link here https://coderefinery.github.io/reproducible-research/02-organizing-projects/#how-do-you-collaborate-on-writing-academic-papers
Propose to reformulate question and hone dotted list

Fix: Change exercise

- Recording your data version (and others' data that you use)

Notion to introduce: Persistent identifier.

- Sharing code and data
Review and maybe move it to the end.

Exercise 2:
- seems to not fit the lesson: change / rewrite?
- https://coderefinery.github.io/reproducible-research/02-organizing-projects/#word-count---an-example-project

Link to concept map (based on sketch made in discussion group): https://github.com/arockenberger/reproducible-research-conceptmap
fork / download and edit!


Learning outcomes:
The learning outcomes should focus on reproducible research and not the tools.

- Explain what is reproducible
     - data, software and hardware
     - motivate reproducibility for the researchers
- persistent identifier
- Metadata and data provenance

conda channel.

modularity: need to have knowledge of git
Have a page:
- write a document to motivate the need of git
for reproducible. And git is part of it. Git is
a tool to solve this problem.

More emphasis on the benefit to the researcher
Types of reproducibility:

**Related reources:**
- https://www.fosteropenscience.eu/resources


### Part 2

#### [Documentation](https://coderefinery.github.io/documentation/)

Comments (to be merged to the notes at the bottom):
* The title should be "code documentation", inside and beside the code, then it can give a reference to other relevant parts, like version control.
* Prerequisites is technical requirements to follow the lesson. Rather it is, skill and exprience-wise, important that participants have some ideas and experiences of version control.
* Having basic understanding of Git is used as a connection to other module: need to separate clearly what a tool is and what the learning outcome is.
* Motivation: What if documentation is not together with the source code and not version controlled?
* Regarding a learning outcome "Know what makes a good documentation", it should give concrete ideain terms of contents, i.e., including examples, tutorials on how to use.
* Documentation checklist (02-requirements) should include process flow (which stage this version of the code is in terms of the project).
* In the motivation, it should give a structure of the "documentation" is about, when it comes to documentation design. Project documentation, design documentation, code documentation, installation documentation and usage documentation.
* Depending on the phase, a useful tool could be different.
* Installation guide, maintenance guide, user guide, contribution guide -diffirent users may go to different sections. Would be better to section the documentation depending on potential users?
* Specify the target users of the documentations in the objective of this workshop.

#### [Jupyter](https://coderefinery.github.io/jupyter/)


###### Content
- Motivation
- Jupyter (Julia, Python, R)
- Very many Programming kernels
- Show examples which are avaible like the LIGO experiment
- Keyboard shortcuts.
- Discussion on Integrated Development Environments (Previously we had a lesson [Pycharm IDE](https://www.jetbrains.com/pycharm/))
    - Participants give some thought to how they work
    - JupyterLab approaching a IDE
- Second lesson participants use the notebook (type a long)
- Version control with Notebook (Git extensions installed)
- table of contents extension
- Monte Carlo simulation, to illustrate literate programming
- consider using another example for episode 2, something less mathematical etc, to cater to humanities etc
- Round off with mentioning possible pitfalls
- emphasize that multiple languages supported, add this to ILOs
- need to show how different kernels can be used with mybinder
- show how different environments (different kernels) can be used with jupyter - suitable for advanced learners
- Exercises

###### Missing
- How it  is teached it is a static lesson. How is the interactive part?
- When to the Notebook format become a hurdle?
- Mention other kernels
- Possibly mention other notebook systems (Rmarkdown)
###### Participants
We want to cater for people unexperienced with Jupyter and for people who have use Jupyter Notebooks. More CodeRefinery participants have experience with Notebooks now than previously.

###### [Mybinder](https://mybinder.org/)
How stable is mybinder.org? Some instability have been seen.

###### Extensions
- Jupyterhub

###### New exercises/lessons
- How to create new environments, like a Pytorch Machine Learning environment
  - this connects to reproducibility lesson
- Visualization? Plugins for connectiong pandas and interact. Immediately visulize data (nteract) without writing matplotlib code. Nice features for viz. Indirectly catering to R by talking about Python dataframes
-
#### [Social coding](https://cicero.xyz/v3/remark/0.14.0/github.com/coderefinery/social-coding/master/talk.md)


Notes:
- CC0 is problematic in most European countries, not allowed to waive copyright and turns code/database because in conflict with copyright
- share with future self
- good source for choosing a license is https://choosealicense.com/ - good take away for participants
- Creative commons provides a course with a certificate, might be interesting to take (but costs money) - here is a link: https://certificates.creativecommons.org/
- Are we allowed to license our own software or do we need to ask the university?
- What happens with patents in Nordic countries?
- Would be good to set up a working group who examines what is allowed and not allowed in countries (create a matrix for Nordic countries as quick reference) @arockenberger is interested in a work group like that
- Commercialization aspects (e.g. LGPL 2 vs 3)
- Provide a list of questions that participants can ask the university?
- Question to participants: How do you see your code to evolve and being reused as the project progresses? How can you organize a community around it? Who to review PRs, ...
- Motivation for master students: make the project displayable on your CV
- The motivation for the different learner personas should be made more clear, also to readers of the material who are not in the room
- This lesson needs a maintainer, otherwise we risk misinforming people
- Our goal is not to give legal advice (emphasize this in presentation)
- Takeaway from this lesson is to know what kinds of questions to ask at local universities/contacts
- Exercise: look at several projects on github, which of them should you use/copy/depend on? What could happen if you copy code from a repo without a LICENSE? We have an exercise on this but should give this more weight.

Learning objectives: 3 things every participant should know:
- when: when and what are you allowed to copy and learn from?
- how: how do you make it easier for others to reuse your work? FLAIR (FAIR plus license; however L is already part of reuse)
- why: how can you get more credit for your work? long term benefits for sharing or making reusable? both for self and others.

For some participants "copying" can sound like plagiarism. We agree "reuse" sounds better.  Make sure it's not too code specific (people reuse things that aren't code!).

Who are we when we talk to participants? Are we private persons? Are we representatives of universities? What are we allowed to say? We might find ourselves in a role conflict in legal aspects.

Example: you find a function that does almost what you want. Maintainers are often super happy to get contributions to make it what you want and this may land you on the authors/contributors list.

Exercise ideas:
- Go to https://choosealicense.com/ and choose a license for an example project (from CodeRefinery project examples) - discuss/in pairs WHY you chose this particular license.  Have a variety of example projects which have different best licenses.


### Part 3

#### [Automated testing](https://coderefinery.github.io/testing/)

Notes:
- is it not easier to motivate testing from the perspective of the entire system rather than starting from unit tests
- we should probably not start with that strong statement, some people don't need testing right away
- tests should **not** be regarded as a separate process
- we should avoid jargon
- how can we motivate to spend time on doing the extra work? often it is not only the programmer but a requirement to have functionality implemented and the functionality counts to the project lead and users - pressure to focus on features rather than quality
- goal is to convince, not necessarily how to do it technically
- where do we want to place ourselves on the Bloom's taxonomy? be able to run a test? be able to analyze the quality of a test?
- just changing terms a little bit, e.g. "reliability" instead of "tests". anchoring to something more relatable and real.
- for motivation connect it to reproducible research and modular code development. e.g. introduce test before refactoring and make sure functionality can be reproduced.
- why travis and not gitlab ci? since we offer gitlab.
- how do I know my test is a good test? teach people how to judge their tests. should I have written this test in the first place?
- tests should not take more time than you gain later.


#### [Git collaborative](https://coderefinery.github.io/git-collaborative/)


#### Instructor training
Options include (+1 if you like):
* Instructor training lesson +40
* Social coding
* Reproducible research  +1 (ES, ...)
* Modular code development
* Jupyter +1
* Git intro
* Documentation


#### Discussion

1. General
- onboarding was good, i.e. instructions to read background papers and review a lesson or two
- should make clear how to proceed after workshop. Can one just teach a lesson without mentioning coderefinery? Can a "graduate" start teaching CR workshops right away?
  - have self-reporting web form linked from all lesson repositories
  - also add instructions in instructor training material
- remember to refer/cite carpentry instructor training material where appropriate
- mechanism for people who have taught CR workshop to be added to list of instructors. Enables others to find other instructors in their location to run workshop with
- what is a recognized CR instructor?
    - have attended instructor training (publish a list of attendees - by consent - after each workshop. Include institution and PI details, such as ORCID)
    - have been helper or instructor in one workshop
- rebalance so that there's more focus on how to teach the lessons, less on how to improve them
- consider to extend workshop to 2 full days

2. What are the learning objectives?
- Be able to present existing CR material (as new teacher one would trust the material (not necessarily critique existing material), contributions come later)
- without previous teaching experience it's hard to improve lessons -> focus more on how to teach how to teach
- focus on building confidence in how to teach -> include live coding exercises and other teaching exercises
- not just about teaching people to teach, but also to teach other people how to teach (for 2nd and 3rd generations!)
- learn how to handle classrooms with participants with different backgrounds and skill levels
- understand fundamentals of teaching theory
- be able to reflect on and design lessons based on Bloom's taxonomy
- know where to find resources and lists about how to organize and deliver a workshop

3. Should this lesson be formalized in the same way as the other CR lessons?
- yes, must be seen to embrace own methodology
- important that the lesson is backwards designed

4. Target audience
- someone who wants to teach CR workshops

Possible learner personas:
- A wants to present existing material.
- B wants to develop their own lessons so that they can spread their special knowledge.
- C wants general background on teaching strategies, so that they can use it in their own work.
- D wants to practice their presentation skills, so that they can teach better
- E wants to join CodeRefinery in maintnance of our material
- F wants to develop certain CodeRefinery lessons (secondary)
- G wants to get credit for their instructor training.

Providing general credits: https://allcontributors.org/


## Future

- Engage with the Research Data Alliance's Working Groups and Interest Groups, also CODATA Research Data Summer Schools. https://www.rd-alliance.org/groups/interest-groups
    - Example of discussions from the last RDA Plenary: https://www.rd-alliance.org/management-computational-notebooks

## Feedback of first day

Content:
\+ good overview over what CodeRefinery is all about
\+ good hints about pedagogy in general
\+ helpful hints about 'best' teaching practice +1
\+ Comprehensive exposure of topics
\- a lot of different things! (i.e. cognitive overload ahead)

* were there too many unanounced conceptual transitions (flow issue)? +1
* could the material be improved by framing it episodic introductions and conclusions? +1

\- Covered too little material up to coffee break, then lots afterwards
\- There is no FAQ section
\- didn't stick to the timing +2


Presentation:
\+ hackmd is a great tool +4
\+ many different instructors which interacted with each other & the audience
\+ Content on website
\+ Friendly and communal environment
\+ (Optional) start with the lunch was quite nice
\+ Engaging the audience in discussion +1
* did they stay on topic?
* were discussions too long?

\+ All the the presenters spoke clearly, easy to follow
\+ Style was encouraging, I feel motivated to teach this content despite having little formal coding background
\+ For the purposes of an instructor workshop, the looser style of today worked well, with more discussion and allowing people to dip into the written references
\- too much text projected on screen -> those where not slides but scrolling through pages, but should have been slides
* bullet point-based slides preferred?
* set clear expectations about what to expect (ie there will be walls of text but you aren't expected to read it.)

\- The rhythm at the end of the day "lost" couple participants occasionally
\- Check technical environment beforehand (sound issues)
\- On-screen text too small -> could have changed resolution instead of just zooming browser
\- Hard to connect the "instructor lessons" to the "tasks" tomorrow.
\- running text instead of key points while presenting +1
\- Hack pad is a little bit confusing
\- Did not specify URL for later reference +1


## Day 2
## Git intro

1. guacamole as the exmaple, is it better to make it more closer to life. May be pseudo-code to make guacamole
2. Avacodos do not grow in Sweden so making Guac is not climate friendly
3. For user excercise, to make more interesting , e.g. kahoot (https://kahoot.it/)
4. include overview diagram of all exercises, pseudo-UML. Some thing the learners see where they are.
5. git bisect, should this be taught. Could this be with the automated testing.
6. GUI- some concepts are better undestood. Use difftol more (Meld ?)  https://git-school.github.io/visualizing-git/.
7. Order of lessosns

### Learning objectives
- add something about different degrees of permanence of different file states

### Concept map
1. Git-intro

![](https://i.imgur.com/jG9HWFU.jpg)



## Entry-level Examples of Modular Code
If you write code, please add to this list small snippets of specialized functions.


## Documentation
### overview

1. Prerequesits are not descriptive - Git may be not a requirements in general. Make it clear the requiremnts for documentaiton and there are *this lesson*
2. Learning goal and tool should not be mixed
3. Motivation (more on concept map) - different instructor do this slightly differently
    #. What hapend if you do not have documentaiton,
    #. what if your documentaiton is not close to the code
    #. Must be relevent
4. Why Sphinx. Python requirment is confusing, that leads to the quetion whether I can use Fortran instead ?
5. Why use an existing repo (word count) ?
6. More about what makes a good documentation, then list tools
7. Who the code is for, a new sctiom
    #. Users
    #. contibutors
    #. Evolution of documentaiton from *how to test* to *how to install*. Different stages of development has different types of documentation (Design , development, deployment, maintenance)
8. There are roles
    #. User - This is how I make do something
    #. Admin -  instlation, requirments
    #. Developer - person who wants to contribute
    #. Main developer
![](https://i.imgur.com/v970fn8.jpg)

## Collaborative distributed version control
### overview
1. Objectives need to be better defined.
2. Clarify what are Git-hub specific terms and git terms
3. Suggesting for objective: Does not contain how to share your own repo.(already in intro to git)
4. Relate to the git-intro part where the learners push to Github
5. Objectives.
    #. Learn how to make changes to a remote repository
    #. Learn how to use the commands .... to make the above changes
    #. Learn how to use remote branches, how to use branches to coordinate and code-collaborate
    #. How to submit a pull request. How to ask in a nice way please include my changes.
    #. Best practices when working with remote repos, e.g pull before start working and pushing

### Improvements
1. Is the example realistic enough




I think the workflow is not actually a solution to the problem encountered. The main reason for using a separate branch is to enable review and to keep the master branch clean during development.


## Suggestions
* Please change the name of **NordicHPC**. It is really hard not to think about hardware with this name.



## Feedback of second day
content:
\+ Slightly more clear now on running workshops
\+ Discussions were facilitated well and many people contributed which generated useful ideas
\+ Practical aspects of running a workshop and resources available seem very useful and well thought out
presentation:
\+ Timing kept well today
\+ Lots of breaks





# Open House where we discuss and prepare for online teaching

Video link: https://kth-se.zoom.us/j/152239500

List of good resources:
- about teaching
    - https://software-carpentry.org/blog/2015/06/remote-workshop-cape-town.html
    - https://carpentries.topicbox.com/groups/discuss/T3373743b7b6f00cd/input-needed-tips-for-teaching-and-learning-online-by-the-carpentries-community
    - https://youtu.be/MzsJyOkxqv8 (it's a 45min webinar about teaching Software Carpentry exclusively online, from an instructor with lots of experience in Australia)
    - [Tips for Teaching Online from The Carpentries Community](https://carpentries.org/blog/2020/03/tips-for-teaching-online/)

- about tools
    - https://zoom.us/webinar
    - https://projects.iq.harvard.edu/files/dcewebconf/files/zoomadvancedtrainingv2.4forsite.pdf
    - https://support.zoom.us/hc/en-us/articles/206476093-Getting-Started-with-Breakout-Rooms
    - https://sciencetogether.github.io/tools/
    - Upload shell history in real time to a google document: https://github.com/Sabryr/Teaching-aids
- events
  - https://hackmd.io/@jduckles/collaborative-meetings-workshop (this afternoon: https://twitter.com/abbycabs/status/1240800467019595776)
  - https://twitter.com/jduckles/status/1237474315580235776
  - https://carpentries.topicbox.com/groups/discuss/T19273d8aadd8d57f/is-covid-19-virus-demanding-alternative-software-carpentry-workshop-delivery-options

Technical issues (and solutions?):
- Participants who are no longer in the same physical room can be on networks with varying quality.

Zoom features you may not have known about:
- Whiteboard
- Remote control
- Host can probably enable feedback features (to signal "slower"/"faster"/...)
- Break-out rooms
- Change of background;could be tried for signaling, pink for "stalled", green for "continue".
- Non-verbal communication function including "raise hand", "thumb up/down",green(go)/red(stop) signals, etc. (attendee opens "attendee" pane and raise hands)

Plan for Linux Shell course:
- CodeRefinery advertises if a few other helpers can show up
- Via Zoom
- Ensure that we have the "raise hand", "go faster", etc options.
- Which commands are actually part of Git Bash?

Prior to any course: send the participants and email with a Zoom tutorial on how to use some features like raise hand,...

Ideas
- Better cross-promotion of each other's online training (this will get out of hand... communications manager?)

Plan for today:
- Preparation for next online Bash course (https://scicomp.aalto.fi/training/scip/shell-scripting.html)
   - Anne
- Identify "chunks" in current lesson material that can be turned into 1-3 hour zoom and twitch sessions
   - Radovan
- Preparation for next Open house (teaching exercices, etc.)
   - Anne (afternoon)
- After 4 pm CET follow/participate in Abby's session (https://twitter.com/abbycabs/status/1240800467019595776)
   - Radovan
   - Thor
- Create guide for online training under https://github.com/coderefinery/manuals
    - Thor
    - draft PR: https://github.com/coderefinery/manuals/pull/47

## How can we turn present CR material into online training

- Git intro is a good starting point but we chop it into 3 sessions (each few days apart?)
  - Single-branch workflow
  - Branching, merging, conflict resolution
  - History inspection
  - Sharing repositories, remotes
  - Collaborative Git
  - Automated testing
  - Making code citable
  - Git branch design
  - Social coding and software licensing
  - Building documentation with Sphinx
  - GitHub pages
  - Sharing Jupyter notebooks
  - Reproducible environments with Docker/Singularity
  - Snakemake
  - Conda
- Twitch-session on particular topics
  - How we do code review
  - Modularization/refactoring of code
  - Implementing an automated test
  - How to clean up messy history
  - How we work with Docker

## Things to prepare and practice for online training

- Roles (suggestion):
    - instructor focuses on delivering the lesson
    - one person should observe the chat and signaling from the participants, give feedback to the instructor, maybe organize breakout rooms
    - helpers start breakout rooms with participants that raise their hands
- Technical challenges:
    - chat window on zoom can be too small so perhaps we need to provide zoom and a parallel chat solution
    - backchannel to instructor: chat, and it can be public. audio feedback could be confusing


## Follow up-steps

- Advertise Aalto shell course through CR? No public advertisement yet but we can give the info to personal contacts. But inform registrants of cancelled software carpentry course.
- Anne will go through the shell lesson and give feedback on what commands work in Git Bash and which don't
- We dedicate next open house (March 24) to a dry-run of online Git-intro lesson
- Should we add the list of resources to the manuals (which Thor started?)


## Experimenting with Zoom features

- We created a breakout room and the host went into one of the breakout rooms but with this lost being host and another meeting participant became the host
- Before the host goes to a breakout room, the host should transfer ownership to somebody otherwise ownership goes to person next in line (?)
- Host ownership can be transferred (can be done in attendee list)
- We should create breakoutroom before the lesson, make sure we have enough. Seems we cannot add more.
- Make host (moderator) separate from speaker
- We need 3 roles: speaker/instructor, helper (helpers are co-hosts), host
- Sharing screen can change keyboard layout (maybe only happens with xmonad)
- As co-host if you are in a breakout room you can join other breakout rooms
- It can be useful if helpers help out with assigning persons to rooms (can be a challenge for instructor to balance this while also running the session)
- It is possible to annotate whiteboards (so one person can draw on top of another person's drawing)
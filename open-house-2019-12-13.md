# Open House

Agenda:

- Introduction round
Present: Thor, Bjørn, Anne, Juho, João

- Training material updates
    - Feedback from recent CodeRefinery workshops
        Modular code development: https://github.com/coderefinery/modular-type-along
        Reproducible Research:
        https://eglerean.github.io/reproducible-research/
        Carpentries lesson on docker:
        https://carpentries-incubator.github.io/docker-introduction/
    - Summarize inputs from the CodeRefinery Instructor Training (last November)
- What would you like to work on today? Need help?
    - New tutorial on data versioning
        - Enrico Glerean
        - Richard Darst
    - CodeRefinery Instructor Training material
    - Jupyter & Reproducible Research lessons
        - binder: should we keep it in this lesson or move it to Reproducible research
    - Discuss CodeRefinery December Newsletter
        - Thor
        - On CR Drive under "news-blogs"
        - Radovan: CR beyond Nordics, after SG meeting
    - Modular code development:
        - Radovan: jekyllify the draft and implement suggestions I got
    - other?
    - Reviewing and testing tutorials is also a great way to contribute
        - Juho: Documentation, Git-Intro
    - RSE conference discussion


# Collaborative work today

- One group on docker and reproducibilty
- One group on the newsletter

### Docker and reproducibility lesson

- should Docker be installed on participants' laptops?
    - windows7 is complicated, windows10 is fine (windows 10 home edition too? *EG: No, it doesn't work on Windows 10 home ed.*)
    - need to be admin on the laptop
    - e.g. in Aalto, students don't have admin rights but they can apply before the meeting
- convincing demo is good (Example to run Rstudio without installing it: https://eglerean.github.io/reproducible-research/05-environments/#examples-of-useful-docker-images)
- learning outcomes
    - wow effect, this is really interesting
    - how to encode own work for the future
    - how to use existing images to reproduce other's work or to use different versions of tools without installing
- CodeRefinery org in Docker Hub would boost the "wow!" effect. Cf. https://hub.docker.com/orgs
- Good point: use smaller images for classroom (Busybox or Alpine, instead of Ubuntu)
- Challenge: a "wow!" demo won't give students practical hands-on learning
- use repo2docker https://github.com/jupyter/repo2docker to demonstrate "how to run another person's computer"
- suggestion: move first conceptional docker episode to before
  dependencies and workflows, and there include the steps to start building
  image. In the last container episode everyone will then have the image
  built locally
- use quay.io instead of dockerhub?
- if participants don't do it themselves, they will never do it on their own


Learning outcomes:
       - freeze environment
       - get someone else software environment
       - reproduce and expand software environment
       Tips: ask to pull an image during  break (or do another exercise in between?)

- Used by João and Juho at CSC to get Admins and Coders to start with Docker: https://github.com/CSCfi/docker-introduction
- there is also this: https://ome.github.io/training-docker/
- Use this picture: https://cscfi.github.io/docker-introduction/01-introduction/index.html
- https://devopswithdocker.com/

Enrico adding some docker materials:
- https://slides.com/anishakeshavan/introduction-to-docker/#/
- https://neurohackweek.github.io/docker-for-scientists/


Team: Thor, Radovan, Joao, Juho
When: 10-15:00 CET

### Newsletter

[draft](https://docs.google.com/document/d/1vMtRTkd6cbZPiRKzBvA7GFRDZwp31TL0nmyvPirKWp8/edit?usp=sharing)

Goal: Thor is responsible but dispatch section/articles to CodeRefinery team.

Team: Thor, Radovan (Nordics section, in the afternoon), Anne
When: 10-11:00, 14:00-15:00 CET

- Nordic RSE conference (open call, etc.); afternoon
- Expanding beyond the Nordics (afternoon)
- Nordic HPC (get feedback from Richard)
- Read and review (all)


### Nordic RSE

Created a new repository
https://github.com/nordic-rse/RSE-conference-manual
where we can keep information on how to organize Nordic-res (for future committees, etc.).

- Oct 14 and 15: conference, location to be found
- Radovan will open nordic-rse-announcements@neic.no
- Prefered communication methods: mailing list above, zulip chat.  Slack channel stays so that people can see it, but it redirects to zulip.
- We welcome applications to join the organization committee
- For program and organization committees we can establish later other mailing lists or channels.
- Anne drafts newsletter, Radovan drafts website changes.


### Modular code

Put feedback from last workshop (jekyll)

Team: Radovan, Anne
When: 11-13 CET

----

## Data versioning (DV)

Goal: create a new lesson (needs clarification: generic data management, specific tools, etc.)

Define learning objectives.

By the end of the day,
Team: Richard, Enrico

When: all day

### Summative assessments
- What are the needs for different types of data: original, code, scratch work, that needed for reproducibility.
- Distinguish a good organization from a bad (several examples, evaluate the benefits)
- Table:  {X, Y, Z}.  Where do you store it for: {sharing, archival}.

### Other resources
- Intro to research data mismanagement (darst): https://docs.google.com/presentation/d/1ao26nP9LQPTHzLJ6hmR3F2luE2uc_XTcquBdM334ifk/edit
- Aalto scicomp data organization guide (darst): https://scicomp.aalto.fi/data/organization.html

### DV.1 existing options
- git-annex https://git-annex.branchable.com/
- git-lfs https://git-lfs.github.com/
- DVC https://dvc.org/

Here at the end a comparison between DVC vs git-annex
https://christophergs.github.io/machine%20learning/2019/05/13/first-impressions-of-dvc/ Apparently git-annex only keeps the most recent version of a large file. This is not ideal maybe in a proper data versioning sense? (git-annex can save old versions, but it can also drop them.  Management of old versions isn't as developed, but checking out old versions is definitely possible).


# Summary

Here we give a short summary of what we have achieved during the day.

### Docker and reproducibility lesson

- 1 PR merged
- 1 PR pending. Some more work done to reduce the container size: https://github.com/CSCfi/word-count/tree/juho/alpine-base-image

### Newsletter

- Thor has made an amazing work on the newsletter.
- Final [draft](https://docs.google.com/document/d/1vMtRTkd6cbZPiRKzBvA7GFRDZwp31TL0nmyvPirKWp8/edit?usp=sharing) is "finalized" (thanks to all)
- Nordic RSE date decided: 14-15 october 2020; however, Richard just mentioned it conflicts with Autumn holidays in Finland.
- Google form for Venue bid https://forms.gle/d1EKXTp6rCTFkmJ99 (feedback welcome)
- (Anne) Will write a manual for organizing RSE conference (https://github.com/nordic-rse/RSE-conference-manual)

### Data Versioning

- Lots of brainstorming
- personas
- Possible summative assessment defined

See notes above.

## Software Team Interviewer Guide

*The purpose of the Software Team Interview is to elicit and record a sketch of how a team produces and supports it software capabilities.  This sketch is used as part of the productivity and sustainability improvement planning (PSIP) process to provide a baseline description for measuring improvement and as the source for team practices that will be the focus of improvement.  After each iteration of the PSIP process, the sketch should be updated to reflect improvements.*

## Guidelines:

### Pre-interview

If the team does not seem to have a common understanding of their software practices, it is worth having the team preview the [PSIP interview prompts](SoftwareTeamInterviewTemplate.md).  Doing so facilitates discussion between team members toward a common understanding of how the team produces software.

If the team already has already has a common understanding of their software practices, you could still brief them on what we hope to accomplish from the interview and PSIP process.

Prior to the interview, assign these roles:
- Host: Sets up meeting logistics, prepares for recording if planned, monitors meeting quality, different than the interviewer.
- Interviewer: Leads discussion by expressing prompts and keeping the conversation focused.  Makes sure topics are fully and efficiently discussed.
- Interviewee: The software team itself.
- Notetakers: Best to have a lead notetaker who catches the stream of discussion as much as possible, with others who follow up filling in details.  The lead notetaker role can rotate among notetakers, switching at major transitions in discussion.

### During the Interview

***_Use team vocabulary:_*** We want to start our interviews using plain language and avoid misunderstood words that may be jargon to the interviewees, or bring up negative connotations. Even words like productivity, lifecycle model, regression testing, and others may be misunderstood, or negatively received by some people.

***_Get details:_*** Ask specific questions, getting into details as much as you have time, and to the extent that the topic is one where improvements could be made.

***_Cover all productivity and sustainability subjects:_*** Even though we want to avoid using vocabulary that is unfamiliar or vaguely understood, we do want information to emerge that addresses formal productivity and sustainability concerns.

As you conduct the interview, assess if you have missed any of these basic discussions:

#### **Team Opportunities and Challenges**

1. Attributes of this team that could be leveraged to improve productivity and sustainability (strong practices, processes, tools; positive attitudes about new approaches).

2. Attributes that could limit or challenge software improvements (skepticism about impact of improvements; dedication to science limits priority of improvements).

#### **Software Development**

1. How software requirements are determined and transformed into implemented code, tested and deployed (the software lifecycle), 

2. How integration of new and revised capabilities into the existing software will preserve existing capabilities (regression testing), 

3. How users will learn about utilizing the code in their scientific efforts (documentation and training).

**Tools**

1. Source management tools and processes (how source code will be developed and managed), 

2. Issue tracking tools and processes (how feature requests and software faults or "bugs" will be recorded and managed), 

3. Regression testing tools and processes (how regression tests will be invoked),

4. Software distribution tools and processes (how will users and collaborators access software products).

#### **Software used but not developed (a.k.a, third-party software):** 

Use of third-party software typically reduces the cost (time and effort) compared to developing the same capability independently.  At the same time, it also increases risk.  If the project makes significant use of scientific software developed by others, the following requirements should be addressed:

 

1. Describe how the third-party software is tested for correct behavior, initially and when upgrading to a new version (verification and validation).

2. Describe how loss of functionality via faults and missing features is handled by the third-party software.  Describe how complete loss of the third-party capability would be addressed by the application (risk mitigation).

**Summarize your project practices: Training**

1. How new software developers will be trained,

2. How the value of the work of departing developers will be retained.

**Summarize your project practices: Improvement strategies**

1. How software productivity and sustainability will be improved over the life of the proposed research project.

2. How improvement efforts will be rewarded.

### Before Ending the Interview

1. Identify candidate practices that the team will focus on improving as part of the PSIP effort.  A list of candidate practices should emerge from the interview discussions, but may need refinement in post-interview discussions.

2. Record potential practices for improvement. Set a follow up meeting for about one week later for finalizing their software practices sketch and selecting practices that will be improved during the first PSIP iteration.

3. Improving a software practice using PSIP requires planning how to complete the improvement. If the software team does not have a process for this kind of planning, it is strongly encouraged that one of the first practices to improve is lightweight formal planning.

4. Assign a shepherd.  This person will be the contact point for the software team, to monitor progress and answer questions.

### After the Interview

1. The shepherd stays in regular contact with the software team.

2. The shepherd and the software team execute a complete PSIP iteration as sketch in the [PSIP Timeline document](PSIP-Timeline.md).


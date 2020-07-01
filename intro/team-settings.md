# Team Settings

* Traditional team
* Agile team
* DevOps team

## Traditional team settings

The term _development_ describes the programmers in the team.

Testers and QA are often dedicated project roles whose activities start afte the programmers have finished their work. Operations contains database, system, network, and other types of administrators who set up and maintain the server and systems.

The Operations group essentialy accompanies and accounts for the "last mile" in the delivery process.

In the worst case, waterfall-like scenario, programmers code the application that is tested by testers afterward. QA performs down-streamed quality assurance afterward. The walls in the form of organizational or process borders between different groups prevent close collaboration.

### Attributes

* Hero cult
* Emphasis on titles
* Shadow responsibilities
* Favor a plan over planning

#### Hero cult

> Team is nothing, individuals are kings.

Consider a programmer who fails to document his work adequately and delivers low-quality software that requires adjustments and bug fixes that can only be formed by the hero creator because he did not document or share his knowledge, decisions, and project experience with the team.

#### Emphasis on titles

Everyone in the team plays a role. One person is an "only a developer" and other a senior developer. Often, the primary factor behind a promotion is the duration of the person's membership in the company and not its technical or soft skills.

#### Shadow responsabilities

People persue other activities that are not part of their responsibilities simply to protect their turf and ensure their influence or to indluge their pet projects.

#### Favor a plan over planning

Everything is planned, but the activity of planning is seldom performed. Planning, for example adjusting the original plan, is a rare activity.

### Cultural Barriers

* Separated teams
* No common languages
* Fear

#### Separated teams

Separated or loosely coupled working groups. Unfortunally a collection of great teams is not a replacement for one team that pursues a unified and shared project goal.

#### No common language

Specialized teams and project roles prefer to use the language that is most comfortable for them, instead of a shared language that the whole project understands or even better, one that is also understood by the user and stakeholders. As result, misunderstandings occur.

#### Fear

What others do is bad, and any activities by other people that could impact one's own type of work are confronted with skepticism. Perciving shared goals and knowledge as risky will lead to fear on all sides, especially fear of losing power, influence, and reputation.

## Agile team settings

Agile movement addressed the pains of suboptimal collaboration and divergent goals.

The __one team__ approach fosters communication and collaboration by bringing different parties together to form one team that shares the same goals.

The term _developer_ takes a different meaning, as both programmers and testers develop the software. Different roles work together seamlessly and comprise the working group known as developers.

Many projects experience the best results by allowing everyone in the team to perform QA and be responsible for quality.

### New approach

* __Quality__: testers are not solely responsible for quality, rather, the whole team works together to maintain quality.
* __Development__: programmers do not code alone, rather, everyone helps them understand what to code.
* __Project roles__: cross-funcitonal teams are set up and roles decoupled from activities.

If you define work as activities to be accomplished together, you break down role boundaries and allow team memebers to add value in multiple areas.

For example, you can enable programmers to conduct exploratory tests, and QA leads to work with the application code if they find a fixable bug.

### Development and Operations

In Agile approaches, Development consists of programmers, testers and QA. __Operations often acts or gets treated as a silo__.

Agile approaches claim to produce happier participants. However, the Operations department is still perceived by some as a strange group of highly specialized server techies in the engine room.

In contrast to developers, the Operations team is taked with the deliverables received from the Development teams and making software available on production machines such that the software can be used by users. At the same time, Operations team often receives non-functional requirements, such as target values for the avilability of the application. The shipped software may conflict with those requirements.

The main task of the Development team is to fulfill the customer's functional requirements, test the solution, and provide software updates in quick succession. New features that have been implemented and tested by the developers add potential value for the customer. On the one hand, Development team wants change, on the other hand, Operations team is mainly interested in reliable and stable software.

### Blame Game

* Conflicts during deployment
* Conflicts after deployment
* Conflicts about performance

#### Conflicts during deployment

Most conflicts originate from time pressures. Typically, a new software release must be deployed quickly. Another scenario that requires Operations team to react quickly is when the system is down, and restoring it becomes the highest priority. This situation often leads to a blame game where each side accuses the other of causing the problem.

Example scenario:

1. Development passes a new release but Operations is unable to get it running on Production system.
2. Operations team contacts members of the Development team to get them to fix the problem, the former describes the errors experienced while trying to bring the release to production.
3. Development blocks communication and does not offer any help.
4. Development claims that software ran in test environment without problems, therefore reasons that the Operation team is at fault for not bringing the release to life.
5. Test and production environment may be different in some minor detail and neither party be aware of that.

#### Conflicts after deployment

Example scenario:

1. Many more users are using new features than expected.
2. Response times slow down until software stops responding entirely.
3. Escalating the issue leads to finger pointing: development claims is the fault of the database group, database team blames the network group, and so.
4. Company begins and object investigation. By the time the root cause is discovered, users have already been scared away from the new application and company incurs heavy losses in sales and reputation.

#### Conflicts about performance

* Test environment does not fully mirror production environment.
* Finger pointing.

### Operations as bottleneck

The conflict between Development and Operations __worsened when Development began adopting more Agile processes__. Iterative models such as Scrum, have become mainstream, but all too often, companies have stopped adding people and activities to the Scrum process at the point where software releases were shipped to production.

The __one team approach__ should also include expert from Operations who develop, for instance, automation scripts or _Infrastructure as code_.

The __advantages of Agile processes are often nullified__ because of the obstacles to collaboration, processes, and tools that are built up in front of Operations. As a result, __software is release frequently but only in test environments__ and rarely brought to the production phase. Consequently, not all releases are production-ready, and in sum, the cycle time from the inception of an idea to its delivery to users is still too long.

High frequency of software releases only on development and the incentives for Operations leads to what many people in the __company will perceive as a bottleneck at Operations__.

__Developments may have finished the functionality in fast cycles by using Agile frameworks__, but operations may not want or be unable to receive all the changes in fine-grained portions.

Development will blame operations for not being able or willing to set the software live. Operations will blame the Development team members because of their inability to develop production-ready software.

The __root cause of these mismatches__ can be narrowed down to __different goals and suboptimal collaboration__ between these groups.

## DevOps team settings

DevOps one team approach consist of programmers, testers, QA, __and experts from operations__. They all develop software and help to bring it to the user.

### Values and goals

* Commitment to __shared goals and values__.
* Collective ownership.

Essential to improving collaboration is the __alignment of incentives__ across teams as well as the __application of shared processes and tools__. This includes a shared definition of quality for the whole project and commitment to it.

Aligning with defined quality attributes, visibility and transparency can help to foster collaboration. __Incentives must treat development and operations groups as one team__. That is, they should be rewarded for developing as many changes that are stable and shipped.

As a pre-requisite, teams are cross-functional. Thus, individual experts share their skills and experiences with others, which leads to a one team approach where individuals have at least abasic understanding of other's domains.

DevOps is about __team play__ and a __collaborative problem-solving approach__. If a service goes down, everyone must know what procedures to follow to diagnose the problem and get the system up and running again. Additionally, all roles and skills necessary to perform these tasks must be available and able to work together well. __Training__ and __effective collaboration__ are critical here.

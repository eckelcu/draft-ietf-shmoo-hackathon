---
title: "Running an IETF Hackathon"
abbrev: "ietf-hackathon"
docname: draft-ietf-shmoo-hackathon-latest
category: info

ipr: trust200902
area: "General"
workgroup: "Stay Home Meet Occasionally Online"
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: C. Eckel
    name: Charles Eckel
    organization: Cisco Systems
    email: eckelcu@cisco.com
    country: United States of America

normative:

informative:

  SURVEY:
    title: "IETF 107 Hackathon Participant Survey"
    target: "https://www.surveymonkey.com/results/SM-9HLRXN8M7/"

  IETF-108-HACKATHON-WIKI:
    title: "IETF 108 Hackathon Wiki"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki/108hackathon/"

  IETF-RUNNING-CODE-SPONSOR:
    title: "IETF Running Code Sponsor"
    target: "https://www.ietf.org/about/support/#running-code/"

  REMARK:
    title: "remark GitHub Repository"
    target: "https://github.com/gnab/remark/"

  DATATRACKER:
    title: "IETF Datatracker"
    target: "https://datatracker.ietf.org/"

  IETF-HACKATHON-GITHUB:
    title: "IETF-Hackathon GitHub"
    target: "https://github.com/ietf-hackathon/"

  REQUEST-SESSIONS:
    title: "IETF Session Request"
    target: "https://datatracker.ietf.org/secr/sreq/"

  AGENDAS:
    title: "IETF Meeting Agenda"
    target: "https://datatracker.ietf.org/meeting/agenda/"

  HACKATHON-WEBSITE:
    title: "IETF Hackathon Website"
    target: "https://www.ietf.org/how/runningcode/hackathons/"

  MEETING-WEBSITE:
    title: "IETF Meeting Website"
    target: "https://www.ietf.org/how/meetings/"

  REGISTRATION-SYSTEM:
    title: "IETF Meeting Registration System"
    target: "https://registration.ietf.org/"

  NOTE-WELL:
    title: "IETF Note Well"
    target: "https://ietf.org/about/note-well/"

  DATATRACKER-ACCOUNT:
    title: "IETF Datatracker Account Creation"
    target: "https://datatracker.ietf.org/accounts/create/"

  EMAIL-LIST:
    title: "IETF Hackathon Email List"
    target: "https://www.ietf.org/mailman/listinfo/Hackathon/"

  EMAIL-ALIAS:
    title: "IETF Hackathon Chairs Email Alias"
    target: "mailto:hackathon-chairs@ietf.org"

  MEETECHO:
    title: "Meetecho"
    target: "https://www.meetecho.com/"

  HACKNET:
    title: "HackNet"
    target: "https://hacknet.meeting.ietf.org/"

  WEBEX-ACCOUNT:
    title: "IETF Webex Account"
    target: "https://ietf.webex.com/webappng/sites/ietf/dashboard?siteurl=ietf/"

  GATHER:
    title: "Gather"
    target: "https://gather.town/"

  HEDGEDOC:
    title: "HedgeDoc"
    target: "https://notes.ietf.org/"

  IETF-106-SURVEY:
    title: "IETF 106 Meeting Survey"
    target: "https://www.ietf.org/media/documents/IETF_106_Meeting_Survey.pdf"

  IETF-110-SURVEY:
    title: "IETF 110 Meeting Survey"
    target: "https://ql.tc/8K1JeZ/"

  IETF-BLOG:
    title: "IETF Blog"
    target: "https://www.ietf.org/blog/"

  GITHUB-REPO:
    title: "GitHub Repository for draft-ietf-shmoo-hackathon"
    target: "https://github.com/eckelcu/draft-ietf-shmoo-hackathon/"

  MEETING-WIKI:
    title: "IETF Meeting Wiki"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki"

  RESULTS-PRESENTATIONS:
    title: "IETF 110 Hackathon Project Results Presentations"
    target: "https://github.com/ietf-hackathon/ietf110-project-presentations"

  PARTICIPANTS:
    title: "IETF 110 Hackathon Participant List"
    target: "https://registration.ietf.org/110/participants/hackathon/"

  IETF-110-HACKATHON-WEBSITE:
    title: "IETF 110 Hackathon Website"
    target: "https://www.ietf.org/how/runningcode/hackathons/110-hackathon/"

  IETF-110-HACKATHON-WIKI:
    title: "IETF 110 Hackathon Wiki"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki/110hackathon/"

  LOST-AND-FOUND:
    title: "IETF 110 Hackathon Lost and Found"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki/110hackathon/lost&found"

  RESULTS-PRESENTATION-SCHEDULE:
    title: "IETF 110 Hackathon Results Presentation Schedule"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki/110hackathon/resultspresentationschedule"

  TEAM-SCHEDULE:
    title: "IETF 110 Hackathon Team Schedule"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki/110hackathon/teamschedule"

  HACKDEMO:
    title: "IETF 113 Hackdemo Happy Hour"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki/113hackathon/hackdemo"

  CODE-LOUNGE:
    title: "IETF 113 Code Lounge"
    target: "https://trac.ietf.org/trac/ietf/meeting/wiki/113hackathon/codelounge"

  TICKET:
    title: "IETF Support Email Alias"
    target: "mailto://tickets@meeting.ietf.org"

  RIPE-CALENDAR:
    title: "RIPE Upcoming Events"
    target: "https://www.ripe.net/participate/meetings/calendar/"

  NSRC-CALENDAR:
    title: "Network Startup Resource Center Calendar"
    target: "https://nsrc.org/calendar/"

  CODE-SPRINT:
    title: "IETF Code Sprint"
    target: "https://www.ietf.org/how/runningcode/code-sprint/"

--- abstract

IETF Hackathons encourage the IETF community to collaborate on running code related to existing and evolving Internet standards. This document provides a set of practices that have been used for running IETF Hackathons. These practices apply to Hackathons in which both in-person and remote participation are possible with adaptations for Hackathons that are online only.

--- middle

# Introduction

IETF Hackathons encourage the IETF community to collaborate on running code related to existing and evolving Internet standards. IETF Hackathons aim to:

* Advance the pace and relevance of IETF standards activities by bringing the speed and collaborative spirit of open source development into the IETF
* Bring developers and young people into IETF and get them exposed to and interested in the IETF

IETF Hackathons are free to attend and open to everyone. Software developers are the primary audience, but participation by subject-matter experts who are not necessary developers is encouraged and very important as well. Similarly, while the Hackathon is meant to attract newcomers and those who do not typically view themselves as standards people, long time IETF contributors, including Internet-Draft authors, working group chairs, and subject-matter experts, are key participants as well. Group dynamics and blending of skill sets and perspectives are extremely valuable aspects of IETF Hackathons.

In addition to the running code created and improved as a result of each Hackathon, the exchange of ideas, extensions of human networks, and establishment of trust, respect, and friendships are some of the most valuable outputs of each Hackathon. Code written in a programming language can be more illustrative and less confrontational than opinions expressed during a meeting or in an email. Working together to find common understanding of proposals, concerns, and solutions that result in improvements to evolving Internet standards is as important as the development of running code that implements or validates the correctness of these same proposals.

Consequently, IETF Hackathons are collaborative events, not competitions. Any competitiveness among participants is friendly and in the spirit of advancing the pace and relevance of new and evolving Internet standards. IETF Hackathons are inclusive, not only in terms of who can participate but also in terms of the projects included in each Hackathon. All projects should be related to existing or proposed Internet standards in some way. Examples include, but are not limited to, interoperability of implementations, proof of concepts, and tools.

IETF Hackathons foster an open environment, with much of the code being open source and projects results typically shared publicly. The Hackathon operates under the {{NOTE-WELL}}; however, the rules and terms around code are those of the license associated with the code. Although code is often and preferably open source, it may be proprietary as well.

This document provides a set of practices that have been used for running IETF Hackathons.

# Timing

The first IETF Hackathon was held the weekend before the start of the IETF 92 meeting. The rationale was to avoid conflicts yet make it relatively convenient for those attending the IETF meeting to participate in the Hackathon as well. Holding the Hackathon on the weekend was also viewed as making it more accessible to non IETF meeting participants, including students and working professionals who would have other commitments during the week. The weekend before was viewed as better than the weekend after so that things learned during the Hackathon could be shared and discussed with the rest of the IETF community during working group sessions and the like. This worked well at IETF 92, was repeated at IETF 93, and quickly became an established norm with the IETF meeting being officially extended to include the Hackathon at the start. An additional benefit of this timing noted and appreciated by participants is that it serves as a more informal and social way to physically and mentally acclimate to changes in time zones and surroundings.

## Agenda

The IETF Hackathon is a strenuous event. Though not a competition, participants want to make the most of their time together, much as with the IETF meeting in general. Competitive Hackathons typically run non-stop for on the order of 40 hours. There is a strict deadline and teams are judged and winners declared at the end. Afterward everyone is wiped out and heads off to briefly celebrate or commiserate, but mainly to recuperate. As the IETF Hackathon serves as the start of the overall IETF meeting, we aim to strike a compromise that provides enjoy time to get valuable work accomplished without exhausting themselves before the main IETF meeting even starts. While some people participate in the Hackathon only, the majority of people remain and plan to be actively engaged in the rest of the IETF meeting.

The typical agenda is as follows:

    Saturday before IETF meeting week
        08:30: Room open for setup by project champions
        09:00: Room open for all - Pastries and coffee provided
        09:30: Hackathon kickoff
        09:45: Form Teams
        12:30: Lunch provided
        15:30: Afternoon break - Snacks provided
        19:00: Dinner provided
        22:00: Room closes

    Sunday before IETF meeting week
        08:30: Room opens - Pastries and coffee provided
        12:30: Lunch provided
        13:30: Hacking stops, prepare brief presentation of project results
        14:00: Project results presentations to other participants
        15:45: Closing remarks and opportunities for next time
        16:00: Hackathon ends
        17:00: Tear down complete

The time on Saturday morning provides team champions time for setup and participants time to socialize and learn more about projects and team they might want to join. The kickoff presentation and formalities are kept to minimum to leave as much time as possible for team to work together with their team on their projects. The proximity of teams to each other fosters communication and collaboration across teams as well.

Lunch and dinner are provided as a convenience and an incentive to remain at the Hackathon. Participants are free to come and go as they like. It is well understood and accepted that there are other things vying for time and that meeting with friends and colleagues outside of the Hackathon is an entirely reasonable thing to do.

The room closes Saturday evening to give hotel staff unfettered access to the room and to encourage people to pace and take care of themselves. There are no rules against continuing work on projects outside of the Hackathon room. Similarly, working on projects long before and after the Hackathon is allowed and encouraged.

The end of the Hackathon on Sunday is driven by other IETF meeting events. There typically are Newcomer events that start at 16:00. The IETF Hackathon typically includes many newcomers in its list of participants and it is important to provide them time to participate in the Newcomer events. The opening reception for the IETF typically start at 17:00, and we want to make it easy for all Hackathon participants to join that as well.

[Hackdemo Happy Hour](#hackdemo-happy-hour) and the [Code Lounge](#code-lounge) exist to facilitate ongoing discussion and work on projects beyond the official end of the Hackathon weekend.

## Hackdemo Happy Hour

Hackdemo Happy Hour provides an opportunity for more in depth sharing and discussion than is possible within the time constraints of the result presentations that occur at the end of the Hackathon. This opportunity is made available to all teams. As with the results presentations, participation is optional.

Initially, we did something similar as part of Bits and Bites. This worked well for the Hackathon but the Bits and Bites event was eventually abandoned for other reasons. Hackdemo Happy Hour was created as a low cost, informal event to provide a venue for the IETF community to engage with the Hackathon teams in more in depth discussions related to their projects.

Hackdemo Happy Hour is typically Monday evening, roughly from 18:00 - 19:30, often overlapping a bit with the last working group session of the day but continuing long enough to allow everyone an opportunity to join. The goal is to make it convenient to attend by not conflicting with other meetings but also no running too late into the night.

Light snacks and beverages are provided, and a cash bar is available to align with the spirit of a happy hour.

## Code Lounge

The Code Lounge provides space for groups to gather and continue to collaborate on running code after the Hackathon. It is typically in the IETF Lounge and open the same hours as the IETF Lounge. Champions are encouraged to look at the final agenda and determine time slots best suited to ensure attendance of Code Lounge sessions as well as any related working group sessions. It is okay for multiple teams to sign up for the same time slots. This is in fact encouraged for work that spans multiple working groups or projects.

## Code Sprint

The IETF {{CODE-SPRINT}} develops tools that support the work of the IETF. The Code Sprint existed long before the Hackathon and benefitted from being a focused event in a quiet space with few interruptions. However, there is a great deal of synergy between the Code Sprint and the Hackathon, and they attract some of the same participants. For example, some Hackathon projects, such as those related to YANG model validation, involve the creation or modification of IETF tools. It is therefore advantageous to co-locate these two events when practical, and when separate space is deemed helpful, to allocate spaces that are physically close to each other to make it easy for participants to switch back and forth between the two events.

## Online Only

The IETF 107 Hackathon was originally scheduled to be the weekend at the start of the IETF meeting in Vancouver. When COVID-19 hit and it became clear the IETF meeting could not occur in person, the Hackathon already had 23 projects and 176 registrations. With only 10 days until the anticipated start of the Hackathon, a {{SURVEY}} went out to the Hackathon community, including all project champions and registered participants, to see if they wanted to participate in the Hackathon exactly as planned except with everyone participating remotely rather than in person. A relatively small number of people expressed interest in participating, with even fewer wanting to continue to champion their projects. The fact that the Hackathon was planned for the weekend before the IETF meeting and in the local time zone, both of which were historically very convenient and attractive to Hackathon participants, suddenly became huge obstacles. Consequently, the IETF 107 Hackathon was cancelled.

We knew more in advance that IETF 108 would be an online only meeting. We moved and expanded the schedule to run the entire work week before the rest of the IETF meeting. The Hackathon kickoff was set for Monday, the closing for Friday, with all the time in between left for individual project teams to arrange to meet how and when was most convenient for them. The kickoff and closing sessions were schedule to align with the time frame established for the IETF 108 meeting. All of this was, of course, not ideal, and it worked much better for some people than for others, but at least everyone knew the plan and corresponding time commitment well in advance and had the ability to plan accordingly.

We ultimately had 19 projects and almost 300 registrations. It is hard to say how many people actually participated and for how long, but many projects were able to get substantial work done. For the closing, 10 teams produced and shared presentations summarizing their findings and achievements. All results presentations as well as the agenda and a recording of the closing session are available via the {{IETF-108-HACKATHON-WIKI}}. This level of participation was strong enough to be considered a success and justify including the Hackathon in future online only IETF meetings.

Hackdemo Happy Hour and the Code Lounge are not applicable for online only Hackathons.

# Funding

The Hackathon requires funding, and that funding increases with the number of participants. Participating has always been free; therefore, funding from other sources than participant fees is required.

## Sponsorship

The initial funding model was to have Hackathon sponsors sign up to sponsor and fund the Hackathon for one year. As part of starting the Hackathon, Cisco volunteered to sponsor and fund the Hackathon for its first year (i.e., three Hackathons, one at each IETF meeting during a calendar year). This sponsorship was to rotate. Huawei volunteered to sponsor the second year of the Hackathon. After the second year, a sponsor for the 3rd year was not found. However, the Hackathon had become a proven success. Consequently, the IETF decided to fund the Hackathon as part of the IETF meeting, with Hackathon sponsorship being on a best effort basis.

Online only Hackathons in response to the COVID-19 pandemic, and increased remote participating in general, result in increased cloud infrastructure requirements that make Hackathon sponsorship more attractive to cloud infrastructure providers.

Hackathon sponsorship is available at different levels as part of being an {{IETF-RUNNING-CODE-SPONSOR}}.

## Expenses

The primary expenses associated with the Hackathon are those for hosting an in-person event, e.g., meeting space, food and beverage, etc. It is often challenging to quantify the portion of this associated with the Hackathon from that incurred for the IETF meeting overall.

### In-person Event Expenses

The following expenses are associated with in-person participation in a Hackathon. When the IETF meeting is online only, these expenses are eliminated.

#### Meeting Space

The meeting space for the Hackathon is sometimes included as part of the overall contract for the IETF meeting. Other times, additional expense is incurred to secure a large enough space earlier than would otherwise have been required. Typically, the space is needed for setup from Friday afternoon before the start of the IETF meeting until Sunday afternoon. After the Hackathon, the space is typically repurposed for the IETF Lounge. If the size of the Hackathon continues to increase, it might be necessary to use the same space as is later used for the IETF plenary.

#### Food and Beverage

Some portion of the food and beverage expense is often included as part of a minimum spend the IETF is obligated to make. When a Hackathon sponsor is identified, funds resulting from this sponsorship are typically used to offset food and beverage expenses, or to increase the food and beverage budget.

The minimum food and beverage for the Hackathon has been,

* coffee, tea, and water Saturday and Sunday morning
* lunch Saturday and Sunday

Additional items, in order of importance, include,

* beer Saturday evening
* dinner Saturday evening
* continental breakfast Saturday and Sunday
* afternoon snacks Saturday and Sunday

#### T-shirts

Hackathon t-shirts are an important part of the Hackathon. They have been provided for all in-person Hackathons and greatly appreciated by many participants. They also serve as great advertising for the IETF, the Hackathon, and sponsors. Cisco or other event sponsors have often covered expenses associated with t-shirts. The current model is that the secretariat covers the expenses using whatever funding is available.

The number of size distribution of t-shirts for IETF 107 is provided here as an example.

* 380 t-shirts at a cost of roughly $10 USD / t-shirt with shipping to the Secretariat included
  * 50 Small
  * 120 Medium 
  * 110 Large
  * 75 XL
  * 25 XXL

The t-shirts are all standard cut. We previously tried providing fitted cut t-shirts as an option for Hackathon participants, but these were not well received.

#### Stickers

Laptop stickers are popular with developers. Stickers have been made available at the Hackathon for those that want them. Expenses have been covered by the IETF LLC, Director of Communications and Operations.

### Remote Participation Expenses

The following expenses are associated things done primarily to facilitate remote participation in a Hackathon. This includes participation when the Hackathon is online only as well as remote participation when the Hackathon is in-person.

* Meetecho: cost associated with Hackathon kickoff and closing
* Gather: costs associated with premium service, required to enable more than 25 concurrent users. This has not been necessary, but will almost certainly be if Gather becomes a valuable way for Hackathon participants to meet within and across teams.
* Webex: IETF Webex accounts are made available to champions for the duration of the Hackathon and some period beyond that encompasses at least the rest of the IETF meeting. These accounts are available at no additional cost to the IETF at present
* Network: setup and support of the IETF network, and remote access to it

The change in timing and extended duration of the Hackathon at an online only IETF meeting increases the duration and use of remote participation facilities from 7 days to 12 days. This may result in increases to the cost of providing these facilities.

# Project Presentations

Project presentations are an important mechanism for capturing what each team intends to accomplish, what they actually accomplished, and sharing the results and findings with the IETF community.

For the first few Hackathons, we had two very distinct types of presentations:

1. Presentations that served as project pitches at the start of the Hackathon
2. Presentations that summarized results at the end of the Hackathon.

## Project Pitches

The project pitches were 5-10 minute presentations by a champion of a project describing what they wanted to do and how they proposed to accomplish it. This gave everyone in the room a better understanding of all the projects and helped participants match themselves with appropriate projects. This worked well when we had few projects, but it became unwieldy as the number of projects increased. As knowledge of the Hackathon grew and advanced planning became more common, many participants knew exactly which team they planned to join and wanted to get to work as quickly as possible rather than spend time listening to presentations. Project pitches were dropped from the Hackathon. Champions are encouraged to share this type of information in advance via the [Meeting Wiki](#meeting-wiki) instead.

## Project Results Presentations

The project results presentations were brief presentations by each team of what problem they tried to solve, what they achieved, and highlights that included lessons learned, feedback to associated working groups, and collaboration with open source communities and other standards organizations. They also highlight individuals who participated in their first IETF Hackathon or first IETF event, which helps facilitate the introduction of such individuals to the IETF community. The production and presentation of results summaries is optional. Fortunately, despite the lack of awards and prizes, most teams participate.

As with the project pitches, project results presentations can become unwieldy as the number of projects increases. With this in mind, the total time for all results presentations is limited to 2 hours. The maximum duration of each presentation is calculated based on the number teams that indicate the desire to present. This maximum is strictly enforced to ensure all teams have the opportunity to present their results. Maximum durations of 3-5 minutes are typical.

### Templates

Project results presentation templates provides guidance on what to cover. The use of these templates is optional. They are made available in various formats in a GitHub repo created specifically for the presentations for each IETF Hackathon, e.g., {{RESULTS-PRESENTATIONS}}.

#### PPTX

For portability, presentations that use this template should be made exported into PDF format as well.

#### HTML format

This template should render within any browser. It can be rendered as a slideshow using {{REMARK}}.

## Upload to GitHub

All project results presentations are uploaded to the GitHub repo created the Hackathon, e.g., {{RESULTS-PRESENTATIONS}}. The contents of this repo are used as the source for all results presentations at the end of the Hackathon and remain as a reference after the Hackathon.

One must be a member of the {{IETF-HACKATHON-GITHUB}} organization to upload a new presentation or update/replace an existing presentation.

To be added as a member, presenters are asked to:

* include the name by which they are known in their GitHub profile
* enable two-factor authentication (2FA)
* send your GitHub username to the Chair(s)

Presenters are asked to do this at their earliest convenience as the Chair(s) typically get very busy as the start of presentations approaches.

## Presenting in Person

Presentations are run from a shared Chromebook at the front of the Hackathon room. This Chromebook is provided by the Secretariat.

## Presenting Remotely

Remote presenters are welcome to run their own presentations using the screen sharing functionality in Meetecho. Alternatively, the Hackathon Chairs can share the presentation and advance slides for the presenter.

# Tooling

The IETF Hackathon uses the same tooling used by the IETF community for its work and meetings.

## Datatracker

The {{DATATRACKER}} supports the notion of Teams that are not part of the standards development process. The Hackathon exists as one such Team. From the Datatracker menu, navigate to "Other" -> "Active Teams" -> "Hackathon". Here exists a Datatracker space for the Hackathon similar to what is available for working groups, including meeting materials, agendas, etc. Initially, there was some attempt to copy materials hosted in the {{IETF-HACKATHON-GITHUB}} to the Datatracker. Now this is done only when required for integration with other IETF tooling, including to:

* {{REQUEST-SESSIONS}} for the Hackathon kickoff and closing, and for Hackdemo Happy Hour
* post {{AGENDAS}}

## IETF Website

### Hackathon Website

The IETF website includes a {{HACKATHON-WEBSITE}}. This website contains information about the Hackathon in general as well as links to past, present, and future Hackathons. The relevant links are updated after each IETF meeting. Other content on the website is updated on a more ad hoc basis.

### Meeting Website

Each IETF {{MEETING-WEBSITE}} contains information about the corresponding Hackathon, including the dates of the Hackathon in the header and a link to the Hackathon website in the "Additional Events" section.


## Registration

Registration for the Hackathon is through the IETF meeting {{REGISTRATION-SYSTEM}}. Participant registration for the Hackathon is:

* independent of participation registration for the meeting
* free
* required

As with meeting registration, registrants for the Hackathon acknowledge the {{NOTE-WELL}} during the registration process.

### Participant List

An active list of all registered participants, e.g., {{PARTICIPANTS}}, is maintained by the Secretariat. Important information displayed for each registrant includes the set of projects and technologies in which each participant is interested and an email address. This information is optional at the time of registration and may be updated or removed by editing one's registration.


### Caps on Registrations

Registrations were capped for the first several Hackathons. This was done both for space and costs considerations. The cap was hit multiple times, each time resulting in temporary confusion and frustration among would be registrants, followed by the cap being increased. Currently, there are no caps enforced by the registration system.

## Meeting Wiki

The {{MEETING-WIKI}} serves as the primary source of information for each Hackathon.

### Hackathon

A page within the meeting wiki, e.g., {{IETF-110-HACKATHON-WIKI}}, is created by the Secretariat for each Hackathon and initialized with information that is based largely on the information from the previous Hackathon. Once created, the Hackathon Chairs update and moderate this page. Champions are requested and responsible for adding information about projects for which they are a champion.

Anyone can edit the wiki by logging in using their Datatracker login credentials. Credentials can be obtained by creating a {{DATATRACKER-ACCOUNT}}.

### Lost and Found

A Lost and Found wiki page, e.g., {{LOST-AND-FOUND}}, is created by the Chairs for each Hackathon. Participants looking for a team are encouraged to add themselves to the "Skills to Offer" table, providing some information about their skills and interests. This will help others with matching needs and/or interests find them. Champions wanting help on their projects are encouraged to add their teams to the "Skills Needed" table, providing some information about the skills they seek.

### Results Presentation Schedule

A Results Presentation Schedule wiki page, e.g., {{RESULTS-PRESENTATION-SCHEDULE}}, is created by the Chairs for each Hackathon. Hackathon teams are welcome and encouraged to present their results during the Hackathon Closing. Hackathon teams add the name of their project and the name of the presenter to the table at the bottom of this page.


### In Person Only

The following wiki pages are applicable for in-person Hackathons only.

#### Hackdemo Happy Hour

A Hackdemo Happy Hour wiki page, e.g., {{HACKDEMO}}, is created by the Chairs for each Hackathon. Champions are welcome and encouraged to add their project by entering the project name/acronym and a contact name and email address in the table displayed on the page.

#### Code Lounge

A Code Lounge wiki page, e.g., {{CODE-LOUNGE}}, is created by the Chairs for each Hackathon. Champions are welcome and encouraged to add their project by entering the project name/acronym and a contact name and email address in the table displayed on the page.

### Online Only

The following wiki pages are applicable for online Hackathons only.

#### Team Schedule

A Team Schedule wiki page, e.g., {{TEAM-SCHEDULE}}, is created by the Chairs for each online only Hackathon. Online only Hackathons take place globally for an entire week. It is up to individual project teams to determine the preferred dates, times, and ways to meet to work on their project within the context of that week (e.g., Zoom, Webex, Slack). This page is meant to help facilitate coordination of schedules within and across teams.

## Email List

The Hackathon email list, {{EMAIL-LIST}}, is used for all email communication and announcements related to the Hackathon. All registrants are given the option to subscribe to the list. Anyone interested in staying up to date on the Hackathon is able to subscribe at any time. Once subscribed, anyone can send and respond to emails to the list. The same list is used for each Hackathon. Anyone wishing to receive email for a specific Hackathon only can unsubscribe after that Hackathon has concluded.

### Hackathon Chairs Email Alias

The email alias, {{EMAIL-ALIAS}}, was created and is maintained by the Secretariat. It is used on Hackathon webpages and wiki pages to provide a single point of contact for the Hackathon.

## GitHub

The {{IETF-HACKATHON-GITHUB}} is used to share code, presentations, and other artifacts at IETF Hackathons. The Hackathon Chairs are responsible for administering the GitHub organization.

Code for Hackathon projects often exist elsewhere, which is perfectly fine. Anyone needing a place to host code for the Hackathon can request the creation of a repository for their project.

A repository is created and maintained by the Chairs for each Hackathon, e.g., {{RESULTS-PRESENTATIONS}}. This repo is for participants to upload project results presentations. The contents of this repo are used as the source for all presentations at the end of the Hackathon and remain as a reference after the Hackathon.

## Meetecho

{{MEETECHO}} is used for the kickoff and closing sessions of the Hackathon. This provides many capabilities, including the following:

* allows participants to join Hackathon sessions in person or remotely
* validates registration of participants at time of joining Hackathon sessions
* enables remote presenters of project results presentations
* captures recording of Hackathon kickoff and closing

## Network

Access to the IETF network is an important aspect of the Hackathon. The IETF network provides unfettered Internet access that is not typical within many residential, corporate, and university environments. For many of IETF participants and projects, access to the Internet and each other via wireless access to the IETF network is sufficient. However, due to the nature of the work done in the IETF, wired access and special networking capabilities are often required.

The NOC has graciously met the needs of the Hackathon since its inception and continues to add more capabilities over time. Champions are able to request in advance wired access and special networking functionality, including static IPv4 and IPv6 addresses, IPv6 only networking, a closed user group, NAT64, and IPv6 PD. All of this, and the IETF network in general, is made available by the start of the Hackathon and in advance for setup to the extent possible.

### Remote Networking

Online only meetings present both a personal networking challenge and a computer networking challenge. The NOC came to the rescue for the latter with an experimental mechanism to join the IETF network while attending a meeting remotely. This evolved into what is now known as {{HACKNET}}, a global Layer 2 VPN designed to support IETF protocol development across teams within the IETF Hackathon. A limited set of devices for connecting to HackNet are supported. In addition to layer 2 connectivity, a subset of the networking capabilities available at in-person meetings are available. Both the set of devices and the set of networking capabilities are expected to expand and evolve over time. However, it is important to note that HackNet is still an experiment and not a production service. Best effort support is available via email to {{TICKET}}.

## Webex

Champions can request a {{WEBEX-ACCOUNT}} they can use to schedule meetings for their team. These are similar to the Webex accounts allocated to working group chairs to be used for virtual interim meetings. An account can be requested by a team champion at any time. Accounts remain active and available throughout the duration of the Hackathon and the associated IETF meeting. A project name may be used in place of "Working Group Name" in the request form.

## Gather

{{GATHER}} facilitates virtual hallway interaction during IETF meetings. A dedicated area within the overall space is created by the Secretariat for the Hackathon. The area includes tables, identified by letters of the alphabet, that teams are free to self assign and use as and when they like. Eight to ten seats around each table facilitate group discussions within the team. A whiteboard or shared notes tablet, e.g., {{HEDGEDOC}}, at tables facilitates sharing of information within the team. The tables also facilitate collaboration across teams. One cautionary note, Gather has relative high network bandwidth and CPU requirements, and as such may not be well suited for some Hackathon participants.

The Gather space remains available between IETF meetings, with incremental improvements and additions made during this time. The space is cleaned about a month prior to the start of the next meeting, removing anything left over from the previous meeting.  Hackathon teams are encouraged to make a copy of anything they want to retain within a week of the end of the IETF meeting.

# Statistics and Metrics

Statistics for the Hackathon have been gathered informally from the first Hackathon, at IETF 92, and more formally since IETF 101. Registration is required but it is also free, which can lead to misleading statistics. Starting with IETF 101, an effort has been made by the Secretariat to validate registrations for all in-person participants by checking registrations at the main entrance to the Hackathon room. Badges similar to those issued for the rest of the IETF meeting are now issued for the Hackathon as well. There is still no good mechanism for determining the number of remote participants.

Hackathon participation has grown from 45 at IETF 92 to a maximum of 406 at IETF 104. Participation tends to be slightly higher when the IETF meeting is located in Europe. Recent in-person Hackathons have had roughly 30-40% as many participants as the corresponding IETF meeting. For roughly 20-30% of Hackathon participants, the Hackathon is their first experience at any IETF event.

## IETF Survey Results

For each IETF meeting, there is a post event survey that often includes a question or two about the Hackathon, e.g., {{IETF-106-SURVEY}}

## Hackathon Survey Results

Hackathon specific surveys have been used on some occasions to obtain more detailed feedback about the Hackathon from the IETF community. This has been especially useful for feedback on online only Hackathons. Survey have been short with most questions being optional, e.g., {{IETF-110-SURVEY}}.

# Roles and Responsibilities

This section provides a summary of the roles and responsibilities of individuals and groups involved in a successful IETF Hackathon. The summary provided here is not meant to be exhaustive. Some responsibilities are described entirely or in more detail throughout the rest of the document.

## Hackathon Chair(s)

The role of a Hackathon chair is similar to that of a working group chair. As with working groups, it is typically best to have co-chairs share responsibilities and workload. The Chairs work very closely with the Secretariat on all responsibilities. Key responsibilities include:

* Organize and deliver a Hackathon at each IETF meeting, soliciting help from all other roles to do much of the heavy lifting
* Encourage and provide guidance to champions who volunteer to lead projects
* Maintain the Hackathon wiki, e.g., {{IETF-110-HACKATHON-WIKI}}, and all of its child pages.
* Moderate [Hackathon email list](#email-list)
* {{REQUEST-SESSIONS}} for the Hackathon opening and closing in the IETF meeting
* Emcee the Hackathon, including the opening and closing sessions and announcements in between
* Create and manage the GitHub repository used for each Hackathon, e.g.,{{RESULTS-PRESENTATIONS}}
* Serve as main point of contact for all Hackathon questions and concerns

## Secretariat

Key responsibilities include:

* Configure and manage Hackathon [registration system](#registration)
* Maintain Hackathon [website](#hackathon-website)
* Create and maintain web page for each Hackathon, e.g., {{IETF-110-HACKATHON-WEBSITE}}
* Create wiki page for each Hackathon, e.g., {{IETF-110-HACKATHON-WIKI}}. This is initialized and updated at times by the Secretariat, but the Chair(s) are ultimately responsible for maintaining it.
* Handle venue logistics for Hackathon, Hackdemo Happy Hour, and Code Lounge (e.g., reserve room, food and beverages, AV, etc.)
* Internal IETF promotion (e.g., email messages to IETF community)
* Assist with external outreach, as needed, including finding sponsors
* Validate Hackathon registrations for in-person participants, including issuing badges and [Hackathon t-shirts](#t-shirts) when available

## Sponsor

Key responsibilities include:

* Provide some funding to help offset costs of Hackathon (either per meeting or per year, depending on model)
* Optionally provide t-shirts or other giveaways
* Optionally provide support staff to assist with Hackathon

Key benefits include:

* Sponsor logo on Hackathon t-shirts
* Sponsor logo on Hackathon signage
* Sponsor logo on Hackathon webpage and wiki
* Sponsor logo and call out in Hackathon kickoff and closing presentation
* Sponsor logo and call out in IETF Plenary presentation
* Sponsor logo and call out in Hackathon recap on {{IETF-BLOG}}
* Recognition in IETF community for helping the IETF Hackathon remain free and open to everyone

## Champions of Projects

Champions of projects are the key to a successful Hackathon. Key responsibilities for champions include:

* Volunteer to lead a project at the Hackathon
* Serve as primary contact for the project
* Add and manage information on the Hackathon wiki for the project
* Promote the project to appropriate groups inside IETF and outside as well
* Welcome and organize members of the team
* Provide focus, guidance, and leadership for the project

## IETF LLC, Director of Communications and Operations (was ISOC)

Key responsibilities include:

* Promotion outside of IETF, including web search engine ad words, social media posts, and listing on external event calendars such as {{RIPE-CALENDAR}} and {{NSRC-CALENDAR}}.
* Outreach to local universities
* Provide photographer, including optional team photos and candid photos of collaborating during in-person events
* [Laptop stickers](#stickers) at in-person events

## Judges

The first several Hackathon involved judges who listened to project results presentations by teams at the closing of each Hackathon and identified winning teams for an arbitrary number of project categories. Prizes were made available to members of winning teams. This was done as an incentive to participate in the Hackathon and present results, and  to provide a fun yet informative end to the Hackathon that could be appreciated by the entire IETF community. Judging and awarding of prizes led to confusion regarding the nature of the Hackathon, making it appear to some overly competitive. Procurement of appropriate prizes was financially and logistically challenging. Arrangement of judges, determination of winners, and awarding of prizes all became more time consuming, especially as the number of projects and participants grew. Ultimately, it was deemed best to eliminate judging, awards, and prizes entirely. Apparently the IETF community has an innate incentive to participate and present results in the Hackathon.

# Implementation Status

The practices described in this document have been established, used, and refined over the course of running numerous IETF Hackathons, including several at online only IETF meetings. The {{GITHUB-REPO}} GitHub repository has been used to collaborate on this document. The [IETF-Hackathon GitHub](#github) contains code associated with IETF Hackathons.

# Security Considerations

[HackNet](#remote-networking) enables Hackathon participants to join the IETF network while attending a meeting remotely. The intent is for those connecting remotely to have as open a network as possible, just like those connecting to the IETF network at an in person meeting. A user must have a Datatracker account to access HackNet and is expected to respect it just as they are expected to respect the IETF network at an in person meeting. If HackNet is exploited, it is addressed as an exploitation of the IETF network would be at an in person meeting.

## Privacy Considerations

Participant names are displayed publicly in the [Participant List](#participant-list). As part of their registration, participants may opt in to display their email address as well.

The email addresses of individual champions are often shared publicly by the champions on the wiki. This is done voluntarily by individual champions to make it easier for others to contact them.


# IANA Considerations

This document has no IANA actions.



--- back

# Acknowledgments
{:numbered="false"}

The IETF Secretariat, notably Alexa Morris and Stephanie McCammon, contributed significantly to the creation of the IETF Hackathon and the practices in this document. Among other things, Alexa drafted the initial breakdown of [Roles and Responsibilities](#roles-and-responsibilities), and Stephanie McCammon created the initial Hackathon website and wiki. These have evolved over time and are used to run each Hackathon.

Greg Wood, Barry Leiba, Michael Richardson, Benson Muite, Dhruv Dhody, Karl Auerbach, Mallory Knodel, Lars Eggert, and Robert Sparks also provided significant contributions to the Hackathon and to this document.

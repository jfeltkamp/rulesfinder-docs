# Project Planning and Execution

If you are the person who initiated a new RuFi project, or if you have been given responsibility for its execution, then you should familiarize yourself with the following information.

## Installing the RulesFinder Participation and Argumentation Software

To start a new RuFi project, you need a new installation of the software. Currently, it is not possible to run multiple projects simultaneously with a single software installation.

For offers to use the software as a service (SaaS) on one of our servers, you can find information on the page [rulesfinder.org](https://rulesfinder.org).

As a developer, you can [download the software for free](../get-rufi/install-rufi.md) and use it. The software is released under an open-source license. You can find more details in the licence.txt files that are attached to the program parts.

## Try out RuFi with Demo Content

To get off to a good start with working in RuFi, it is always a good idea to first familiarize yourself with the demo content. Every RuFi installation comes with a _RuFi Demo_ module that you can easily install. After the module is installed, you will find the demo content in the overviews under the menu paths: _RuFi > Overview > Problems_ (```/sections?node_type=problem```) or _RuFi > Overview > Rules_ (```/sections?node_type=rule```)

!!! info "Install Demo Content"

    To install the demo content, you need administrator rights. Go to the "Manage" section and select "Extend" from the submenu (URL path: ```/admin/modules```). Select the "RuFi Demo" module from the list and confirm with "Install" below the list.

Before you really start with the project, you can play the game "We live together in a shared apartment and create a set of house rules" with those who are not yet familiar with RuFi.

## Inviting Participants

Invite the participants who should take part in the negotiations. Our recommendation is that all persons who are affected by the negotiated contract or set of rules, or who should follow the rules defined therein, can participate in the negotiations (or are sufficiently represented).

To avoid an unmanageable flood of contributions, the number of participants should not exceed 10-20 persons.

!!! info "Invite Participants"

    You need a list of the names and email addresses of all participants.
    Repeat the following steps for each participant.

    1. Select the following path in the menu: _Manage > People > Add User_ (URL: ``/admin/people/create``).
    2. Enter name, email address, and an arbitrary but secure password in the form.
    3. Select "Member" for the user group. Participants with limited rights can be assigned the "Beginner" group.
    3. Activate the checkbox _Notify user of new account_.
    4. Click the button _Create new account_ at the end of the page.

Once you have completed these steps, emails will be sent to those invited. Included is a link with which the participants are asked to set their own password. It is not necessary for you to share the password you set with the participants.

!!! tip "Tip: Customize the invitation email text"

    You can still customize the invitation text before creating the accounts. To do this, select the path in the menu: _Configuration > People > Account settings_ (URL: ``/admin/config/people/accounts``) and select the tab _Welcome (new user created by administrator)_ at the bottom of the page.

## Project Moderation

The success of the project depends greatly on moderation. There is a dedicated user role with extended permissions for moderation. The moderation can consist of several persons.
The tasks of the moderator include:

* providing assistance as the first point of contact when needed
* checking newly created content to see if it meets the expected form, and providing feedback if necessary
* Moderating meetings
* Conducting elections and votes
* Mediating impartially in conflicts

Moderation can be performed at the project start by the initiators or project managers. However, since the role requires the trust of the participants, moderation should sooner or later be confirmed by an election.



## Introducing Participants to the Software

Draw the attention of new participants to this documentation, especially to the [How to Proceed](/get-involved/) and the [User Guide](/operation-manual/), where the most important rules are summarized in a compact form.

Discuss the procedure and user guide and make sure that no one is left behind for technical reasons. If someone still feels overwhelmed, it may be advisable to let this user start with the _Beginner_ role, which is more of an observer role and offers the possibility to participate in evaluations and votes.

It is highly recommended to work with new participants on the demo content in a playful way first, before addressing the serious questions. Even if it is just a game, everyone should take their roles seriously, and actually solve one or the other problem. The experiences that participants gain here can make a big difference at the project start.

## Scheduling Regular Sprint Meetings

During the project, regular meetings should take place. A proven practice is to divide the project into ongoing sprints of one or two weeks each. Meetings can then take place between sprints. They serve, on the one hand, to complete the old sprint and conduct votes (Review) and, on the other hand, to plan the next sprint (Planning).

In order to be able to use the RuFi software during a meeting, e.g. for voting, it is advisable to hold the meetings in an **online conference**.

### Review

In the review, the rules processed during the sprint are discussed individually before being finally voted on. The following questions should be discussed for each rule:

1. Is the **problem cited** for the rule formally [correctly presented](../write_content/probleme/), relevant and does it express a legitimate interest?
2. Are all participants of the opinion that the argumentation is complete?<br> (If necessary, small changes can also be inserted or ratings added during the meeting.)
3. Are there contra arguments that have _change requests_ attached to be introduced?
4. Is the **rule** formally [correctly presented](../write_content/regeln/)?
5. Does the rule contradict other existing rules?

Once all participants have been asked about these topics, the vote can be held whether the rule should come into force or not. The RuFi voting tool can be used for this, or another procedure can be chosen.

The moderation should definitely ensure that the **voting result** matches the **expectations** that arise from the quality of the argumentation and its ratings. If there are significant deviations, the reasons should be clarified and inserted as arguments. In such a case, the proposal to postpone the decision again is also justified.

!!! tip "Document Results"

    The results of votes should be recorded in a static protocol for transparency and security purposes, which is countersigned by several participants.

### Planning

In order to process topics effectively, it is important that participants follow these topics in a focused manner. Therefore, a manageable number of topics should be discussed and determined for each upcoming project sprint.

The RuFi software is not yet equipped for this purpose. However, solutions are planned so that moderators can limit sections or individual problems for processing in a project sprint.

## First Sprint: Define Project Goals

Start with the most important and fundamental questions and continue with the less important topics in descending order. Existentially important problem areas (such as _Finances_) should take higher priority than topics that concern, for example, the well-being of those involved or codes of conduct ("Must-Should-Could"). Establish a structure of three to five sections that roughly cover all topic areas to be dealt with.

For topics that can only be difficultly or not at all assigned, you should additionally set up an area _Miscellaneous_ at the end. At a later time, the initial topic structure can be revised so that the area _Miscellaneous_ can possibly be dissolved again through new assignments.

The topic of the **first sprint** - as well as the **first section of the contract** - should be the common goals and purposes, and how these are to be achieved. In the first section, also determine the values that should be particularly observed, and address the basic problems that typically arise.

If participants want to bring up topics that are important to them and are _burning on their soul_, but do not fit thematically into the planning, we recommend that problem statements can also be inserted as drafts in other topic areas, but then only taken up at the appropriate time.

## Further Sprint Planning

The following sprints should work through all sections from front to back - depending on the type of project and the expected effort - until the first contract draft is ready.

Naturally, all participants have sharpened their ideas and thoughts in the process, which is why it makes sense to revise especially the first section, the common goals, once more. Should the contract ever be presented to a judge, it contains the important agreements that form the basis for interpreting all other contract clauses.

## Final Sprint

For the last sprint, before the first final version is completed and adopted, all participants should carefully review the entire contract work again:

* whether all important [problem statements](../write_content/probleme/) have been processed
* whether all [rules are correctly formulated](../write_content/regeln/) and are consistent with each other
* whether all [transferable _change requests_](../write_content/change-requests/) have been inserted
* whether all [arguments are correctly formulated](../write_content/argumente/)
* whether all [texts are well formulated](../write_content/general-edit-texts/)

If everyone is satisfied with the result, the regulation can be decided or the contract can become legally binding by all participants confirming the contract with location, date, and their signature.

To create a **final version**, there is a dedicated entity type _Version_, which technically captures a snapshot of all content at the time of its creation and outputs a structured version of all rules (without problems and arguments).

## Long-Term Use with Editing Cycles

Depending on the type of project, it may make sense to revise the set of rules or to work with it continuously, for example, to adapt it to the structures of a changing organization or environment. For long-term agreements, such as multi-year cooperations with complex requirements, the possibility of updates should be planned from the beginning so that reorientations and practical experiences can be incorporated into the set of rules.

Often, it is only from the application of practical rules that it becomes apparent that they are not suitable for solving the problems for which they were introduced, that they even produce opposite effects or bring other, new problems to light. For this reason, it is recommended to persistently improve the set of rules. Such occasions also provide a good foundation for goal-oriented discussions in which the common endeavor is reflected upon and cooperation can be strengthened.

This is a particular strength of the RulesFinder participation and argumentation software, as all essential contents of the discussion are permanently stored and can be reused, improved, and supplemented.

New and better versions of the contract can be easily created and replace older contract versions.

## Contract Versions

Long-term use of the RuFi software is enabled with contract versions and corresponding sequential version numbers, with later versions replacing earlier versions. At any time, complete intermediate states or decision-ready versions of the set of rules can be fixed. For this purpose, only an entity of the type "Version" is created, which automatically captures and permanently stores a snapshot of all other entities at that time.[^1]

[^1]: Technically, no copy of the data is stored, but a data array with the IDs of all entities (problems, rules, arguments, ...) and their revision IDs at the time of version creation is created and stored.

A version has a comment field in which the following can be entered:

* the reason why the new version was created
* who actively participated in the session
* who did not participate in the session (and possibly who represented them)
* what the outcome of the vote was
* when the new version of the set of rules should come into force
* etc.

In the RuFi standard configuration, only a moderator has the permission to create a new version.

### Contract Validity

We recommend formally regulating the validity of a contract and its revised versions, e.g. through validity clauses, signatures, discharge statements, meeting minutes, etc. Otherwise, unexpected complications in legal matters may arise. 

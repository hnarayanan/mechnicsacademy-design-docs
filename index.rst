==========================================
Design documentation for Mechanics Academy
==========================================

The following design document begins with a high-level goal and
follows the following thought process to arrive at a specific
implementation that realises this goal.

::

         Overarching ambition
                  |
                  |
          Concrete sub-goals
           |               \
           |                \
   Requisite content  Desired behaviour
           |             /     |
           |            /      |
   Information architecture    |
     |              |          |
     |              |          |
     |      UX and visual front-end design
     |              |          |
     |              |          |
   Back-end functionality      |
           |                   |
           |                   |
          Specific implementation

Overarching ambition
====================

Mechanics Academy aims to be a comprehensive resource for anyone
interested in learning mechanics.

Concrete sub-goals (SGs)
========================

#. Attract learners to the rich and useful topic of mechanics

#. Act as a catalogue of high-quality learning resources for mechanics

#. Offer help and support to mechanics learners

#. Provide mechanisms to test learning and gauge competency

#. Serve as a conduit between a community with certain competency and
   the industry

#. Provide scientific computing services "on the cloud" for easy
   access to powerful computational mechanics tools

Requisite content and related architecture
==========================================

Fun and engaging  open-access motivating material (SG 1)
--------------------------------------------------------

#. Demonstration videos (including sections of complete lectures)

   =========  ===========================================================
    Content    Links/embeds to (potentially snippets of) external videos
    Meta       Source/author information, description, license
   =========  ===========================================================

#. Videos and visuals of thought-provoking observations in nature

   =========  ===========================================================
    Content    Links/embeds to (potentially snippets of) external videos
    Meta       Source/author information, description, license
   =========  ===========================================================

#. Application-relevant simulations

   =========  ===========================================================================
    Content    Links/embeds to external motivating simulations
    Meta       Source/author information, description, license
    Notes      e.g. `Projectile and orbital motion simulations <http://bit.ly/14cGrXi>`_
   =========  ===========================================================================

Original content to motivate learners (SG 1)
--------------------------------------------

#. Documented (video) user stories emphasising the importance of the
   material (e.g. interviews with rock-star scientists)
#. Demonstrations of research-level problem solving in the real world
#. Application-relevant simulations that demonstrate the usefulness of
   scientific computing

   =========  ===================================
    Content    Embedded motivating simulations
    Meta       Description, motivating questions
   =========  ===================================

Catalogue of best existing Open Educational Resources (SG 2)
------------------------------------------------------------

All the following can be served with rich, user-searchable metadata
(classification, crowd-sourced ratings and perhaps even a review). In
addition, consider whether the following need to be embeds or whether
just a link will suffice.

.. Think of providing tests/exercises around existing material

#. Complete courses

   =========  =======================================================================================
    Content    Embedded lecture videos, lecture notes, assignments/solutions, exams/solutions
    Meta       Source/instructor information, syllabus, license, links to related external resources
   =========  =======================================================================================

#. Independent external resources

   =========  ==================================================================================================================================
    Content    Embedded Interesting demo media, instructional videos, related notes, tutorials, practice (including simulation-based) exercises
    Meta       Source/author information, license
   =========  ==================================================================================================================================

Original course material of high quality (SG 2)
-----------------------------------------------

The following content will be modular and (a) fills obvious gaps in
existing content and (b) meets the competency needs of society and
industry.

#. Complete courses
#. Short tutorials (e.g. Try Ruby)
#. Other standalone resources (e.g. primer notes)

Engaged community of co-learners, mechanics experts and potential employers (SG 3, 5)
-------------------------------------------------------------------------------------

#. Curated discussion forums
#. Presence on social media
#. Invited contributions from domain experts
#. Blog covering topics of interest to the community and meta news
   about to Mechanics Academy

Mechanisms to get (personalised) help and support (SG 3)
--------------------------------------------------------

#. Web conferencing and other forms of direct communication (direct
   messaging) between multiple people.
   e.g. The instructor and a few learners on Google+
#. Other technology that fosters collaborative learning (???)
#. Ticketing system (which is linked to e-mail)
#. Easily searchable, meta-data rich knowledge base

In browser (including simulation-based) exercises (SG 4)
--------------------------------------------------------

.. edX SaaS-style "Test Driven" learning

#. Original short quizzes or exercises to test initial competence
#. Original short quizzes or exercises on external material
#. Quizzes or exercises as part of OER catalogue
#. Short quizzes or exercises in between video lectures
#. Final exams or exercises

"In-person" proctored examinations (???) (SG 4)
-----------------------------------------------

#. As part of a university course with ID verification
#. "Serious," large projects submitted for personal evaluation

Connect strong students who opt-in with interested employers (???) (SG 5)
-------------------------------------------------------------------------

Market tools potentially useful to the community (???) (SG 5)
-------------------------------------------------------------

Beautiful web-based interface for select software (???) (SG 6)
--------------------------------------------------------------

Elegant (Heroku-style) interface for scm-based pushing of research code (???) (SG 6)
------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 2

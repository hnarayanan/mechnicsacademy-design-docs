====================
An attempt at design
====================

We begin with our overarching ambition for the project and go through
the following thought process to arrive at a specific implementation
that realises this ambition.

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

#. Serve as a conduit between a community with mechanics-related
   competency and the industry

#. Provide scientific computing services "on the cloud" for easy
   access to powerful computational mechanics tools

Requisite content and related architecture
==========================================

Fun and engaging open-access motivating material (SG 1)
-------------------------------------------------------

.. cssclass:: table-bordered

==============  =============================================================================
 Content         #. Demonstration videos (including portions of complete lectures)
                 #. Videos and pictures of thought-provoking observations in nature
                 #. Popular science articles
                 #. Hands-on, application-relevant simulation that demonstrate the
		    usefulness of scientific computing
 Presentation    #. Links to/embeds of (possibly portions of) content
                 #. Complete lists of motivating material?
 Meta            #. Source/author information
 		 #. Description
		 #. License
 Examples	 #. `Mechanical energy conservation <http://bit.ly/X7ICoc>`_
                 #. `Projectile and orbital motion simulations <http://bit.ly/14cGrXi>`_
 Ideas		 #. Use the `About TedEd`_-style of marking up an embed to illustrate points
 		 #. Ask a thought-provoking question as in `exercises on TedEd`_
		 #. Emphasise motivation on home page like `MIT OCW does`_
==============  =============================================================================

.. _About TedEd: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/about/teded.png
.. _Exercises on TedEd: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/teded-3.png
.. _MIT OCW does: file:////Users/harish/Sites/mechanicsacademy/doc/design/screenshots/home/mitocw.png


Original content to motivate learners (SG 1)
--------------------------------------------

.. cssclass:: table-bordered

==============  ====================================================================================
 Content         #. Hands on, application-relevant simulation demos to play with
 		 #. Animations and pictures of simulation results related to realistic application
		 #. Popular science versions of computational science articles
 		 #. Documented---primarily video--user stories emphasising the importance of the
		    material, e.g.

 		    * Interviews with rock-star scientists
		    * Showing off tough research-level questions labs are trying to answer
 Presentation    #. Embeds of (possibly teasers of) content
                 #. Complete lists of motivating material?
 Meta            #. Description (e.g. motivating questions)
 Examples
 Ideas		 #. Have a prominent interactive demo right on the home page like `Codecademy has`_
==============  ====================================================================================

.. _Codecademy has: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/home/codecademy.png


Catalogue of best existing Open Educational Resources pertinent to mechanics (SG 2)
-----------------------------------------------------------------------------------

All the following can be served with rich, user-searchable metadata
(classification, crowd-sourced ratings and perhaps even a review). In
addition, consider whether the following need to be embeds or whether
just a link will suffice.

.. Think of providing tests/exercises around existing material

#. Complete courses

   .. cssclass:: table-bordered table-hover

   =========  =======================================================================================
    Content    Embedded lecture videos, lecture notes, assignments/solutions, exams/solutions
    Meta       Source/instructor information, syllabus, license, links to related external resources
   =========  =======================================================================================

#. Independent external resources

   .. cssclass:: table-bordered table-hover

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

Mechanisms to get help and support (SG 3)
-----------------------------------------

.. Personalised aspects of these support (e.g. workshops) can be tied
.. to a revenue stream.

#. Web conferencing and other forms of direct communication (direct
   messaging) between multiple people.
   e.g. The instructor and a few learners on Google+
#. Ticketing system (which is linked to e-mail)
#. Easily searchable, meta-data rich knowledge base
#. Other technology that fosters collaborative learning (???)

In browser exercises, including those based on simulation (SG 4)
----------------------------------------------------------------

.. edX SaaS-style "Test Driven" learning

#. Original short quizzes or exercises to test initial competence
#. Original short quizzes or exercises on external material
#. Quizzes or exercises as part of OER catalogue
#. Short quizzes or exercises in between video lectures
#. Final exams or exercises

Market tools potentially useful to the community (SG 5)
-------------------------------------------------------

.. The following ideas need more careful consideration in the
   future. For now, we do not worry about them.

--------------------------------------------------------------------

.. cssclass:: muted

"In-person" proctored examinations (SG 4)
-----------------------------------------

#. As part of a university course with ID verification
#. "Serious," large projects submitted for personal evaluation

.. cssclass:: muted

Connect strong students who opt-in with interested employers (SG 5)
-------------------------------------------------------------------

#. Act as a means to demonstrate student capabilities, e.g. published
   code samples and hosting a cool visual CV with results.

.. The following compute-server (Scikumo) needs to be separate in
   order to force a clean interface with Mechanics Academy

.. cssclass:: muted

Beautiful web-based interface for select software (SG 6)
--------------------------------------------------------

.. cssclass:: muted

Heroku-style interface for handling generic research code (SG 6)
----------------------------------------------------------------

#. Act as a means for reproducible research through the sharing of
   code in a systematic way
#. People can share big data across calculations

--------------------------------------------------------------------

.. _

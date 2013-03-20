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
interested in learning modern applied mechanics (which is an exciting
blend of applied mathematics, mechanics theory, material science and
scientific computing). It is in particular aimed at university level
students and industry professionals.

Concrete sub-goals (SGs)
========================

0. Increase awareness about and grow the resource

#. Attract learners to these rich and useful topics

#. Act as a catalogue of high-quality learning resources for these
   topics

#. Offer help and support to learners

#. Provide mechanisms to test their learning and gauge competency

#. Serve as a conduit between a community with mechanics-related
   competency and the industry

#. Provide scientific computing services "on the cloud" for easy
   access to powerful computational mechanics tools

Requisite content and related information architecture
======================================================

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
 Metadata        #. Source/author information
 		 #. Description
		 #. License
 Examples	 #. Numerous demonstration videos on `MIT Tech TV`_
 		 #. `Mechanical energy conservation <http://bit.ly/X7ICoc>`_
                 #. `Projectile and orbital motion simulations <http://bit.ly/14cGrXi>`_
 Ideas		 #. Use the `About TedEd`_-style of marking up an embed to illustrate points
 		 #. Ask a thought-provoking question as in `exercises on TedEd`_
		 #. Emphasise motivation on home page like `MIT OCW does`_
==============  =============================================================================

.. _MIT Tech TV: http://techtv.mit.edu/collections/physicsdemos/videos
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

		    * Invite contributions from domain experts
 		 #. Documented---primarily video---user stories emphasising the importance of the
		    material, e.g.

 		    * Interviews with rock-star scientists
		    * Showing off tough research-level questions labs are trying to answer
 Presentation    #. Embeds of (possibly teasers of) content
                 #. Complete lists of motivating material?
 Metadata        #. Description (e.g. motivating questions)
 Ideas		 #. Have a prominent interactive demo right on the home page like `Codecademy has`_
==============  ====================================================================================

.. _Codecademy has: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/home/codecademy.png


Curated catalogue of best existing Open Educational Resources pertinent to mechanics (SG 2, 4)
----------------------------------------------------------------------------------------------

.. cssclass:: table-bordered

==============  ====================================================================================
 Content	 #. Complete courses, including

		    * Lecture videos
		    * Lecture notes
		    * Assignments/solutions
		    * Exams/solutions
 		 #. Independent external resources, such as

		    * Interesting demo media
		    * Instructional videos
		    * Related notes
		    * Tutorials
		    * Practice (including simulation-based) exercises
		 #. Original tests and exercises to augment existing courses
 Presentation    #. List of links to complete courses and external resources
 		 #. Embeds of complete courses and related external resources
		 #. Embeds of complete courses along with related original exercises
 Metadata        #. Source/instructor information
                 #. Syllabus
		 #. Description
		 #. License
		 #. Links to related external resources
		 #. Topics covered
		 #. Difficulty level
		 #. Prerequisites
		 #. Crowd-sourced ratings?
		 #. Review?
 Examples	 #. MIT OCW's `Classical Mechanics`_ course
 		 #. Oxford Podcasts' `Quantum Mechanics`_ course
 		 #. Reading list on MIT OCW's `History and Philosophy of Mechanics`_ course
		 #. Yale OCW's `mechanics lectures`_ as part of introductory physics courses
		 #. `MATLAB exercises`_ on numerical computation for mechanical engineers
		 #. `Continuum mechanics article`_ on Wikipedia
 Ideas		 #. All the embeds above should be served in a way that offers some value over
 		    the original source, e.g. rich metadata search, better visual presentation,
		    augmented original exercises. They should do more than `Academic Earth's embeds`_.
		 #. Recent/featured courses in the catalogue can be featured on the home page
		    like `Udacity`_ and `OEDb do`_
		 #. Course listings can be classified in various ways: `topic`_,
		    `difficulty level`_, `kinds of media`_, `visually`_, `goal oriented`_
		 #. Consider simple JS exercises like Khan Academy. e.g., what would it take for
                    the pendulum to hit Lewin?
		 #. Allow for easily jumping to different sections of a long lecture based on
		    concepts or topics `like they do at OYC`_
		 #. Full, persistent keyboard control of pauses, skip forward/backwards 30 s or so.
		 #. Ability to mark areas of interesting content (videos/other), and collect all
		    these highlights into one place, such as the dashboard
		 #. Exercises should be well-integrated with the rest of the content, but students
		    who want to should be able to skip them
		 #. Some advanced exercises should prompt students to explore further
		 #. Related external material should be accessible right there and then alongside
		    the lectures, `as on OYC`_

==============  ====================================================================================

.. _Classical Mechanics: http://ocw.mit.edu/courses/physics/8-01-physics-i-classical-mechanics-fall-1999/
.. _Quantum Mechanics: http://podcasts.ox.ac.uk/series/quantum-mechanics
.. _History and Philosophy of Mechanics: http://ocw.mit.edu/courses/special-programs/sp-341-history-and-philosophy-of-mechanics-newtons-principia-mathematica-fall-2011/readings/
.. _mechanics lectures: http://oyc.yale.edu/physics/phys-200/lecture-1
.. _MATLAB exercises: http://ocw.mit.edu/courses/mechanical-engineering/2-086-numerical-computation-for-mechanical-engineers-spring-2012/matlab-r-exercises/
.. _Continuum mechanics article: http://en.wikipedia.org/wiki/Continuum_mechanics
.. _OEDb do: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/home/oedb.png
.. _Udacity: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/home/udacity.png
.. _topic: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/listing/teded-1.png
.. _difficulty level: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/listing/udacity.png
.. _kinds of media: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/listing/oedb.png
.. _visually: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/listing/teded-2.png
.. _goal oriented: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/listing/treehouse-3.png
.. _Academic Earth's embeds: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/academicearth.png
.. _like they do at OYC: http://oyc.yale.edu/physics/phys-200/lecture-1
.. _as on OYC:  file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/oyc-2.png

Original course material of high quality (SG 2, 4)
--------------------------------------------------

.. cssclass:: table-bordered

==============  ====================================================================================
 Content	 #. Complete courses, including

		    * Lecture videos
		    * Lecture slides/notes
		    * Interactive simulation demos
		    * Exercises, especially simulation-based
		    * Knowledge-bases/Wikis related to the course
		 #. Short tutorials focusing on technical topics, including

		    * Interactive simulation demos with simple step-by-step exercises
		    * Instructional videos
		    * Related notes
		 #. Other independent resources, including

		    * Interesting simulation demos
		    * Instructional (e.g. how-to) videos
		    * Related notes (e.g primers)
		    * Interactive exercises to augment existing courses
 Presentation    #. Course listings linking to individual courses
 		 #. Tutorial listings linking to individual tutorials
		 #. Resources embedded into courses/tutorials
		 #. Standalone resource listings linking to individual resources
 Metadata        #. Instructor information
                 #. Syllabus
		 #. Description
		 #. Links to related external resources
		 #. Topics covered
		 #. Difficulty level
		 #. Prerequisites
		 #. Crowd-sourced ratings?
 Examples	 #. Continuum mechanics course
 		 #. FEniCS tutorial
 		 #. Computational biomechanics course
 Ideas		 #. The original material on the site will be modular and

 		    * Fills obvious gaps in existing content
		    * Meets the competency needs of industry
		 #. This material can be classified into `theory, programming and application`_,
 		    as in the examples above
		 #. `Course overview pages`_ should clearly indicate what is being covered in them,
		    as well as what their prerequisites are
		 #. Logged in students should have an `overview of progress through the material`_
		 #. Homework exercises can be worked on by students locally, and tested server-side
		    through a `sequence of automated tests`_
		 #. Interactive exercises can be `tied to a lesson`_ or `served standalone`_
		 #. `Try Ruby`_ is a beautiful example of a short, interactive tutorial
		 #. `Course wikis`_ can help collect information related to the course, and kept
		    up-to-date by students
		 #. Not all content needs to `revolve around video`_
		 #. edX has a particularly clean way to move through `lectures`_ and
		    `interspersed exercises`_ as one progresses through a course. So `does Udacity`_.
		 #. Having a `discussion thread`_ tied to a lecture video allows students to ask
		    questions immediately as they're having them
		 #. Resources relevant to a lecture video should be linked to directly beside the
		    video
==============  ====================================================================================

.. _theory, programming and application: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/listing/mechanicsacademy.png
.. _Course overview pages:  file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/preview-and-overview/codeschool.png
.. _overview of progress through the material: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/dashboard/udacity.png
.. _sequence of automated tests: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/hw/edx.png
.. _tied to a lesson: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/interactive-exercises/codecademy.png
.. _served standalone: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/interactive-exercises/khanacademy.png
.. _Try Ruby: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/interactive-exercises/codeschool.png
.. _Course wikis: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/knowledge-base/edx.png
.. _revolve around video: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/cmuoli.png
.. _lectures: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/edx-1.png
.. _interspersed exercises: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/edx-2.png
.. _does Udacity: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/udacity.png
.. _discussion thread: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/lectures-and-exercises/khanacademy.png


Engaged community of co-learners, mechanics experts and potential employers (SG 3, 5)
-------------------------------------------------------------------------------------

.. cssclass:: table-bordered

==============  =============================================================================
 Content         #. Curated discussion forum
                 #. Presence on social media
		 #. Blog covering topics of interest to the community and meta news about
		    Mechanics Academy
		 #. Invite contributions from domain experts?
		 #. Allow people to have beautiful visual profiles (about->codecademy)
 Ideas		 #.
==============  =============================================================================

Other mechanisms to get help and support (SG 3)
-----------------------------------------------

.. Personalised aspects of these support (e.g. workshops) can be tied
.. to a revenue stream.

.. Personalised support on OER?

#. Web conferencing and other forms of direct communication (direct
   messaging) between multiple people.
   e.g. The instructor and a few learners on Google+
#. Ticketing system (which is linked to e-mail)
#. Easily searchable, meta-data rich knowledge base/FAQ
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

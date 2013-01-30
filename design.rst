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


Catalogue of best existing Open Educational Resources pertinent to mechanics (SG 2)
-----------------------------------------------------------------------------------

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


Original course material of high quality (SG 2)
-----------------------------------------------

.. cssclass:: table-bordered

==============  ====================================================================================
 Content	 #. Complete courses, including

		    * Lecture videos
		    * Lecture slides/notes
		    * Interactive simulation demos
		    * Exercises, especially simulation-based
		 #. Complete tutorials focusing on technical topics, including

		    * Interactive simulation demos with simple step-by-step exercises
		    * Instructional videos
		    * Related notes
		 #. Other independent resources, including

		    * Interesting simulation demos
		    * Instructional (e.g. how-to) videos
		    * Related notes (e.g primers)
		    * Interactive exercises to augment existing courses
 Presentation    #. Course listings linking to individual course pages
 		 #. Tutorial listings linking to individual course pages
		 #. Resources embedded into courses/tutorials
		 #. Resource listings linking to individual resources
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
 Ideas		 #. Original courses can be classified into `theory, programming and application`_,
 		    as in the examples above
==============  ====================================================================================

.. _theory, programming and application: file:///Users/harish/Sites/mechanicsacademy/doc/design/screenshots/courses/listing/mechanicsacademy.png

.. The following content will be modular and (a) fills obvious gaps in
.. existing content and (b) meets the competency needs of society and
.. industry.


.. . Try Ruby)

Engaged community of co-learners, mechanics experts and potential employers (SG 3, 5)
-------------------------------------------------------------------------------------

#. Curated discussion forums
#. Presence on social media
#. Invited contributions from domain experts
#. Blog covering topics of interest to the community and meta news
   about to Mechanics Academy

Other mechanisms to get help and support (SG 3)
-----------------------------------------------

.. Personalised aspects of these support (e.g. workshops) can be tied
.. to a revenue stream.

.. Personalised support on OER?

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

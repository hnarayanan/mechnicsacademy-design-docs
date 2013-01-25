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
 Requisite content and desired behaviour
         |             /      |
         |            /       |
 Content architecture         |
   |              |           |
   |              |           |
   |       UX and visual front-end design   <--  How do others do it?
   |              |
   |              |
 Back-end functionality
         |
         |
 Specific implementation

Overarching ambition
====================

Mechanics Academy aims to be a comprehensive resource for anyone
interested in learning mechanics.

Concrete sub-goals (SGs)
========================

#. Attract new learners to the rich and useful topic of mechanics

#. Act as a catalogue of high-quality learning resources for mechanics

#. Create an engaged community of co-learners and mechanics experts

#. Provide mechanisms to test learning and gauge competency

#. Serve as a conduit between a community with certain competency and
   potential employers

#. Provide scientific computing services "on the cloud" for easy
   access to powerful computational mechanics tools

Requisite content and related architecture
==========================================

Catalogue of motivating material (SG 1)
---------------------------------------

Fun and interesting (existing) open-access material
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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

Original motivating material
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Documented (video) user stories emphasising the importance of the material (e.g. interviews with rock-star scientists)
#. Demonstrations of research-level problem solving in the real world
#. Application-relevant simulations that demonstrate the usefulness of scientific computing

   =========  ===================================
    Content    Embedded motivating simulations
    Meta       Description, motivating questions
   =========  ===================================

Catalogue of high-quality learning resources (SG 2)
---------------------------------------------------

Catalogue of best existing Open Educational Resources
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  ..   * Complete courses

  ..     * **Content:** Lecture videos, lecture notes,
  ..     assignments/solutions, exams/solutions
  ..     * **Meta:** Source/instructor information, syllabus, license,
  ..     links to related external resources

  ..   * External resources

  ..     * **Content:** Interesting demo media, instructional videos,
  ..     related notes, tutorials, practice (including simulation-based)
  ..     exercises
  ..     * **Meta:** Source/author information, license

  .. # Original, high-quality course content

  ..   * **Content:**
  ..   * **Meta:**
  ..   * **Notes:** This course content should (a) fill obvious gaps in
  ..   existing material and (b) meet the competency requirements of
  ..   society/industry.

  .. # Community of co-learners, mechanics experts and potential employers

  .. # Mechanisms to evaluate learning and gauge competency

  .. # In-browser (including simulation-based) exercises

  .. # Conduit between competent community and interested employers

  ..   * Get strong students (who opt-in) in touch with potential employers
  ..   * Market relevant tools to the community

  .. # Scientific computing services "on the cloud"

  ..   * Elegant interface a la Heroku for git-based pushing of code
  ..   * Beautiful web interface for specialised code

.. toctree::
   :maxdepth: 2

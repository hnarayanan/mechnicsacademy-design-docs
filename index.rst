******************************************
Design documentation for Mechanics Academy
******************************************

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

Concrete sub-goals
==================

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

Catalogue of motivating material
********************************

#. Cute/interesting existing (open access) demo videos

 Interesting (open access) demo media

   =========  =================================================
    Content    Demo videos
    Meta       Source/author information, description, license
   =========  =================================================

#. Simulations related to fun applications of the theory

   1. Existing content

   =========  =============================================================================================================================
    Content    Links/embeds to external motivating simulations
    Meta       Source/author information, description, license
    Notes      e.g. `Projectile and orbital motion simulations <http://www.khanacademy.org/cs/projectile-and-orbital-motion/1002164118>`_
   =========  =============================================================================================================================

   2. Original content

   =========  ===================================
    Content    Embedded motivating simulations
    Meta       Description, motivating questions
   =========  ===================================

#. Catalogue of best existing Open Educational Resources

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


Lesson 7 snowflake fall blocks lesson
========================================

design a blinking rectangle animation.

Topic
-----

Forever

Quick Links
-----------
.. toctree::
   :maxdepth: 4

   ./snowflake-fall/activity
   ./snowflake-fall/quiz
   ./snowflake-fall/quiz-answers
   ./snowflake-fall/challenges


Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn how to show LEDs with a, ``pause`` to pause program execution for a specified amount of milliseconds. We will be learning how to show images using forever loop as well as simple commands, such as pause and show LEDs.

Documentation
-------------

.. code-block:: cards

   basic.showLeds(`
       . . . . .
       . . . . .
       . . # . .
       . . . . .
       . . . . .
       `)
   basic.pause(100)
   basic.forever(() => {})

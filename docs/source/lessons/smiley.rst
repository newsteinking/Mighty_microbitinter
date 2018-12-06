
Lesson 5 smiley blocks lesson
=====================================

Design a blinking image lesson

Topic
-----

Show LEDs

Quick Links
-----------
.. toctree::
   :maxdepth: 4

   ./smiley/activity
   ./smiley/quiz
   ./smiley/quiz-answers
   ./smiley/challenges




Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn how to **show LEDs** to turn on a LED light pattern on the LED screen. We will be learning basic comments such as show LEDs and pause.

Documentation
-------------


* **\ `show LEDs </reference/basic/show-leds>`_\ **
* **\ `on button pressed </reference/input/on-button-pressed>`_\ **

.. code-block:: cards

   input.onButtonPressed(Button.A, () => {})
   basic.showLeds(`
       . . . . .
       . . . . .
       . . # . .
       . . . . .
       . . . . .
       `)

Objectives
----------


* learn how to show LEDs on the LED screen
* learn how to run code when an input button is pressed

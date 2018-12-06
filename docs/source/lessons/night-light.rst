
Lesson 11 night light lesson
=================================

change the brightness of the @boardname@.

Topic
-----

Set Brightness

Quick Links
-----------

.. toctree::
   :maxdepth: 4

   ./night-light/activity
   ./night-light/challenges
   ./night-light/quiz
   ./night-light/quiz-answers



Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn how to **set brightness** of an image ``set brightness`` to set the brightness of the LED screen. We will be learning how to set the brightness of the LED screen using LED show LEDs, on button pressed and set brightness.

Documentation
-------------

.. code-block:: cards

   led.setBrightness(255)
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


* learn how to set the brightness of the LED screen
* learn how to run code when an input button is pressed
* learn how to turn on all LEDs

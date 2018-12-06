
Lesson 8 screen wipe blocks lesson
======================================

Clear the screen by pressing button "A".

Topic
-----

Clear Screen

Quick Links
-----------
.. toctree::
   :maxdepth: 4

   ./screen-wipe/activity
   ./screen-wipe/quiz
   ./screen-wipe/quiz-answers
   ./screen-wipe/challenges



Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn how to **clear screen**\ , ``clear screen`` to turn off all the LED lights on the LED screen. We will be learning how to clear all LED lights on the LED screen using clear screen, input on button pressed as well as simple commands, such as show animation.

Documentation
-------------

.. code-block:: cards

   basic.clearScreen()
   basic.showLeds(`
       . . . . .
       . . . . .
       . . # . .
       . . . . .
       . . . . .
       `)
   input.onButtonPressed(Button.A, () => {})

Objectives
----------


* learn how to show a series of images on the LED screen
* learn how to run code when an input button is pressed
* learn how to turn off all the LED lights on the LED screen

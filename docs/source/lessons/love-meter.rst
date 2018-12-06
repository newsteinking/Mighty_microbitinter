
love meter blocks lesson
========================

Create a love meter with the @boardname@.

Topic
-----

On Pin Pressed

Quick Links
-----------
.. toctree::
   :maxdepth: 4

   ./love-meter/activity
   ./love-meter/quiz
   ./love-meter/quiz-answers
   ./love-meter/challenges



Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn how to use the **pin pressed**\ , ``on pin pressed`` to run code when the user holds the GND pin with one hand, and presses pin 0 with the other hand, thus completing a circuit. We will be learning how to create a love meter using input on pin pressed, a local variable, math random, If (conditional) as well as simple commands, such as show number, pause, and show string.

Documentation
-------------

.. code-block:: cards

   if (true) {}
   input.onPinPressed(TouchPin.P0, () => {})
   let x = 0
   Math.randomRange(0, 3)
   basic.showNumber(0)
   basic.pause(100)

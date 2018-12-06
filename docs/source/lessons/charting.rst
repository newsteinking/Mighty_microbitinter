
charting lesson
===============

Create a charting app for simulating and measuring the acceleration applied to the @boardname@

Topic
-----

Acceleration

Quick Links
-----------

.. toctree::
   :maxdepth: 4

   ./charting/activity
   ./charting/challenge
   ./charting/quiz
   ./charting/quiz-answers



Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn the functions of **on data received**\ , **send number** and **receive number** and chart ``plot bar graph`` for ``acceleration`` in the "x" dimension.

Documentation
-------------

.. code-block:: cards

   input.acceleration(Dimension.X)
   led.plotBarGraph(0, 1023)
   basic.showNumber(0)
   radio.onReceivedNumber(function (receivedNumber) {})
   radio.sendNumber(0)

Objectives
----------


* learn how to repeat code in the background forever
* learn how to get the acceleration value (g-force), in one of three specified dimensions
* learn how to display a vertical bar graph based on the value and high value.
* learn how to register code to run when a packet is received over radio
* learn how to broadcast a number data packet to other @boardname@s connected via radio
* learn how to read the next radio packet as a number data packet

.. code-block:: package

   radio

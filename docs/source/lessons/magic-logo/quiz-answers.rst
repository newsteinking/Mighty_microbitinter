.. role:: raw-html-m2r(raw)
   :format: html


magic logo quiz answers
=======================

show an image that points up when the logo is up.

Name
----

Directions
----------

This is the answer key for the `magic logo quiz </lessons/magic-logo/quiz>`_

Answer the questions while completing the tutorial. Pay attention to the dialogues!

1. Define 'on logo up'
----------------------

A function that will run code when the @boardname@ screen is facing up and vertically orientated.

:raw-html-m2r:`<br/>`

2. Write the condition that detects when the @boardname@ logo is facing up and vertically orientated.
-----------------------------------------------------------------------------------------------------

The ``logo up`` event is raised when...


* the screen is facing up and the board is horizontal
* the screen is facing down and the board is horizontal
* the board is vertical and the logo is facing up

:raw-html-m2r:`<br/>`

.. code-block:: blocks

   input.onGesture(Gesture.LogoUp, function () {
   })

:raw-html-m2r:`<br/>`

3. Write the code to display a downward pointing arrow when the logo is down.
-----------------------------------------------------------------------------


.. image:: /static/mb/lessons/magic-logo-0.png
   :target: /static/mb/lessons/magic-logo-0.png
   :alt: 


:raw-html-m2r:`<br/>`

.. code-block:: blocks

   input.onGesture(Gesture.LogoDown, function () {
       basic.showLeds(`
   . . # . .
   . . # . .
   # # # # #
   . # # # .
   . . # . .
   `)
   })

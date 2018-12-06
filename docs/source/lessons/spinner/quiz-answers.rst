.. role:: raw-html-m2r(raw)
   :format: html


spinner quiz answers
====================

a spin the @boardname@ game with the input on shake.

Name
----

Directions
----------

Use this activity document to guide your work in the `spinner activity </lessons/spinner/activity>`_.

Answer the questions while completing the tutorial. Pay attention to the dialogues!

1. Write the code that stores a random number between 0 and 3 into a local variable named 'random arrow'.
---------------------------------------------------------------------------------------------------------

:raw-html-m2r:`<br/>`

.. code-block:: blocks

   let randomArrow = Math.randomRange(0, 4)

2. Write the if statement that will display this down arrow from your code. Hint- This occurs if the local variable 'random arrow' returns 1.
---------------------------------------------------------------------------------------------------------------------------------------------


.. image:: /static/mb/lessons/spinner-0.png
   :target: /static/mb/lessons/spinner-0.png
   :alt: 


:raw-html-m2r:`<br/>`

.. code-block:: blocks

   let randomArrow = Math.randomRange(0, 4);
   if (randomArrow == 1) {
       basic.showLeds(`
   . . # . .
   . . # . .
   # # # # #
   . # # # .
   . . # . .
   `)
   }

3. Write the if statement that will display this right arrow. Hint- This occurs if the local variable 'random arrow' returns 2.
-------------------------------------------------------------------------------------------------------------------------------


.. image:: /static/mb/lessons/spinner-1.png
   :target: /static/mb/lessons/spinner-1.png
   :alt: 


:raw-html-m2r:`<br />`

.. code-block:: blocks

   let randomArrow = Math.randomRange(0, 4);
   if (randomArrow == 2) {
       basic.showLeds(`
   . . # . .
   . . # # .
   # # # # #
   . . # # .
   . . # . .
   `)
   }

.. role:: raw-html-m2r(raw)
   :format: html


rotation animation quiz
=======================

Learn how to create a rotating image with a while loop.

Name
----

Directions
----------

Use this activity document to guide your work in the `rotation animation tutorial </lessons/rotation-animation/activity>`_.

Answer the questions while completing the tutorial. Pay attention to the dialogues!

1. What is a " variable"?
-------------------------

:raw-html-m2r:`<br />`

2. Write the code to create a variable called foo that stores a boolean and initialize it to false.
---------------------------------------------------------------------------------------------------

:raw-html-m2r:`<br/>`

3. Explain why you use a while loop with a variable
---------------------------------------------------

.. code-block:: blocks

   let rotating = true;
   while (rotating) {
       basic.showLeds(`
           . . . . .
           . . . . .
           . . # . .
           . . . . .
           . . . . .
           `)
       basic.showLeds(`
           . . . . .
           . . . . .
           . . . . .
           . . . . .
           . . . . .
           `)
   }

:raw-html-m2r:`<br/>`

4. Draw the areas on the @boardname@s to illustrate the code below. Explain why you chose to draw in those areas.
-----------------------------------------------------------------------------------------------------------------

.. code-block:: blocks

   basic.showLeds(`
           . . # . .
           . . # . .
           . . # . .
           . . # . .
           . . # . .
           `)
   basic.showLeds(`
           . . . . .
           . . . . .
           # # # # #
           . . . . .
           . . . . .
           `)
   basic.showLeds(`
           . . . . #
           . . . # .
           . . # . .
           . # . . .
           # . . . .
           `)
   basic.showLeds(`
           . . . . #
           . . . # .
           . . # . .
           . # . . .
           # . . . .
           `)


.. image:: /static/mb/lessons/looper-2.png
   :target: /static/mb/lessons/looper-2.png
   :alt: 


:raw-html-m2r:`<br/>`

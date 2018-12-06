
snowflake fall blocks quiz answers
==================================

Create a snowflake fall animation.  

This is the answer key for the `snowflake fall quiz </lessons/snowflake-fall/quiz>`_.

1. What is a forever loop?
--------------------------

Run code in the background forever (answers may vary).

2. Draw the picture that will be produced with this code
--------------------------------------------------------

.. code-block:: blocks

   basic.forever(() => {
       basic.showLeds(`
   . # . # .
   # # # # #
   # # # # #
   . # # # .
   . . # . .`);
   });


.. image:: /static/mb/lessons/flashing-heart-0.png
   :target: /static/mb/lessons/flashing-heart-0.png
   :alt: 


3.Write the code for a forever loop and show LEDS for these images!
-------------------------------------------------------------------


.. image:: /static/mb/lessons/snowflake-fall-0.png
   :target: /static/mb/lessons/snowflake-fall-0.png
   :alt: 


.. code-block:: blocks

   basic.forever(() => {
       basic.showLeds(`
           . . . . .
           . . # . .
           . # # # .
           . . # . .
           . . . . .
           `);
       basic.showLeds(`
           . . . . .
           . . . . .
           . . . . .
           . . . . .
           . . . . .
           `)
   });

4. Write the code for a forever loop and show LEDS for these images!
--------------------------------------------------------------------


.. image:: /static/mb/lessons/snowflake-fall-1.png
   :target: /static/mb/lessons/snowflake-fall-1.png
   :alt: 



.. image:: /static/mb/lessons/snowflake-fall-2.png
   :target: /static/mb/lessons/snowflake-fall-2.png
   :alt: 


.. code-block:: blocks

   basic.forever(() => {
       basic.showLeds(`
           . . . . .
           . . # . .
           . # # # .
           . . # . .
           . . . . .
           `);
       basic.showLeds(`
           # # # # #
           # # . # #
           # . # . #
           # # . # #
           # # # # #
           `)
   });

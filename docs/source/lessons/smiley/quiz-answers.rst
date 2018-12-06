.. role:: raw-html-m2r(raw)
   :format: html


smiley blocks quiz answers
==========================

This is the answer key for the `smiley quiz </lessons/smiley/quiz>`_.

1. Describe what ``show LEDs`` does
---------------------------------------

A function that will display an image on the LED screen

2. Why is there an extra empty frame after the smiley face?
-----------------------------------------------------------


.. image:: /static/mb/lessons/smiley-0.png
   :target: /static/mb/lessons/smiley-0.png
   :alt: 


:raw-html-m2r:`<br/>`

The extra empty image with show LED creates a blinking smiley, allowing the @boardname@ to alternate between showing the smiley and the empty screen.

3. Draw the image created with this code
----------------------------------------

.. code-block:: blocks

   basic.showLeds(`
       . # . # .
       . # . # .
       . . . . .
       # . . . #
       . # # # .
       `)


.. image:: /static/mb/blocks/lessons/smiley-4.png
   :target: /static/mb/blocks/lessons/smiley-4.png
   :alt: 


4. Write the code to make this image
------------------------------------

.. code-block:: blocks

   basic.showLeds(`
       . # . # .
       . # . # .
       . . . . .
       # . . . #
       . # # # .
       `)
   basic.showLeds(`
       . . . . .
       . . . . .
       . . . . .
       . . . . .
       . . . . .
       `)


.. image:: /static/mb/blocks/lessons/smiley-6.png
   :target: /static/mb/blocks/lessons/smiley-6.png
   :alt: 


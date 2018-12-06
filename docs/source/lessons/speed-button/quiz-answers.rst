.. role:: raw-html-m2r(raw)
   :format: html


speed button quiz answers
=========================

counter that keeps track of how many times button "A" has been pressed.

This is the answer key for the `speed button quiz </lessons/speed-button/quiz>`_.

1. What is a variable?
----------------------

:raw-html-m2r:`<br/>`

A variable that is available throughout your main function.

2. If the rectangle below represents the @boardname@, shade the area that shows the value of the variable count.
----------------------------------------------------------------------------------------------------------------

.. code-block:: blocks

   let count = 0


.. image:: /static/mb/lessons/speed-button-0.png
   :target: /static/mb/lessons/speed-button-0.png
   :alt: 


3. If the rectangle below represents the @boardname@, shade the areas that will be displayed after two button presses on Button A. Explain why that particular area is shaded.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

.. code-block:: blocks

   let count = 0
   input.onButtonPressed(Button.A, () => {
       count = count + 1
       basic.showNumber(count, 100)
   })

:raw-html-m2r:`<br/>`


.. image:: /static/mb/lessons/speed-button-1.png
   :target: /static/mb/lessons/speed-button-1.png
   :alt: 


After two button presses, **count** will be equal to 2.

5. If the rectangle below represents the @boardname@, shade the areas that will be displayed after five button presses on Button A. Explain why that particular area is shaded.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

.. code-block:: blocks

   let count = 0
   input.onButtonPressed(Button.A, () => {
       count = count + 1
       basic.showNumber(count, 100)
   })


.. image:: /static/mb/lessons/speed-button-2.png
   :target: /static/mb/lessons/speed-button-2.png
   :alt: 


After five button presses, **count** will be equal to 5.

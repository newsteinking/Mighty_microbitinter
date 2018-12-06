.. role:: raw-html-m2r(raw)
   :format: html


counter quiz
============

Learn how to create a counter with the @boardname@ button. 

Name
----

Directions
----------

Use this activity document to guide your work in the `counter tutorial </lessons/counter/activity>`_.

Answer the questions while completing the tutorial. Pay attention to the dialogues!

1. What is a variable?
----------------------

:raw-html-m2r:`<br/>`

2. Draw the stored value for the variable called count
------------------------------------------------------

.. code-block:: blocks

   let count = 0


.. image:: /static/mb/empty-microbit.png
   :target: /static/mb/empty-microbit.png
   :alt: 


:raw-html-m2r:`<br/>`

3. Draw which LEDs are ON after running this code and pressing button "A" once. Explain you chose to draw that number
---------------------------------------------------------------------------------------------------------------------

.. code-block:: blocks

   let counts = 0
   input.onButtonPressed(Button.A, () => {
       counts = counts + 1
       basic.showNumber(counts, 150)
   })


.. image:: /static/mb/empty-microbit.png
   :target: /static/mb/empty-microbit.png
   :alt: 


:raw-html-m2r:`<br/>`

4. Draw which LEDs are ON after running this code and pressing button "A" three times. Explain you chose to draw that number
----------------------------------------------------------------------------------------------------------------------------

.. code-block:: blocks

   let counting= 0
   input.onButtonPressed(Button.A, () => {
       counting = counting + 1
       basic.showNumber(counting, 100)
   })


.. image:: /static/mb/empty-microbit.png
   :target: /static/mb/empty-microbit.png
   :alt: 


:raw-html-m2r:`<br/>`

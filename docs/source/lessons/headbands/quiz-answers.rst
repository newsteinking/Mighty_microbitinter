.. role:: raw-html-m2r(raw)
   :format: html


headbands quiz answers
======================

create a charades game with a collection of strings.

Name
----

Directions
----------

Use this activity document to guide your work in the `headbands tutorial </lessons/headbands/activity>`_.

Answer the questions while completing the tutorial. Pay attention to the dialogues!

1. What is the meaning of the term 'collection' in programming? What is a 'collection' of strings?
--------------------------------------------------------------------------------------------------

:raw-html-m2r:`<br/>`

A 'collection' is a group of variables of the same type stored together. A 'collection' of strings is a group of strings stored together.

2. Consider the following lines of code.
----------------------------------------

.. code-block:: blocks

   let coll: string[] = []
   coll.push("puppy")
   coll.push("clock")

Write the line of code that will display the string "puppy" using ``||variables:coll||``.

:raw-html-m2r:`<br/>`

.. code-block:: blocks

   let coll: string[] = []
   basic.showString(coll[0])

3. Consider the following lines of code.
----------------------------------------

.. code-block:: blocks

   let coll: string[] = []
   coll.push("puppy")
   coll.push("clock")
   coll.push("cat")

Write the line of code that will display the string "cat" using ``||variables:coll||``.

:raw-html-m2r:`<br/>`

.. code-block:: blocks

   let coll: string[] = []
   basic.showString(coll[2])

4. Consider the following line of code.
---------------------------------------

.. code-block:: blocks

   let coll: string[] = []

Write the five (5) lines of code that will add the following five words to ``||variables:coll||``\ : ``"puppy"``\ , ``"clock"``\ , ``"night"``\ , ``"cat"``\ , and ``"cow"``.

:raw-html-m2r:`<br/>`

.. code-block:: blocks

   let coll: string[] = []
   coll.push("puppy")
   coll.push("clock")
   coll.push("night")
   coll.push("cat")
   coll.push("cow")

5. Write the code to get a string from the collection at a random position.
---------------------------------------------------------------------------

:raw-html-m2r:`<br/>`

.. code-block:: blocks

   let coll: string[] = []
   let index = Math.randomRange(0, coll.length)
   let word = coll[index]

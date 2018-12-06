
Seismograph Activity
====================

Welcome! In this project, you will build your own seismograph. This activity will teach how to use the @boardname@ to chart the strength of the acceleration. Let's get started! Project duration: 25 minutes.

~avatar avatar
--------------

Engineering: In this project, you will build your own seismograph @boardname@ from tape and a household plate. 

~
-

What you'll need:
-----------------


* @boardname@ 
* micro USB cable
* Plate 
* Tape 
* Scissors


.. image:: /static/mb/lessons/seismograph11.png
   :target: /static/mb/lessons/seismograph11.png
   :alt: 


Engineering Steps
=================

1.
--

Prepare Tape: Measure and cut approximately 10mm of tape. The tape will be fastened to a micro USB cable.  


.. image:: /static/mb/lessons/seismograph1.png
   :target: /static/mb/lessons/seismograph1.png
   :alt: 


2.
--

Fasten Tape: Fasten tape to the micro USB cable and to the plate. Attach the @boardname@ to the @boardname@ USB cable. 


.. image:: /static/mb/lessons/seismograph0.png
   :target: /static/mb/lessons/seismograph0.png
   :alt: 


~avatar avatar
--------------

Computer Science: The seismograph has been built. We are ready to program the @boardname@ to be a seismograph! 

~
-

Programming Steps
=================

3.
--

We will measure ``acceleration (mg)`` in terms of strength or Magnitude.

.. code-block:: blocks

   input.acceleration(Dimension.Strength);

4.
--

Use the plot bar chart to visualize the acceleration on the LED screen. Use a forever to keep reading the acceleration value and displaying it on the screen.

.. code-block:: blocks

   basic.forever(() => {
       led.plotBarGraph(input.acceleration(Dimension.Strength), 0);
   });

6.
--

At rest, the @boardname@ is always subject to Earth gravity, whose magnitude is measured around ``1023``. Substract ``1023`` to measure a data close to ``0``. 

.. code-block:: blocks

   basic.forever(() => {
       led.plotBarGraph(input.acceleration(Dimension.Strength) - 1023, 0);
   });

~
-

~avatar avatar
--------------

Data Analysis: We now need to use the @boardname@ to Analyze Data and chart for the strength of the acceleration.

~
-

Data Analysis Steps
===================

7.
--

First, notice that moving the @boardname@ in the simulator in any direction, you will change the acceleration value, which is being displayed as the same color as the @boardname@ simulator. Also, notice that by moving the @boardname@ simulator, there is a changing acceleration value. Second, the flat colored horizontal line will start a waving line to display the value of the strength as measured in milli-gravities. Finally, notice that the LED display will fluctate based on the movement of the @boardname@ simulator. 


.. image:: /static/mb/lessons/analyze20.png
   :target: /static/mb/lessons/analyze20.png
   :alt: 


8.
--

Connect a @boardname@ to your computer using your USB cable


.. image:: /static/mb/lessons/seismograph33.png
   :target: /static/mb/lessons/seismograph33.png
   :alt: 


Click or tap the **Download** button for the seismograph program to run the program on the @boardname@. 

9.
--

A black line should appear directly beneath the colored line. The black line measures the @boardname@ acceleration.  And the colored line measures @boardname@ simulator acceleration. 

Run the acceleration experiment by vigarously moving the plate in any direction or move the object below the @boardname@ (such as a table).

Every time the @boardname@ moves in any direction,  you generate data points that can be reviewed in Excel later. The more attempts to move the @boardname@, the more data to be reviewed in Excel.  


.. image:: /static/mb/lessons/seismograph5.png
   :target: /static/mb/lessons/seismograph5.png
   :alt: 


10.
---

Please find seismogrph experiment obervations: 

First, notice that moving the @boardname@ in any direction, you will change the acceleration value, which is being displayed as a milli-gravities value. By moving the @boardname@, there will be a changing acceleration value. 


.. image:: /static/mb/lessons/seismograph7.png
   :target: /static/mb/lessons/seismograph7.png
   :alt: 


Second, the horizontal line will move to plot the value of the strength as measured in milli-gravities. The horizontal line's movement is based on the @boardname@ acceleration in Magnitude or Strength. 


.. image:: /static/mb/lessons/seismograph6.png
   :target: /static/mb/lessons/seismograph6.png
   :alt: 


Third, notice that the LED display fluctates based on the movement of the @boardname@. 


.. image:: /static/mb/lessons/seismograph8.png
   :target: /static/mb/lessons/seismograph8.png
   :alt: 


Now we are ready to graph or chart the accceleration of the @boardname@. We want a printout of the @boardname@ acceleration graphed in Excel.

11.
---

In order to receive the the data plotted by Excel, click or tap anywhere in the on the chart data.


.. image:: /static/mb/analyze1.png
   :target: /static/mb/analyze1.png
   :alt: 


12.
---

You have two options to Analyze Data: 


* Local File: Save the data to your local Downloads folder and open it in Excel. 
* Stream to Cloud: Upload your data to Microsoft Azure to analyze it. 

Click or tap Download data


.. image:: /static/mb/lessons/seismograph9.png
   :target: /static/mb/lessons/seismograph9.png
   :alt: 


13.
---

A CSV file will be generated to display the data points collected by the @boardname@. Click or tap on the data Excel file that was downloaded to your local Downloads Folder. 


.. image:: /static/mb/lessons/analyze9.png
   :target: /static/mb/lessons/analyze9.png
   :alt: 


14.
---

Select the data that you want to include in your chart. The chart should include the first two columns: time and acceleration. 

Click or tap on the first two columns (A, B) to include time and acceleration data from the @boardname@  

15.
---

Click or tap on Insert then select Recommended Charts. We can select a chart that’s just right for the data.


.. image:: /static/mb/analyze3.png
   :target: /static/mb/analyze3.png
   :alt: 


On the Recommended Charts tab, scroll through the list of chart types that Excel recommends for your data. 

We want to select the chart called Line. A line chart is used to display trends over time. We will use the line chart because there are many data points over time. 

Click on the chart type to see how your data will look in that format. When you find the chart type that you want, click it, and then click OK. 


.. image:: /static/mb/lessons/analyze16.png
   :target: /static/mb/lessons/analyze16.png
   :alt: 


Tip: If you don’t see the line chart, click the All Charts tab to see the line chart.

16.
---

Use the Chart Elements, Chart Styles, and Chart Filters buttons next to the upper-right corner of the chart to add chart elements like axis titles or data labels, to customize the look of your chart

Alternatively, click or tap on the Design Ribbon. 

Let's select Style 10 as an example. 


.. image:: /static/mb/lessons/analyze19.png
   :target: /static/mb/lessons/analyze19.png
   :alt: 


~avatar avatar
--------------

Excellent, you're ready to continue with the `challenges </lessons/seismograph/challenge>`_

~
-

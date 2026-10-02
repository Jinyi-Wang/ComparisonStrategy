# Juxtaposition

In this part, you will compare two datasets and answer three groups of questions about the differences between them. In this design, the two datasets are shown in two neighborhoods **side by side**.

![Example of the juxtaposition visualization](comparison-method/assets/jux/test1.png)

## How to read the figure
* **Dataset A** is shown in the left neighborhood.
* **Dataset B** is shown in the right neighborhood.
* Each household in the neighborhood is represented by a box-and-whisker-like node glyph which encodes information about the households voltage measurements over time.

## How to read node glyph
* **Upper whisker** represents the maximum voltage value across all households in the neighborhood.
* **Bottom whisker** represents the minimum voltage value across all households in the neighborhood.
* **Upper box border** represents maximum voltage value for that specific household.
* **Bottom box border** represents minimum voltage value for that specific household.
* **Line in the box** represents the voltage value for a single time point or the voltage variation over a selected time period for that specific household. 
* **Vertical position:** for all of these visual elements a higher position indicates a higher voltage value, while a lower position indicates a lower voltage value.


## How to answer

Each question names a node corresponding to a household, for example **h.23**. There are three types of questions:

#### **Value questions** 
Value questions ask which dataset has the *higher* value:
<img src="comparison-method/assets/jux/node.png" alt="drawing" style="width:750px;"/>

* **Maximum / minimum voltage value across all households:** check the upper / bottom whisker, a higher position indicates a higher value, while a lower position indicates a lower value.
* **Maximum / minimum voltage value for that household:** check the upper / bottom box border, a higher position indicates a higher value, while a lower position indicates a lower value.
* **Voltage value:** check the voltage line in the box, a higher position indicates a higher value, while a lower position indicates a lower value.

*Answers: Dataset A, Dataset B, or Same.*


#### **Variation questions** 
Variation questions ask which dataset shows greater variation over time: 
<img src="comparison-method/assets/jux/variation.png" alt="drawing" style="width:550px;"/>

* **Voltage curve:** assess the degree of dispersion of each time series around its central tendency over the time period. A greater degree of dispersion indicates greater variation.

*Answers: Dataset A, Dataset B, or Same.*


#### **Range questions** 
Range questions ask which dataset has the larger range for the node, that is, the difference between the maximum and minimum voltage value for that node:
<img src="comparison-method/assets/jux/range.png" alt="drawing" style="width:600px;"/>

* **Maximum / minimum voltage value for that household:** check the difference between upper / bottom box border, larger the difference indicates larger the range.

*Answers: Dataset A, Dataset B, or Same.*

#### Note
When you are ready, select **Continue** to start the questions.

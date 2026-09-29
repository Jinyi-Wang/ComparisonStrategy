# Explicit encoding

In this part, you will compare two datasets and answer a series of questions about the differences between them. In this design, the **difference** between the two datasets is **drawn directly in the figure**.

![Example of the explicit encoding visualization](comparison-method/assets/exp/test.png)

## How to read the figure

* **The difference between Dataset B and Dataset A (B − A)** is shown in the grid as each node.
* The node symbol is a box-and-whisker symbol, but it is **fixed, faded background**, they represent a constant reference frame, not an actual data value.

## How to read symbol
**B − A** difference is shown through three separate encodings on top of that fixed symbol:
* **Line in the box** represents voltage value difference between dataset B and A, or voltage variation over time between dataset B and A. 
* **Dashed line in the box** represents the centerline of the symbol. It is fixed in the symbol and provide reference of the line position.
* **Vertical position** for the line in the box, vertical position represents the voltage difference B − A: 
  * A line above the centerline indicates B − A > 0, meaning Dataset B has a higher voltage value than Dataset A.
  * A line below the centerline indicates B − A < 0, meaning Dataset B has a lower voltage value than Dataset A.
  * The farther from the center line, the larger the absolute difference between the two datasets.
* **Left arrow:** the direction of the upper end represents the difference between B and A in maximum voltage value across all households; the direction of the bottom end represents the difference between B and A in minimum voltage value across all households.
* **Right arrow:** the direction of the upper end represents the difference between B and A in maximum voltage value for that household; the direction of the bottom end represents the difference between B and A in minimum voltage value for that household.
* **Arrow direction** indicates the the difference of B − A. Movement away from the centerline represents a positive difference \(B - A > 0\), whereas movement toward the centerline represents a negative difference \(B - A < 0\). 
  * For the upper ends of the arrows: arrow uses ▲ if B > A, ▼ if B < A, or ● if B = A.
  * For the bottom ends of the arrows: arrow uses ▼ if B > A, ▲ if B < A, or ● if B = A.
  

## How to answer

Each question names a node, for example **h.23**. There are three types of questions:

#### **Value questions** 
Ask which dataset has the *higher* value of one of these:
![Example of the explicit encoding visualization](comparison-method/assets/exp/node.png)

* **Maximum / minimum voltage value across all households:** check the upper / bottom end of left arrow. Movement away from the centerline represents a positive difference \(B - A > 0\), whereas movement toward the centerline represents a negative difference \(B - A < 0\). 
* **Maximum / minimum voltage value for that household:** check the upper / bottom end of right arrow. Movement away from the centerline represents a positive difference \(B - A > 0\), whereas movement toward the centerline represents a negative difference \(B - A < 0\). 
* **Voltage value:** check the voltage line in the box, a higher position of the line indicates a larger value of B − A, while a lower position indicates a smaller value of B − A.

*Answers: Dataset A, Dataset B, or Same.*

#### **Variation questions** 
Ask which dataset shows greater variation over time: 
<img src="comparison-method/assets/exp/variation.png" alt="drawing" style="width:500px;"/>

* **Variation line:** check the line in the box, the line above the dashed line indicates the variation of B - A > 0, while line below the dashed line indicates the variation of B - A < 0.

*Answers: Dataset A, Dataset B, or Same.*

#### **Range questions** 
Ask which dataset has the larger range for the node, that is, the difference between the maximum and minimum voltage value for that node:
<img src="comparison-method/assets/exp/range.png" alt="drawing" style="width:550px;"/>

* **Maximum / minimum voltage value for that household:** check the right arrow, two ends moving away from the centerline indicates the range is larger in Dataset B, while two ends moving toward the centerline indicates the range is smaller in Dataset B.

*Answers: Dataset A, Dataset B, or Same.*

#### Note
If anything is unclear, please read this page again. When you are ready, select **Next** to start the questions.



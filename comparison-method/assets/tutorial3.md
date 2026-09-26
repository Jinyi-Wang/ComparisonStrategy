# Explicit encoding

In this part, you will compare two datasets and answer a series of questions about the differences between them. In this design, the difference between the two datasets is **drawn directly in the figure**.

![Example of the explicit encoding visualization](comparison-method/assets/exp/node.png)

## How to read the figure

* **The difference between Dataset B and Dataset A (B − A)** is shown in the grid as each node.
* The node symbol is a box-and-whisker symbol, but it is **fixed, faded background**, they represent a constant reference frame, not an actual data value.

## How to read symbol
**B − A** difference is shown through three separate encodings on top of that fixed symbol:
* **Line in the box** represents voltage value difference between dataset B and A, or voltage variation over time between dataset B and A. 
* **Dashed in the box** represents the centerline of the symbol. It is fixed in the symbol and provide reference of the line position.
* **Vertical position:** for the line in the box, vertical position represents the voltage value: a higher position indicates a higher voltage value, while a lower position indicates a lower voltage value.
* **Left arrow:** the direction of the upper end represents the difference between B and A in maximum voltage value across all households; the direction of the bottom end represents the difference between B and A in minimum voltage value across all households.
* **Right arrow:** the direction of the upper end represents the difference between B and A in maximum voltage value for that household; the direction of the bottom end represents the difference between B and A in minimum voltage value for that household.
* **Arrow direction** indicates the the difference of B − A. Movement away from the centerline represents a positive difference (\( B - A > 0\)), whereas movement toward the centerline represents a negative difference (\(B - A < 0\)). 
  * For the upper ends of the arrows: arrow uses ▲ if B > A, ▼ if B < A, or ● if B = A.
  * For the bottom ends of the arrows: arrow uses ▼ if B > A, ▲ if B < A, or ● if B = A.
  

## How to answer

Each question names a node, for example **h.23**. There are three types of questions:

1. **Value questions** ask which dataset has the *higher* value of one of these:

    * **Maximum / minimum voltage value across all households:** check the upper / bottom end of left arrow.Movement away from the centerline represents a positive difference (\( B - A > 0\)), whereas movement toward the centerline represents a negative difference (\(B - A < 0\)). 
    * **Maximum / minimum voltage value for that household:** check the upper / bottom end of right arrow. Movement away from the centerline represents a positive difference (\( B - A > 0\)), whereas movement toward the centerline represents a negative difference (\(B - A < 0\)). 
    * **Voltage value:** check the voltage line in the box, the line above the dashed line indicates B - A > 0, while line below the dashed line indicates B - A < 0.

*Answers: Dataset A, Dataset B, or Same.*

2. **Variation questions** ask which dataset shows greater variation over time: 

* **Variation line:** check the line in the box, the line above the dashed line indicates B - A > 0, while line below the dashed line indicates B - A < 0.

*Answers: Dataset A, Dataset B, or Same.*

3. **Range questions** ask which dataset has the larger range for the node, that is, the difference between the maximum and minimum voltage value for that node:

    * **Maximum / minimum voltage value for that household:** check the right arrow, two ends moving away from the centerline indicates the range is larger in Dataset B, while two ends moving toward the centerline indicates the range is smaller in Dataset B.

*Answers: Dataset A, Dataset B, or Same.*

If anything is unclear, please read this page again. When you are ready, select **Next** to start the questions.



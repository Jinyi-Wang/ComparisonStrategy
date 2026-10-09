# Explicit encoding

In this part, you will compare two datasets and answer a series of questions about the differences between them. In this design, the **difference** between the two datasets is **computed and explicitly encoded (drawn) directly in the figure**.

<img src="comparison-method/assets/exp/test1.png" alt="drawing" style="width:800px;"/>

## How to read the figure

* Each node in the neighborhood shows **the computed difference between Dataset B and Dataset A (B − A)**.
* The node glyph includes a faded box-and-whisker-like reference glyph that does not encode data itself. It provides a consistent visual frame of reference across the visual comparison strategies. 


## How to read the glyph
**B − A** difference is shown through three separate encodings on top of that fixed node glyph:
* **Line in the box** represents the computed difference of voltage value between dataset B and A, or the computed difference of voltage variation over time between dataset B and A. 
* **Dashed line in the box** represents the centerline of the glyph. It is fixed in the glyph and provides a reference of the line position.
* **Vertical position** for the line in the box, vertical position represents the voltage difference B − A: 
  * A line above the centerline indicates B − A > 0, meaning Dataset B has a higher voltage value than Dataset A.
  * A line below the centerline indicates B − A < 0, meaning Dataset B has a lower voltage value than Dataset A.
  * The farther from the center line, the larger the absolute difference between the two datasets.
* **Left arrow:** the direction of the upper end represents the difference between B and A in maximum voltage value across all households; the direction of the bottom end represents the difference between B and A in minimum voltage value across all households.
* **Right arrow:** the direction of the upper end represents the difference between B and A in maximum voltage value for that household; the direction of the bottom end represents the difference between B and A in minimum voltage value for that household.
* **Arrow direction** indicates the difference of B − A. Upward movement represents a positive difference \(B - A > 0\), whereas downward movement represents a negative difference \(B - A < 0\). 
  * Arrow uses ▲ if B > A, ▼ if B < A, or ● if B = A.
  

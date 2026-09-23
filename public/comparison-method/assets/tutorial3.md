# Explicit encoding

In this part, you will compare two datasets and answer a series of questions about the differences between them. In this design, the comparison between the two datasets is **drawn directly in the figure**.

![Example of the explicit encoding visualization](comparison-method/assets/exp/node.png)

## How to read the figure

* **Explicit Encoding** shows a single box-and-whisker symbol per node, representing the difference between **Dataset B and Dataset A (B − A)** — not either dataset directly.
* The box-and-whisker is a **fixed, faded background symbol**, they represent a constant reference frame, not an actual data value.
* **B − A** difference is instead shown through three separate encodings layered on top of that fixed symbol:
  * **A line inside the box** — current voltage value difference between dataset B and A, or voltage variation over time between dataset B and A.
  * **A left-side arrow** — the direction of B relative to A for maximum and minimum voltage value in the whole neighborhood.
  * **A right-side arrow** — the direction of B relative to A for maximum and minimum voltage value in that household.
  * For the upper whisker and upper box border: arrow uses ▲ if B > A, ▼ if B < A, or ● if B = A.
  * For the bottom whisker and bottom box border: arrow uses ▼ if B > A, ▲ if B < A, or ● if B = A.
  


## How to answer

Each question names a node, for example **h.23**. For every question:

1. Find that node in **both** datasets.
2. Compare the two datasets for that node, as the question asks.
3. Select the answer that best matches your comparison.

Please use only the information shown in the two datasets. There are no right or wrong strategies, so take your time and answer as accurately as you can.

## The three kinds of questions

**Value questions** ask which dataset has the *higher value* of one of these:

* **Maximum / minimum voltage value in the whole neighborhood:** check the direction of left arrow.
* **Maximum / minimum voltage value in that household:** check the direction of right arrow.
* **Current voltage value:** check the current voltage line in the box.

*Answers: Dataset A, Dataset B, or Same.*

**Variation questions** ask which dataset shows *greater variation* over time.

*Answers: Dataset A, Dataset B, or Same.*

**Range questions** ask which dataset has the *larger range* for the node, that is, the difference between the maximum and minimum voltage value for that node.

*Answers: Dataset A, Dataset B, or Same.*

If anything is unclear, please read this page again. When you are ready, select **Yes** in the sidebar and click **Next**.

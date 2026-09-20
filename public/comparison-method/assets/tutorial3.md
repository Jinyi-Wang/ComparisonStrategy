# Explicit encoding

In this part, you will compare two datasets and answer a series of questions about the differences between them. In this design, the comparison between the two datasets is **drawn directly in the figure**.

![Example of the explicit encoding visualization](comparison-method/assets/exp/node.png)

## How to read the figure

* **Explicit Encoding** shows a single box-and-whisker symbol per node, representing the difference between Dataset B and Dataset A (B − A) — not either dataset directly.
* The box-and-whisker is a **fixed, faded background symbol**, they represent a constant reference frame, not an actual data value.
* B − A difference is instead shown through three separate encodings layered on top of that fixed symbol:
  * **A line inside the box** — current value difference between dataset B and A, or current value trend between dataset B and A.
  * **A left-side arrow** — the *global* maximum and minimum direction of B relative to A across the whole dataset.
  * **A right-side arrow** — the *local* maximum and minimum direction of B relative to A for that specific node.
  * For the upper whisker and upper box border: arrow uses ▲ if B > A, ▼ if B < A, or ● if B = A.
  * For the bottom whisker and bottom box border: arrow uses ▼ if B > A, ▲ if B < A, or ● if B = A.
  

## How to answer

Each question names a node, for example **h.23**. For every question:

1. Find that node in **both** datasets.
2. Compare the two datasets for that node, as the question asks.
3. Select the answer that best matches your comparison.

Please use only the information shown in the two datasets. There are no right or wrong strategies, so take your time and answer as accurately as you can.

## The three kinds of questions

**Value questions** ask which dataset has the *larger* value of one of these:

* **Maximum / minimum global** the highest / lowest value over the time period across all nodes.
* **Maximum / minimum local** the highest / lowest value over the time period for that node.
* **Current value:** current value at that timestamp.

*Answers: Dataset A, Dataset B, or Same.*

**Trend questions** ask whether the two datasets change in the same way over time, or whether Dataset B is increasing or decreasing more than Dataset A.

*Answers: Same, Dataset B is increasing more, or Dataset B is decreasing more.*

**Range questions** ask which dataset has the larger range for the node, that is, the difference between its maximum and minimum local value.

*Answers: Same, Dataset A, or Dataset B.*

If anything is unclear, please read this page again. When you are ready, select **Yes** in the sidebar and click **Next**.

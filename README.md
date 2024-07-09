# Molokai Nut Company (MNC)

The Molokai Nut Company (MNC) manufactures four different products based on macadamia nuts grown on the Hawaiian Islands: chocolate-covered whole nuts (Whole), chocolate-covered nut pieces (Cluster), crunchy nut bars coated with chocolate (Crunch), and plain roasted nuts (Roasted). The company has seen growing demand for these products. However, rising raw material prices and foreign competition are forcing MNC to pay close attention to its margins to ensure it operates as efficiently as possible.

To meet next week's demand, MNC needs to produce at least 1000 kilograms of the Whole product, between 400 and 500 kilograms of the Cluster product, no more than 150 kilograms of the Crunch product, and no more than 200 kilograms of the Roasted product.

Each kilogram of Whole, Cluster, Crunch, and Roasted contains, respectively, 60%, 40%, 20%, and 100% macadamia nuts, with the remaining weight composed of chocolate. The company has 1100 kilograms of nuts and 800 kilograms of chocolate available for use next week.

The various products are also manufactured using four different machines that shell, roast, and coat the nuts with chocolate (if necessary) and package the products. Table 1 summarizes the time required for each product on each machine. Each machine has 60 hours of available time next week.

| Machine      | Whole | Cluster | Crunch | Roasted |
|--------------|-------|---------|--------|---------|
| Shelling     | 1.00  | 1.00    | 1.00   | 1.00    |
| Roasting     | 2.00  | 1.50    | 1.00   | 1.75    |
| Coating      | 1.00  | 0.70    | 0.20   | 0.00    |
| Packaging    | 2.50  | 1.60    | 1.25   | 1.00    |

*Table 1: Minutes required per kilogram*

The operations manager recently presented to the board of directors the summarized financial data of MNC's average weekly operations from the last quarter, available in Table 2.

|                | Whole  | Cluster | Crunch | Roasted |
|----------------|--------|---------|--------|---------|
| Sales Revenue  | €5304  | €1800   | €510 | €925   |
| Variable Costs | €3296  | €1280   | €338  | €660   |
| Quantity Sold  | 1040 kg| 500 kg  | 150 kg | 200 kg  |

*Table 2: Summarized financial data of MNC's average weekly operations*

**Questions**

1) Present a linear programming model for this problem, knowing that the MNC intends to maximize profit for the next week.
2) Create a spreadsheet to model this problem and solve it using Excel Solver (other software will not be accepted)
3) Present the optimal solution in the context of the problem, as well as other information that may be relevant (give preference to illustrative tables and figures).
4) Create a sensitivity report and answer the following questions:
    a) Is the solution degenerate?  
    b) Is the solution unique?  
    c) If MNC wanted to decrease the production of any product, which would you recommend and why?  
    d) If MNC wanted to increase the production of any product, which would you recommend and why?  
    e) What resources are preventing MNC from earning more money? If it could have more of these resources, how much should it have and how much would it be willing to pay for them?  
    f) How much would MNC be willing to pay to acquire more chocolate?  
    g) If the marketing department wanted to reduce the selling price of the Whole product by €0.25, would the optimal solution change?
5) Create a table and graph that illustrate the impact on total profit of changing the time required in the packaging process for each product, making them vary between 70% and 130% of their original value, in 10% increments. Interpret the information in the resulting graph.
6) Create a table and graph that illustrate the impact on total profit of changing the availability of nuts and chocolate by varying them between 70% and 100% of their original value, in 10% increments. Interpret the information in the resulting graph.
7) Introduce some change to the given problem, so that the linear programming model presented in 1. has to be changed. It can be any change that leads, for example: i) to the inclusion of new restrictions; ii) changes in the objective function; iii) to
use of integer or binary variables; iv) the inclusion of new decision variables; v) changing the original decision variables. Some coherent change in the context of the problem is enough, multiple changes are not necessary.
    <br>
    a) Present the new model in linear programming.
    <br>
    b) Solve the new problem and present the main results (give preference to illustrative tables and figures).

# Green Company Sales Optimization

### Introduction
---
> Linear programming was first used by Leonid Kantorovich to develop a mathematical model to reduce the cost of armies expenses. Nowadays, linear programming 
> is used in a wide branch of industries, such as trasnportation, energy and manufacture; to make processes more efficient and cost efective. Green Company is 
> a seudonym for the world's largest oilfield services company with presence in more than 85 countries in the world. 

### Problem
---
> Green Company has asked us to maximize the sales of certain drill BITS of the company for the second quarter of 2019, taking into account: 
  * Sales forecast made on the first quarter of 2019
  <details>
  <summary>Forecast</summary>
  
  | **BIT Type** | **Revenue Incremental Goal/Q(%)** | **Driver**                                                                                                           |
  |:------------:|:---------------------------------:|----------------------------------------------------------------------------------------------------------------------|
  |    PDC NT    |                12%                | Focused on best-selling products after analysis and  with higher price to adress new technology                      |
  |     PDC R    |                 8%                | Focused on best-selling products after  analysis, with a expected trend increase base on forecasted activity increase |
  |      RT      |                 3%                | Set as commodity for the rest of the products                                                                        |
  |      RI      |                 1%                | Set as commodity for the rest of the products                                                                        |
  
  </details>
  
  <details>
  <summary>Definition of variables</summary>
  
 | **BIT Type** |         **Definition**        |
  |:------------:|:-----------------------------:|
  |      PDC     | Polycristaline Diamod Compact |
  |    PDC NT    |       PDC New Technology      |
  |     PDC R    |        PDC Regular Tech       |
  |      RT      |          Roller Tooth         |
  |      RI      |         Roller Insert         |                                                                       
  </details>
  
  * The available inventory of drill BITS for the second quarter of 2019
  <details>
  <summary>Available Inventory</summary>
  
  | **BIT Type** | **Size** | **Inventory Q2-2019** |
  |:------------:|:--------:|:---------------------:|
  |    PDC NT    |   16 ''  |           1           |
  |              |  12.25'' |           10          |
  |              |   8.5''  |           8           |
  |     PDC R    |   16''   |           8           |
  |              | 12 1/4'' |           10          |
  |              | 8 1/2 '' |           8           |
  |              | 6.125 '' |           8           |
  |      RI      |   26''   |           5           |
  |              |   16''   |           1           |
  |      RT      |   26''   |           1           |
  |              |   16''   |           6           |
  |              | 12 1/4'' |           2           |
  |              |   8.5''  |           2           |
  |              |  6.125'' |           6           |
  </details>
  * Mantain or increase the profit level after the optimization

### Data
---
> For the optimization problem, we gathered data for each BIT Type sales from january-2019 to march-2019. 

> Sales period January-2019
<kbd>
  <img src="img/January2019.png" 
       alt="January 2019"
       caption="Sales period January-2019"/>
</kbd>

> Sales period February-2019
<kbd>
  <img src="img/February2019.png" 
       alt="February 2019"
       caption="Sales period February-2019"/>
</kbd>

> Sales period March-2019
<kbd>
  <img src="img/March2019.png" 
       alt="March 2019"
       caption="Sales period March-2019"/>
</kbd>

### Development
---
> With the data and the forecast constraints we developed the objective function and maximize it with _Solver_ in Excel. 

> PDC NT maximization problem
<kbd>
  <img src="img/PDC_NT_Table.png" 
       alt="PDC_NT_Table"
       caption="PDC NT maximization"/>
</kbd>

> PDC R maximization problem
<kbd>
  <img src="img/PDC_R_Table.png" 
       alt="PDC_R_Table"
       caption="PDC R maximization"/>
</kbd>

> RT maximization problem
<kbd>
  <img src="img/RT_Table.png" 
       alt="RT_Table"
       caption="RT maximization"/>
</kbd>

> RI maximization problem
<kbd>
  <img src="img/RI_Table.png" 
       alt="RI_Table"
       caption="RI maximization"/>
</kbd>

### Results per BIT Type
---
> Once the linear model was optimized, we analyzed the result for each BIT type

> PDC NT Results
* Sales increased 20.5%
* Groos Net increased 20.6%
* Profit increase 0.01%

<kbd>
  <img src="img/Results_PDC_NT.png" 
       alt="PDC_NT_Results"
       caption="PDC NT Result"/>
</kbd>

> PDC R Results
* Sales increased 11.4%
* Gross Net increased 11.4%
* Profit increased 0.01%

<kbd>
  <img src="img/Results_PDC_R.png" 
       alt="PDC_R_Results"
       caption="PDC R Result"/>
</kbd>

> RT Result
* Sales, gross net and profit mantained at the same level fulfilling the company's objective

<kbd>
  <img src="img/Results_RT.png" 
       alt="RT_Results"
       caption="RT Result"/>
</kbd>

> RI Result
* Sales, gross net and profit mantained at the same level fulfilling the company's objective

<kbd>
  <img src="img/Results_RI.png" 
       alt="RI_Results"
       caption="RI Result"/>
</kbd>

### Global Results
---

> Once we analyzed the result for each BIT type, we made graphs and calculate percentages to observe the global result of the maximization problem. 

> Sales and Gross Net final results

<kbd>
  <img src="img/Sale_Gross_Net_Results.png" 
       alt="Sale_Gross_Net_Results"
       caption="Sales and Gross Net Result"/>
</kbd>

> Quantities final sales

<kbd>
  <img src="img/Quantities_Result.png" 
       alt="Quantities_Results"
       caption="Quantities Result"/>
</kbd>

> Final results 

<kbd>
  <img src="img/Final_results.png" 
       alt="Final_Results"
       caption="Final Result"/>
</kbd>

### Conclusion
---
> With the help of _Solver_ in Excel we maximized Green Company sales subject to the forecast constraints and the company available inventory, increasing 
> sales by 11.7% and gross net by 11.8%. This proves how linear programming can be usefull for improving companies sales, process and cost.

> Sales and Gross Net final results

<kbd>
  <img src="img/Final_results_2.png" 
       alt="Final_Results"
       caption="Final Result"/>
</kbd>

<kbd>
  <img src="img/Final_results_3.png" 
       alt="Final_Results"
       caption="Final Result"/>
</kbd>

### Recomendations
---
> Taking into account the results from the maximization problem, we will recommend the company:
* Increase the available inventory
  * By increasing the available inventory, Green Company could increase their sales and generate a higher profit
* Innovate RT and RI
  * RT and RI are BIT's that are _old_ in term of technology. For this reason, Gree Company is not interested in increasing its sales but maintaining them. 
  * A better solution will be to innovate and adapt them to the _new_ technology which could improve the performace and efficiency of the BIT at drilling. This improvement
  * could increase the demand of the BIT on the market at thus increase Green Company sales
* Focus on PDC NT
  * Since new technology is always more efficient than old, Green Company should focus on PDC NT to increase its demand in the market, but without leaving aside
  * PDC R that even thought is regular technology, it is the most demanded BIT on the market.






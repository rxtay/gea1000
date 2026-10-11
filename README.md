# GEA1000 Project

|       | **YearReleased** | **NASales** | **EUSales** | **JapanSales** | **OtherSales** | **GlobalSales** | **Usedprice** | **ReviewScore** | **MaxPlayers** |
| ----- | ---------------- | ----------- | ----------- | -------------- | -------------- | --------------- | ------------- | --------------- | -------------- |
| count | 1754.000         | 1754.000    | 1754.000    | 1754.000       | 1754.000       | 1754.000        | 1754.000      | 1754.000        | 1754.000       |
| mean  | 2007.361         | 0.506       | 0.289       | 0.094          | 0.107          | 0.996           | 19.443        | 68.375          | 1.662          |
| std   | 1.362            | 1.138       | 0.854       | 0.448          | 0.252          | 2.513           | 7.512         | 13.897          | 1.237          |
| min   | 2004.000         | 0.010       | 0.000       | 0.000          | 0.000          | 0.010           | 4.950         | 12.000          | 1.000          |
| 25%   | 2006.000         | 0.100       | 0.000       | 0.000          | 0.010          | 0.140           | 14.950        | 60.000          | 1.000          |
| 50%   | 2007.000         | 0.200       | 0.030       | 0.000          | 0.030          | 0.340           | 17.950        | 70.000          | 1.000          |
| 75%   | 2008.000         | 0.460       | 0.270       | 0.020          | 0.100          | 0.900           | 19.950        | 79.000          | 2.000          |
| max   | 2010.000         | 15.850      | 12.880      | 6.500          | 3.310          | 35.830          | 49.950        | 98.000          | 8.000          |

![image.png](/assets/image.png)

![image.png](/assets/image%201.png)

- All five sales distributions are positively skewed, with relatively few games achieving exceptionally high sales.
- GlobalSales and NASales have more widely spread distributions than JapanSales and OtherSales on the transformed scale.
- JapanSales has a particularly large concentration at zero; this suggests that many games did not achieve recorded sales in the Japanese market.
- The log transformation reduces the influence of extreme values on the horizontal scale; this makes the distributions easier to examine while preserving substantial right-skewness.

| Category               | **Frequency** | **Proportion (%)** |
| ---------------------- | ------------- | ------------------ |
| The worst of the worst | 4             | 0.23               |
| Generally unfavourable | 170           | 9.69               |
| Mixed/average          | 941           | 53.65              |
| Generally favourable   | 578           | 32.95              |
| Universally acclaimed  | 61            | 3.48               |

![image.png](/assets/image%202.png)

![image.png](/assets/image%203.png)

![image.png](/assets/image%204.png)

|            | **NASales** | **EUSales** | **JapanSales** |
| ---------- | ----------- | ----------- | -------------- |
| NASales    | 1.000       | 0.894       | 0.646          |
| EUSales    | 0.894       | 1.000       | 0.709          |
| JapanSales | 0.646       | 0.709       | 1.000          |

$$
EUSales =0.671(NASales)-0.050 \\
JapanSales =0.254(NASales)-0.034 \\
JapanSales =0.371(EUSales)-0.013
$$

![image.png](/assets/image%205.png)

| **Action-related** | **Non First Person** | **First Person** | **Total** |
| --- | --- | --- | --- |
| False | 519 | 168 | 687 |
| True | 812 | 255 | 1067 |
| **Total** | **1331** | **423** | **1754** |

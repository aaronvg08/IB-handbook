Outliers in [[Statistics|statistics]] are values that are far off from the usual set. They are usually caused by random environment issues or controlled variables after failing to be controlled.

![[outliers.png|center|500]]

In order to identify outliers mathematically, you can use the following formulas. They will give you a set of intervals where, if there's any value outside of them, it's an outlier.

$$
\text{Out}_{\text{min}}=\text{Q1}-1.5\cdot\text{IQR}
$$
$$
\text{Out}_{\text{max}}=\text{Q3}-1.5\cdot\text{IQR}
$$
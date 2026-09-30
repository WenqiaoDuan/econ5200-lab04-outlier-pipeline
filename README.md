# econ5200-lab04-outlier-pipeline
# Outlier Detection on California Housing

## Objective

I analyzed the California Housing dataset to identify outliers using three different methods and determine which method was most suitable for the analysis.

## Methodology

* I diagnosed and fixed three bugs in an outlier-detection pipeline.
* I used an `OutlierDetector` class with three methods: Modified Z-score, Tukey fences, and Isolation Forest.
* I checked the settings of each method and used the `summary()` method to report the results.
* I applied the Modified Z-score and Tukey fence methods to the `MedInc` variable.
* I applied Isolation Forest to all 9 columns.
* I compared the outliers identified by the three methods.
* I wrote a method-selection memo and recommended the Isolation Forest method.
* I built an interactive explorer to compare the three outlier-detection methods.

## Key Findings

* The Modified Z-score method flagged **400** outliers in `MedInc`.
* The Tukey fence method flagged **681** outliers in `MedInc`.
* Isolation Forest flagged **1,032** outliers using all 9 columns.
* All three methods agreed on **322** outliers.
* Based on my comparison of the methods, I recommended the **Isolation Forest method**.

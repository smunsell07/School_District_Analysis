# School District Analysis

## Overview of the School District Analysis

The chief data scientist for the PyCity School District, Maria, has provided all the district's standardized test data for analysis, reporting, and presentation. She would like insights about performance trends and patterns to inform discussions and strategic decisions at the school and district level. Some of the test data has been compromised and is unreliable. Specifically, the ninth grade math and reading scores from Thomas High School are no longer able to be used in the analysis. This report details how the data outcomes have been affected.

## Results 
* How is the district summary affected?

The modified and original district summaries can be seen below. The unusable data from Thomas High School ninth grade has essentially left the district summary unchanged.
![district_summary_DataFrame](resources/district_summary_DataFrame.png)
![district_summary_DataFrame_orig](resources/district_summary_DataFrame_orig.png)

* How is the school summary affected?

Below is the full modified school summary followed by the specific outcomes of Thomas High School (the only school affected) before and after the unusable data was replaced. 
![school_summary_DataFrame_1](resources/school_summary_DataFrame_1.png)
![school_smmary_DataFrame_2](resources/school_summary_DataFrame_2.png)
![school_summary_DataFrame_THS_orig](resources/school_summary_DataFrame_THS_orig.png)
![school_summary_DataFrame_THS](resources/school_summary_DataFrame_THS.png)

* How does replacing the ninth graders' math and reading scores affect Thomas High School's performanced relative to other schools?

As can be seen, the math, reading, and overall percentages have dipped below passing for Thomas High School. This has dropped the school from second in overall passing rates to eighth.
![THS_affect_orig](resources/THS_affect_orig.png)
![THS_affect](resources/THS_affect.png)
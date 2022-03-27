# School District Analysis

## Overview of the School District Analysis

The chief data scientist for the PyCity School District, Maria, has provided all the district's standardized test data for analysis, reporting, and presentation. She would like insights about performance trends and patterns to inform discussions and strategic decisions at the school and district level. Some of the test data has been compromised and is unreliable. Specifically, the ninth grade math and reading scores from Thomas High School are no longer able to be used in the analysis. This report details how the data outcomes have been affected.

## Results 
* How is the district summary affected?

The modified and original district summaries can be seen below. The unusable data from Thomas High School ninth grade has essentially left the district summary unchanged.
![district_summary_DataFrame](resources/district_summary_DataFrame.png)
![district_summary_DataFrame_orig](resources/district_summary_DataFrame_orig.png)

* How is the school summary affected?

Below is the full modified school summary followed by the specific outcomes of Thomas High School (the only school affected) before and after the unusable data was replaced with NaN.
![school_summary_DataFrame_1](resources/school_summary_DataFrame_1.png)
![school_smmary_DataFrame_2](resources/school_summary_DataFrame_2.png)
![school_summary_DataFrame_THS_orig](resources/school_summary_DataFrame_THS_orig.png)
![school_summary_DataFrame_THS](resources/school_summary_DataFrame_THS.png)

* How does replacing the ninth graders' math and reading scores affect Thomas High School's performanced relative to other schools?

As can be seen below, the math, reading, and overall percentages have dipped below the passing mark for Thomas High School. This has dropped the school from second in overall passing rates to eighth.
![THS_affect_orig](resources/THS_affect_orig.png)
![THS_affect](resources/THS_affect.png)

* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
    * Scores by school spending
    * Scores by school size
    * Scores by school type

*Math and Reading Scores by Grade* The Thomas High School ninth grade math and reading scores were the only ones affected as seen below. The original math and reading scores were replaced by Nan, or null, which means no score is being recorded.

Math scores by grade, before and after replacement:
![math_by_grade_orig](resources/math_by_grade_orig.png)![math_by_grade](resources/math_by_grade.png)

Reading scores by grade, before and after replacement:
![reading_by_grade_orig](resources/reading_by_grade_orig.png)![reading_by_grade](resources/reading_by_grade.png)

*Scores by School Spending* The scores by school spending before and after replacement are as follows:
![spend_orig](resources/spend_orig.png)![spend](resources/spend.png)

Thomas High School falls in the $630-$644/student spending range. The scores by school spending were affected slightly in the $630-$644 range, however, after rounding the percentages to the nearest ones place, the scores by school spending are unchanged.

*Scores by School Size* The scores by school size before and after replacement are as follows:
![size_orig](resources/size_orig.png)![size](resources/size.png).Thomas High School is defined as a medium size school. As with the school spending, the scores by school size were affected slightly in this range. However, after rounding, the scores were unchanged.

*Scores by School Type* The scores by school type before and after replacement are as follows:![type_orig](resources/type_orig.png)![type](resources/type.png)

Thomas High School is a charter school. Similar to the size and spending categories, after rounding to the ones place, the scores were unchanged by the score replacement.

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. Thomas High School's overall passing rate changed from 91% to 65%.
2. The significant change in overall passing percentage dropped the school's ranking from 2nd to 8th as compared to other campuses in the district.
3. The reading and math scores from Thomas High School's ninth graders show NaN which provides no data for any one looking at the report.
4. The campus reading and math averages shifted slightly in addition to the overall, math, and reading passing rates. 

The larger district data views were minorly impacted as compared to the campus data.




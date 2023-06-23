---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 4.5 Expectation
parent_type: CourseSection
parent_uid: 025c498f-3f5e-1c53-924f-7e40eb06a220
title: 4.5 Expectation
uid: 90fda877-efb6-3e46-64c0-2e2391cf24bc
---

*   {{% resource_link 806a4693-2318-694a-48c3-8ec44933fcaf "\<Great Expectations" %}}
*   {{% resource_link 025c498f-3f5e-1c53-924f-7e40eb06a220 "4.5.1Expectation: Video" %}}
*   {{% resource_link f42ae4d8-9239-286f-9b72-3890b787a4ed "4.5.2Uneven Dice" %}}
*   {{% resource_link 264ec427-1e9b-f721-357f-6e77d50cabc6 "4.5.3Expected Number Of Heads: Video" %}}
*   {{% resource_link 58e8b630-1c49-1570-2379-740ba37f4560 "4.5.4Expected Number of Heads" %}}
*   {{% resource_link b48a4b28-6073-ca8e-d6f8-798aa6cc7b8c "4.5.5Total Expectation: Video" %}}
*   {{% resource_link 0f03efb4-df2a-6db6-0c1e-d631add97393 "4.5.6Another Dice and Coin Game" %}}
*   {{% resource_link 55648eb4-2206-ad2f-d86d-f7a74b886ba5 "4.5.7Mean Time to Failure: Video" %}}
*   {{% resource_link 0478e0a1-b67b-68a3-d605-fa5a1211c5c2 "4.5.8Three Machines Failing" %}}
*   {{% resource_link 726b3c5f-6c9f-3677-6c3f-c0f1fc6c579a "4.5.9Linearity of Expectation: Video" %}}
*   {{% resource_link 227b2e2a-0866-9a2d-a0e7-3f27da222929 "4.5.10Fair and Biased Coins" %}}
*   {{% resource_link e211decc-ac95-15d4-9ceb-30e7a41528a9 "4.5.11Binomial Board Breaking" %}}
*   {{% resource_link 806a4693-2318-694a-48c3-8ec44933fcaf "4.5.12Great Expectations" %}}
*   {{% resource_link 90fda877-efb6-3e46-64c0-2e2391cf24bc "4.5.13Expectation of a Uniform Distribution" %}}
*   {{% resource_link f195ee84-9b9a-ee3c-cf61-f90bea10cebb "\>Deviation: Markov & Chebyshev Bounds" %}}

Expectation of a Uniform Distribution
-------------------------------------

Let \\(X\\) be a random variable with uniform distribution over the integers from \\(-n\\) to \\(n\\). Let \\(Y := X^2\\).

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(E\[X\] = 0\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;\\(E\[Y\] = 0\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;\\(E\[Y\] > E\[X\]\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;\\(E\[X+Y\] = E\[X\]+E\[Y\]\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(E\[XY\] = E\[X\]E\[Y\]\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;\\(X\\) and \\(Y\\) are independent variables&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;\\(E\[Y^2\] = E\[Y\]\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}1.  Since \\(PDF\_X(x)\\) is symmetric around 0, we know the mean has to be 0.
2.  All values of \\(Y\\) are nonnegative and most of them are actually positive with non-zero probability. There is no way for the mean to be 0. It has to be some positive value.
3.  Obvious, since \\(E\[X\]=0\\) and \\(E\[Y\]>0\\).
4.  True by linearity of expectation, no matter what \\(X\\) and \\(Y\\) are.
5.  This is tricky. The equation does not hold in general for non-independent \\(X\\) and \\(Y\\). However, in this particular case, it happens to hold. To see this, note that the right hand side is 0, since \\(E\[X\]=0\\). At the same time, the random variable \\(XY=X^3\\). Its PDF is symmetric around 0, so its mean must be 0 as well.
6.  \\(X\\) and \\(Y\\) are obviously not independent.
7.  \\(E\[Y\]=\\sum\_{i=0}^n 2i^2\\frac{1}{2n+1} \< \\sum\_{i=0}^n 2i^4\\frac{1}{2n+1} = E\[Y^2\]\\).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link 806a4693-2318-694a-48c3-8ec44933fcaf "BackGreat Expectations" %}}
*   {{% resource_link f195ee84-9b9a-ee3c-cf61-f90bea10cebb "ContinueDeviation: Markov & Chebyshev Bounds" %}}
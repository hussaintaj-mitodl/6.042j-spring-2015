---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 1.2 Proof Methods
parent_type: CourseSection
parent_uid: 604f8e07-2680-3e77-8aac-7885f0f6eaf0
title: 1.2 Proof Methods
uid: 62bbb99c-a9ee-dcc2-6f2b-179d17f08907
---

*   {{% resource_link 4ffc0201-99af-966d-3433-5699386f1e96 "\<Friends and Strangers" %}}
*   {{% resource_link 604f8e07-2680-3e77-8aac-7885f0f6eaf0 "1.2.1Proof By Contradiction: Video" %}}
*   {{% resource_link 085afa70-42da-2b6c-fb59-640ad14b8297 "1.2.2Proof By Contradiction" %}}
*   {{% resource_link 352e6518-0068-3c82-2398-9a1643662d4c "1.2.3Proof By Cases: Video" %}}
*   {{% resource_link 61e20f75-1cbf-4ed1-6f13-c3626b49e8f3 "1.2.4When to Prove by Cases" %}}
*   {{% resource_link 4ffc0201-99af-966d-3433-5699386f1e96 "1.2.5Friends and Strangers" %}}
*   {{% resource_link 62bbb99c-a9ee-dcc2-6f2b-179d17f08907 "1.2.6A Bogus Proof by Cases" %}}
*   {{% resource_link 93b788b4-e73b-5932-f1e8-4ff4cd792ad8 "1.2.7A Bogus Proof by Contradiction" %}}
*   {{% resource_link 93b788b4-e73b-5932-f1e8-4ff4cd792ad8 "\>A Bogus Proof by Contradiction" %}}

A Bogus Proof by Cases
----------------------

  

Which step(s) contain the logical error?

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;This proof is by case analysis.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; There are two cases:

**Case 1**: _\\(a\\) is positive._

**Case 2**: _\\(a\\) is negative._

&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; One of these cases must always hold, because an integer is either positive or negative. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;**Case 1**: Suppose \\(a\\) is positive. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Since \\(a\\) is an integer, we must have that \\(a\\geq 1\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Hence, \\(2a^2 = 2a\\cdot a \\geq 2a\\cdot 1 > a\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; This implies the claim holds in Case 1. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;**Case 2**: Suppose \\(a\\) is negative. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Since \\(a\\) is an integer, we must have that \\(a\\leq -1\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Hence, \\(2a^2 \\geq 2\\cdot (-1\\cdot -1) = 2 > -1 \\geq a\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; This implies the claim holds in Case 2. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; The claim therefore holds in both cases. \\(\\blacksquare\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Explanation

These two cases are NOT exhaustive, they leave out the case where \\(a=0\\), in which case \\(2a^2=2\\cdot 0^2=0=a\\).

Line 2 is not logically erranous because saying "There are two cases" implies the existence of **at least** two cases.

Line 3 claims that those are the ONLY two cases, and is therefore incorrect.

You should note that this proof can easily be modified to prove the correct claim that for any integer \\(a\\), \\(2a^2 \\geq a\\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link 4ffc0201-99af-966d-3433-5699386f1e96 "BackFriends and Strangers" %}}
*   {{% resource_link 93b788b4-e73b-5932-f1e8-4ff4cd792ad8 "ContinueA Bogus Proof by Contradiction" %}}
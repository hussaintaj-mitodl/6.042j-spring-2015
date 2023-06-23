---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 1.10 Recursive Definition
parent_type: CourseSection
parent_uid: dc6ecd4f-10b9-4f9f-9744-a385e4bab210
title: 1.10 Recursive Definition
uid: 07b69d15-ceb4-77f3-20ed-fe861b5c21fc
---

*   {{% resource_link dc6ecd4f-10b9-4f9f-9744-a385e4bab210 "\<Recursive Definition" %}}
*   {{% resource_link dc6ecd4f-10b9-4f9f-9744-a385e4bab210 "1.10.1Recursive Data: Video" %}}
*   {{% resource_link 07b69d15-ceb4-77f3-20ed-fe861b5c21fc "1.10.2Matching Parentheses" %}}
*   {{% resource_link fdcfb358-e60e-4cb1-9117-16fffe96f2dc "1.10.3Functions of F18" %}}
*   {{% resource_link 4d13ab6c-1f82-b729-3b6c-5d3cde131d62 "1.10.4Structural Induction: Video" %}}
*   {{% resource_link 85a5d448-503d-ca4e-ab98-376d8f3a64dc "1.10.5Structural Induction: Definition" %}}
*   {{% resource_link 1674b24a-caef-1bd9-9db9-d98134454ea8 "1.10.6Counting Cases" %}}
*   {{% resource_link 80a90ec9-826e-9f36-96ce-5b09a2a47a1d "1.10.7Recursive Functions: Video" %}}
*   {{% resource_link fdcfb358-e60e-4cb1-9117-16fffe96f2dc "\>Functions of F18" %}}

Matching Parentheses
--------------------

  
{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;No string in \\(M\\) can start with a right parenthesis.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Every string in \\(M\\) must start with a left parentheses.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;\\(M\\) is an infinite set.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;Every string in \\(M\\) must have even length. &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}For any string of length greater than \\(0\\), if it starts with a right parenthesis, it is immediately unmatched. The empty string also vacuously satisfies this statement.

The empty string is a counterexample.

There are a variety of ways to show \\(M\\) is infinite. For example, for any proposed longest string, simply append "()" to the end.

In order for a string to be matched, its length must be a multiple of 2, for pairs of left and right parentheses. Note that the empty string has length 0 which is also even.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link dc6ecd4f-10b9-4f9f-9744-a385e4bab210 "BackRecursive Definition" %}}
*   {{% resource_link fdcfb358-e60e-4cb1-9117-16fffe96f2dc "ContinueFunctions of F18" %}}
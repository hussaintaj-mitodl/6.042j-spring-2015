---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 1.8  Induction
parent_type: CourseSection
parent_uid: 5179d7c0-c3f7-a60a-33d7-c24d9d219172
title: 1.8  Induction
uid: 253ab197-eaf3-519a-13ef-cb16953f03b0
---

*   [\<Strong vs Ordinary Induction vs WOP \[optional\]]({{< baseurl >}}/pages/proofs/tp4-1/vertical-b16ab258826d)
*   {{% resource_link 5179d7c0-c3f7-a60a-33d7-c24d9d219172 "1.8.1Induction: Video" %}}
*   {{% resource_link 5c7eefc2-aa74-f435-dfec-3b66a4c02648 "1.8.2Bogus Induction: Video" %}}
*   {{% resource_link 6d413e3e-b440-3af3-a219-81e485215c1b "1.8.3Same Colored Horses" %}}
*   {{% resource_link e659ea46-e05d-a013-4891-d46568748b97 "1.8.4Strong Induction: Video" %}}
*   {{% resource_link 4321e156-8199-9df6-f538-8c7a19aa954a "1.8.5Unstacking Game Score" %}}
*   [1.8.6WOP vs Induction: Video \[optional\]]({{< baseurl >}}/pages/proofs/tp4-1/vertical-98aa517cd42e)
*   [1.8.7Strong vs Ordinary Induction vs WOP \[optional\]]({{< baseurl >}}/pages/proofs/tp4-1/vertical-b16ab258826d)
*   {{% resource_link 253ab197-eaf3-519a-13ef-cb16953f03b0 "1.8.8Induction by n+3" %}}
*   {{% resource_link dad01cbe-c80c-4126-95e9-b6ec587ed583 "1.8.9Induction Rules" %}}
*   {{% resource_link 204cc8ce-9c42-a967-c8a9-370e652616a2 "1.8.10Postage by Induction" %}}
*   {{% resource_link c5ce275b-3e72-b2a0-8993-6e67ebcb3ea0 "1.8.11A Bogus Induction" %}}
*   {{% resource_link dad01cbe-c80c-4126-95e9-b6ec587ed583 "\>Induction Rules" %}}

Induction by n+3
----------------

  

Alice wants to prove by induction that predicate \\(P\\) holds for certain nonnegative integers. She has proven that for all nonnegative integers \\(n = 0,1,2,3\\ldots \\)  
  

\\(P(n) \\text{ IMPLIES } P(n+3)\\).

1.  Suppose Alice also proves that \\(P(5)\\) holds. Which of the following propositions can she infer? The universe of discourse for \\(n\\) is the nonnegative integers.{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(P(n)\\) holds for all \\(n \\geq 5 \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(P(3n)\\) holds for all \\(n \\geq 5 \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(P(n)\\) holds for \\(n = 8, 11, 14, \\ldots \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(P(n)\\) does not hold for \\(n \\leq 4 \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(\\forall n.\\; P(3n + 5) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(\\forall n > 2.\\; P(3n - 1) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(P(0) \\text{ IMPLIES } \\forall n.\\; P(3n + 2) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(P(0)\\text{ IMPLIES }\\forall n. P(3n) \\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(P\\) will be true on 5 and all numbers that are greater by a multiple of 3. That is, 5, 8, 11, 14, etc. This is exactly what answer (5) says. Answers (3) and (6) talk of the same sequence except number 5, so they are still propositions that Alice can infer, although not the strongest possible. Answer (8) is also a valid conclusion: if Alice knows \\(P\\) is true on 0, she knows it will also be true on 3, 6, 9, etc.; so, it will be true on all multiples of 3 (note that the truth of \\(P\\) on 5 is not relevant here).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  Which of the following could Alice prove in order to conclude that \\(P(n)\\) holds for all \\(n \\geq 5\\)?{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P(0)\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(P(5)\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(P(5) \\text{ and } P(6)\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(P(0), P(1), \\text{ and } P(2)\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(P(5), P(6), \\text{ and } P(7)\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(P(2), P(4), \\text{ and } P(5)\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(P(2), P(4), \\text{ and } P(6)\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(P(3), P(5), \\text{ and } P(7)\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}Once Alice proves \\(P(5), P(6), \\text{ and } P(7)\\), she can conclude that \\(P(n)\\) holds for all \\(n \\ge 5\\). \\(P(5), P(6), \\text{ and } P(7)\\) can also follow from proving \\(P\\) of any three nonnegative intergers, up to 7, that leave remainders on division by 3 as 0, 1, and 2.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackStrong vs Ordinary Induction vs WOP \[optional\]]({{< baseurl >}}/pages/proofs/tp4-1/vertical-b16ab258826d)
*   {{% resource_link dad01cbe-c80c-4126-95e9-b6ec587ed583 "ContinueInduction Rules" %}}
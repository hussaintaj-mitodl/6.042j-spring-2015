---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 1.3 Well Ordering Principle
parent_type: CourseSection
parent_uid: 376535e1-bbaf-1919-fdc3-bdd7b7043dea
title: 1.3 Well Ordering Principle
uid: 741f3260-8193-4295-dbbc-bb664f773ab7
---

*   {{% resource_link 1d2f445c-bc60-b397-ff61-397004f8db62 "\<Well Ordering Principle - Examples" %}}
*   {{% resource_link 376535e1-bbaf-1919-fdc3-bdd7b7043dea "1.3.1Well Ordering Principle 1: Video" %}}
*   {{% resource_link 0c28bcd2-9489-4bf0-d41a-8f8844365509 "1.3.2Domain for Well Ordering Principle" %}}
*   {{% resource_link ce296ec8-3514-e093-cadf-682b4da32586 "1.3.3Well Ordering Principle 2: Video" %}}
*   {{% resource_link 6560768e-86c3-cf93-f8bc-271ce4082b77 "1.3.4Well Ordering Proofs and Counterexamples" %}}
*   {{% resource_link 31d41b21-bc2a-9aee-e3ff-73e0e968501d "1.3.5Well Ordering Principle 3: Video" %}}
*   {{% resource_link dc6369eb-4657-ab61-8c48-08862bf7c80f "1.3.6WOP Proof for Geometric Sum" %}}
*   {{% resource_link 1d2f445c-bc60-b397-ff61-397004f8db62 "1.3.7Well Ordering Principle - Examples" %}}
*   {{% resource_link 741f3260-8193-4295-dbbc-bb664f773ab7 "1.3.8A Bogus Well Ordering Principle Proof" %}}
*   {{% resource_link 8de160a9-e729-9f7f-ec8a-58aef5106eef "\>Logic & Propositions" %}}

A Bogus Well Ordering Principle Proof
-------------------------------------

  

The Fibonacci numbers

\\(0, 1, 1, 2, 3, 5, 8, 13, \\ldots \\)

are defined as follows. Let \\(F(n)\\) be the \\(n^{th}\\) Fibonacci number. Then

*   \\(F(0) ::= 0\\)
*   \\(F(1) ::= 1\\)
*   \\(F(n) ::= F(n-1) + F(n-2), \\;\\; \\text{ for } n \\geq 2 \\text{ } (\\star)\\)

* * *

  

Identify which step(s) contain the logical error!

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; The proof is by the WOP. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Let \\(Even(n)\\) mean that \\(F(n)\\) is even. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Let \\(C\\) be the set of counterexamples to the assertion that \\(Even(n)\\) holds for all \\(n \\geq 0\\). That is

\\(C ::=\\{n \\geq 0 \\;|\\; \\text{NOT}(Even(n))\\}\\)

We prove by contradiction that \\(C\\) is empty. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Assume that \\(C\\) is not empty. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; By the WOP, there is a least nonnegative integer, \\(m \\in C\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Then \\(m \\geq 0\\), since \\(F(0) = 0\\) is an even number. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Now, suppose \\(m \\geq 2\\) so the definition \\((\\star)\\) of \\(F(m)\\) applies. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; In this case, both \\(F(m-1)\\) and \\(F(m-2)\\) are both even, since \\(m\\) is the minimum counterexample such that \\(F(m)\\) is not even. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; But by \\((\\star)\\) in the case that \\(n = m\\), we see that \\(F(m)\\) is the sum of two even numbers, so it is also even; thus \\(Even(m)\\) is true. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; This deduction contradicts the condition in the definition of \\(m\\) that \\(\\text{NOT}(Even(m))\\) is true. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; This contradiction implies that \\(C\\) must be empty. Hence, \\(F(n)\\) is even for all \\(n \\geq 0.\\;\\;\\blacksquare\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Steps 1 through 10 contain no logical errors. The fatal flaw is in the final step 11. The proof only shows that there is a minimum \\(m\\) in \\(C\\) and it is not 0. The assumption that \\(m \\geq 2\\) leads to a contradiction; it leaves the case \\(m = 1\\) unexamined, while in fact, \\(1 \\in C\\). (The supposition that "\\(m \\geq 2\\) so the definition (\*) of \\(F(m)\\) applies" is no excuse for ignoring the case \\(m = 1\\).)

If you said that step 7 contains a logical error, you were on the right track. The natural place to handle the case \\(F(1)\\) would have been right after step 6. But the the proof explicitly avoided the case \\(m = 1\\), by saying, "suppose \\(m \\geq 2\\)." However, there is no _logical_ error in line 7: it is simply the beginning of a proof for the case when \\(m \\geq 2\\). On the other hand, it's reasonable to say that line 7 is the place where the proof makes an organizational, or perhaps strategic, error because it skips the \\(m = 1\\) case.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link 1d2f445c-bc60-b397-ff61-397004f8db62 "BackWell Ordering Principle - Examples" %}}
*   {{% resource_link 8de160a9-e729-9f7f-ec8a-58aef5106eef "ContinueLogic & Propositions" %}}
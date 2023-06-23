---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 1.9  State Machines - Invariants
parent_type: CourseSection
parent_uid: 470546ac-8124-6c93-8505-a0f7571765aa
title: 1.9  State Machines - Invariants
uid: bd55b53d-c54b-1a4a-4c52-a30e9c3119d3
---

*   {{% resource_link 44f9694e-dcc7-c2cd-211f-ed7a017efdc6 "\<Derived Variables and Termination" %}}
*   {{% resource_link 470546ac-8124-6c93-8505-a0f7571765aa "1.9.1State Machines Invariants: Video" %}}
*   {{% resource_link c9c18fad-0944-7554-62d1-010531375954 "1.9.2State Machine Invariants" %}}
*   {{% resource_link 783b1ae0-b2ad-6045-34d3-f48ce92854c0 "1.9.3Derived Variables: Video" %}}
*   {{% resource_link 44f9694e-dcc7-c2cd-211f-ed7a017efdc6 "1.9.4Derived Variables and Termination" %}}
*   {{% resource_link bd55b53d-c54b-1a4a-4c52-a30e9c3119d3 "1.9.5Integer Multiplication" %}}
*   {{% resource_link 00863914-a78e-473a-cade-704c69bead8e "1.9.6Chocolate Bars" %}}
*   {{% resource_link 00863914-a78e-473a-cade-704c69bead8e "\>Chocolate Bars" %}}

Integer Multiplication
----------------------

  

Suppose that the following procedure is used to multiply two non-negative integers _a_ and _b_.

*   \\(x ::= a\\)
*   \\(y ::= b\\)
*   \\(p ::= 0\\)

Repeat the following commands:

*   if \\(x = 0\\), then output \\(p\\) and terminate; else
*   if \\(x\\) is even, then set \\(x \\leftarrow x/2\\) and \\(y \\leftarrow 2y\\); else
*   if \\(x\\) is odd, then set \\(x \\leftarrow x - 1\\) and \\(p \\leftarrow p + y\\).

  

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(xy = p\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(xy = ab\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(xy + p = ab\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(xyp = ab\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}Predicates (1), (2), and (4) are preserved by the second command of the algorithm, but not necessarily by the third command. Predicate (3) is preserved by both commands. In the second command, the product \\(xy\\) remains the same and so does \\(p\\), so the sum keeps its old value. In the third command, the product \\(xy\\) decreases by \\(y\\) and \\(p\\) increases by \\(y\\), so the sum again keeps its old value.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(x\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(xy\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(p - y\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(x + p\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every transition, \\(x\\) is either halved or reduced by 1, so it is strictly decreasing. In contrast, \\(xy\\) either remains the same or reduces by \\(y\\), so it is weakly decreasing. \\(p-y\\) and \\(x+p\\) may each decrease or increase.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link 44f9694e-dcc7-c2cd-211f-ed7a017efdc6 "BackDerived Variables and Termination" %}}
*   {{% resource_link 00863914-a78e-473a-cade-704c69bead8e "ContinueChocolate Bars" %}}
---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 3.2 Asymptotics
parent_type: CourseSection
parent_uid: 7fcb0761-6e29-48a6-ad10-caa832263c78
title: 3.2 Asymptotics
uid: 2b8275cb-f5d7-304c-3775-80b64cb09fc8
---

*   {{% resource_link c4f72171-1e9e-ed96-b6f2-319be0d10496 "\<Practice with Big O" %}}
*   {{% resource_link 7fcb0761-6e29-48a6-ad10-caa832263c78 "3.2.1Asymptotic Notation: Video" %}}
*   {{% resource_link 7ce8643e-34ad-237e-8704-bca116ee1c91 "3.2.2Asymptotics as Relations" %}}
*   {{% resource_link f5736212-af2c-ef40-8c06-bbea00eb25c6 "3.2.3Asymptotic Properties: Video" %}}
*   {{% resource_link 1f7846ca-c133-388f-d786-cae947c99035 "3.2.4Little oh Big Oh" %}}
*   {{% resource_link bb9ab3ea-0c54-6b87-900f-afd21424cd19 "3.2.5Theta" %}}
*   {{% resource_link 6874492c-9816-6ab0-1d32-ee77315bd540 "3.2.6Asymptotic Blunders: Video" %}}
*   {{% resource_link df4075eb-ddf7-23b1-3e4e-1e74f6a84766 "3.2.7Asymptotics the Right Way" %}}
*   {{% resource_link c4f72171-1e9e-ed96-b6f2-319be0d10496 "3.2.8Practice with Big O" %}}
*   {{% resource_link 2b8275cb-f5d7-304c-3775-80b64cb09fc8 "3.2.9Practice with Order of Growth" %}}
*   {{% resource_link 71ca5272-63f2-4aa7-d717-ef63328e47ef "\>Counting with Bijections" %}}

Practice with Order of Growth
-----------------------------

  

For each pair of \\(f(n) \\) and \\(g(n) \\) below, determine which of the listed relations apply.

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\lim\_{n \\rightarrow \\infty} |\\frac{f(n)}{g(n)}| = \\lim\_{n \\rightarrow \\infty} \\frac{ln(n) / ln(3)}{ln(n) / ln(7)} = \\frac{ln(7)}{ln(3)} \\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\lim\_{n \\rightarrow \\infty} |\\frac{f(n)}{g(n)}| = \\lim\_{n \\rightarrow \\infty} \\frac{0}{33} = 0 \\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
3.  {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\frac{f(n)}{g(n)} = 0 \\) for \\(n \\equiv 1 (\\text{mod } 4) \\), and \\(\\frac{g(n)}{f(n)} = 0 \\) for \\(n \\equiv 0 (\\text{mod } 4) \\), so the 2 functions and their quotient never converge to some limit.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
4.  {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\lim\_{n \\rightarrow \\infty} |\\frac{f(n)}{g(n)}| = \\lim\_{n \\rightarrow \\infty} \\frac{1.01^{n}}{n^{100}} = \\lim\_{n \\rightarrow \\infty} \\frac{1.01^{n} ln(1.01)}{100 \\cdot n^{99}} = ... = \\lim\_{n \\rightarrow \\infty} \\frac{1.01^{n} ln(1.01)^{100}}{100!} = \\infty \\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link c4f72171-1e9e-ed96-b6f2-319be0d10496 "BackPractice with Big O" %}}
*   {{% resource_link 71ca5272-63f2-4aa7-d717-ef63328e47ef "ContinueCounting with Bijections" %}}
---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 3.2 Asymptotics
parent_type: CourseSection
parent_uid: 7fcb0761-6e29-48a6-ad10-caa832263c78
title: 3.2 Asymptotics
uid: 1f7846ca-c133-388f-d786-cae947c99035
---

*   {{% resource_link f5736212-af2c-ef40-8c06-bbea00eb25c6 "\<Asymptotic Properties: Video" %}}
*   {{% resource_link 7fcb0761-6e29-48a6-ad10-caa832263c78 "3.2.1Asymptotic Notation: Video" %}}
*   {{% resource_link 7ce8643e-34ad-237e-8704-bca116ee1c91 "3.2.2Asymptotics as Relations" %}}
*   {{% resource_link f5736212-af2c-ef40-8c06-bbea00eb25c6 "3.2.3Asymptotic Properties: Video" %}}
*   {{% resource_link 1f7846ca-c133-388f-d786-cae947c99035 "3.2.4Little oh Big Oh" %}}
*   {{% resource_link bb9ab3ea-0c54-6b87-900f-afd21424cd19 "3.2.5Theta" %}}
*   {{% resource_link 6874492c-9816-6ab0-1d32-ee77315bd540 "3.2.6Asymptotic Blunders: Video" %}}
*   {{% resource_link df4075eb-ddf7-23b1-3e4e-1e74f6a84766 "3.2.7Asymptotics the Right Way" %}}
*   {{% resource_link c4f72171-1e9e-ed96-b6f2-319be0d10496 "3.2.8Practice with Big O" %}}
*   {{% resource_link 2b8275cb-f5d7-304c-3775-80b64cb09fc8 "3.2.9Practice with Order of Growth" %}}
*   {{% resource_link bb9ab3ea-0c54-6b87-900f-afd21424cd19 "\>Theta" %}}

Little oh Big Oh
----------------

  

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;If \\(f = o(g) \\), then \\(f = O(g) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;If \\(f = o(g) \\), then \\(g \\neq O(f) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;When \\(f \\sim g \\) and \\(f \\neq o(g) \\), \\(f = O(g) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;When \\(f \\nsim g \\) and \\(f = o(g) \\), \\(f = O(g) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;If \\(f = O(g) \\), then \\(f = o(g) \\).&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
2.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(x^{a} = o(x^{b}) \\) for all integers \\(a \\) and \\(b \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(b \\cdot x^{a} = o(x^{b}) \\) for all nonnegative constants \\(b > a\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(ln(x)=o(x^{\\varepsilon}) \\) for all \\(\\varepsilon > 0 \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(x^{c} = o(a^{x}) \\) for any \\(a, c \\in \\mathbb{R} \\) with \\(a > 1 \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(log(x)=o(x^{\\epsilon}) \\) for all \\(\\epsilon > 0 \\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
3.  {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;It accommodates cases in which a limit of \\(f(x)/g(x) \\) does not exist.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;The limit superior, \\(limsup \\), is a more strict limit compared to the ordinary limit, \\(lim \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(O(g(x)) \\) gives an upper bound instead of a lower bound on the growth of \\(f(n) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(x) \\) can oscillate wildly as long as it never gets bigger than \\(c \\cdot g(x) \\) for \\(x > n \\) and \\(c > 0 \\).&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link f5736212-af2c-ef40-8c06-bbea00eb25c6 "BackAsymptotic Properties: Video" %}}
*   {{% resource_link bb9ab3ea-0c54-6b87-900f-afd21424cd19 "ContinueTheta" %}}
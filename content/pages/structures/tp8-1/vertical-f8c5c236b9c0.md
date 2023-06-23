---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 2.10 Trees
parent_type: CourseSection
parent_uid: cbeb9c37-cb9c-a67c-cf21-6c0b8aeab325
title: 2.10 Trees
uid: 2a01183c-af7f-5488-2ed3-2634942e321c
---

*   {{% resource_link c7f2521e-8a2b-dbb6-52a3-411f0df14ab4 "\<Minimum Spanning Trees" %}}
*   {{% resource_link cbeb9c37-cb9c-a67c-cf21-6c0b8aeab325 "2.10.1Trees: Video" %}}
*   {{% resource_link cff972ff-cc8a-d21c-f422-d92a0e5a67fd "2.10.2Trees: Many Definitions" %}}
*   {{% resource_link f27baedb-b7ff-1c6b-93c7-80ab901b300c "2.10.3Tree Coloring: Video" %}}
*   {{% resource_link 94910ea3-ef5d-30f1-d3d3-08cd3030540b "2.10.42-Colorable Trees" %}}
*   {{% resource_link 40d32947-15d8-2fe5-f91a-1450343afbca "2.10.5Spanning Trees: Video" %}}
*   {{% resource_link efd45133-bd7b-8c4f-cfe5-0e4364935d4a "2.10.6Span all the Graphs!" %}}
*   {{% resource_link c9523658-4578-2eac-5fd7-65fa5889d8c4 "2.10.7Tree or Not Tree?" %}}
*   {{% resource_link 7d4e917a-f9ec-f1c5-28b0-1cc40169cd5a "2.10.8Leaves" %}}
*   {{% resource_link c7f2521e-8a2b-dbb6-52a3-411f0df14ab4 "2.10.9Minimum Spanning Trees" %}}
*   {{% resource_link 2a01183c-af7f-5488-2ed3-2634942e321c "2.10.10Graph Algorithm" %}}
*   {{% resource_link 47305688-cc38-9e2f-9dc3-019a395b3b37 "\>Stable Matching" %}}

Graph Algorithm
---------------

  

The algorithm _STAR MARK_ starts with a simple undirected graph, \\(G\\), with a finite set of vertices, \\(V\\), and a set of one or more edges, \\(E\\). Initially, all edges are unmarked. Then, _STAR MARK_ proceeds to mark some of the edges, by repeatedly performing the following steps until no further step is possible:

1.  Choose any unmarked edge \\(e \\in E\\) such that there is currently no path of marked edges between the endpoints of \\(e\\).
2.  Mark edge \\(e\\).

* * *

**Preserved Invariants**  
{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;There is always an edge that has not been marked.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;The marked edges form an acyclic graph.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;The marked edges form a tree.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;There is always a vertex not touching a marked edge.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}1.  Predicate 1 is true for the start state, since by definition there is at least one edge, but it is _not_ preserved.
2.  Predicate 2 is a preserved invariant and vacuously holds for the start state, which has no marked edges.
3.  Predicate 3 is vacuously true for the start state, but it is _not_ preserved.
4.  Predicate 4 is true for the start state but is _not_ preserved.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

* * *

**Derived Variables**  

Choose the property that best describes each of the following derived variables.

Answer with the strongest applicable property. For example, for a variable that is constant, the answer should be "constant", even though it is also both weakly increasing and weakly decreasing.

1.  \# of unmarked edges{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of unmarked edges decreases by 1.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  \# of marked edges{{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of marked edges increases by 1.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
3.  (# of unmarked edges) + (# of marked edges){{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of marked edges increases by 1 and the number of unmarked edges decreases by 1. So, their sum remains constant and is always equal to the initial number of unmarked edges in the graph.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
4.  (# of marked edges) - (# of unmarked edges){{< quiz_multiple_choice questionId="Q5_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of marked edges increases by 1 and the number of unmarked edges decreases by 1. So, their difference increases by 2.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
5.  (# of connected components) in \\(G'\\) with vertices in \\(V\\) and edges in \\(M\\), where \\(M\\) is the set of marked edges{{< quiz_multiple_choice questionId="Q6_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}Each newly marked edge connects 2 vertices that previously had no path of marked edges between them, so these 2 vertices belonged to different connected components of \\(G'\\), and the newly marked edge "joins" these components into one. As a result, the number of components in \\(G'\\) decreases by 1.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link c7f2521e-8a2b-dbb6-52a3-411f0df14ab4 "BackMinimum Spanning Trees" %}}
*   {{% resource_link 47305688-cc38-9e2f-9dc3-019a395b3b37 "ContinueStable Matching" %}}
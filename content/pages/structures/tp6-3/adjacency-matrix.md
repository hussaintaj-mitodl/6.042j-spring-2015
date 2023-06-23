---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: '2.5  Digraphs: Walks & Paths'
parent_type: CourseSection
parent_uid: 711aeeca-1552-65f2-21e5-af2643f1a05f
title: '2.5  Digraphs: Walks & Paths'
uid: e2165a11-69e6-c54f-cd9f-f1a57a2ef044
---

*   {{% resource_link 6bb54428-ef58-6956-4c92-74c82cf35ba5 "\<Longest Path" %}}
*   {{% resource_link 711aeeca-1552-65f2-21e5-af2643f1a05f "2.5.1Digraphs: Walks & Paths: Video" %}}
*   {{% resource_link e35dfdb4-de2b-e630-325d-55d289ab953a "2.5.2Walks and Paths" %}}
*   {{% resource_link 2827e6c9-e688-3174-fa8f-3cbf0a54d29b "2.5.3Digraphs: Connected Vertices: Video" %}}
*   {{% resource_link 6bb54428-ef58-6956-4c92-74c82cf35ba5 "2.5.4Longest Path" %}}
*   {{% resource_link e2165a11-69e6-c54f-cd9f-f1a57a2ef044 "2.5.5Adjacency Matrix" %}}
*   {{% resource_link 7126aa7b-0db7-c84d-fd9d-d2a73a6571a2 "2.5.6Counting Paths" %}}
*   {{% resource_link 7126aa7b-0db7-c84d-fd9d-d2a73a6571a2 "\>Counting Paths" %}}

Adjacency Matrix
----------------

Suppose we have an adjacency matrix A representation of a directed graph G.

Which of the following must be true for any adjacency matrix, regardless of the underlying graph?

Some matrix definitions:  
{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(A = A^T\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;A cell \\((i, j)\\) in the matrix \\(A^2\\) has non-zero value iff there is a length 2 path between the \\(i\\)-th and \\(j\\)-th vertices.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Every row in \\(A\\) must be different.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}For an undirected graph, the transpose of a matrix is itself because having an edge from \\(i\\) to \\(j\\) is equivalent to having an edge from \\(i\\) to \\(j\\). However, for directed graphs, this is not the case because these two edges would point in opposite directions.  
There is a length 2 path iff there exists some k such that \\(i, k, j\\) are connected iff exists index k such that \\((i, k) = 1\\) and \\((k, j) = 1\\) iff row \\(i\\) times column \\(j\\) is not 0 iff In \\(A^2, (i, j)\\) is not zero.  
If two rows in an adjacency matrix are the same, then this just represents that two vertices have edges leading to the same set of vertices.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link 6bb54428-ef58-6956-4c92-74c82cf35ba5 "BackLongest Path" %}}
*   {{% resource_link 7126aa7b-0db7-c84d-fd9d-d2a73a6571a2 "ContinueCounting Paths" %}}
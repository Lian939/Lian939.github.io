---
title: Article summary X
---

## Summary
[Lex et al.(2014)](https://ieeexplore.ieee.org/abstract/document/6876017) introduced a visualization technique UpSet that employed a matrix-based layout to show intersections of sets and their sizes. UpSet used two separate but interlinked views to represent the data: the set view (for set operations and cardinality tasks) and the element view (for attribute- and element-related tasks). UpSet represented the sets as matrix columns, and the row represented the intersection of different sets. Points were placed in the cells corresponding to the set involved in each intersection and were connected with a straight line. The matrix could also represent aggregates of set combinations as an expandable row, with points encoding the set involved in each set. UpSet also used bars to represent the elements in each combination and their attributes. The key features of UpSet were sorting, grouping and querying by various set‐based and attribute‐based criteria. In this paper, they distinguished UpSet with two types of set visualization techniques (element-centric techniques and set-centric techniques), also they demonstrated the utility of UpSet for real-life data analysis with two use cases from cancer biology and economics.

## Reaction
This paper pointed out the similarities and differences between UpSet and other visualization method. The most common visualization method for sets and their intersections, Euler and Venn diagrams could only identify which sets were participating in an intersection, but it was hard to spot the largest or smallest overlaps. Compared with two types of set visualization techniques, firstly, UpSet was better at certain tasks pertaining to set intersections, cardinality quantification or attribute related tasks than the other element-centric techniques (such as Bubble Sets, Visual Links, LineSets, and Kelp Diagrams), but it was not like some methods that can put more emphasis on the individual elements, Secondly, unlike the set-centric techniques (e.g. ConSet, Set O’Grams, and Doubledecker), UpSet only encoded the matrix elements which sets contribute to which intersection, could visualize element attributes and not limited to a small number of sets. The closest thing to UpSet was Radial Sets, but UpSet used a simplified visual encoding and employed a task-driven aggregation approach. Ranking the intersections and hiding combinations without intersection were very great, however, UpSet might be too complicated and nonintuitive with a large number of sets. Also, uploading data by users to the web-based UpSet looked difficult.

## Questions
1. How should we understand and use the deviation of the cardinality?
2. Dose UpSet support the task B14 (create a new set using set-theoretic operation: e.g. create the complement of A as a new set to compare with other sets.) identified by [Alsallakh et al.(2014)](https://kar.kent.ac.uk/39007/) ?
3. How to define the new attributes by users?
4. Upset might be good to visualize medication*medication interactions, but is it possible to visualize these interactions at different times?



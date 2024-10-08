---
title: "Concept drift detection in toxicology datasets using discriminative subgraph-based drift detector"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2022-12-03
venue: "Briefings in Bioinformatics'23"
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://killshot667.github.io/shabarisnair.github.io/files/concept.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Due to the increasing importance of graphs and graph streams in data representation in today’s era, concept drift detection in graph
streaming scenarios is more important than ever. Contributions to concept drift detection in graph streams are minimal and practically
non-existent in the field of toxicology. This paper applied the discriminative subgraph-based drift detector (DSDD) to graph streams
generated from real-world toxicology datasets. We used four toxicology datasets, each of which yielded two graph streams – one with
abrupt drift points and one with gradual drift points.We used DSDD both with the standard minimum description length (MDL) heuristic
and after replacing MDL with a much simpler heuristic SIZE (number of vertices + number of edges), and applied it to all generated graph-streams containing abrupt drift points and gradual drift points for varying window sizes. Following that, we compared and analyzed the results. Finally, we applied a long short-term memory based graph stream classification model to all the generated streams and compared the difference in the performances obtained with and without detecting drift using DSDD. We believe that the results and analysis presented in this paper will provide insight into the task of concept drift detection in the toxicology domain and aid in the application of DSDD in a variety of scenarios.
1. What is the research question(s) addressed in this paper? (50 words or less)\

- This paper examines the algorithmic innovations that enabled Google to outperform
competitors such as Lycos and AltaVista.

2. Discuss how this paper is related to your iCAN course material. Be specific
and justify your response. (500 words or less)

- This paper relates to several concepts covered in CS400 and CS401. The “hyperlink trick”
counts the number of pages that link to a target page, thereby forming a tree structure. As
illustrated in the figures of the paper, the relationships among these pages can be
visualized as a tree: pages at the bottom layer are assigned an authority score of 1, and
the score of a page in an upper layer depends on the scores of the lower-layer pages. This
process can also be described as recursion, since each calculation step depends on the
result of the previous step.

3. What are the results or findings presented in the paper? Do you agree with the
findings given the proposed methodology? Be specific and justify your
response. (500 words or less)

- This paper explains the operation of Google’s PageRank algorithm by examining three
core principles: the hyperlink trick, the authority trick, and the random surfer model.
PageRank effectively addressed the “needle in a haystack” problem, enabling Google’s
search engine to deliver more relevant information and outperform competitors such as
Lycos and AltaVista.
- The hyperlink trick counts the number of hyperlinks pointing to a target page. Assuming
each page is worth one point, all links from lower layers contribute to the target page’s
score. However, this method has two major limitations: (1) negative reviews also increase
the score, since computers cannot interpret webpage content; and (2) the mechanism is
susceptible to manipulation by web spammers, requiring continuous countermeasures
from engineers.
- To improve reliability, the authority trick was introduced, weighting links by the credibility
of their sources. For example, a link from a recognized expert carries greater influence
than one from an ordinary user. Authority is computed by summing the scores of all
incoming links, with each page starting from an initial baseline value of 1.
Despite these refinements, both tricks suffer from cyclic dependencies, creating a
“chicken-and-egg” problem. When web pages form loops such as A B C A, it
becomes diﬃcult to compute stable scores. To resolve this, the random surfer model was
introduced. In this stochastic framework, a hypothetical user follows a hyperlink with 85%
probability or jumps to a random page with 15% probability (values assumed in the paper
for illustrative purposes). The random restart breaks cycles and prevents infinite loops,
ensuring that scores can be consistently calculated.

4. What questions would you like future work on this topic to address? (50 words
or less)
- Can the "authority trick" identify URLs from certain institutions, like universities(those end
in ".edu") and government institutions (those end in ".gov"), and give them more weights?

5. Provide a talking point (or point of discussion) related to the paper you would
like to bring up in the class. Be specific and clear. (50 words or less)
- The counting methods described in the paper may lead to a form of populism in
information dissemination, where users are more likely to encounter popular content
rather than accurate, authentic, or valuable information. Which algorithm can effectively
address this problem?

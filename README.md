Download Link: https://assignmentchef.com/product/solved-cse-396-assignment-4
<br>









In lecture this week, we learned (formally) that not all computational problems are able to be represented by a regular expression. This hopefully isn’t very shocking, since we eluded to it from the beginning that the DFA model is quite limited (finite memory, read-once, etc.). Our method to accomplish this was by applying the Pumping Lemma. More specifically, if we satisfy all of the hypotheses for the contrapositive of the Pumping Lemma (namely, we can find a string within our candidate language that cannot be pumped properly), then we may conclude that the candidate language is not regular.

Note that the statement provided by the Pumping Lemma does not assert an “if and only if.” What this means is that if a language is not regular, it’s not necessarily the case that the Pumping Lemma does not hold. There does exist a more powerful tool, the Myhill-Nerode theorem, that provides a method to prove if a language is regular or not regular directly, including the ability to prove a language is regular without the need to construct a DFA recognizing it (see <a href="https://en.wikipedia.org/wiki/Myhill%E2%80%93Nerode_theorem">https://en.wikipedia.org/wiki/Myhill%E2% </a><a href="https://en.wikipedia.org/wiki/Myhill%E2%80%93Nerode_theorem">80%93Nerode_theorem</a><a href="https://en.wikipedia.org/wiki/Myhill%E2%80%93Nerode_theorem">)</a>. Interestingly, John Myhill (the Myhill in Myhill-Nerode) was a UB professor for many years.

Problem 1.  Complete the TopHat worksheet.

Problem 2.  Using the application of the contrapositive of the Pumping Lemma (from lecture), prove that the following language <em>L</em><sub>1 </sub>is not a regular language, where

<em>L</em><sub>1 </sub>= {<em>w </em>| <em>w </em>∈ {0<em>,</em>1}<sup>∗</sup><em>,</em>the middle symbol of <em>w </em>is 1}<em>.</em>

Problem 3. (19 points) Using the application of the contrapositive of the Pumping Lemma (from lecture), prove that the following language <em>L</em><sub>2 </sub>is not a regular language, where

<em>L</em><sub>2 </sub>= {<em>x</em>#<em>y</em>#<em>z </em>| <em>x,y,z </em>∈ {0<em>,</em>1}<sup>∗</sup><em>,x </em>+ <em>y </em>= <em>z </em>(as binary numbers)}<em>.</em>



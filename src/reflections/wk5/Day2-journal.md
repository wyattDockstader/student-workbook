https://wyattdockstader.github.io/megslist/

<b>What are the three types of relationships?</b>
One to One, One to Many and Many to Many

<b>What are the benefits of the traditional linking of relationships instead of Embedding</b>
In the case of a high write volume application using traditional linking would help to avoid the document reaching its max size and increasing write performance as the database wouldnt have to refactor information arrays to the new size as it grows.

<b>What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?</b>
The biggest challenge of many to many relationships is establishing the maximum size of each side of the relationship and deciding on which way to model it. for example if both sides of a many to many relationship were around say 5 possible relationships i would use 2 way imbedding but if it was something like 5 possible relationships to 10,000 the one way imbedding model would be better because a collection that size would easily break the max size limit.
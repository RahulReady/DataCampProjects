# Disney Movie Box Office Success
## Motivation
Who doesn't like watching Disney movies? If you don't, sorry, we cannot be friends. What types of Disney movies are the most popular? Is there a relation between the genre of a Disney movie and the expected gross income of the movie?

## Topics Covered
<ul>
<li><strong>Groupby:</strong> Finding out relations between movie genre and years.</li>
<li><strong>Data Transformations:</strong>  One hot encoding the genre column for Regression analysis. (drop_first gets rid of 1 extra column)</li>
<li><strong>Linear Regression:</strong> Finding out the relation between genre and gross income from the movie.</li>
<li><strong>Pair Bootstrap Estimates:</strong> Repeatedly shuffling the data to get an average estimate for intercept and coefficient values.</li>
</ul>

## Steps taken
<ul>
<li>Understanding data</li>
<li>Group and visualize data</li>
<li>Data Transformation for analysis (OHE)</li>
<li> Use pair bootstrap estimates to get a confidence interval for the intercept and coefficients. use np.random.choice() to shuffle the indices.</li>
<li>Interpret results and make a conclusion</li>

</ul>

## Exercise: Faceting

1. Using faceting, find out how many years are represented in the census.
1. Which years have the most and least observations?
1. Is the column formatted as Number, Date, or Text? How does changing the format change the faceting display?

<details>
  <summary>
    Solution
  </summary>
    <ol>
      <li>For the column <code>yr</code> do <code>Facet</code> > <code>Text facet</code>. A box will appear in the left panel showing that there are 26 unique entries in this column.</li>
      <li>After creating a facet, click <code>Sort by count</code> in the facet box. The year with the most observations is 1997. The least is 1977.</li>
      <li>By default, the column <code>yr</code> is formatted as Text. You can change the format by doing <code>Edit cells</code> > <code>Common transforms</code> > <code>To number</code>. Doing <code>Facet</code> > <code>Numeric facet</code> creates a box in the left panel that shows a histogram of the number of entries per year. Notice that the data is shown as a number, not a date. If you instead transform the column to a date, the program will assume all entries are on January 1st of the year.</li>
  </ol>
</details>
  

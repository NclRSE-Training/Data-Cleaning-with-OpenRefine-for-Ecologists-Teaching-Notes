## Exercise 1


1. What scientific names (genus and species) are selected by this procedure?
1. How would you restrict this to one of the species selected?

<details>
  
<summary>
    Solution
  </summary>
  <ol>
    <li>Do <code>Facet > Text facet</code> on the <code>scientificName</code> column after filtering. This will show that two names match your filter criteria. They are <code>Baiomys taylori</code> and <code>Chaetodipus baileyi</code>.
    <li>To restrict to only one of these two species, you could:
      <ul>
        <li>Check the <code>case sensitive</code> box within the <code>scientificName</code> facet. Once you do this, you will see that using the upper-case <code>Bai</code> will only > > return <code>Baiomys taylori</code>, while using lower-case <code>bai</code> will only return <code>Chaetodipus baileyi</code>.</li>
        <li>You could include more letters in your filter (i.e. typing <code>baio</code> will exclusively return <code>Baiomys taylori</code>, while <code>bail</code> will only return <code>Chaetodipus baileyi</code>).</li>
    </ul>
  </ol>
  


  </details>

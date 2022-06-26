## Exercise 1


1. What scientific names (genus and species) are selected by this procedure?
1. How would you restrict this to one of the species selected?

<details>
  
<summary>
    Solution
  </summary>
        Do ```Facet > Text facet``` on the scientificName column after filtering. This will show that two names match your filter criteria. They are Baiomys taylori and Chaetodipus baileyi.
        To restrict to only one of these two species, you could:
            Check the case sensitive box within the scientificName facet. Once you do this, you will see that using the upper-case Bai will only > > return Baiomys taylori, while using lower-case bai will only return Chaetodipus baileyi.
            You could include more letters in your filter (i.e. typing baio will exclusively return Baiomys taylori, while bail will only return Chaetodipus baileyi).


  </details>

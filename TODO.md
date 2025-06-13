# Get rid of carousel

**priority**: high

a nice-to-have. This would be more accessible for screenreaders and search https://getbootstrap.com/docs/4.0/components/carousel/#with-captions

in the code: https://github.com/YoussefRaafatNasry/portfolYOU/blob/master/_includes/elements/carousel.html

# Add blockquotes for user insights
https://getbootstrap.com/docs/4.0/content/typography/#blockquotes

# add T chart for problems and solutions
https://getbootstrap.com/docs/4.0/content/tables/

# Change card columns to 2 instead of 3

**priority**: medium for now, high when ifsc gets published

`<div class="card-columns m-2 mt-5">` in `index.html:2`

-> changing the columns isnt' working, still shows 3 idk why

# add blog back

**priority**: low

add techwriting portfolio selections and some blog writing about accessibility in climbing etc 


# Make table of contents collapsible

**priority**: medium

no clue how- bootstrap docs don't include anything for collapsing it https://getbootstrap.com/docs/4.0/components/list-group/

might also consider flush style https://getbootstrap.com/docs/4.0/components/list-group/#flush

Would have to replace this item from the parent repo: https://github.com/yousinix/portfolYOU/blob/master/_includes/elements/list.html

# Fix search bar

search bar stopped working after we added the changes to the navbar
```
include_relative project_classes/project_search.html

```
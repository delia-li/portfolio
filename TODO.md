# Add blockquotes for user insights
https://getbootstrap.com/docs/4.0/content/typography/#blockquotes

# Change card columns to 2 instead of 3

**priority**: medium for now, high when ifsc gets published

`<div class="card-columns m-2 mt-5">` in `index.html:2`

-> changing the columns isnt' working, still shows 3 idk why

# add blog back

**priority**: low

add techwriting portfolio selections and some blog writing about accessibility in climbing etc 


# Make table of contents sticky and on the left hand side

**priority**: medium

one option is accordion https://getbootstrap.com/docs/5.3/components/accordion/

another option is vertical navbar but does it allow nesting? https://getbootstrap.com/docs/5.3/components/navs-tabs/#vertical


# Fix search bar

search bar stopped working after we added the changes to the navbar
```
include_relative project_classes/project_search.html

```

# embed figma prototype resume
```
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/proto/aNkaXJYQyoLDqexU5coIrU/resumes?node-id=149-1520&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&embed-host=share" allowfullscreen></iframe>

```

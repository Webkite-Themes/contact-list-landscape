#Contact List Portrait Card
---
##changelog

###0.2.2

* Added if check against filterableFacets
* Wrapped non filted enums in span

###0.2.1

* Minor color fixes for drak version of the theme

###0.2.0

* Sort and Filter areas should only appear when you have sorts or filters available respectively
* An active sort now has a directional icon to indicate which direction
* Inline filter buttons!
* No results text for when we filter down to zero
* Initial overflow behavior for the filter bar
  * Tokens will remain on one line and flow over to the right, obscured after exceeding the bar.
* Making certain a comma is only added between City and State when both are present
* Most tags are now inside the {{#facet}} check, meaning they should only appear when they exist in the spreadsheet
  * This does not apply to facet headings
  
###0.1.0

* Initial development of the landscape card and basis for 3 main themes
* Sort and Filter menus should cause the results to be sorted and filtered respectively
* Able to select facet values in the results to add them to the filter bar
* Able to paginate by input and by pressing the arrows
* Proper call to Google Fonts
* Calling images from the dataset
* Custom sort menu, and filter menu with hierarchy arrows

—[Chris](mailto:chris@webkite.com)
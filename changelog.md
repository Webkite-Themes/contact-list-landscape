#Contact List Landscape Card
---
##changelog

###1.0.0

* Head off list-style declarations
* Update pagination to stay on one line
* Remove link to WebKite
* Make sure address doesn't drop below label
* Accommodate long URLs
* Compress all partials into one
* Gradient fallback for IE
* Persistent borders around inline filter buttons

###0.2.5

* Disabled styles for pagination once you've reached the end or are at the beginning of a result set
* No longer displaying pagination if there's only one page of results
* Including box-shadow removal and background removal in the reset
* Styles and markup for the filter overview behavior
* Tweaks between light and dark variants for consistent spacing
* Fix for bug noticed where sort button did not span the container at sm and xs sizes
* Making sure addresses have line breaks appropriately

###0.2.4

* Minor tweaks on filter button

###0.2.3

* Properly wrapping all facet output in checks
* Background position standardized for Firefox
* Margins between filter area and sort area depend on both existing
* More specific font declarations on buttons
* Tweaking of filters so that spacing between strings and tokens is more conistent
* Inline filter menus have a max-height

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
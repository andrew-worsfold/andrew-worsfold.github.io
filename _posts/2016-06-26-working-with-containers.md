---
layout: post
title: Working with containers
---

The latest version of the [Tailor page builder](http://www.gettailor.com) for WordPress (1.2.0) changes the way that container elements like tabs, lists and carousels behave.  Now, instead of collapsing when only one child element remains, they will exist until all children have been removed or destroyed.

## Removing children

![Removing children from containers in Tailor]({{ site.baseurl }}/img/gifs/list-removing.gif "Removing children from containers in Tailor")

<b>Note:</b> this does not apply to row and column structures.  If a column is removed from a row leaving only one other column, the remaining row and column will collapse as expected.

![Collapsing rows in Tailor]({{ site.baseurl }}/img/gifs/row-collapsing.gif "Collapsing rows in Tailor")

In the image above, the first column is destroyed leaving only the second column.  The remaining row and column collapse, leaving only the elements from the second column (in this case a content element).  Because the colours were applied at the column level, the content element appears unstyled.

## Adding children 

Adding children to containers works exactly the same as before.  Simply drag the desired element(s) over the center of the container.

![Adding children to containers in Tailor]({{ site.baseurl }}/img/gifs/tabs-adding.gif "Adding children to containers in Tailor")

## Reordering children

Reordering children is possible for all container types; though the exact method can differ.  For example:

### Tabs
![Reordering tabs in Tailor]({{ site.baseurl }}/img/gifs/tabs-reordering.gif "Reordering tabs in Tailor")

### Toggles
![Reordering toggles in Tailor]({{ site.baseurl }}/img/gifs/toggles-reordering.gif "Reordering toggles in Tailor")

## Carousel items
![Reordering carousel items in Tailor]({{ site.baseurl }}/img/gifs/carousel-reordering.gif "Reordering carousel items in Tailor")
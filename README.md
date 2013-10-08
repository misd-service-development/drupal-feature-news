Drupal 7 University of Cambridge news feature
=============================================

This feature adds a node view mode for news listing items.

For each content type you will need to set the display settings for the 'News listing item' type to only show the (summary) body. This would typically look like:

![News listing item display configuration](doc/display.png)

If you are using a `field_link` provided by the [Link feature](https://github.com/misd-service-development/drupal-feature-link) you also need to make your link field available (it doesn't matter what format setting you use). The teaser will then link to your custom URL rather than to the node.

Creating a list of news items
-----------------------------

To create a list of sidebar teasers produced by a view, have a block with the following format options:

![Format options](doc/view_format.png)

The view block then needs to be set to appear on the appropriate page(s) in the 'Sub-content' region.

Creating a page of news items
---------------------------

For a page of news items you should use the [horizontal teaser](https://github.com/misd-service-development/drupal-feature-teasers) node view mode.

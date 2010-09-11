Comment Sanity module for Drupal
---------------------------------------

This module provides more sane defaults for several of Drupal's comment settings.

For all node types these settings are enforced:

* Oldest first by default
* Do not display comment controls
* Removes collapsed options leaving "Flat" or "Threaded" options
* Removes "Read only" from default form... why would a new node be "Read only" without any comments!? Leaves "Disabled" or "Enabled" options. Nodes can still be set to "Read only" individually.

See this article I wrote several years ago on the thinking behind this module:
http://www.lullabot.com/articles/drupal-usability-comment-configuration
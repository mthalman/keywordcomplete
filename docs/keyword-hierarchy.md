# Keyword Hierarchy

The keyword hierarchy allows you to organize all of the keywords in your database. This is a hierarchical system in that each keyword can have its own collection of child keywords. There is no limit to the depth of keywords that you can create. To view the hierarchy, select the Keyword Hierarchy view button on the left panel.

-INSERT SCREENSHOT-

## Adding a new keyword

There are two ways that a keyword can be added:
1. Click the Add (+) button at the top of the hierarchy panel. This will open a dialog that lets you configure the [attributes](keyword-attributes.md) of the keyword. This is the option to use if you want to add a new keyword at the root level.
2. Otherwise, to add a child keyword, you can right-click the existing keyword you want to use as the parent and select "New Child Keyword".

## Editing a keyword's attributes

Keywords contain a variety of [attributes](keyword-attributes.md) that can be configured.

To set a keyword's attributes, right-click the keyword in the hierarchy tree and select "Edit". This will open a dialog that lets you change its attributes.

## Deleting a keyword

Deleting a keyword removes it from the database along with all of its descendant keywords. If that keyword was a member of a [keyword set](keyword-sets.md), it will automatically be removed from that set. If that keyword had been selected, it will automatically be removed as a [selected keyword](selecting-keywords.md).

To remove a keyword, right-click the keyword in the hierarchy tree and select "Delete" or press the Delete button.

## Moving keywords

In some cases, you'll want to move a keyword so that it exists under a different parent. This can easily be done by dragging and dropping it where you want it to go. If you want a child keyword to be at the root level, right-click it and select "Set as Root".

-INSERT GIF-

## Filtering

The hierarchy tree can be filtered down to keywords that contain the text that is entered into the filter box above the hierarchy tree. To maintain good performance, the filtering doesn't take effect until you've typed at least three characters. To reset the hierarchy tree, just clear the text in the filter box.

By default, the hierarchy tree will be filtered to keywords whose name contain the text in the filter box. If you check the "Search synonyms" box, the filtering logic will also look for matching text in the [synonyms](keyword-attributes.md) of each keyword.

-INSERT GIF-

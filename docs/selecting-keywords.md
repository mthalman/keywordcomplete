# Selecting Keywords

The whole point of Keyword Complete is to generate a full list of keywords by typing in just a few relevant keywords and then having the app expand those keywords based on the hierarchy and attributes of those keywords.

For example, if I've configured my keyword hierarchy appropriately, I could type in "Grand View Point Overlook" and "Utah Juniper" and automatically have the following list of keywords generated for me: Canyonlands National Park, conifer, Coniferae, Coniferophyta, coniferous, Grand View Point Overlook, Juniper, Juniperus osteosperma, National Park, Pinophyta, Plant, tree, United States, Utah, Utah Juniper.

Selecting keywords consists of three stages:
1. Select
2. Refine
3. Copy

## Select Stage
In this stage, you're selecting the relevant keywords that you want to include. Typically, you want to select the most specific keyword possible. For example, if I'm selecting keywords for a photo of a Utah Juniper tree, I should select "Utah Juniper" rather than just "Juniper" or "Tree". Assuming I've defined my keyword hierarchy such that Utah Juniper is defined as a child of Juniper, then I'll automatically get the Juniper keyword for free.

To select a keyword, just type into the "Select Keyword" textbox in the Select stage portion of the screen. This will automatically lookup keywords that begin with that text from your keyword hierarchy. When you pick one, it'll be added as a selected keyword. If you don't happen to have a keyword that matches the text you type, one will automatically be added when you hit Enter. By default, it will be added as a root keyword. If you want the option to set which parent keyword it should be contained within, enable the "Prompt to set state for new keywords" option in the [Options](options.md) panel.

To remove a specific keyword just click the X button on the selected keyword. To remove all selected keywords, click the Clear button.

-INSERT GIF-

### Rules for Keyword Generation

Keyword Complete uses a set of rules to determine which keywords are generated based on the keywords that have been selected.

For a given selected keyword,
* its name is included in the generated list unless its ["Exclude from output"](keyword-attributes.md) attribute is enabled.
* its synonyms are included in the generated list.
* these rules are applied to each of its [related keywords](keyword-attributes.md), recursively.
* these rules are applied to its parent keyword, recursively.

## Refine Stage
Once you've selected your keywords you have the opportunity to efficiently refine the keywords that have been generated. You can remove keywords that have been generated that you feel are not relevant to the specific case you're working on by simply clicking the X button on the keywords.

-INSERT GIF-

## Copy Stage
Now that you've got the full list of keywords, you can copy and paste them into your photo management app. To copy the keywords to the clipboard, just click the button with the copy icon next to the Copy stage.

Depending on the target app, it may require the list of keywords to be in a specific format. For example, they may need to be comma-delimited or semicolon-delimited. To change the format of the list of keywords, choose the desired format from the dropdown on the right side. There's also the option to convert all the text to lowercase if you wish.

-INSERT GIF-

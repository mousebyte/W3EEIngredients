# Contributing
The biggest part of this list will be the location information, and it will also be the hardest information to accurately gather, so I'll take all the help I can get.
If you would like to contribute to the list, your pull request should contain a list of which items were added/updated and a brief description of what was changed.

## Formatting
All ingredient names, quantity, quality, and substance names should be capitalized (just so it looks nice). If an ingredient has no secondary substance, the field should be left blank.

### Locations
The location field for an ingredient should contain ALL known locations where it can be found. Entries should be separated by commas. There are two special values for location. First, if an ingredient can be obtained by dismantling some other ingredient, its last location entry should be `dismantling <other ingredient name>. Second, if an item can only be found at an alchemy shop (and/or as a quest reward), its location field should contain the quests it is rewarded for followed by "alchemy shops". Don't use "alchemy shops" for ingredients that can be found elsewhere, e.g. herbs, because we all know you can buy Celandine from an alchemy shop.

Locations for herbs in the game world should start with the nearest waypoint/signpost name, followed by a more specific location in parentheses if applicable. Example:

`Woesong Bridge (west fields), Hangman's Tree (north forest)`

If an herb is present in more than one area around a waypoint, then put all areas in the same parentheses and separate them by commas. Example:

`Woesong Bridge (village, west fields)`

Monster drop ingredients follow a similar format. Start with the name of the monster, and then in parentheses where to find it. If the monster is encountered as part of a quest, include the quest name. Examples:

`Drowner (random encounters near bodies of water)`

`Golem (cave under Temple Isle, Quest: "Wandering in the Dark")`

`Cockatrice (Contract: "Shrieker")`

# Alfred Workflows (Optimzed for Alfred v4)
Alfred v4 Workflows. Here is a list of the **Alfred Workflows I use in my workflow**.
Most workflows are **made by me**. A few of them are based on work from others, in which case credits will be mentioned under "About this Workflow".

## Add To-Do to Things 3
*Based on the official culturedcode Quicksilver/Alfred script.*

### Getting started
**`+ Remember the milk`** creates a new TODO in inbox named "Remember the milk".

### Advanced Syntax

`title #tag1 #tag2 [project name/area name] ::note >duedate`

**Example:** `+ Remember the milk #groceries Shopping/Daily ::I love milk >20190616`

#### Notes
- Only existing tags can be added. This parameter is case-insensitive. If #tag1 doesn’t exist, '#tag1' will be added to the to-do’s title.
- To-dos can only be added to existing projects or areas. This parameter is case-insensitive. Projects or areas that don’t already exist will be ignored entirely; the text won’t be added to the to-do’s title.
- Format for the due date will reflect your Mac’s short date format. Check this in System Preferences > Language & Region > Advanced… > Dates. Invalid due date formats will result in the parameter’s text being added to the to-dos title.
- If you’re using a dark theme for Alfred, there’s a white Inbox icon available in this Workflow’s folder. Right-click the Workflow and click Show in Finder to find it.

## Bear
*Based on chrisbro/alfred-bear.*

### New Note

**`bn Notes about milk #milk #notes`** creates a new Bear note with the title and text "Notes about milk!" and the tags "#milk" and "#notes" attached to it.

### Search

**Example:** `bs servername01` search for notes containing the text servername01

### Search by Tag

**Example:** `bst linux` search for notes tagged with #Linux

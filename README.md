# Alfred Workflows (Optimzed for Alfred v4)
Alfred v4 Workflows. Here is a list of the **Alfred Workflows I use in my workflow**.
Most workflows are **made by me**. A few of them are based on work from others, in which case credits will be mentioned under "About this Workflow".

## Add To-Do to Things 3
*Based on the official culturedcode Quicksilver/Alfred script.*

![Alfred and Things 3 Screenshot](https://github.com/danielbahl/alfredv4/blob/master/Add-To-Do-to-Things-3-screenshot-1.png?raw=true)

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

![Alfred and Bear Screenshot](https://github.com/danielbahl/alfredv4/blob/master/Bear-screenshot-1.png?raw=true)

### New Note

**`bn Notes about milk #milk #notes`** creates a new Bear note with the title and text "Notes about milk!" and the tags "#milk" and "#notes" attached to it.

### Search

**Example:** `bs servername01` search for notes containing the text servername01

### Search by Tag

**Example:** `bst linux` search for notes tagged with #Linux

## Currency Exchange

To change DKK to another currency, change the Workflow "Script Filter" from DKK to another currency.

### Convert $ USD to DKK

**`$100`** converts USD $100 to DKK, example: $100 = 666.23 DKK (2019-06-15)

![USD to DKK](https://github.com/danielbahl/alfredv4/blob/master/Currency-Exchange.alfredworkflow-screenshot-1.png?raw=true)

### Convert € EUR to DKK

**`€1`** converts EUR €1 to DKK, example: €1 = 7.48674 DKK (2019-06-15)

![EUR to DKK](https://github.com/danielbahl/alfredv4/blob/master/Currency-Exchange.alfredworkflow-screenshot-2.png?raw=true)

### Convert £ GBP to DKK

**`£1`** converts GBP £1 to DKK, example: £1 = 8.38717 DKK (2019-06-15)

![GBP to DKK](https://github.com/danielbahl/alfredv4/blob/master/Currency-Exchange.alfredworkflow-screenshot-3.png?raw=true)

### Convert DKK to EUR/USD/GBP/...

**`DKK 300 EUR`** converts 300 DKK to EUR, example: `DKK 300 EUR` = EUR €40,0708 (2019-06-15)
**`DKK 10 USD`** converts 10 DKK to USD, example: `DKK 10 USD` = USD $1,50098  (2019-06-15)

![DKK to USD](https://github.com/danielbahl/alfredv4/blob/master/Currency-Exchange.alfredworkflow-screenshot-4.png?raw=true)

## Dig
Simple Alferd Workflow to perform simple DNS lookups

### Find A/CNAME record of root domain

**`dig danielbahl.com`** digs danielbahl.com and resolves it to a hostname or IP.

![dig alfred screenshot by daniel bahl](https://github.com/danielbahl/alfredv4/blob/master/Dig.alfredworkflow-screenshot-1.png?raw=true)

### Find MX-records (Mail eXchanger) for a specific internet domain

**`dig danielbahl.com mx`** digs mx for danielbahl.com and resolves it to a hostnames

![dig mx alfred screenshot by daniel bahl](https://github.com/danielbahl/alfredv4/blob/master/Dig.alfredworkflow-screenshot-2.png?raw=true)

### Find NS-records (Name Servers) for a specific internet domain

**`dig danielbahl.com ns`** digs NS for danielbahl.com and resolves it to a hostnames

![dig ns alfred screenshot by daniel bahl](https://github.com/danielbahl/alfredv4/blob/master/Dig.alfredworkflow-screenshot-3.png?raw=true)


### Find TXT-records (Text/SRV/SPF etc.) for a specific internet domain

**`dig danielbahl.com txt`** digs TXT for danielbahl.com

![dig txt alfred screenshot by daniel bahl](https://github.com/danielbahl/alfredv4/blob/master/Dig.alfredworkflow-screenshot-4.png?raw=true)

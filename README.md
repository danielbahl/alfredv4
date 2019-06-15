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

## Emoji Search
*Based on James Sumners (jsumners/alfred-emoji) awesome work!* Optimized and edited a bit to fit my emoji needs :)

**Hotkey Enabled** Please note that this Workflow has the CMD+. hotkey enabled. So it's easy to find and insert emojis everywhere by using the keyboard shortcuts CMD + .(dot)

![Alfred Emoji Search](https://github.com/danielbahl/alfredv4/blob/master/Emoji-Search-screenshot-1.png?raw=true)

### Getting started
**`emo hello`** find emojis matching the search-term "hello". Press ENTER to copy it to clipboard or CMD+ENTER to insert it directly into the content you are working on.

![Alfred Emoji Search](https://github.com/danielbahl/alfredv4/blob/master/Emoji-Search-screenshot-2.png?raw=true)

### Hotkey
Press `cmd+.` and type `100` to find emojis matching the search-term "100". Press ENTER to copy it to clipboard or CMD+ENTER to insert it directly into the content you are working on.

## SMB Mounter + Unmounter Server

Fast mounting smb network share. Please also refer to https://support.apple.com/en-bw/HT208209 for speedier SMBs on your Mac. This script mounts/unmounts a network-share to your desktop.

#### Please change the IP, Sharename, Username and Password inside the Script to make this work. Also change notification and keyword to  fit your needs :) 🦄

![smbmount](https://github.com/danielbahl/alfredv4/blob/master/smb-mounter-screenshot-1.png?raw=true)

## Royal TSX

This awesome workflow works together with Royal TSX enabling searching and connecting to remote servers from Alfred.

![royaltsx](https://github.com/danielbahl/alfredv4/blob/master/royal-tsx-screenshot-1?raw=true)

### Ad-hoc

`royal rdp://1.2.4.5` created an ad-hoc remote desktop connection to IP 1.2.4.5.
`royal ssh://awesomeworkstation.com` created an ad-hoc SSH connection to IP 1.2.4.5.

### Search

`royal web01` search for web01 in your Royal Bookmarks. Press enter to open Royal TSX and connect.

### Direct Connections

Every morning I connect to a specific server, my workstation. That's why I've made a keyword called "workstation" that connects directly to a specific server in Royal. For this to work you'll need the UUID from Royal for this specific server. Therefore, I have made a Clipboard action that you can connecte the Royal keyword. Then use the Royal keywork to connect to the server, now you have the UUID in your clipboard. Now insert the UUID from your clipboard into the workstation workflow script. 

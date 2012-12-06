# Launchbar Syntax Highlighted Yojimbo

A [Launchbar](http://www.obdev.at/products/launchbar/index.html) Applescript action to add syntax highlighted code snippets to [Yojimbo](http://www.barebones.com/products/Yojimbo/), using [pygments](http://pygments.org).

## Installation Instructions

You will need to have installed Launchbar, Yojimbo, and pygments. You probably have the first 2 already setup if you are interested in these scripts. Pygments is a fairly easy install, but out of the scope of these instructions.

* Install (or confirm install) pygments
* Move the `New Yojimbo Snippets` directory into `~/Library/Application Support/Launchbar/Actions`
* Create a directory: `~/Code/snippets`
    * Alternatively you can edit the Applescripts to use a different folder
* Done!

## Usage

To use the snippet you can do one of two things.

* Select some code
* Use the Instant Send feature of Launchbar
* Type the language that you want i.e. for HTML `htmlSnippet`
* Hit return
* A snippet will be added to your library with syntax highlighing and the tags `snippet` and `html`

Alternatively you can: 

* Select the code snippet
* Copy it with ⌘ - c 
* Open Launchbar
* Type `htmlSnippet` or enough letters to allow that to come up
* Press return
* Paste in the snippet in the resulting text box with ⌘ - v
* Press return again
* The snippet is then uploaded

## Notes

The languages currently supported are python, bash, ruby, perl, and html. These are the most common snippets I come across. Ideally I would like to consolidate these inside a single script, thus making it easier to add new languages, but that has not happened yet. I would also like to be able to input a title for the item in Yojimbo, currently it just timestamps the entry and adds the tags.

A useful tip is to create a few smart folders in Yojimbo that look for the tags, `snippet`, `html`, `ruby`, and whatever language you are snipping. If you do not like the Monokai theme, you can edit the Applescripts to replace that with a theme of your choosing.
 

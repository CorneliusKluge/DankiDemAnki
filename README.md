# DankiDemAnki
Collaborative German Anki decks for Media IT studies <br>
The Anki-addon [CrowdAnki](https://github.com/Stvad/CrowdAnki) is used for the distribution via GitHub.

## Before you start
* Please make sure Anki is running the most recent version.
* Install [CrowdAnki](https://github.com/Stvad/CrowdAnki).
* You should create a new Anki user dedicated to DankiDemAnki, because when importing Anki decks, all of the current user's data will be overwritten.
* Download this repository into your desired directory. 

Just as a quick warning: CrowdAnki doesn't seem to be very stable or well bugfixed. On my first two days of working with it, I've already encountered various ways to freeze or crash Anki, so please follow the instructions below carefully.

## Importing
Be sure you pull the repository before importing for the most recent version. <br>
You can import Anki cards by following these steps: <br>
* "Data" -> "CrowdAnki: Import From Disk" -> From this repo's directory, choose your subject folder (For example "Betriebssysteme".) -> Don't tick anything. -> OK. 

You should now have successfully imported one subject deck into your Anki app. This needs to be repeated for each subject folder.

## Creating new DankiDemAnki cards
* Deck hierarchy goes as following, illustrated by Betriebssysteme: "Betriebssysteme" > "1 - Einleitung". <br> Going any deeper is probably not necessary. 
* If you have the luck of using an already structured guideline, please also use numbers as first part of the name of your decks. Anki sorts alphabetically, but users may want to study chronologically instead.
* To make working with Anki more user friendly, I'd encourage you to use a consistent style when creating new cards.
* Use as few highlighting as possible, but as much as needed. When editing, press Ctrl+Shift+X for HTML editor.
* Try to use different approaches to the medium. Don't always write "Wie lautet die Definition von x?", try to get creative when appropriate!
* Use images, videos, helpful internet ressources! A picture often says more than a thousand words. :)
* I myself haven't done so yet, but don't be afraid of using different card layouts to make the learning experience less repetitive. (Instead of only using the front for questions and the backside for answers.)

## Exporting
* "Data" -> "Export" -> **Choose the "CrowdAnki JSON..." format and only your current subject's deck!** (Deviating from this may lead to others not being able to import your data or your app crashing.) Include Media and Tags. -> "Export..." -> This repo's directory (NOT the subject folder!)

You should now have successfully exported all of your subject's updates into the repo. If you have GitHub Desktop installed, you can see your changes there.

## Contributing to DankiDemAnki via GitHub
* Try to commit your changes often to not lose your them when importing.
* Despite this being a German course, please use English in your commit messages and when communicating through GitHub.
* When creating commit messages I would advise you to follow these rules: https://chris.beams.io/posts/git-commit/
